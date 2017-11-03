---
TOCTitle: 'Anmerkungen zu dieser Version von Microsoft Windows Server Update Services 3.0'
Title: 'Anmerkungen zu dieser Version von Microsoft Windows Server Update Services 3.0'
ms:assetid: '94d1385f-4872-4c29-8822-3a4ec5e45ae4'
ms:contentKeyID: 18127529
ms:mtpsurl: 'https://technet.microsoft.com/de-de/library/Cc708491(v=WS.10)'
---

Anmerkungen zu dieser Version von Microsoft Windows Server Update Services 3.0
==============================================================================

In diesen Versionsanmerkungen werden bekannte Probleme im Zusammenhang mit Microsoft® Windows® Server Update Services 3.0 (WSUS) sowie Empfehlungen und Anforderungen für die Installation der Anwendung beschrieben. Die Anmerkungen unterteilen sich in die folgenden Abschnitte:

-   Systemanforderungen für die Installation der WSUS 3.0-Serverkomponente
-   Konfigurationsanforderungen für die Installation der WSUS 3.0-Serverkomponente
-   Systemanforderungen für die Installation der WSUS 3.0-Remotekonsolenkomponente
-   Konfigurationsanforderungen für die Installation der WSUS 3.0-Remotekonsolenkomponente
-   Systemanforderungen für die Installation der Clientkomponente
-   Softwareanforderungen für die Installation der WSUS 3.0-Serverkomponente
-   Speicherplatzanforderungen für die Installation der WSUS 3.0-Serverkomponente
-   Anforderungen für ein Upgrade auf WSUS 3.0
-   Befehlszeilenparameter für das Setup
-   Probleme beim Setup und Upgrade
-   Bekannte Probleme
-   WSUS 3.0 unter Windows Server® 2008
-   WSUS 3.0 unter Windows Small Business Server 2003

> [!NOTE]
> Dieses Dokument kann über das [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=71220) ([http://go.microsoft.com/fwlink/?LinkId=71220](http://go.microsoft.com/fwlink/?linkid=71220)) heruntergeladen werden. 

Wichtiger Hinweis für die Konfiguration: Das Kennwort des Proxyservers im Konfigurations-Assistenten muss überschrieben werden
------------------------------------------------------------------------------------------------------------------------------

Wenn Sie einen Proxyserver verwenden, der eine Authentifizierung durch Benutzername/Kennwort verlangt, und Sie beim Ausführen des Assistenten zum Konfigurieren des WSUS-Servers das Kennwort des Proxyservers nicht überschreiben, könnte es passieren, dass der WSUS-Server die Updates nicht synchronisieren kann. Da der Konfigurations-Assistent am Ende des Installationsvorgangs automatisch gestartet wird, führt dieses Problem nach einem Upgrade von einer älteren WSUS-Version auf WSUS 3.0 möglicherweise zu Synchronisierungsfehlern.

Sie können dieses Problem umgehen, indem Sie den Konfigurations-Assistenten nach dem Upgrade abbrechen oder indem Sie während der Ausführung des Konfigurations-Assistenten das richtige Proxykennwort noch einmal eingeben. Wenn das Problem bereits aufgetreten ist, gehen Sie auf der Seite **Optionen** zur Option **Updatequelle und Proxyserver**, geben Sie das Proxykennwort erneut ein, und speichern Sie die Einstellung.

Systemanforderungen für die Installation der WSUS 3.0-Serverkomponente
----------------------------------------------------------------------

#### Serverkomponente von WSUS 3.0 wird von Windows Server 2003 Service Pack 1 und Windows Server 2008 unterstützt

Die Serverkomponente von WSUS 3.0 wird von Windows Server 2003 Service Pack 1 und Windows Server 2008 unterstützt.

#### Serverkomponente von WSUS 3.0 wird von Windows 2000 Server nicht unterstützt

Die Serverkomponente von WSUS 3.0 wird vom Betriebssystem Microsoft Windows® 2000 Server nicht unterstützt.

#### WSUS 3.0 wird auf Servern mit Terminaldiensten nicht unterstützt

WSUS 3.0 wird zwar möglicherweise auf Servern mit Terminaldiensten ausgeführt, diese Ausführung wird aber weder unterstützt noch empfohlen. In Konfigurationen mit SQL Server-Remoteimplementierungen wird WSUS 3.0 auf Servern mit Terminaldiensten nicht ausgeführt. Da alle benutzerdefinierten Remoteaktionen (einschließlich der Installation) auf einem Terminalserver-Lizenzserver unter dem Systemkonto ausgeführt werden und das Systemkonto des Servers auf dem Remote-SQL-Server möglicherweise nicht über entsprechende Berechtigungen verfügt, kann die Installation fehlschlagen.

Konfigurationsanforderungen für die Installation der WSUS 3.0-Serverkomponente
------------------------------------------------------------------------------

#### IIS muss installiert sein

Für Microsoft Windows Server Update Services 3.0 sind Internetinformationsdienste (IIS) erforderlich, die nicht standardmäßig unter Microsoft Windows Server 2003 oder Windows Server 2008 installiert sind. Wenn Sie versuchen, WSUS 3.0 ohne IIS zu installieren, zeigt das WSUS-Installationsprogramm eine Fehlermeldung an, aus der hervorgeht, dass IIS nicht installiert ist.

#### Wenn IIS im IIS 5.0-Isolationsmodus ausgeführt wird, schlägt die Installation fehl

Wenn Sie auf dem Server ein Upgrade von Windows 2000 Server auf Windows Server 2003 vorgenommen haben, wird IIS möglicherweise im IIS 5.0-Kompatibilitätsmodus ausgeführt. Sollte jedoch stattdessen im IIS-Manager der IIS 5.0-Isolationsmodus aktiviert worden sein, schlägt die Installation fehl. Sie müssen daher vor dem Installieren von WSUS 3.0 den IIS 5.0-Isolationsmodus deaktivieren.

#### Wenn IIS-Komponenten im 32-Bit-Kompatibilitätsmodus auf einer 64-Bit-Plattform installiert sind, kann die Installation von WSUS 3.0 fehlschlagen

Alle IIS-Komponenten sollten auf 64-Bit-Plattformen im 64-Bit-Modus installiert werden. Die Installation kann fehlschlagen, wenn IIS-Komponenten im 32-Bit-Kompatibilitätsmodus installiert sind.

#### Proxyserver müssen sowohl HTTP als auch HTTPS unterstützen

Wenn Sie den WSUS-Stammserver (der WSUS-Server, der Updates direkt von Microsoft Update abruft) konfigurieren und zwischen WSUS-Server und Internet ein Proxyserver bereitgestellt werden soll, muss der Proxyserver sowohl HTTP als auch HTTPS unterstützen.

#### Wenn auf Port 80 mehrere Websites ausgeführt werden, müssen vor der Installation von WSUS so viele Websites gelöscht werden, dass nur noch eine übrig bleibt

Wenn auf Port 80 mehrere Websites (z. B. Windows® SharePoint® Services) ausgeführt werden, müssen Sie vor dem Installieren von WSUS so viele Websites löschen, dass nur noch eine übrig bleibt. Falls Sie dies versäumen, gelingt es den Clients Ihres Servers u. U. nicht, sich selbst zu aktualisieren.

#### Beim Installieren von WSUS 3.0 müssen Antivirenprogramme möglicherweise deaktiviert werden

Beim Installieren von WSUS 3.0 müssen Antivirusprogramme möglicherweise deaktiviert werden, damit die Installation erfolgreich ausgeführt werden kann. Starten Sie den Computer nach dem Deaktivieren des Antivirenprogramms neu. Beginnen Sie erst dann mit dem Installieren von WSUS. Durch den Neustart wird verhindert, dass für den Installationsvorgang erforderliche Dateien gesperrt werden. Wenn die Installation abgeschlossen ist, aktivieren Sie das Antivirusprogramm wieder. Auf der Website des Herstellers des Antivirusprogramms finden Sie genaue Anweisungen zum Deaktivieren und erneuten Aktivieren Ihres Antivirusprogramms.

| ![](images/Cc708491.Caution(WS.10).gif)Vorsicht                                                                                                                                                                                                                                                                                                               |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Diese Problemumgehung kann die Sicherheit des Computers oder Netzwerks vor Angriffen böswilliger Benutzer oder schädlicher Software wie Viren beeinträchtigen. Dieses Verfahren wird nicht empfohlen. Die Informationen werden jedoch zur Verfügung gestellt, damit Sie die Problemumgehung nach eigenem Ermessen verwenden können. Verwenden Sie diese Problemumgehung auf eigene Gefahr. |

> [!NOTE]
> Ein Antivirusprogramm soll den Computer vor Viren schützen. Laden Sie keine Dateien von nicht vertrauenswürdigen Quellen herunter, öffnen Sie diese Dateien nicht, rufen Sie keine nicht vertrauenswürdigen Websites auf, und öffnen Sie keine E-Mail-Anlagen, während das Antivirusprogramm deaktiviert ist. 

#### Für WSUS 3.0 muss die Option für geschachtelte Trigger in SQL Server aktiviert sein

Die Option für geschachtelte Trigger ist standardmäßig aktiviert. Sie kann jedoch vom SQL Server-Administrator deaktiviert werden.

Wenn eine SQL Server-Datenbank als Windows Server Update Services-Datenspeicher verwendet werden soll, sollte der SQL Server-Administrator überprüfen, ob die Option für geschachtelte Trigger auf dem Server aktiviert ist, bevor der WSUS 3.0-Administrator WSUS 3.0 installiert und die Datenbank beim Einrichten von WSUS angibt.

Die datenbankspezifische Option "RECURSIVE\_TRIGGERS" wird vom WSUS 3.0-Setup aktiviert, die globale Serveroption für geschachtelte Trigger jedoch nicht.

Verwenden Sie den folgenden Befehl, um zu überprüfen, ob die Option für geschachtelte Trigger aktiviert ist:

**sp\_configure 'nested triggers'**

Um die Option für geschachtelte Trigger in SQL Server zu aktivieren, führen Sie den folgenden Befehl mithilfe einer Batchdatei auf dem Computer mit SQL Server aus:

**sp\_configure 'nested triggers', 1**

**GO**

**RECONFIGURE**

**GO**

Wenn SQL Server Management Studio nicht auf dem Server verfügbar ist, sollten Sie die SQL-Skripts über die Befehlszeile ausführen. Sie können das Dienstprogramm zur Microsoft SQL Server 2005-Befehlszeilenabfrage im [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=70728) (http://go.microsoft.com/fwlink/?LinkId=70728) herunterladen. Führen Sie zu Beginn **sqlcmd** aus.

Wenn Sie SQL-Skripts für Windows Internal Database ausführen möchten, müssen Sie zusätzlich SQL Native Client von derselben Downloadseite herunterladen.

#### Einschränkungen und Anforderungen für Remote-SQL-Installationen

In WSUS 3.0 können die Datenbanksoftware und die restlichen Komponenten der WSUS 3.0-Anwendung auf getrennten Computern ausgeführt werden. Anforderungen für das Konfigurieren einer Remote-SQL-Installation

-   Für den Back-End-Computer des Remote-SQL-Paars kann kein als Domänencontroller konfigurierter Server verwendet werden.
-   Auf dem Front-End-Server einer Remote-SQL-Installation darf Terminalserver nicht ausgeführt werden.
-   Wenn auf dem Back-End-Computer Windows Server 2003 ausgeführt wird, muss als Datenbanksoftware auf diesem Computer mindestens Microsoft SQL Server 2005 Service Pack 1 (im [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=66143) unter http://go.microsoft.com/fwlink/?LinkId=66143 verfügbar) installiert sein. Für den Fall, dass auf dem Back-End-Computer Windows Server® 2008 ausgeführt wird, muss SQL Server 2005 Service Pack 2 installiert sein.
-   Sowohl der Front-End- als auch der Back-End-Computer müssen einer Active Directory-Domäne beigetreten sein. Sollten sich diese Computer in verschiedenen Domänen befinden, müssen Sie vor dem Installieren von WSUS eine domänenübergreifende Vertrauensstellung zwischen den Domänen einrichten.
-   Wenn in einer Remote-SQL-Konfiguration bereits WSUS 2.0 installiert ist und Sie ein Upgrade auf WSUS 3.0 vornehmen möchten, sollten Sie WSUS 2.0 auf dem Back-End-Computer mithilfe von **Software** in der Systemsteuerung deinstallieren und dabei sicherstellen, dass die vorhandene Datenbank intakt bleibt. Installieren Sie anschließend SQL Server 2005 SP 1 oder SP 2, und aktualisieren Sie die vorhandene Datenbank. Installieren Sie zum Schluss auf dem Front-End-Computer WSUS 3.0.

#### WSUS kann nicht installiert werden, wenn bestimmte Vorabversionen von Internet Explorer 7 in Verbindung mit Terminaldiensten installiert sind

Die Installation von WSUS schlägt fehl, wenn bestimmte Release Candidates von Explorer 7 zusammen mit Terminaldiensten installiert sind.

Systemanforderungen für die Installation der WSUS 3.0-Remotekonsolenkomponente
------------------------------------------------------------------------------

Die Remotekonsolenkomponente von WSUS 3.0 kann auf den folgenden Plattformen installiert werden:

-   Windows Server 2008
-   Windows Vista®
-   Windows Server 2003 SP1
-   Windows XP SP2

Konfigurationsanforderungen für die Installation der WSUS 3.0-Remotekonsolenkomponente
--------------------------------------------------------------------------------------

#### Zwischen Remoteverwaltungskonsole und WSUS 3.0-Server sollte eine Breitbandverbindung vorhanden sein

Wenn Sie den Server mit WSUS 3.0 über eine Schmalband-WAN-Verbindung mit einer Remoteverwaltungskonsole verbinden, kann es zu Geschwindigkeitsproblemen kommen. Sie können zwar die Anzahl der angezeigten Updates und Computer beschränken, indem Sie die entsprechenden Ansichten filtern, es empfiehlt sich aber eher, zwischen der Remoteverwaltungskonsole und den Servern mit WSUS 3.0 eine Breitbandverbindung zu verwenden. Wenn bei der Remotekonsole Probleme mit der Arbeitsgeschwindigkeit auftreten, sollten Sie sich für die Remoteverwaltung über Terminalserver mit dem Server verbinden.

Systemanforderungen für die Installation der Clientkomponente
-------------------------------------------------------------

"Automatische Updates" ist die WSUS-Clientsoftware. Sie kann mit WSUS unter den folgenden Betriebssystemen verwendet werden:

-   Windows Vista
-   Windows Server 2008
-   Microsoft Windows Server 2003, alle Editionen
-   Microsoft Windows XP Professional SP2
-   Microsoft Windows 2000 Professional SP4, Windows 2000 Server SP4 oder Windows 2000 Advanced Server mit SP4

Softwareanforderungen für die Installation der WSUS 3.0-Serverkomponente
------------------------------------------------------------------------

In der folgenden Tabelle wird die für Windows Server 2003 SP 1-Plattformen erforderliche Software aufgeführt. Die für Windows Server 2008 erforderliche Software wird im Abschnitt zu WSUS 3.0 unter Windows Server 2008 behandelt.

Stellen Sie sicher, dass der WSUS 3.0-Server den Anforderungen in dieser Liste entspricht, bevor Sie das WSUS 3.0-Setupprogramm starten. Wenn nach der Installation eines dieser Updates ein Neustart des Computers erforderlich ist, sollten Sie den Computer neu starten, bevor Sie WSUS 3.0 installieren.

###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Anforderung</th>
<th style="border:1px solid black;" >Details</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Internetinformationsdienste (IIS)</td>
<td style="border:1px solid black;">Installation vom Betriebssystem.
Siehe Problem 1: IIS muss installiert sein.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft .NET Framework Version 2.0 Redistributable Package (x86)</td>
<td style="border:1px solid black;">Siehe &quot;Microsoft .NET Framework 2.0 Redistributable (x86)&quot; im <a href="http://go.microsoft.com/fwlink/?linkid=68935">Microsoft Download Center</a> (http://go.microsoft.com/fwlink/?LinkId=68935). Für 64-Bit-Plattformen siehe &quot;Microsoft .NET Framework 2.0 Redistributable (x64)&quot; im <a href="http://go.microsoft.com/fwlink/?linkid=70637">Microsoft Download Center</a> (http://go.microsoft.com/fwlink/?LinkId=70637).</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Management Console 3.0 für Windows Server 2003</td>
<td style="border:1px solid black;">Diese Komponente ist für die Verwendung der WSUS 3.0-Benutzeroberfläche erforderlich. Sie finden sie unter &quot;Microsoft Management Console 3.0 für Windows Server 2003 (KB907265)&quot; im <a href="http://go.microsoft.com/fwlink/?linkid=70412">Microsoft Download Center</a> (http://go.microsoft.com/fwlink/?LinkId=70412). Für 64-Bit-Plattformen finden Sie sie unter &quot;Microsoft Management Console 3.0 for Windows Server 2003 x64 Edition (KB907265)&quot; im <a href="http://go.microsoft.com/fwlink/?linkid=70638">Microsoft Download Center</a> (http://go.microsoft.com/fwlink/?LinkId=70638 – in englischer Sprache).</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Report Viewer</td>
<td style="border:1px solid black;">Diese Komponente ist für die Verwendung der WSUS 3.0-Benutzeroberfläche erforderlich. Siehe &quot;Microsoft Report Viewer Redistributable 2005&quot; im <a href="http://go.microsoft.com/fwlink/?linkid=70410">Microsoft Download Center</a> (http://go.microsoft.com/fwlink/?LinkId=70410).</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">SQL Server 2005 (optional)</td>
<td style="border:1px solid black;">WSUS 3.0 installiert automatisch Windows Internal Database, sofern nicht bereits eine kompatible Version von SQL Server vorhanden ist. Wenn Sie beabsichtigen, eine vollständige SQL Server-Datenbank zu verwenden, müssen Sie unter Windows Server 2003 (mindestens) SQL Server 2005 SP1 verwenden (im <a href="http://go.microsoft.com/fwlink/?linkid=66143">Microsoft Download Center</a> verfügbar unter http://go.microsoft.com/fwlink/?LinkId=66143), und unter Windows Server 2008 muss SQL Server 2005 SP2 installiert sein (im <a href="http://go.microsoft.com/fwlink/?linkid=84823">Microsoft Download Center</a> verfügbar unter http://go.microsoft.com/fwlink/?LinkId=84823).</td>
</tr>
</tbody>
</table>
  
| ![](images/Cc708491.note(WS.10).gif)Hinweis                                                                                                                                                                                                                                                                                                 |  
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| Wenn WSUS 2.0 zuvor installiert wurde und eine Datenbank unter SQL Server 2000, SQL Server Desktop Engine 2000 oder einer anderen SQL Server-Version vor SQL Server 2005 SP 1 (oder unter Windows Server 2008 vor SQL Server 2005 SP2) verwendet wird, wird bei der Installation von WSUS 3.0 Windows® Internal Database installiert und die Datenbank dorthin migriert. |
  
Speicherplatzanforderung für die Installation der WSUS 3.0-Serverkomponente  
---------------------------------------------------------------------------
  
Zum Installieren von Windows Server Update Services ist mindestens der folgende Speicherplatz erforderlich:
  
-   1 GB auf der Systempartition  
-   2 GB auf dem Volume, auf dem die Datenbankdateien gespeichert werden  
-   20 GB auf dem Volume, auf dem die Inhalte gespeichert werden
  
| ![](images/Cc708491.Important(WS.10).gif)Wichtig                                                                 |  
|-----------------------------------------------------------------------------------------------------------------------------------------------|  
| WSUS 3.0 kann nicht auf komprimierten Laufwerken installiert werden. Stellen Sie sicher, dass das ausgewählte Laufwerk nicht komprimiert ist. |
  
Anforderungen für ein Upgrade auf WSUS 3.0  
------------------------------------------
  
#### Vergewissern Sie sich vor dem Upgrade, dass Ihre WSUS-Installation korrekt ausgeführt wird, und erstellen Sie eine Sicherungskopie der WSUS-Datenbank
  
Wenn Sie ein Upgrade von einer früheren Version auf WSUS 3.0 vornehmen, sollten Sie sich zunächst vergewissern, dass die aktuelle Installation korrekt ausgeführt wird, und Sie sollten eine Sicherungskopie der WSUS-Datenbank erstellen.
  
1.  Überprüfen Sie in den Ereignisprotokollen, ob in der jüngeren Vergangenheit Fehler, Probleme bei der Synchronisierung zwischen Downstreamservern und Upstreamservern oder Probleme mit Clients aufgezeichnet wurden, die keine Berichte erstellen. Stellen Sie sicher, dass diese Probleme gelöst wurden, bevor Sie fortfahren.  
2.  Sie können „DBCC CHECKDB“ ausführen, um sicherzustellen, dass die WSUS-Datenbank korrekt indiziert ist. Weitere Informationen zu CHECKDB finden Sie im [Abschnitt zu DBCC CHECKDB](http://go.microsoft.com/fwlink/?linkid=86948) (http://go.microsoft.com/fwlink/?LinkId=86948) (möglicherweise in englischer Sprache).  
3.  Erstellen Sie eine Sicherungskopie der WSUS-Datenbank.
  
#### Software Update Services 1.0 muss deinstalliert werden
  
Die Installation von WSUS 3.0 schlägt fehl, wenn Software Update Services 1.0 auf dem gleichen Computer installiert ist. Sie sollten Software Update Services 1.0 deinstallieren, bevor Sie WSUS 3.0 installieren.
  
#### Die Aktualisierung einer Betaversion von WSUS 3.0 auf die RTM-Version von WSUS 3.0 wird nicht unterstützt, die Aktualisierung der RC-Version auf die RTM-Version ist jedoch zulässig
  
Wenn bereits eine Betaversion von WSUS 3.0 installiert ist, müssen Sie diese deinstallieren und die Datenbank löschen, bevor Sie die RTM-Version von WSUS 3.0 installieren. Eine Aktualisierung ist nur von der RC-Version auf die RTM-Version möglich.
  
#### Eine Aktualisierung von WSUS 2.0 auf WSUS 3.0 auf einem 64-Bit-Betriebssystem ist nicht möglich
  
WSUS 2.0 wird auf 64-Bit-Betriebssystemen nicht unterstützt. Eine Aktualisierung von WSUS 2.0 auf WSUS 3.0 ist auf 64-Bit-Systemen nicht möglich.
  
Befehlszeilenparameter für das Setup  
------------------------------------
  
Mithilfe der WSUS-Befehlszeilenparameter können Sie unbeaufsichtigte Installationen von WSUS 3.0 durchführen. In dieser Tabelle werden die Befehlszeilenparameter für WSUS 3.0 aufgeführt.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Option</th>
<th style="border:1px solid black;" >Beschreibung</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>/q</strong></td>
<td style="border:1px solid black;">Führt eine automatische Installation aus.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>/u</strong></td>
<td style="border:1px solid black;">Deinstalliert das Produkt. Deinstalliert auch die Windows Internal Database-Instanz, sofern vorhanden.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/p</strong></td>
<td style="border:1px solid black;">Überprüft nur die Voraussetzungen. Es erfolgt keine Installation des Produkts, das System wird aber auf das Vorliegen der entsprechenden Voraussetzungen geprüft. Nicht erfüllte Voraussetzungen werden gemeldet.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><strong>/?, /h</strong></td>
<td style="border:1px solid black;">Zeigt die Befehlszeilenparameter und deren Beschreibungen an.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><strong>/g</strong></td>
<td style="border:1px solid black;">Nimmt ein Upgrade von WSUS 2.0 vor. Der einzige gültige Parameter bei dieser Option ist /q (automatische Installation). Die einzige gültige Eigenschaft bei dieser Option lautet „DEFAULT_WEBSITE“.</td>
</tr>
</tbody>
</table>
  
In dieser Tabelle werden die Befehlszeileneigenschaften für WSUS 3.0 aufgeführt.
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Eigenschaft</th>
<th style="border:1px solid black;" >Beschreibung</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">CONTENT_LOCAL</td>
<td style="border:1px solid black;">0=Inhalte lokal gehostet, 1=Auf Microsoft Update gehostet</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">CONTENT_DIR</td>
<td style="border:1px solid black;">Pfad zu Verzeichnis mit Inhalten. Der Standardpfad ist <em>WSUSInstallationslaufwerk</em><strong>\WSUS\WSUSContent</strong>, wobei <em>WSUSInstallationslaufwerk</em> für das lokale Laufwerk mit der größten Menge an freiem Speicherplatz steht.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">WYUKON_DATA_DIR</td>
<td style="border:1px solid black;">Pfad zum Windows Internal Database-Datenverzeichnis.</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">SQLINSTANCE_NAME</td>
<td style="border:1px solid black;">Der Name sollte im Format <em>Servername</em>\<em>SQL-Instanzname</em> angezeigt werden. Wenn sich die Datenbankinstanz auf dem lokalen Computer befindet, verwenden Sie die Umgebungsvariable &quot;%COMPUTERNAME%&quot;. Wenn keine existierende Instanz vorhanden ist, wird als Standard &quot;%COMPUTERNAME%\WSUS&quot; festgelegt.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DEFAULT_WEBSITE</td>
<td style="border:1px solid black;">0=Port 8530, 1=Port 80</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">PREREQ_CHECK_LOG</td>
<td style="border:1px solid black;">Pfad und Dateiname für Protokolldatei</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">CONSOLE_INSTALL</td>
<td style="border:1px solid black;">0=WSUS-Serverkomponente installieren, 1=nur die Konsole installieren</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">ENABLE_INVENTORY</td>
<td style="border:1px solid black;">0=Inventurfeatures nicht installieren, 1=Inventurfeatures installieren</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DELETE_DATABASE</td>
<td style="border:1px solid black;">0=Datenbank beibehalten, 1=Datenbank entfernen</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">DELETE_CONTENT</td>
<td style="border:1px solid black;">0=Inhaltsdateien beibehalten, 1=Inhaltsdateien entfernen</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">DELETE_LOGS</td>
<td style="border:1px solid black;">0=Protokolldateien beibehalten, 1=Protokolldateien entfernen (wird mit dem Installationsschalter /u verwendet)</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">CREATE_DATABASE</td>
<td style="border:1px solid black;">0=Aktuelle Datenbank verwenden, 1=Datenbank erstellen</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">PROGRESS_WINDOW_HANDLE</td>
<td style="border:1px solid black;">Fensterhandle zur Rückgabe von MSI-Statusmeldungen</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">MU_ROLLUP</td>
<td style="border:1px solid black;">1=Am Programm zur Verbesserung von Microsoft Update teilnehmen, 0=Nicht teilnehmen</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">FRONTEND_SETUP</td>
<td style="border:1px solid black;">1=Inhaltsordner nicht in die Datenbank schreiben, 0=Inhaltsordner in die Datenbank schreiben (für NLB)</td>
</tr>
</tbody>
</table>
  
#### Beispiel:
  
```  
WSUSSetup.exe /q DEFAULT\_WEBSITE=0 (install in quiet mode using port 8530) WSUSSetup.exe /q /u (uninstall WSUS)  
```  
| ![](images/Cc708491.Important(WS.10).gif)Wichtig                                                                                                                                                                                            |  
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| Wenn Sie WSUS 3.0 im stillen Modus (/q) installieren, und auf dem Computer nicht alle vorausgesetzten Komponenten installiert sind, wird während der Installation eine Datei mit der Bezeichnung "WSUSPreReqCheck.xml" erstellt und im Verzeichnis "%TEMP%" gespeichert. |
  
Probleme beim Setup  
-------------------
  
#### IIS wird während der Installation von WSUS 3.0 neu gestartet
  
IIS werden vom WSUS 3.0-Setup ohne Benachrichtigung neu gestartet. Dies hat möglicherweise Auswirkungen auf vorhandene Websites Ihrer Organisation. IIS wird bei der Installation von WSUS 3.0 gestartet, wenn dies noch nicht erfolgt ist.
  
#### Wenn Verbindungen zu einer vorhandenen WSUS-Datenbank hergestellt sind, kann die Installation fehlschlagen
  
Wenn Sie von einer vorhandenen Installation auf WSUS 3.0 aktualisieren und Verbindungen zur vorhandenen WSUS-Datenbank hergestellt wurden (z. B. SQL Server Management Studio ist geöffnet), kann die Installation fehlschlagen. Trennen Sie alle Verbindungen, und installieren Sie WSUS 3.0 erneut.
  
#### Bei der WSUS-Installation wird das falsche Verzeichnis für Datenbankdateien angezeigt
  
Auf dem Bildschirm zu Beginn der WSUS-Installation wird fälschlicherweise angezeigt, dass der Speicherort der Datenbank auf das übergeordnete Verzeichnis der Datenbank festgelegt ist. Der Standardspeicherort ist z. B. %systemdrive%\\WSUS\\UpdateServicesDbFiles, dieser Speicherort wird jedoch als %systemdrive%\\WSUS angezeigt.
  
#### Wenn WSUS auf einem Computer installiert wird, auf dem Multilingual User Interface Packs (MUI) mit einer anderen Standardsprache als Englisch vorhanden sind, wird die Hilfe nicht in Englisch, sondern in der Standardsprache angezeigt
  
Auf Computern, auf denen MUI-Packs mit einer anderen Standardsprache als Englisch vorhanden sind, können Sie WSUS auch dann installieren, wenn als Gebietsschema des aktuellen Benutzers Englisch festgelegt ist. Die Benutzeroberfläche wird zwar in Englisch angezeigt, wenn aber auch die Hilfe in Englisch angezeigt werden soll, müssen Sie wie folgt vorgehen: Kopieren Sie die englischsprachige CHM-Hilfedatei (*WSUSInstallationsverzeichnis*\\documentation\\mui\\0409\\WSUS30Help.chm) in das Hauptdokumentationsverzeichnis (*WSUSInstallationsverzeichnis*\\documentation\\WSUS30Help.chm). Die Hilfe müsste nun in allen Sprachen korrekt angezeigt werden.
  
Probleme beim Upgrade  
---------------------
  
#### Beim Upgrade von WSUS 3.0 RC auf WSUS 3.0 RTM wird das SSL-Zertifikat nicht der WSUS-Website zugewiesen
  
Die WSUS-Website wird während des Upgrades von WSUS 3.0 RC auf WSUS 3.0 RTM gelöscht und neu erstellt. Infolgedessen wird das SSL-Zertifikat nicht mehr der WSUS-Website zugewiesen. Sie müssen daher das Zertifikat nach dem Upgrade neu zuweisen.
  
#### Wiederherstellen nach einem fehlgeschlagenen Upgrade
  
Wenn Sie von WSUS 2.0 auf WSUS 3.0 aktualisieren, und das Update fehlschlägt, müssen Sie WSUS 2.0 erneut installieren und die Datenbank aus der Sicherung wiederherstellen.
  
#### Ein Upgrade von WSUS 2.0 auf WSUS 3.0 ist nicht möglich, wenn eine WSUS 3.0-Datenbank aus einer früheren Installation vorhanden ist
  
Wenn Sie bisher WSUS 3.0 verwendet und anschließend erneut WSUS 2.0 installiert haben, müssen Sie die WSUS 3.0-Datenbank auf dem Computer löschen, bevor WSUS 3.0 erneut installiert werden kann.
  
#### Eine Änderung des Computernamens vor dem Upgrade auf WSUS 3.0 kann zum Fehlschlagen des Upgradevorgangs führen
  
Wenn der Computername nach der Installation von WSUS 2.0 und vor der Aktualisierung auf WSUS 3.0 geändert wird, kann die Aktualisierung fehlschlagen.
  
Mithilfe des folgenden Skripts können Sie die Administratorgruppen ASPNET und WSUS entfernen und erneut hinzufügen. Führen Sie die Aktualisierung anschließend erneut durch.
  
*&lt;DBLocation&gt;* muss durch den Ordner ersetzt werden, in dem die Datenbank installiert ist, und *&lt;ContentDirectory&gt;* muss durch den lokalen Speicherordner ersetzt werden.
  
```  
sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "USE SUSDB DECLARE @asplogin varchar(200) SELECT @asplogin=name from sysusers WHERE name like '%ASPNET' EXEC sp\_revokedbaccess @asplogin" sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "USE SUSDB DECLARE @wsusadminslogin varchar(200) SELECT @wsusadminslogin=name from sysusers WHERE name like '%WSUS Administrators' EXEC sp\_revokedbaccess @wsusadminslogin"   sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "USE SUSDB DECLARE @asplogin varchar(200) SELECT @asplogin=HOST\_NAME()+'\\ASPNET' EXEC sp\_grantlogin @asplogin EXEC sp\_grantdbaccess @asplogin EXEC sp\_addrolemember webService,@asplogin" sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "USE SUSDB DECLARE @wsusadminslogin varchar(200) SELECT @wsusadminslogin=HOST\_NAME()+'\\WSUS Administrators' EXEC sp\_grantlogin @wsusadminslogin EXEC sp\_grantdbaccess @wsusadminslogin EXEC sp\_addrolemember webService,@wsusadminslogin"   sqlcmd.exe -S *&lt;DBLocation&gt;* -E -Q "backup database SUSDB to disk=N'*&lt;ContentDirectory&gt;*\\SUSDB.Dat' with init"  
```
  
#### Vorherige Datenbanksicherung kann vom Setup überschrieben werden
  
Bei der Installation von WSUS 3.0 wird die Datenbank dem Verzeichnis hinzugefügt, das während der Installation angegeben wird. In der Standardeinstellung ist dies *%systemdrive%*\\WSUS\\UpdateServicesDbFiles. Wenn in diesem Verzeichnis eine vorherige Datenbanksicherung vorhanden ist, wird diese mit der neuen Datenbank überschrieben. Administratoren sollten Datenbankdateien sichern, bevor Updates auf dem Computer durchgeführt werden, auf dem sich die Datenbank befindet.
  
#### Bei der Migration von MSDE auf SQL Server 2000 oder SQL Server 2005 unter WSUS 2.0 muss ein Registrierungswert geändert werden
  
Wenn Sie in einer WSUS 2.0-Installation eine Migration von SQL Server 2000 oder SQL Server 2005 vorgenommen haben, müssen Sie den Wert **HKLM\\SOFTWARE\\Microsoft\\Update Services\\Server\\Setup\\WmsdeInstalled** von 1 in 0 ändern. Falls Sie dies versäumen und ein Upgrade auf WSUS 3.0 vornehmen, schlägt das Upgrade fehl.
  
#### Beim Abbrechen einer gestarteten WSUS 2.0-Installation wird der WSUS-Registrierungsschlüssel gelöscht
  
Wenn Sie die Installation von WSUS 2.0 starten und dann abbrechen, wird der WSUS-Registrierungsschlüssel gelöscht. Dies kann zu Problemen führen, wenn WSUS 3.0 bereits installiert ist. Das gleiche Problem tritt auf, wenn Sie mit der Deinstallation von WSUS 2.0 beginnen, den Vorgang dann abbrechen und versuchen, eine Aktualisierung von WSUS 2.0 auf WSUS 3.0 durchzuführen.
  
#### Wenn bei der Deinstallation von WSUS 3.0 die Protokolldateien beibehalten werden, haben diese nach einer Neuinstallation möglicherweise nicht mehr die richtigen Berechtigungen
  
Bei der Deinstallation von WSUS 3.0 haben Sie die Option, die Protokolldateien der Installation beizubehalten. Wenn Sie WSUS 3.0 erneut installieren, verlieren die alten Protokolldateien ihre Berechtigungen (normalerweise nur für WSUS-Administratoren). Sie sollten die Berechtigungen für diese Protokolldateien wiederherstellen.
  
#### Wenn Windows SharePoint Services nach WSUS 3.0 RC installiert wurde, kann die Aktualisierung auf WSUS 3.0 RTM mit einer Problemumgehung durchgeführt werden
  
Wenn Sie zuerst WSUS 3.0 RC und dann Windows SharePoint Services auf demselben Computer installiert haben, können Sie die Aktualisierung auf WSUS 3.0 RTM nur durchführen, indem Sie den benutzerdefinierten Port (Port 8530) für die Installation auswählen. Um diese Installation über die Befehlszeile auszuführen, öffnen Sie eine Befehlsshell, und geben Sie dann den folgenden Befehl ein: **WSUSSetup /q / g/ DEFAULT\_WEBSITE=0**. (Um diese Installation über die Benutzeroberfläche auszuführen, geben Sie **WSUSSetup /g DEFAULT\_WEBSITE=0** ein.)
  
Wenn WSUS auf einem Computer mit Multilingual User Interface-Packs (MUI) installiert ist, wird die Hilfe nicht in der aktuellen Sprache des Benutzers, sondern in der Standardsprache angezeigt
  
#### Wenn auf Clients mit WSUS 2.0 Updates mit dem Status „Nicht zutreffend“ vorhanden sind, werden die Updates nach dem Upgrade auf WSUS 3.0 für kurze Zeit als „Unbekannt“ angezeigt
  
Wenn auf einem WSUS 2.0-Server Clients mit Updates mit dem Status „Nicht zutreffend“ vorhanden sind, wird für diese Updates nach dem Upgrade des Servers auf WSUS 3.0 für kurze Zeit der Status „Unbekannt“ angezeigt. Bei der nächsten Prüfung durch den Client wird als Updatestatus wieder „Nicht zutreffend“ angezeigt.
  
Bekannte Probleme  
-----------------
  
#### Problembehandlung bei mehrfachen Downloadfehlern oder wiederholten Synchronisierungsfehlern des Clients
  
Wenn auf einem WSUS 3.0-Client mehrere Downloadfehler auftreten, oder die Synchronisierung des Clients mit dem WSUS 3.0-Server über einen längeren Zeitraum fehlschlägt, ist der Downloadcache des Clients möglicherweise beschädigt. Um diesen Zustand zu beheben, können Sie den Downloadcache des Clients aus dem Dateisystem löschen.
  
So löschen Sie den Downloadcache des Clients
  
1.  Löschen Sie alle Dateien und Unterverzeichnisse im folgenden Speicherort auf dem Clientcomputer: **%windir%\\SoftwareDistribution\\Download**  
2.  Versuchen Sie, das Update zu installieren, indem Sie eine erneute Synchronisierung des Clientcomputers mit WSUS 3.0 ausführen. Dieser Installationsversuch sollte mit einer Meldung ähnlich der folgenden fehlschlagen: **WU\_E\_DM\_NOTDOWNLOADED, "Das Update wurde nicht heruntergeladen."**  
3.  Nach diesem Fehler wird der Download vom Clientcomputer automatisch neu gestartet, und die Installation kann fortgesetzt werden.
  
#### Wenn die Synchronisierung fehlschlägt, führen Sie erneut eine Synchronisierung aus
  
Wenn die Synchronisierung fehlschlägt, sollten Sie zur Problembehandlung zunächst versuchen, den Server erneut zu synchronisieren. Wenn die nachfolgenden Synchronisierungen fehlschlagen, verwenden Sie die Problembehandlungsinformationen im [Windows Server Update Services 3.0-Betriebshandbuch](http://go.microsoft.com/fwlink/?linkid=81072) (http://go.microsoft.com/fwlink/?LinkId=81072 – möglicherweise in englischer Sprache).
  
#### Das direkte Ändern der WSUS 3.0-Konfiguration in der Datenbank wird nicht unterstützt
  
Die Konfigurationsdaten von Windows Server Update Services werden in einer SQL Server-Datenbank gespeichert. Das Ändern der Konfigurationsdaten durch den direkten Zugriff auf die Datenbank wird jedoch nicht unterstützt. Versuchen Sie nicht, die WSUS 3.0-Konfiguration zu ändern, indem Sie direkt auf die Datenbank zugreifen. Ändern Sie die WSUS 3.0-Konfiguration mithilfe der WSUS 3.0-Konsole oder durch Aufrufen von WSUS 3.0-APIs.
  
#### Langsame Benachrichtigung über Downloadfehler bei aktivierten Datenträgerkontingenten
  
Wenn Datenträgerkontingente aktiviert sind und das Kontingent erreicht wird, werden Fehler des WSUS-Servers beim Herunterladen von Updates möglicherweise nicht rechtzeitig angezeigt. Um dieses Problem zu beheben, deaktivieren Sie Datenträgerkontingente oder erhöhen das Kontingent.
  
#### Wenn WSUS 3.0 mithilfe von SSL bereitgestellt wird, kann auf Clientcomputern der Fehler mit dem Fehlercode 0x8024400a auftreten
  
Auf Clientcomputern kann bei der SSL-Kommunikation mit einem WSUS 3.0-Server der Fehler mit Fehlercode "0x8024400a" auftreten. Ein Update zum Behandeln dieses Problems finden Sie im [Knowledge Base-Artikel 905422](http://go.microsoft.com/fwlink/?linkid=70593) (http://go.microsoft.com/fwlink/?LinkId=70593 – möglicherweise in englischer Sprache).
  
#### Das WSUS-Administratordomänenkonto wird bei der Deinstallation von WSUS nicht gelöscht
  
Die WSUS-Administratorgruppe wird als Domänenkonto (nicht als lokales Konto) auf Domänencontrollern erstellt. Alle Installationen, die dieses Domänenkonto verwenden, werden daher beim Deinstallieren von WSUS ungültig. Aus diesem Grund wird das WSUS-Administratordomänenkonto beim Deinstallieren von WSUS nicht gelöscht.
  
#### Wenn ein Downstreamserver in einen Upstreamserver umgewandelt wird, müssen die Katalogstandortupdates erneut importiert werden
  
Wenn Sie einen Downstreamserver zu einem Upstreamserver heraufstufen, müssen Sie alle Katalogstandortupdates erneut importieren. Andernfalls kann der Standort neue Revisionen der Katalogstandortupdates nicht mit diesem Server synchronisieren.
  
#### Beim Verwenden von IIS mit SSL ist nicht verschlüsselter Zugriff weiterhin möglich, wenn die Option „Sicheren Kanal voraussetzen (SSL)“ nicht aktiviert ist
  
Wenn Sie IIS durch Installation eines Sicherheitszertifikats für die Verwendung von SSL eingerichtet haben, ist der Zugriff auf die Site mit nicht verschlüsseltem HTTP weiterhin möglich, falls die Option "Sicheren Kanal voraussetzen (SSL)" nicht aktiviert ist. Weitere Informationen zum [Aktivieren der Verschlüsselung](http://go.microsoft.com/fwlink/?linkid=70601) finden Sie unter http://go.microsoft.com/fwlink/?LinkId=70601 (möglicherweise in englischer Sprache).
  
#### Das Importieren einer Katalogwebsite kann ohne Lese- und Schreibberechtigungen für den Ordner „%windir%\\TEMP“ fehlschlagen
  
Wenn das Netzwerkdienstkonto beim Importieren einer Katalogwebsite nicht über Lese- und Schreibberechtigungen für den Ordner „%windir%\\TEMP“ verfügt, kann das Importieren fehlschlagen. Eine Fehlermeldung wie die folgende wird angezeigt: „Die Anforderung konnte vom Server nicht verarbeitet werden.“ ---&gt; Die Datei 'C:\\WINDOWS\\TEMP\\*tempDateiname*.dll' konnte nicht gefunden werden."
  
#### Synchronisierung zwischen WSUS 3.0 und einem Downstreamreplikatserver mit WSUS 2.0 dauert sehr lange
  
Wenn Sie WSUS 3.0 auf einem Upstreamserver installieren und mit einem Downstreamreplikatserver synchronisieren, auf dem WSUS 2.0 ausgeführt wird, können Leistungsprobleme auftreten. Informationen zum Beheben dieses Problems finden Sie im [Knowledge Base-Artikel 910847](http://go.microsoft.com/fwlink/?linkid=70669) (http://go.microsoft.com/fwlink/?LinkId=70669 – möglicherweise in englischer Sprache).
  
#### Wenn der E-Mail-Server ausgefallen oder nicht erreichbar ist, schlagen E-Mail-Benachrichtigungen ohne Hinweis fehl
  
Wenn der E-Mail-Server des Netzwerks offline ist, werden keine E-Mail-Benachrichtigungen von WSUS 3.0 gesendet, und Sie erhalten keine entsprechenden Benachrichtigungen. In das Ereignisprotokoll wird jedoch Ereignis 10052 (HealthCoreEmailNotificationRed) geschrieben.
  
#### Geänderte Einstellungen auf einem Upstreamserver werden nicht sofort an den Downstreamserver weitergegeben
  
Wenn die Konfiguration des Upstreamservers geändert wird, kann es einige Zeit dauern, bis die Konfigurationsänderungen in Kraft treten. Wenn Sie beispielsweise eine Einstellung auf dem Upstreamserver ändern, z. B. eine neue Sprache auswählen, und sofort auf dem Downstreamserver eine Synchronisierung starten, wird die Änderung nicht übernommen. Stattdessen wird die Änderung bei der nächsten geplanten Synchronisierung vom Downstreamserver übernommen. Die Wartezeit nimmt entsprechend der Anzahl von Updates auf dem Upstreamserver zu.
  
#### Beim Deinstallieren von WSUS 3.0 wird die Datenbankinstanz nicht deinstalliert
  
Bei der Deinstallation von WSUS 3 wird die Datenbankinstanz nicht deinstalliert. Die Instanz wird möglicherweise auch von anderen Anwendungen verwendet, die beim Löschen der Instanz fehlschlagen würden.
  
Falls Windows Internal Database deinstalliert werden muss, kann die Anwendung mit den folgenden Befehlen deinstalliert werden:
  
(auf 32-Bit-Plattformen)
  
```  
msiexec /x {CEB5780F-1A70-44A9-850F-DE6C4F6AA8FB} callerid=ocsetup.exe  
```  
(auf 64-Bit-Plattformen)
  
```  
msiexec /x {BDD79957-5801-4A2D-B09E-852E7FA64D01} callerid=ocsetup.exe  
```  
Sie können den Server-Manager verwenden, um Windows Internal Database Service Pack 2 von Windows Server 2008 zu deinstallieren.
  
Beim Entfernen der Anwendung werden die standardmäßigen MDF- und LDF-Dateien jedoch nicht entfernt. Nachfolgende Installationen von WSUS 3.0 schlagen daher fehl. Diese Dateien können im Verzeichnis "%windir%\\SYSMSI\\SSEE" gelöscht werden.
  
#### Wenn der Upstreamserver eines Downstreamservers geändert wird, werden Updates mit dem Status „Unbekannt“ als „Nicht zutreffend“ gemeldet
  
Wenn ein Downstreamserver die Synchronisierung mit einem anderen Upstreamserver startet, werden Updates mit dem Status "Unbekannt" auf dem neuen Upstreamserver als "Nicht zutreffend" gemeldet. Dieser temporäre Zustand wird beim nächsten Statusbericht des Downstreamservers behoben, nachdem die Clients mit dem Downstreamserver synchronisiert wurden.
  
#### Wenn mehrere Computer mit dem gleichen Namen von einem WSUS 3.0-Replikatserver verwaltet werden, schlägt das Berichterstattungsrollup fehl
  
Wenn mehrere Computer mit dem gleichen Namen von einem WSUS 3.0-Replikatserver verwaltet werden, schlägt das Berichterstattungsrollup fehl. Die für den WSUS-Stammserver verfügbaren Berichte sind daher unvollständig. Dieses Problem wird durch das Löschen aller doppelten Computereinträge auf dem Replikatserver gelöst.
  
#### Wenn der Assistent für die Serverbereinigung über eine Remotekonsole auf mehreren Servern ausgeführt wird und bei einem Server ein Timeout auftritt, werden die Verbindungen zu allen Servern getrennt
  
Der Assistent für die Serverbereinigung kann über eine Remotekonsole auf mehreren Servern ausgeführt werden. Wenn beim Bereinigungsvorgang jedoch auf einem der Server ein Timeout auftritt, werden die Verbindungen der Konsole zu allen Servern getrennt. Es gehen keine Daten verloren. Die Remoteverbindungen zu den einzelnen Servern müssen jedoch vom Administrator zurückgesetzt werden.
  
#### Der Assistent für die Serverbereinigung löscht Dateien schon nach 30 Tagen, nicht erst nach drei Monaten
  
Der Text des Assistenten für die Serverbereinigung ist fehlerhaft. Der Text lautet: „Löschen Sie Updates, die abgelaufen sind und drei Monate lang nicht genehmigt wurden, und löschen Sie alte Revisionen von Updates, die drei Monate lang nicht genehmigt wurden.“ Die korrekte Zeitspanne ist 30 Tage, nicht drei Monate.
  
#### Beim Starten und Beenden der Verbindung in kurzen Abständen hintereinander wird im Konfigurations-Assistenten die Fehlermeldung „Kein Fehler“ angezeigt
  
Bei der Konfiguration von WSUS müssen Sie eine Verbindung zum Upstreamserver (entweder Microsoft Update oder der Upstreamserver des Intranets) herstellen, um grundlegende Informationen über den Server zu übermitteln. Wenn Sie auf **Verbindung starten** und direkt danach auf **Verbinden beenden** klicken, wird irrtümlich die Fehlermeldung "Kein Synchronisierungsfehler" angezeigt.
  
#### WSUS-Clients mit Windows Vista RTM sind nun in der Lage, auf Microsoft Update nach Updates zu suchen
  
Bei vorherigen Versionen von WSUS konnten Clients mit Windows Vista RTM Updates nur vom WSUS-Server abrufen. Bei WSUS 3.0 RTM sind Vista-Clients nun in der Lage, Updates auch von Microsoft Update abzurufen. Sie können Vista-Clients an Microsoft Update verweisen, indem Sie **Windows Update** in der Systemsteuerung aufrufen und auf den Link **Online nach Updates vom Microsoft Update-Dienst suchen** klicken. Wenn die Gruppenrichtlinienoption **Zugriff auf alle Windows Update-Features entfernen** aktiviert ist, wird der Link von Windows Update nicht angezeigt.
  
WSUS 3.0 unter Windows Server 2008  
----------------------------------
  
#### Unterstützte Versionen
  
WSUS 3.0 unterstützt Windows Server 2008 in der 32-Bit- und in der 64-Bit-Version.
  
#### Voraussetzungen
  
###  

 
<table style="border:1px solid black;">
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th style="border:1px solid black;" >Anforderung</th>
<th style="border:1px solid black;" >Details</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Internetinformationsdienste (IIS)</td>
<td style="border:1px solid black;">Installation vom Betriebssystem. Stellen Sie sicher, dass die folgenden Komponenten aktiviert sind:
Windows-Authentifizierung
Statischer Inhalt
ASP.NET
6.0 Verwaltungskompatibilität
IIS Metabase-Kompatibilität</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft .NET Framework Version 2.0 Redistributable Package (x86)</td>
<td style="border:1px solid black;">Nicht erforderlich unter Windows Server 2008, als Teil des Betriebssystems bereits installiert</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;">Microsoft Management Console 3.0</td>
<td style="border:1px solid black;">Nicht erforderlich unter Windows Server 2008, als Teil des Betriebssystems bereits installiert</td>
</tr>
<tr class="even">
<td style="border:1px solid black;">Microsoft Report Viewer</td>
<td style="border:1px solid black;">Diese Komponente ist für die Verwendung der WSUS-Benutzeroberfläche erforderlich. Siehe „Microsoft Report Viewer Redistributable 2005“ im <a href="http://go.microsoft.com/fwlink/?linkid=70410">Microsoft Download Center</a> (http://go.microsoft.com/fwlink/?LinkId=70410).</td>
</tr>
</tbody>
</table>
  
#### Problem 1: Die Konfigurationsdatei von IIS 7.0 muss vor der Ausführung von WSUS 3.0 aktualisiert werden
  
Bevor WSUS 3.0 unter Windows Server 2008 ausgeführt wird, muss die IIS-Konfigurationsdatei aktualisiert werden. Die folgenden Schritte müssen durchgeführt werden:
  
1. Öffnen Sie die IIS-Konfigurationsdatei: %WINDIR%\\system32\\inetsrv\\applicationhost.config
  
2. Entfernen Sie im Tag &lt;System.webServer&gt;&lt;modules&gt; die Zeichenfolge &lt;add name="CustomErrorMode"&gt;, soweit vorhanden.
  
3. Fügen Sie im Tag &lt;System.webServer&gt;&lt;modules&gt; die Zeichenfolge &lt;remove name="CustomErrorMode"&gt; hinzu.
  
Der Tag sollte daraufhin folgendermaßen aussehen:
  
```  
 &lt;System.webServer&gt; &lt;modules&gt; &lt;remove name="CustomErrorMode"&gt; &lt;/modules&gt; &lt;/System.webServer&gt;  
```
  
#### Problem 2: Beim Installieren von WSUS 3.0 auf dem benutzerdefinierten Port unter Windows Server 2008 Beta 3 müssen Sie die Website vorab erstellen
  
Wenn Sie beabsichtigen, WSUS 3.0 unter Windows Server 2008 Beta 3 zu installieren, und Sie WSUS dabei für die Verwendung des benutzerdefinierten Ports 8530 konfigurieren möchten, müssen Sie vor dem Starten des WSUS-Installationsprogramms eine Website mit der Bezeichnung „WSUS-Verwaltung“ auf Port 8530 erstellen.
  
WSUS 3.0 unter Windows Small Business Server 2003  
-------------------------------------------------
  
#### Problem 1: Wenn das virtuelle IIS-Stammverzeichnis auf bestimmte IP-Adressen oder Domänennamen eingeschränkt ist, kann der WSUS 3.0-Server nicht aktualisiert werden
  
Bei einigen Installationen von Windows Small Business Server ist die IIS-Standardwebsite in den "Einschränkungen für IP-Adressen und Domänennamen" enthalten. Ist dies der Fall, ist der Windows Update-Client auf dem Server möglicherweise nicht in der Lage, sich selbst zu aktualisieren.
  
#### Problem 2: Installieren von WSUS 3.0 unter Small Business Server – Integrationsprobleme
  
-   Wenn in Windows Small Business Server 2003 ein ISA-Proxyserver zum Herstellen einer Internetverbindung verwendet wird, müssen unter **Einstellungen** folgende Informationen eingegeben werden: Proxyservereinstellungen, Proxyservername und Port.  
-   Wenn ISA die Windows-Authentifizierung verwendet, müssen die Anmeldeinformationen für den Proxyserver im Format "DOMÄNE\\Benutzer" eingegeben werden. Der Benutzer muss Mitglied der Gruppe "Internetbenutzer" sein.
  
#### Problem 3: Wenn Sie ein Subnetz ohne den Windows SBS-Assistenten zum Netzwerk hinzugefügt haben, müssen Sie das folgende Verfahren durchführen
  
Während des Setupvorgangs des WSUS-Servers werden zwei virtuelle IIS-Stämme auf dem Server installiert: „SelfUpdate“ und „ClientWebService“. Weiterhin werden beim Setup einige Dateien im Basisverzeichnis der Standardwebsite (auf Port 80) erstellt, mit denen Clientcomputer automatisch über die Standardwebsite aktualisiert werden können. Normalerweise ist die Standardwebsite so konfiguriert, dass der Zugriff für alle IP-Adressen bis auf den lokalen Host bzw. für bestimmte mit dem Server verbundene Subnetze verweigert wird. Clientcomputer, die sich nicht auf dem lokalen Host oder in diesen bestimmten Subnetzen befinden, können daher nicht automatisch aktualisiert werden. Wenn Sie ein Subnetz ohne die Microsoft Windows Small Business Server 2003-Assistenten zum Netzwerk hinzugefügt haben, müssen Sie die folgenden Schritte ausführen.
  
1.  Erweitern Sie in der Serververwaltung die Optionen **Erweiterte Verwaltung**, **Internetinformationsdienste**, **Websites** sowie **Standardwebsite**. Klicken Sie mit der rechten Maustaste auf das virtuelle Verzeichnis **Selfupdate**, und klicken Sie dann auf **Eigenschaften**.  
2.  Klicken Sie auf **Verzeichnissicherheit**.  
3.  Klicken Sie unter **Einschränkungen für IP-Adressen und Domänennamen** auf **Bearbeiten** und dann auf **Zugriff gewährt**.  
4.  Klicken Sie auf **OK**. Klicken Sie mit der rechten Maustaste auf das virtuelle Verzeichnis **ClientWebService**, und klicken Sie dann auf **Eigenschaften**.  
5.  Klicken Sie auf **Verzeichnissicherheit**.  
6.  Klicken Sie unter **Einschränkungen für IP-Adressen und Domänennamen** auf **Bearbeiten** und dann auf **Zugriff gewährt**.
  
#### Copyright
  
Dieses Dokument behandelt eine Vorabversion eines Softwareprodukts, das bis zur Veröffentlichung grundlegend geändert werden kann. Bei der Vorabversion handelt es sich um vertrauliche und geschützte Informationen der Microsoft Corporation. Das Dokument wird gemäß einer Vertraulichkeitsvereinbarung zwischen dem Empfänger und Microsoft bereitgestellt. Dieses Dokument dient nur zu Informationszwecken. Microsoft übernimmt keine Garantien für dieses Dokuemt, weder ausdrücklich noch konkludent. Die Informationen in diesem Dokument, einschließlich URLs und anderer Verweise auf Internetwebsites, können ohne vorherige Ankündigung geändert werden. Alle Risiken bei der Verwendung dieses Dokument bzw. die Folgen der Verwendung dieses Dokuments trägt der Benutzer. Die in den Beispielen verwendeten Firmen, Organisationen, Produkte, Domänenamen, E-Mail-Adressen, Logos, Personen, Orte und Ereignisse sind frei erfunden, soweit nicht anders angegeben. Jede Ähnlichkeit mit bestehenden Firmen, Organisationen, Produkten, Domänennamen, E-Mail-Adressen, Logos, Personen, Orten oder Ereignissen ist rein zufällig. Die Benutzer sind verpflichtet, sich an alle anwendbaren Urheberrechtsgesetze zu halten. Unabhängig von der Anwendbarkeit der entsprechenden Urheberrechtsgesetze darf ohne ausdrückliche schriftliche Erlaubnis der Microsoft Corporation kein Teil dieses Dokuments für irgendwelche Zwecke vervielfältigt oder in einem Datenempfangssystem gespeichert oder darin eingelesen werden, unabhängig davon, auf welche Art und Weise oder mit welchen Mitteln (elektronisch, mechanisch, durch Fotokopieren, Aufzeichnen usw.) dies geschieht.
  
Es ist möglich, dass Microsoft Rechte an Patenten bzw. angemeldeten Patenten, an Marken, Urheberrechten oder sonstigem geistigen Eigentum besitzt, die sich auf den fachlichen Inhalt dieses Dokuments beziehen. Das Bereitstellen dieses Dokuments gibt Ihnen jedoch keinen Anspruch auf diese Patente, Marken, Urheberrechte oder auf sonstiges geistiges Eigentum, es sei denn, dies wird ausdrücklich in den schriftlichen Lizenzverträgen von Microsoft eingeräumt.
  
© 2007 Microsoft Corporation. Alle Rechte vorbehalten.
  
Microsoft, SQL Server, Windows und Windows Server sind eingetragene Marken oder Marken der Microsoft Corporation in den USA und/oder anderen Ländern.
  
Alle weiteren Marken sind Eigentum der jeweiligen Inhaber.