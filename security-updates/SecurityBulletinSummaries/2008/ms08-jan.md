---
TOCTitle: 'MS08-JAN'
Title: Microsoft Security Bulletin Summary für Januar 2008
ms:assetid: 'ms08-jan'
ms:contentKeyID: 61225059
ms:mtpsurl: 'https://technet.microsoft.com/de-DE/library/ms08-jan(v=Security.10)'
---

Security Bulletin Summary

Microsoft Security Bulletin Summary für Januar 2008
===================================================

Veröffentlicht: Dienstag, 8. Januar 2008 | Aktualisiert: Freitag, 25. Januar 2008

**Version:** 1.2

In diesem Bulletin Summary sind die im Januar 2008 veröffentlichten Security Bulletins aufgeführt.

Mit der Veröffentlichung der Bulletins für Januar 2008 ersetzt dieses Bulletin Summary die Bulletin Advance Notification, die erstmalig am 3. Januar 2008 veröffentlicht wurde. Weitere Informationen zum Bulletin Advance Notification-Service finden Sie unter [Microsoft Security Bulletin Advance Notification](http://www.microsoft.com/germany/technet/sicherheit/bulletins/bulletinadvance.mspx).

Weitere Informationen zum Erhalten automatischer Benachrichtigungen über die Veröffentlichung von Microsoft Security Bulletins finden Sie unter [Microsoft Technische Sicherheitsbenachrichtigungen](http://www.microsoft.com/germany/technet/sicherheit/bulletins/notify.mspx).

Am Mittwoch, den 9. Januar 2008 um 11:00 Uhr pazifischer Zeit (USA & Kanada) stellt Microsoft einen Webcast bereit, um Kundenfragen zu diesen Bulletins zu beantworten. [Registrieren Sie sich jetzt für den Security Bulletin-Webcast im Januar](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032357213&eventcategory=4&culture=en-us&countrycode=us). Ab diesem Datum steht dieser Webcast auf Anfrage zur Verfügung. Weitere Informationen dazu finden Sie unter [Microsoft Security Bulletin Zusammenfassungen und Webcasts.](http://technet.microsoft.com/security/bulletin/summary)

Microsoft stellt auch Informationen bereit, anhand derer Benutzer die Prioritäten für monatliche Sicherheitsupdates und alle nicht sicherheitsrelevanten wichtigen Updates festlegen können, die an demselben Tag veröffentlicht werden wie die monatlichen Sicherheitsupdates. Bitte lesen Sie den Abschnitt **Weitere Informationen**.

### Bulletin-Informationen

#### Kurzzusammenfassungen

Die Security Bulletins für diesen Monat, nach Schweregrad geordnet:

Kritisch (1)
------------

| Kennung des Bulletins                      | Microsoft Security Bulletin MS08-001                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|--------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                    | [**Sicherheitsanfälligkeiten in Windows TCP/IP können Remotecodeausführung ermöglichen (941644)**](http://www.microsoft.com/germany/technet/sicherheit/bulletins/ms08-001.mspx)                                                                                                                                                                                                                                                                                          |
| **Kurzzusammenfassung**                    | Dieses kritische Sicherheitsupdate behebt zwei vertraulich gemeldete Sicherheitsanfälligkeiten in der TCP/IP-Verarbeitung (Transmission Control-Protokoll/Internetprotokoll). Nutzt ein Angreifer diese Sicherheitsanfälligkeit erfolgreich aus, kann er die vollständige Kontrolle über ein betroffenes System erlangen. Ein Angreifer kann dann Programme installieren, Daten anzeigen, ändern oder löschen oder neue Konten mit sämtlichen Benutzerrechten erstellen. |
| **Bewertung des maximalen Schweregrads**   | [Kritisch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                                      |
| **Auswirkung der Sicherheitsanfälligkeit** | Remotecodeausführung                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Erkennung**                              | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Das Update erfordert einen Neustart.                                                                                                                                                                                                                                                                                                                                   |
| **Betroffene Software**                    | **Windows.** Weitere Informationen finden Sie im Abschnitt „Betroffene Software und Downloadadressen“.                                                                                                                                                                                                                                                                                                                                                                   |

Hoch (1)
--------

| Kennung des Bulletins                      | Microsoft Security Bulletin MS08-002                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|--------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                    | [**Sicherheitsanfälligkeit in LSASS kann lokale Erhöhung von Berechtigungen ermöglichen (943485)**](http://www.microsoft.com/germany/technet/sicherheit/bulletins/ms08-002.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Kurzzusammenfassung**                    | Dieses wichtige Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit im Subsystemdienst für die lokale Sicherheitsautorität (LSASS) von Microsoft Windows. Diese Sicherheitsanfälligkeit kann einem Angreifer ermöglichen, beliebigen Code mit erhöhten Berechtigungen auszuführen. Nutzt ein Angreifer diese Sicherheitsanfälligkeit erfolgreich aus, kann er die vollständige Kontrolle über ein betroffenes System erlangen. Ein Angreifer kann dann Programme installieren, Daten anzeigen, ändern oder löschen oder neue Konten mit sämtlichen Benutzerrechten erstellen. |
| **Bewertung des maximalen Schweregrads**   | [Hoch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Auswirkung der Sicherheitsanfälligkeit** | Lokale Erhöhung von Berechtigungen                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Erkennung**                              | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Das Update erfordert einen Neustart.                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Betroffene Software**                    | **Windows.** Weitere Informationen finden Sie im Abschnitt „Betroffene Software und Downloadadressen“.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |

Betroffene Software und Downloadadressen
----------------------------------------

**Wie verwende ich diese Tabelle?**  

In dieser Tabelle finden Sie Informationen zu Sicherheitsupdates, die Sie möglicherweise installieren sollten. Sie sollten jedes aufgeführte Softwareprogramm und jede Komponente überprüfen, um zu sehen, ob Sicherheitsupdates erforderlich sind. Wenn ein Softwareprogramm oder eine Komponente aufgeführt ist, ist die Auswirkung der Sicherheitsanfälligkeit aufgelistet und mit einem Softwareupdate verlinkt.

**Hinweis:** Für eine Sicherheitsanfälligkeit müssen Sie möglicherweise mehrere Sicherheitsupdates installieren. Prüfen Sie für jede aufgeführte Kennung der Bulletins die gesamte Spalte, um basierend auf den in Ihrem System installierten Programmen und Komponenten alle Updates zu finden, die Sie installieren müssen.

**Betroffene Software und Downloadadressen**

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
Details        
</th>
<th style="border:1px solid black;" >
Details        
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS08-001**](http://www.microsoft.com/germany/technet/sicherheit/bulletins/ms08-001.mspx)
</td>
<td style="border:1px solid black;">
[**MS08-002**](http://www.microsoft.com/germany/technet/sicherheit/bulletins/ms08-002.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des maximalen Schweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows-Betriebssystem:
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=980f5457-c7b5-421c-8643-0e57429ec156)
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=7956632e-17d9-4876-8340-84fe3e43e5cc)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=0a766242-2342-4fa0-9b66-8953c54a2211)
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=6a4cf182-8e36-490e-aefe-edb7b3a0df9c)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition und Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=2e8bc7d5-fe81-4ed5-9efa-360738d160ee)
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?familyid=51fc657b-2b4a-4725-a744-d279e027c4a5)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1 und Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=fda060a5-9a1e-4036-9899-13eb61fdd8be)
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=12397b47-b18f-4d4d-b8d7-adec8ff310d5)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition und Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=19d993f9-06dd-4dc4-b0cc-c59e822eb8fa)
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=f19fd790-a4e6-4a8a-8077-d1bbfe37ecca)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 mit SP1 für Itanium-basierte Systeme und Windows Server 2003 mit SP2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=2c2264f7-ebbb-40ab-9dbf-9b4e313665a7)
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=0382a195-aa3d-409b-8a79-9fe61588d8a9)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Small Business Server 2003 Service Pack 1, Windows Small Business Server 2003 R2, Windows Small Business Server 2003 R2 Service Pack 2 und Windows Home Server
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=fda060a5-9a1e-4036-9899-13eb61fdd8be)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=23c0e03a-db66-4618-bce0-af55e5c1b067)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=5f6a37b1-c604-47c9-932f-485db2eda133)
</td>
<td style="border:1px solid black;">
</td>
</tr>
</table>
 

Tools und Anleitungen zur Erkennung und Bereitstellung
------------------------------------------------------

**Sicherheitsportal:**

Verwalten Sie die Software und die Sicherheitsupdates, die Sie den Servern, Desktops und mobilen Computer in Ihrer Organisation bereitstellen müssen. Weitere Informationen finden Sie im [TechNet Update Management Center](http://technet.microsoft.com/de-de/updatemanagement/default.aspx). Im [TechNet Security Center](http://www.microsoft.com/germany/technet/sicherheit/default.mspx) werden zusätzliche Informationen zur Sicherheit in Microsoft-Produkten zur Verfügung gestellt. Verbraucher können die Seite [Sicherheit zu Hause](http://www.microsoft.com/germany/athome/security/default.mspx) besuchen, wo diese Informationen auch durch einen Klick auf „Die neuesten Sicherheitsupdates“ verfügbar sind.

Sicherheitsupdates sind auch über [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) und [Office Update](http://office.microsoft.com/de-de/officeupdate/default.aspx) verfügbar. Sicherheitsupdates sind auch im [Microsoft Download Center](http://www.microsoft.com/downloads/results.aspx?displaylang=de&freetext=sicherheitsupdate) verfügbar. Sie können am einfachsten durch eine Suche nach dem Begriff „security update“ ermittelt werden.

Außerdem können Sicherheitsupdates vom [Windows Update-Katalog](http://go.microsoft.com/fwlink/?linkid=96155) heruntergeladen werden. Der Microsoft Update-Katalog stellt einen durchsuchbaren Katalog der Inhalte bereit, die über Windows Update und Microsoft Update zur Verfügung gestellt werden, einschließlich Sicherheitsupdates, Treiber und Service Packs. Indem Sie mit der Nummer des Security Bulletins suchen (z. B. „MS07-036“), können Sie Ihrem Warenkorb alle anwendbaren Updates (einschließlich verschiedener Sprachen für ein Update) hinzufügen und in den Ordner Ihrer Wahl herunterladen. Weitere Informationen zum Microsoft Update-Katalog, finden Sie unter [Häufig gestellte Fragen zum Microsoft Update-Katalog](http://catalog.update.microsoft.com/v7/site/faq.aspx).

**Anleitungen zur Erkennung und Bereitstellung**

Zu den Sicherheitsupdates dieses Monats stellt Microsoft Anleitungen zur Erkennung und Bereitstellung zur Verfügung: Diese Anleitungen geben auch IT-Profis Informationen zum Einsatz der verschiedenen Tools und zur Bereitstellung des Sicherheitsupdates. Behandelt werden u. a. Windows Update, Microsoft Update, Office Update, Microsoft Baseline Security Analyzer (MBSA), Office Detection Tool, Microsoft Systems Management Server (SMS) und das Erweiterte Sicherheitsupdate-Inventurprogramm (ESUIT). Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer**

Mit dem Microsoft Baseline Security Analyzer können Sie als Administrator Systeme sowohl lokal als auch remote auf fehlende Sicherheitspatches und fehlerhafte Konfigurationen überprüfen. Weitere Informationen zu MBSA finden Sie auf der Website [Microsoft Baseline Security Analyzer](http://www.microsoft.com/germany/technet/sicherheit/tools/mbsa/2_0.mspx).

**Windows Server Update Services**

Mithilfe der Windows Server Update Services (WSUS), können Administratoren die neuesten wichtigen Aktualisierungen und Sicherheitsupdates für Windows 2000 und höher, Office XP und höher, Exchange Server 2003 und SQL Server 2000 schnell und zuverlässig bereitstellen.

Weitere Informationen zum Bereitstellen dieses Sicherheitsupdates mithilfe der Windows Server Update Services finden Sie auf der [Windows Server Update Services Website](http://www.microsoft.com/germany/technet/prodtechnol/windowsserver/wsus/default.mspx).

**Systems Management Server**

Der Systems Management Server von Microsoft stellt eine wertvolle Hilfe beim Bereitstellen von Sicherheitsupdates in Ihrer IT-Umgebung dar. Durch die Verwendung von SMS können Administratoren auf Windows basierte Systeme identifizieren, für die Sicherheitsupdates erforderlich sind, und für eine kontrollierte Bereitstellung dieser Updates im gesamten Unternehmen bei minimalen Unterbrechungen für Endbenutzer sorgen. Die nächste Version von SMS, System Center Configuration Manager 2007, ist jetzt verfügbar (siehe auch [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)). Weitere Informationen zur Verwendung von SMS 2003 durch Administratoren für die Bereitstellung von Sicherheitsupdates finden Sie unter [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). Benutzer von SMS 2.0 können auch die Website [Software Updates Service Feature Pack](http://www.microsoft.com/technet/prodtechnol/sms/sms2/downloads/featurepacks/suspack/default.mspx) besuchen, um Hilfe bei der Bereitstellung von Sicherheitsupdates zu erhalten. Weitere Informationen zu SMS finden Sie auf der Website [Microsoft Systems Management Server](http://www.microsoft.com/germany/smserver/default.mspx).

**Hinweis:** SMS nutzt Microsoft Baseline Security Analyzer und das Microsoft Office Detection Tool, um eine breite Unterstützung bei der Erkennung und der Bereitstellung von Security Bulletin-Updates bereitzustellen. Einige Softwareupdates werden von diesen Tools möglicherweise nicht erkannt. Administratoren können in diesen Fällen die Inventurfunktionen von SMS nutzen, um Updates auf ausgewählten Systemen zu installieren. Weitere Informationen zu diesem Verfahren finden Sie auf der Website [Bereitstellen von Softwareupdates mit der Funktion zur Softwareverteilung von SMS](http://www.microsoft.com/technet/sms/2003/patchupdate.mspx). Bei einigen Sicherheitsupdates, die einen Neustart des Systems erfordern, sind unter Umständen administrative Rechte nötig. Administratoren können das im [SMS 2003 Administration Feature Pack](http://www.microsoft.com/technet/prodtechnol/sms/sms2003/downloads/featurepacks/adminpack.mspx) und im [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161) enthaltene Elevated Rights Deployment Tool verwenden, um diese Updates zu installieren.

### Weitere Informationen:

#### Windows-Tool zum Entfernen bösartiger Software

Microsoft hat eine aktualisierte Version des Microsoft Windows-Tools zum Entfernen bösartiger Software in Windows Update, Microsoft Update, Windows Server Update Services und dem Download Center veröffentlicht.

#### Nicht sicherheitsrelevante, wichtige Updates unter MU, WU und WSUS:

Für diesen Monat:

-   Microsoft hat fünf **nicht sicherheitsrelevante** Updates mit hoher Priorität auf Microsoft Update (MU) und Windows Server Update Services (WSUS) veröffentlicht.
-   Microsoft hat zwei **nicht sicherheitsrelevante** Updates mit hoher Priorität für Windows auf Windows-Update (WU) und WSUS veröffentlicht.

Diese Informationen gelten **nur** für wichtige, **nicht sicherheitsrelevante** Updates auf Microsoft Update, Windows Update und Windows Server Update Services, die an demselben Tag wie das Security Bulletin Summary veröffentlicht wurden. Es werden **keine** Informationen zu **nicht sicherheitsrelevanten** Updates bereitgestellt, die an anderen Tagen veröffentlicht werden.

#### Sicherheitsstrategien und Community

**Strategien für die Verwaltung von Sicherheitspatches:**

Auf der Seite [Security Guidance für Patchverwaltung](http://www.microsoft.com/germany/technet/sicherheit/themen/patchmanagement.mspx) werden zusätzliche Informationen zu den empfohlenen Vorgehensweisen für die Anwendung von Sicherheitsupdates von Microsoft bereitgestellt.

**Weitere Sicherheitsupdates**

Updates für andere Sicherheitsrisiken sind unter den folgenden Adressen erhältlich:

-   Sicherheitsupdates sind im [Microsoft Download Center](http://www.microsoft.com/downloads/results.aspx?displaylang=de&freetext=sicherheitsupdate) verfügbar Sie können am einfachsten durch eine Suche nach dem Begriff „security update“ ermittelt werden.
-   Updates für Benutzerplattformen sind auf [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) verfügbar.
-   Die Sicherheitsupdates, die in diesem Monat über Windows Update veröffentlicht wurden, können Sie auch im „Security and Critical Releases ISO CD Image“ über Microsoft Download Center erhalten. Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 913086](http://support.microsoft.com/kb/913086).

**IT Pro Security Community:**

Auf der Website [IT Pro Security Community](http://go.microsoft.com/fwlink/?linkid=21164) erfahren Sie, wie Sie die Sicherheit erhöhen und die IT-Infrastruktur optimieren können. Sie haben zudem die Möglichkeit sich mit anderen IT-Fachleuten über Sicherheitsthemen auszutauschen.

#### Danksagungen

Microsoft [dankt](http://www.microsoft.com/germany/technet/sicherheit/bulletins/policy.mspx) den folgenden Personen, dass sie zum Schutz unserer Kunden mit uns zusammengearbeitet haben:

-   [IBM Internet Security Systems X-Force](http://www.iss.net/) von Alex Wheeler und Ryan Smith für den Hinweis auf ein in [MS08-001](http://www.microsoft.com/germany/technet/sicherheit/bulletins/ms08-001.mspx) beschriebenes Problem
-   [IBM Internet Security Systems X-Force](http://www.iss.net/) von Alex Wheeler und Ryan Smith für den Hinweis auf ein in [MS08-001](http://www.microsoft.com/germany/technet/sicherheit/bulletins/ms08-001.mspx) beschriebenes Problem
-   Thomas Garnier von [SkyRecon](http://www.skyrecon.com/) für den Hinweis auf ein in [MS08-002](http://www.microsoft.com/germany/technet/sicherheit/bulletins/ms08-002.mspx) beschriebenes Problem.

#### Support

-   Die betroffene Software wurde getestet, um die betroffenen Versionen zu ermitteln. Andere Versionen haben das Ende ihrer Supportlebenszyklen erreicht. Besuchen Sie die Website [Microsoft Support Lifecycle](http://support.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle), um den Supportlebenszyklus für Ihre Softwareversion zu ermitteln.
-   Technischer Support ist über die [Microsoft Support Services](http://go.microsoft.com/fwlink/?linkid=21131) erhältlich. Supportanrufe zu Sicherheitsupdates sind kostenlos.
-   Kunden außerhalb der USA erhalten Support bei ihren regionalen Microsoft-Niederlassungen. Supportanfragen zu Sicherheitsupdates sind kostenlos. Weitere Informationen dazu, wie Sie Microsoft in Bezug auf Supportfragen kontaktieren können, finden Sie auf der Website [Internationale Hilfe und Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Haftungsausschluss

Die Informationen der Microsoft Knowledge Base werden wie besehen und ohne jede Gewährleistung bereitgestellt. Microsoft schließt alle anderen Garantien, gleich ob ausdrücklich oder konkludent, einschließlich der Garantien der Handelsüblichkeit oder Eignung für einen bestimmten Zweck aus. In keinem Fall kann Microsoft Corporation und/oder deren jeweilige Lieferanten haftbar gemacht werden für Schäden irgendeiner Art, einschließlich direkter, indirekter, zufällig entstandener Schäden, Folgeschäden, Folgen entgangenen Gewinns oder spezieller Schäden, selbst dann nicht, wenn Microsoft Corporation und/oder deren jeweilige Lieferanten auf die mögliche Entstehung dieser Schäden hingewiesen wurde. Weil in einigen Staaten/Rechtsordnungen der Ausschluss oder die Beschränkung einer Haftung für zufällig entstandene Schäden oder Folgeschäden nicht gestattet ist, gilt die obige Einschränkung eventuell nicht für sie.

#### Revisionen

-   V1.0 (8. Januar 2008): Bulletin Summary veröffentlicht.
-   V1.1 (23. Januar 2008): Aktualisierung der Bulletin Summary, um dem Bulletin MS08-001 Windows Small Business Server 2003 Service Pack 2 als betroffene Software hinzuzufügen.
-   V1.2 (25. Januar 2008): Aktualisierung der Bulletin Summary, um dem Bulletin MS08-001 Windows Small Business Server 2003 Service Pack 1, Windows Small Business Server 2003 R2, Windows Small Business Server 2003 R2 Service Pack 2 und Windows Home Server als betroffene Software hinzuzufügen.

*Built at 2014-04-18T01:50:00Z-07:00*
