---
TOCTitle: 'MS15-AUG'
Title: Microsoft Security Bulletin Summary für August 2015
ms:assetid: 'ms15-aug'
ms:contentKeyID: 68236015
ms:mtpsurl: 'https://technet.microsoft.com/de-DE/library/ms15-aug(v=Security.10)'
---

Microsoft Security Bulletin Summary für August 2015
===================================================

Veröffentlicht: 11. August 2015 | Aktualisiert: 1. Dezember 2015

**Version:** 3.1

In diesem Bulletin Summary sind die im August 2015 veröffentlichten Security Bulletins aufgeführt.

Weitere Informationen zum Erhalten automatischer Benachrichtigungen über die Veröffentlichung von Microsoft Security Bulletins finden Sie unter [Microsoft Technische Sicherheitsbenachrichtigungen](http://technet.microsoft.com/de-de/security/dd252948.aspx).

Microsoft stellt auch Informationen bereit, anhand derer Benutzer die Prioritäten für monatliche Sicherheitsupdates und alle nicht sicherheitsrelevanten Updates festlegen können, die an demselben Tag veröffentlicht werden wie die monatlichen Sicherheitsupdates. Bitte lesen Sie den Abschnitt **Weitere Informationen**.

Kurzzusammenfassungen
---------------------

In der folgenden Tabelle sind die Security Bulletins für diesen Monat nach Schweregrad geordnet.

Weitere Informationen zu betroffener Software finden Sie im nächsten Abschnitt **Betroffene Software**.

<p></p>
<table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Kennung des Bulletins</strong></td>
<td style="border:1px solid black;"><strong>Titel des Bulletins und Kurzzusammenfassung</strong></td>
<td style="border:1px solid black;"><strong>Bewertung des maximalen Schweregrads<br />
und Auswirkung der Sicherheitsanfälligkeit</strong></td>
<td style="border:1px solid black;"><strong>Neustartanforderung</strong></td>
<td style="border:1px solid black;"><strong>Bekannte<br />
Probleme</strong></td>
<td style="border:1px solid black;"><strong>Betroffene Software</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;"><strong>Kumulatives Sicherheitsupdate für Internet Explorer (3082442)</strong> <br />
Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Internet Explorer. Die schwerwiegendste dieser Sicherheitsanfälligkeiten kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Webseite mit Internet Explorer anzeigt. Ein Angreifer, der diese Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann die gleichen Benutzerrechte wie der aktuelle Benutzer erlangen. Benutzer mit Konten, die über weniger Systemrechte verfügen, sind davon möglicherweise weniger betroffen als Benutzer mit Administratorrechten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in Microsoft Graphics-Komponente können Remotecodeausführung ermöglichen (3078662)</strong><br />
Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft Windows, Microsoft .NET Framework, Microsoft Office, Microsoft Lync und Microsoft Silverlight. Die schwerwiegendste Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer ein speziell gestaltetes Dokument öffnet oder eine nicht vertrauenswürdige Website besucht, in das bzw. die TrueType- oder OpenType-Schriftartdateien eingebettet sind.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework,<br />
Microsoft Office,<br />
Microsoft Lync,<br />
Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-081">MS15-081</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in Microsoft Office können Remotecodeausführung ermöglichen (3080790)<br />
</strong>Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft Office. Die schwerwiegendste Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Microsoft Office-Datei öffnet. Ein Angreifer, der die Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann beliebigen Code im Kontext des aktuellen Benutzers ausführen. Benutzer mit Konten, die über weniger Systemrechte verfügen, sind davon möglicherweise weniger betroffen als Benutzer mit Administratorrechten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/de-de/kb/3080790">3080790</a></td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-082">MS15-082</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in RDP können Remotecodeausführung ermöglichen (3080348)<br />
</strong>Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft Windows. Die schwerste dieser Sicherheitsanfälligkeiten kann die Remotecodeausführung ermöglichen, wenn ein Angreifer zunächst eine speziell gestaltete DLL-Datei (Dynamic Link Library) in das aktuelle Arbeitsverzeichnis des Zielbenutzers einfügt und den Benutzer dann dazu verleitet, eine RDP-Datei (Remote Desktop Protocol) zu öffnen oder ein Programm zu starten, die bzw. das darauf ausgelegt ist, eine vertrauenswürdige DLL zu laden, stattdessen jedoch die speziell gestaltete DLL-Datei lädt. Ein Angreifer, der diese Sicherheitsanfälligkeiten erfolgreich ausnutzt, könnte die vollständige Kontrolle über das betroffene System erlangen. Ein Angreifer kann dann Programme installieren, Daten anzeigen, ändern oder löschen oder neue Konten mit sämtlichen Benutzerrechten erstellen.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/de-de/kb/3080348">3080348</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-083">MS15-083</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit im SMB (Server Message Block) kann Remotecodeausführung ermöglichen (3073921) <br />
</strong>Dieses Sicherheitsupdate behebt eine Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Angreifer eine speziell gestaltete Zeichenfolge an die SMB-Serverfehlerprotokollierung sendet.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-084">MS15-084</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten im Microsoft XML Core Services können Offenlegung von Informationen ermöglichen (3080129)</strong> <br />
Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft Windows und Microsoft Office. Die Sicherheitsanfälligkeiten können die Offenlegung von Informationen ermöglichen, indem die Verwendung von SSL 2.0 (Secure Sockets Layer) explizit zugelassen wird oder Speicheradressen veröffentlicht werden, wenn ein Benutzer auf einen speziell gestalteten Link klickt. Ein Angreifer hat jedoch keine Möglichkeit, Benutzer zum Klicken auf einen speziell gestalteten Link zu zwingen. Vielmehr muss ein Angreifer die Benutzer dazu verleiten, auf den Link zu klicken. Zu diesem Zweck werden Benutzer normalerweise dazu gebracht, auf einen Link in einer E-Mail-Nachricht oder einer Instant Messenger-Nachricht zu klicken.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a> <br />
Offenlegung von Informationen</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/de-de/kb/3076895">3076895</a></td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-085">MS15-085</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in Mount Manager kann Erhöhung von Berechtigungen ermöglichen (3082487) </strong><br />
Dieses Sicherheitsupdate behebt eine Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit kann eine Erhöhung von Berechtigungen ermöglichen, wenn ein Angreifer dem Zielsystem ein schädliches USB-Gerät hinzufügt. Ein Angreifer könnte dann schädliche Binärdateien auf dem Datenträger speichern und ausführen.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a> <br />
Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/de-de/kb/3071756">3071756</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-086">MS15-086</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in System Center Operations Manager kann Erhöhung von Berechtigungen ermöglichen (3075158)</strong> <br />
Dieses Sicherheitsupdate behebt eine Sicherheitsanfälligkeit in Microsoft System Center Operations Manager. Die Sicherheitsanfälligkeit kann Erhöhung von Berechtigungen ermöglichen, wenn ein Benutzer über eine speziell gestaltete URL eine betroffene Website besucht. Ein Angreifer kann Benutzer nicht zum Besuch einer solchen Website zwingen. Er muss den Benutzer zum Besuch dieser Website verleiten. Zu diesem Zweck wird der Benutzer meist dazu gebracht, in einer E-Mail oder einer Instant Messenger-Nachricht auf einen Link zur Website des Angreifers zu klicken.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a> <br />
Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;">Kein Neustart erforderlich.</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Server-Software</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-087">MS15-087</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in UDDI-Diensten kann Erhöhung von Berechtigungen ermöglichen (3082459) <br />
</strong>Dieses Sicherheitsupdate behebt eine Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit könnte die Erhöhung von Berechtigungen gestatten, wenn ein Angreifer durch Einfügen eines bösartigen Skripts in den Suchparameter einer Webseite ein XSS-Szenario (siteübergreifende Skripterstellung) konstruiert. Ein Benutzer muss dazu eine speziell gestaltete Webseite besuchen, auf der das bösartige Skript anschließend ausgeführt wird.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a> <br />
Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;">Kein Neustart erforderlich.</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Server-Software</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-088">MS15-088</a></td>
<td style="border:1px solid black;"><strong>Unsichere Befehlszeilenparameterübergabe kann Offenlegung von Informationen ermöglichen (3082458)</strong><br />
Dieses Sicherheitsupdate behebt die Sicherheitsanfälligkeit durch Offenlegung von Informationen in Microsoft Windows, Internet Explorer und Microsoft Office. Um diese Sicherheitsanfälligkeit auszunutzen, muss ein Angreifer zuerst eine andere Sicherheitsanfälligkeit in Internet Explorer nutzen, um Code in der Sandkastenanwendung auszuführen. Der Angreifer könnte dann Editor, Visio, PowerPoint, Excel oder Word mit einem unsicheren Befehlszeilenparameter ausführen, um die Offenlegung von Informationen zu bewirken. Um vor dieser Sicherheitsanfälligkeit geschützt zu sein, müssen die in diesem Bulletin bereitgestellten Updates sowie das Update für Internet Explorer, das in <a href="https://technet.microsoft.com/de-de/library/security/ms15-079">MS15-079</a> bereitgestellt wird, installiert werden. Kunden, die ein betroffenes Microsoft Office-Produkt ausführen, müssen auch die in <a href="https://technet.microsoft.com/de-de/library/security/ms15-081">MS15-081</a> bereitgestellten relevanten Updates installieren.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a> <br />
Offenlegung von Informationen</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-089">MS15-089</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in WebDAV kann Offenlegung von Informationen ermöglichen (3076949) <br />
</strong>Dieses Sicherheitsupdate behebt eine Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit kann die Offenlegung von Informationen ermöglichen, wenn ein Angreifer ein verschlüsselte Secure Socket Layer (SSL) 2.0-Sitzung mit einem WebDAV-Server erzwingt, auf dem SSL 2.0 aktiviert ist, und mittels einem Man-in-the-Middle-Angriff Teile des verschlüsselten Datenverkehrs entschlüsselt.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a> <br />
Offenlegung von Informationen</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-090">MS15-090</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in Microsoft Windows können Erhöhung von Berechtigungen ermöglichen (3060716)</strong> <br />
Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft Windows. Die Sicherheitsanfälligkeit ermöglicht eine Erhöhung von Berechtigungen, wenn ein Angreifer sich bei einem System anmeldet und eine speziell gestaltete Anwendung ausführt oder einen Benutzer dazu verleitet, eine speziell gestaltete Datei zu öffnen, welche die anfällige Sandboxanwendung ausführt, sodass der Angreifer der Sandbox entkommen kann.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a> <br />
Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/de-de/kb/3060716">3060716</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-091">MS15-091</a></td>
<td style="border:1px solid black;"><strong>Kumulatives Sicherheitsupdate für Microsoft Edge (3084525) <br />
</strong>Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft Edge. Die schwerwiegendste dieser Sicherheitsanfälligkeiten kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Webseite mit Microsoft Edge anzeigt. Ein Angreifer, der diese Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann die gleichen Benutzerrechte wie der aktuelle Benutzer erlangen. Benutzer mit Konten, die über weniger Systemrechte verfügen, sind davon möglicherweise weniger betroffen als Benutzer mit Administratorrechten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Edge</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-092">MS15-092</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in .NET Framework können Erhöhung von Berechtigungen ermöglichen (3086251) <br />
</strong>Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft .NET Framework. Die Sicherheitsanfälligkeiten können eine Erhöhung von Berechtigungen ermöglichen, wenn ein Benutzer eine speziell gestaltete .NET-Anwendung ausführt. Ein Angreifer kann Benutzer jedoch keinesfalls zum Ausführen einer solchen Anwendung zwingen. Ein Angreifer muss Benutzer vielmehr dazu verleiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a> <br />
Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-093">MS15-093</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für Internet Explorer (3088903)</strong> <br />
Dieses Sicherheitsupdate behebt eine Sicherheitsanfälligkeit in Internet Explorer. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Webseite mit Internet Explorer anzeigt. Ein Angreifer, der diese Sicherheitsanfälligkeit erfolgreich ausnutzt, kann die gleichen Benutzerrechte wie der aktuelle Benutzer erlangen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows, <br />
Internet Explorer</td>
</tr>
</tbody>
</table>
 

Ausnutzbarkeitsindex
--------------------

In der folgenden Tabelle wird eine Bewertung der Ausnutzbarkeit aller Sicherheitsanfälligkeiten bereitgestellt, die diesen Monat behoben werden. Die Sicherheitsanfälligkeiten sind nach Kennung des Bulletins und dann nach CVE-ID geordnet. Im Ausnutzbarkeitsindex sind nur Sicherheitsanfälligkeiten enthalten, deren Schweregrad in diesem Bulletin als „Kritisch“ oder „Hoch“ eingestuft wurde.

**Wie verwende ich diese Tabelle?**  

Verwenden Sie diese Tabelle, um etwas über die Wahrscheinlichkeit zu erfahren, dass für die einzelnen Sicherheitsupdates, die Sie möglicherweise installieren müssen, innerhalb von 30 Tagen Angriffe durch Codeausführung und Denial-of-Service stattfinden. Sehen Sie sich unter Berücksichtigung Ihrer konkreten Konfiguration jede der unten stehenden Bewertungen an, um Prioritäten für die Bereitstellung der Updates dieses Monats festzulegen. Weitere Informationen zur Bedeutung und Festlegung dieser Bewertungen finden Sie im [Microsoft-Ausnutzbarkeitsindex](http://technet.microsoft.com/de-de/security/cc998259).

In den nachfolgenden Spalten bezieht sich „Aktuelle Softwareversion“ auf die Themensoftware und „Ältere Softwareversionen“ auf alle älteren, unterstützten Versionen der Themensoftware, wie sie in den Tabellen „Betroffene Software“ und „Nicht betroffene Software“ im Bulletin aufgeführt ist.

<table style="width:100%;">
<colgroup>
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
<col width="16%" />
</colgroup>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><strong>Kennung des Bulletins</strong></td>
<td style="border:1px solid black;"><strong>Titel der Sicherheitsanfälligkeit</strong></td>
<td style="border:1px solid black;"><strong>CVE-ID</strong></td>
<td style="border:1px solid black;"><strong>Bewertung der Ausnutzbarkeit für<br />
aktuelle Softwareversion</strong></td>
<td style="border:1px solid black;"><strong>Bewertung der Ausnutzbarkeit für<br />
ältere Softwareversionen</strong></td>
<td style="border:1px solid black;"><strong>Bewertung der Ausnutzbarkeit<br />
durch Denial-of-Service</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit durch unsichere Befehlszeilenparameterübergabe</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2423">CVE-2015-2423</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2441">CVE-2015-2441</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2442">CVE-2015-2442</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2443">CVE-2015-2443</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2444">CVE-2015-2444</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">ASLR-Umgehung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2445">CVE-2015-2445</a></td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2446">CVE-2015-2446</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2447">CVE-2015-2447</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2448">CVE-2015-2448</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">ASLR-Umgehung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2449">CVE-2015-2449</a></td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2450">CVE-2015-2450</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2451">CVE-2015-2451</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-079">MS15-079</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2452">CVE-2015-2452</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Microsoft Office-Grafikkomponente bzgl. Remotecodeausführung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2431">CVE-2015-2431</a></td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit beim Analysieren von OpenType-Schriftarten</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2432">CVE-2015-2432</a></td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit im Kernel durch Umgehung der ASLR-Sicherheitsfunktion</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2433">CVE-2015-2433</a></td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bei der Analyse von TrueType-Schriftarten</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2435">CVE-2015-2435</a></td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit im Windows Client/Server-Runtime-Subsystem (CSRSS) bzgl. der Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2453">CVE-2015-2453</a></td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Windows KMD durch Umgehung von Sicherheitsfunktionen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2454">CVE-2015-2454</a></td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bei der Analyse von TrueType-Schriftarten</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2455">CVE-2015-2455</a></td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bei der Analyse von TrueType-Schriftarten</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2456">CVE-2015-2456</a></td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit beim Analysieren von OpenType-Schriftarten</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2458">CVE-2015-2458</a></td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit beim Analysieren von OpenType-Schriftarten</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2459">CVE-2015-2459</a></td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit beim Analysieren von OpenType-Schriftarten</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2460">CVE-2015-2460</a></td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit beim Analysieren von OpenType-Schriftarten</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2461">CVE-2015-2461</a></td>
<td style="border:1px solid black;">3 – Ausnutzung unwahrscheinlich</td>
<td style="border:1px solid black;">3 – Ausnutzung unwahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit beim Analysieren von OpenType-Schriftarten</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2462">CVE-2015-2462</a></td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bei der Analyse von TrueType-Schriftarten</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2463">CVE-2015-2463</a></td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bei der Analyse von TrueType-Schriftarten</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2464">CVE-2015-2464</a></td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Dauerhaft</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-080">MS15-080</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Windows-Shell durch Umgehung von Sicherheitsfunktionen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2465">CVE-2015-2465</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-081">MS15-081</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Microsoft Office bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1642">CVE-2015-1642</a></td>
<td style="border:1px solid black;">0 – Ausnutzung erkannt</td>
<td style="border:1px solid black;">0 – Ausnutzung erkannt</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-081">MS15-081</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit durch unsichere Befehlszeilenparameterübergabe</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2423">CVE-2015-2423</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-081">MS15-081</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Microsoft Office bzgl. Remotecodeausführung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2466">CVE-2015-2466</a></td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-081">MS15-081</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Microsoft Office bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2467">CVE-2015-2467</a></td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-081">MS15-081</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Microsoft Office bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2468">CVE-2015-2468</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-081">MS15-081</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Microsoft Office bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2469">CVE-2015-2469</a></td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-081">MS15-081</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Microsoft Office bzgl. Ganzzahlunterlauf</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2470">CVE-2015-2470</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-081">MS15-081</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Microsoft Office bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2477">CVE-2015-2477</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-082">MS15-082</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit durch Spoofing beim Remotedesktop-Sitzungshost</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2472">CVE-2015-2472</a></td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-082">MS15-082</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bzgl. Remotecodeausführung durch Einschleusung von DLL in Remotedesktopprotokoll (RDP)</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2473">CVE-2015-2473</a></td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-083">MS15-083</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in SMB (Server Message Block) bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2474">CVE-2015-2474</a></td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-084">MS15-084</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in MSXML durch Offenlegung von Informationen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2434">CVE-2015-2434</a></td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">3 – Ausnutzung unwahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-084">MS15-084</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in MSXML durch Offenlegung von Informationen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2440">CVE-2015-2440</a></td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">3 – Ausnutzung unwahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-084">MS15-084</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in MSXML durch Offenlegung von Informationen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2471">CVE-2015-2471</a></td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">3 – Ausnutzung unwahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-085">MS15-085</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Mount Manager bzgl. Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-1769">CVE-2015-1769</a></td>
<td style="border:1px solid black;">0 – Ausnutzung erkannt</td>
<td style="border:1px solid black;">0 – Ausnutzung erkannt</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-086">MS15-086</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bzgl. siteübergreifender Skripterstellung in System Center Operations Manager Webkonsole</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2420">CVE-2015-2420</a></td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-087">MS15-087</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in UDDI-Diensten bzgl. Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2475">CVE-2015-2475</a></td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-088">MS15-088</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit durch unsichere Befehlszeilenparameterübergabe</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2423">CVE-2015-2423</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/">MS15-089</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in WebDAV-Client bzgl. Offenlegung von Informationen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2476">CVE-2015-2476</a></td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">3 – Ausnutzung unwahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-090">MS15-090</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Windows-Objekt-Manager bzgl. der Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2428">CVE-2015-2428</a></td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-090">MS15-090</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Windows-Registrierung bzgl. der Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2429">CVE-2015-2429</a></td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-090">MS15-090</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in Windows-Dateisystem bzgl. der Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2430">CVE-2015-2430</a></td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-091">MS15-091</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2441">CVE-2015-2441</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-091">MS15-091</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2442">CVE-2015-2442</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-091">MS15-091</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2446">CVE-2015-2446</a></td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">1 – Ausnutzung wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-091">MS15-091</a></td>
<td style="border:1px solid black;">ASLR-Umgehung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2449">CVE-2015-2449</a></td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">2 – Ausnutzung weniger wahrscheinlich</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-092">MS15-092</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in RyuJIT-Optimierung durch Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2479">CVE-2015-2479</a></td>
<td style="border:1px solid black;">3 – Ausnutzung unwahrscheinlich</td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-092">MS15-092</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in RyuJIT-Optimierung durch Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2480">CVE-2015-2480</a></td>
<td style="border:1px solid black;">3 – Ausnutzung unwahrscheinlich</td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-092">MS15-092</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit in RyuJIT-Optimierung durch Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2481">CVE-2015-2481</a></td>
<td style="border:1px solid black;">3 – Ausnutzung unwahrscheinlich</td>
<td style="border:1px solid black;">4 - Nicht betroffen</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-093">MS15-093</a></td>
<td style="border:1px solid black;">Sicherheitsanfälligkeit bzgl. Speicherbeschädigung</td>
<td style="border:1px solid black;"><a href="http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-2502">CVE-2015-2502</a></td>
<td style="border:1px solid black;">0 – Ausnutzung erkannt</td>
<td style="border:1px solid black;">0 – Ausnutzung erkannt</td>
<td style="border:1px solid black;">Nicht anwendbar</td>
</tr>
</tbody>
</table>
  
Betroffene Software  
-------------------
  
In den folgenden Tabellen sind die Bulletins nach Hauptsoftwarekategorie und Schweregrad aufgeführt.
  
In diesen Tabellen finden Sie Informationen zu Sicherheitsupdates, die Sie möglicherweise installieren sollten. Alle aufgeführten Softwareprogramme bzw. -komponenten sollten überprüft werden, um zu sehen, ob Sicherheitsupdates für Ihre Installation zutreffen. Wenn ein Softwareprogramm oder eine Komponente aufgeführt ist, ist die Bewertung des Schweregrads des Softwareupdates ebenfalls aufgeführt.
  
**Hinweis** Für eine Sicherheitsanfälligkeit müssen möglicherweise mehrere Sicherheitsupdates installiert werden. Durchsuchen Sie in der gesamten Spalte die einzelnen Kennungen der aufgeführten Bulletins, um basierend auf den auf Ihrem System installierten Programmen oder Komponenten zu überprüfen, welche Updates Sie installieren müssen.
  
### Windows-Betriebssysteme und Komponenten (Tabelle 1 von 3)

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-079**](https://technet.microsoft.com/de-de/library/security/ms15-079)
</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/de-de/library/security/ms15-080)
</td>
<td style="border:1px solid black;">
[**MS15-082**](https://technet.microsoft.com/de-de/library/security/ms15-082)
</td>
<td style="border:1px solid black;">
[**MS15-083**](https://technet.microsoft.com/de-de/library/security/ms15-083)
</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/de-de/library/security/ms15-084)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3078071)  
(Kritisch)  
Internet Explorer 8  
(3078071)  
(Kritisch)  
Internet Explorer 9  
(3078071)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3078601)  
(Kritisch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3072303)  
(Kritisch)  
Microsoft .NET Framework 4  
(3072309)  
(Kritisch)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3072310)  
(Kritisch)  
Microsoft .NET Framework 4.6  
(3072311)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3075220)  
(Hoch)  
Windows Vista Service Pack 2  
(3075221)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3073921)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3078071)  
(Kritisch)  
Internet Explorer 8  
(3078071)  
(Kritisch)  
Internet Explorer 9  
(3078071)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3078601)  
(Kritisch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3072303)  
(Kritisch)  
Microsoft .NET Framework 4  
(3072309)  
(Kritisch)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3072310)  
(Kritisch)  
Microsoft .NET Framework 4.6  
(3072311)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3075220)  
(Hoch)  
Windows Vista x64 Edition Service Pack 2  
(3075221)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3073921)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-079**](https://technet.microsoft.com/de-de/library/security/ms15-079)
</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/de-de/library/security/ms15-080)
</td>
<td style="border:1px solid black;">
[**MS15-082**](https://technet.microsoft.com/de-de/library/security/ms15-082)
</td>
<td style="border:1px solid black;">
[**MS15-083**](https://technet.microsoft.com/de-de/library/security/ms15-083)
</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/de-de/library/security/ms15-084)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Mittel**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3078071)  
(Mittel)  
Internet Explorer 8  
(3078071)  
(Mittel)  
Internet Explorer 9  
(3078071)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(3078601)  
(Kritisch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3072303)  
(Kritisch)  
Microsoft .NET Framework 4  
(3072309)  
(Kritisch)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3072310)  
(Kritisch)  
Microsoft .NET Framework 4.6  
(3072311)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(3075220)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(3073921)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3078071)  
(Mittel)  
Internet Explorer 8  
(3078071)  
(Mittel)  
Internet Explorer 9  
(3078071)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(3078601)  
(Kritisch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3072303)  
(Kritisch)  
Microsoft .NET Framework 4  
(3072309)  
(Kritisch)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3072310)  
(Kritisch)  
Microsoft .NET Framework 4.6  
(3072311)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(3075220)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(3073921)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3078071)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(3078601)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(3075220)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(3073921)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-079**](https://technet.microsoft.com/de-de/library/security/ms15-079)
</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/de-de/library/security/ms15-080)
</td>
<td style="border:1px solid black;">
[**MS15-082**](https://technet.microsoft.com/de-de/library/security/ms15-082)
</td>
<td style="border:1px solid black;">
[**MS15-083**](https://technet.microsoft.com/de-de/library/security/ms15-083)
</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/de-de/library/security/ms15-084)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3078071)  
(Kritisch)  
Internet Explorer 9  
(3078071)  
(Kritisch)  
Internet Explorer 10  
(3078071)  
(Kritisch)  
Internet Explorer 11  
(3078071)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(3078601)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(3072305)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(3075220)  
(Hoch)  
Windows 7 für 32-Bit-Systeme Service Pack 1  
(3075222)  
(Hoch)  
Windows 7 für 32-Bit-Systeme Service Pack 1  
(3075226)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3078071)  
(Kritisch)  
Internet Explorer 9  
(3078071)  
(Kritisch)  
Internet Explorer 10  
(3078071)  
(Kritisch)  
Internet Explorer 11  
(3078071)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(3078601)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(3072305)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(3075220)  
(Hoch)  
Windows 7 für x64-basierte Systeme Service Pack 1  
(3075222)  
(Hoch)  
Windows 7 für x64-basierte Systeme Service Pack 1  
(3075226)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-079**](https://technet.microsoft.com/de-de/library/security/ms15-079)
</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/de-de/library/security/ms15-080)
</td>
<td style="border:1px solid black;">
[**MS15-082**](https://technet.microsoft.com/de-de/library/security/ms15-082)
</td>
<td style="border:1px solid black;">
[**MS15-083**](https://technet.microsoft.com/de-de/library/security/ms15-083)
</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/de-de/library/security/ms15-084)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Mittel**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3078071)  
(Mittel)  
Internet Explorer 9  
(3078071)  
(Mittel)  
Internet Explorer 10  
(3078071)  
(Mittel)  
Internet Explorer 11  
(3078071)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(3078601)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(3072305)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(3075220)  
(Hoch)  
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(3075222)  
(Hoch)  
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(3075226)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3078071)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(3078601)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(3075220)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8 und Windows 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-079**](https://technet.microsoft.com/de-de/library/security/ms15-079)
</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/de-de/library/security/ms15-080)
</td>
<td style="border:1px solid black;">
[**MS15-082**](https://technet.microsoft.com/de-de/library/security/ms15-082)
</td>
<td style="border:1px solid black;">
[**MS15-083**](https://technet.microsoft.com/de-de/library/security/ms15-083)
</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/de-de/library/security/ms15-084)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3078071)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme  
(3078601)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3072306)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme  
(3075220)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3078071)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 8 für x64-basierte Systeme  
(3078601)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3072306)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 8 für x64-basierte Systeme  
(3075220)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3078071)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme  
(3078601)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3072307)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme  
(3075220)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3078071)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme  
(3078601)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3072307)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme  
(3075220)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 und Windows Server 2012 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-079**](https://technet.microsoft.com/de-de/library/security/ms15-079)
</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/de-de/library/security/ms15-080)
</td>
<td style="border:1px solid black;">
[**MS15-082**](https://technet.microsoft.com/de-de/library/security/ms15-082)
</td>
<td style="border:1px solid black;">
[**MS15-083**](https://technet.microsoft.com/de-de/library/security/ms15-083)
</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/de-de/library/security/ms15-084)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Mittel**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3078071)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3078601)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3072306)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3075220)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3078071)  
(Mittel)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3078601)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3072307)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3075220)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT und Windows RT 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-079**](https://technet.microsoft.com/de-de/library/security/ms15-079)
</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/de-de/library/security/ms15-080)
</td>
<td style="border:1px solid black;">
[**MS15-082**](https://technet.microsoft.com/de-de/library/security/ms15-082)
</td>
<td style="border:1px solid black;">
[**MS15-083**](https://technet.microsoft.com/de-de/library/security/ms15-083)
</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/de-de/library/security/ms15-084)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3078071)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows RT  
(3078601)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows RT  
(3075220)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3078071)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3078601)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3075220)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 10**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-079**](https://technet.microsoft.com/de-de/library/security/ms15-079)
</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/de-de/library/security/ms15-080)
</td>
<td style="border:1px solid black;">
[**MS15-082**](https://technet.microsoft.com/de-de/library/security/ms15-082)
</td>
<td style="border:1px solid black;">
[**MS15-083**](https://technet.microsoft.com/de-de/library/security/ms15-083)
</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/de-de/library/security/ms15-084)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3081436)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 10 für 32-Bit-Systeme  
(3081436)  
(Kritisch)  
Microsoft .NET Framework 3,5  
(3081436)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3081436)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme  
(3081436)  
(Kritisch)  
Microsoft .NET Framework 3,5  
(3081436)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Server Core-Installationsoption**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-079**](https://technet.microsoft.com/de-de/library/security/ms15-079)
</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/de-de/library/security/ms15-080)
</td>
<td style="border:1px solid black;">
[**MS15-082**](https://technet.microsoft.com/de-de/library/security/ms15-082)
</td>
<td style="border:1px solid black;">
[**MS15-083**](https://technet.microsoft.com/de-de/library/security/ms15-083)
</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/de-de/library/security/ms15-084)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)  
(3078601)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)  
(3075220)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)  
(3073921)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)  
(3078601)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)  
(3075220)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)  
(3073921)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)  
(3078601)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(3072305)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)  
(3075220)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core-Installation)  
(3078601)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3072306)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core-Installation)  
(3075220)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core-Installation)  
(3078601)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3072307)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core-Installation)  
(3075220)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 und MSXML Core Services 6.0  
(3076895)  
(Hoch)
</td>
</tr>
</table>
 
**Hinweise zu MS15-080 und MS15-084**

Dieses Bulletin umfasst mehr als eine Softwarekategorie. Zusätzliche betroffene Software finden Sie in den anderen Tabellen in diesem Abschnitt.

### Windows-Betriebssysteme und Komponenten (Tabelle 2 von 3)

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Vista**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-085**](https://technet.microsoft.com/de-de/library/security/ms15-085)
</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/de-de/library/security/ms15-087)
</td>
<td style="border:1px solid black;">
[**MS15-088**](https://technet.microsoft.com/de-de/library/security/ms15-088)
</td>
<td style="border:1px solid black;">
[**MS15-089**](https://technet.microsoft.com/de-de/library/security/ms15-089)
</td>
<td style="border:1px solid black;">
[**MS15-090**](https://technet.microsoft.com/de-de/library/security/ms15-090)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3046017)  
(Hoch)  
Windows Vista Service Pack 2  
(3079757)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3076949)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3060716)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3046017)  
(Hoch)  
Windows Vista x64 Edition Service Pack 2  
(3079757)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3076949)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3060716)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-085**](https://technet.microsoft.com/de-de/library/security/ms15-085)
</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/de-de/library/security/ms15-087)
</td>
<td style="border:1px solid black;">
[**MS15-088**](https://technet.microsoft.com/de-de/library/security/ms15-088)
</td>
<td style="border:1px solid black;">
[**MS15-089**](https://technet.microsoft.com/de-de/library/security/ms15-089)
</td>
<td style="border:1px solid black;">
[**MS15-090**](https://technet.microsoft.com/de-de/library/security/ms15-090)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(3073893)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(3046017)  
(Hoch)  
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(3079757)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(3076949)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(3060716)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(3073893)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(3046017)  
(Hoch)  
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(3079757)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(3076949)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(3060716)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(3046017)  
(Hoch)  
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(3079757)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(3060716)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-085**](https://technet.microsoft.com/de-de/library/security/ms15-085)
</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/de-de/library/security/ms15-087)
</td>
<td style="border:1px solid black;">
[**MS15-088**](https://technet.microsoft.com/de-de/library/security/ms15-088)
</td>
<td style="border:1px solid black;">
[**MS15-089**](https://technet.microsoft.com/de-de/library/security/ms15-089)
</td>
<td style="border:1px solid black;">
[**MS15-090**](https://technet.microsoft.com/de-de/library/security/ms15-090)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(3046017)  
(Hoch)  
Windows 7 für 32-Bit-Systeme Service Pack 1  
(3079757)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(3076949)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(3060716)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(3046017)  
(Hoch)  
Windows 7 für x64-basierte Systeme Service Pack 1  
(3079757)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(3076949)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(3060716)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-085**](https://technet.microsoft.com/de-de/library/security/ms15-085)
</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/de-de/library/security/ms15-087)
</td>
<td style="border:1px solid black;">
[**MS15-088**](https://technet.microsoft.com/de-de/library/security/ms15-088)
</td>
<td style="border:1px solid black;">
[**MS15-089**](https://technet.microsoft.com/de-de/library/security/ms15-089)
</td>
<td style="border:1px solid black;">
[**MS15-090**](https://technet.microsoft.com/de-de/library/security/ms15-090)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(3046017)  
(Hoch)  
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(3079757)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(3076949)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(3060716)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(3046017)  
(Hoch)  
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(3079757)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(3060716)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 8 und Windows 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-085**](https://technet.microsoft.com/de-de/library/security/ms15-085)
</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/de-de/library/security/ms15-087)
</td>
<td style="border:1px solid black;">
[**MS15-088**](https://technet.microsoft.com/de-de/library/security/ms15-088)
</td>
<td style="border:1px solid black;">
[**MS15-089**](https://technet.microsoft.com/de-de/library/security/ms15-089)
</td>
<td style="border:1px solid black;">
[**MS15-090**](https://technet.microsoft.com/de-de/library/security/ms15-090)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme  
(3046017)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme  
(3076949)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme  
(3060716)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Windows 8 für x64-basierte Systeme  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 8 für x64-basierte Systeme  
(3046017)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8 für x64-basierte Systeme  
(3076949)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8 für x64-basierte Systeme  
(3060716)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme  
(3046017)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme  
(3076949)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme  
(3060716)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme  
(3046017)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme  
(3076949)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme  
(3060716)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2012 und Windows Server 2012 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-085**](https://technet.microsoft.com/de-de/library/security/ms15-085)
</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/de-de/library/security/ms15-087)
</td>
<td style="border:1px solid black;">
[**MS15-088**](https://technet.microsoft.com/de-de/library/security/ms15-088)
</td>
<td style="border:1px solid black;">
[**MS15-089**](https://technet.microsoft.com/de-de/library/security/ms15-089)
</td>
<td style="border:1px solid black;">
[**MS15-090**](https://technet.microsoft.com/de-de/library/security/ms15-090)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3046017)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3076949)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3060716)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3046017)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3076949)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3060716)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows RT und Windows RT 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-085**](https://technet.microsoft.com/de-de/library/security/ms15-085)
</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/de-de/library/security/ms15-087)
</td>
<td style="border:1px solid black;">
[**MS15-088**](https://technet.microsoft.com/de-de/library/security/ms15-088)
</td>
<td style="border:1px solid black;">
[**MS15-089**](https://technet.microsoft.com/de-de/library/security/ms15-089)
</td>
<td style="border:1px solid black;">
[**MS15-090**](https://technet.microsoft.com/de-de/library/security/ms15-090)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Windows RT  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows RT  
(3046017)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows RT  
(3076949)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows RT  
(3060716)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3046017)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3076949)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3060716)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 10**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-085**](https://technet.microsoft.com/de-de/library/security/ms15-085)
</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/de-de/library/security/ms15-087)
</td>
<td style="border:1px solid black;">
[**MS15-088**](https://technet.microsoft.com/de-de/library/security/ms15-088)
</td>
<td style="border:1px solid black;">
[**MS15-089**](https://technet.microsoft.com/de-de/library/security/ms15-089)
</td>
<td style="border:1px solid black;">
[**MS15-090**](https://technet.microsoft.com/de-de/library/security/ms15-090)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Windows 10 für 32-Bit-Systeme  
(3081436)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 10 für 32-Bit-Systeme  
(3081436)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme  
(3081436)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme  
(3081436)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Server Core-Installationsoption**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-085**](https://technet.microsoft.com/de-de/library/security/ms15-085)
</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/de-de/library/security/ms15-087)
</td>
<td style="border:1px solid black;">
[**MS15-088**](https://technet.microsoft.com/de-de/library/security/ms15-088)
</td>
<td style="border:1px solid black;">
[**MS15-089**](https://technet.microsoft.com/de-de/library/security/ms15-089)
</td>
<td style="border:1px solid black;">
[**MS15-090**](https://technet.microsoft.com/de-de/library/security/ms15-090)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)  
(3073893)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)  
(3046017)  
(Hoch)  
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)  
(3079757)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)  
(3060716)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)  
(3073893)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)  
(3046017)  
(Hoch)  
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)  
(3079757)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)  
(3060716)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)  
(3046017)  
(Hoch)  
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)  
(3079757)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)  
(3060716)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core-Installation)  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core-Installation)  
(3046017)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core-Installation)  
(3060716)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core-Installation)  
(3071756)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core-Installation)  
(3046017)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core-Installation)  
(3060716)  
(Hoch)
</td>
</tr>
</table>
 
**Hinweis zu MS15-087**

Dieses Bulletin umfasst mehr als eine Softwarekategorie. Zusätzliche betroffene Software finden Sie in den anderen Tabellen in diesem Abschnitt.

### Windows-Betriebssysteme und Komponenten (Tabelle 3 von 3)

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Vista**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-091**](https://technet.microsoft.com/de-de/library/security/ms15-091)
</td>
<td style="border:1px solid black;">
[**MS15-092**](https://technet.microsoft.com/de-de/library/security/ms15-092)
</td>
<td style="border:1px solid black;">
[**MS15-093**](https://technet.microsoft.com/de-de/library/security/ms15-093)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
(Hoch)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087985)  
(Kritisch)  
Internet Explorer 8  
(3087985)  
(Kritisch)  
Internet Explorer 9  
(3087985)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
(Hoch)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087985)  
(Kritisch)  
Internet Explorer 8  
(3087985)  
(Kritisch)  
Internet Explorer 9  
(3087985)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-091**](https://technet.microsoft.com/de-de/library/security/ms15-091)
</td>
<td style="border:1px solid black;">
[**MS15-092**](https://technet.microsoft.com/de-de/library/security/ms15-092)
</td>
<td style="border:1px solid black;">
[**MS15-093**](https://technet.microsoft.com/de-de/library/security/ms15-093)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Mittel**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
(Hoch)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087985)  
(Mittel)  
Internet Explorer 8  
(3087985)  
(Mittel)  
Internet Explorer 9  
(3087985)  
(Mittel)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
(Hoch)
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087985)  
(Mittel)  
Internet Explorer 8  
(3087985)  
(Mittel)  
Internet Explorer 9  
(3087985)  
(Mittel)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3087985)  
(Mittel)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 7**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-091**](https://technet.microsoft.com/de-de/library/security/ms15-091)
</td>
<td style="border:1px solid black;">
[**MS15-092**](https://technet.microsoft.com/de-de/library/security/ms15-092)
</td>
<td style="border:1px solid black;">
[**MS15-093**](https://technet.microsoft.com/de-de/library/security/ms15-093)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
(Hoch)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3087985)  
(Kritisch)  
Internet Explorer 9  
(3087985)  
(Kritisch)  
Internet Explorer 10  
(3087985)  
(Kritisch)  
Internet Explorer 11  
(3087985)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
(Hoch)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3087985)  
(Kritisch)  
Internet Explorer 9  
(3087985)  
(Kritisch)  
Internet Explorer 10  
(3087985)  
(Kritisch)  
Internet Explorer 11  
(3087985)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2008 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-091**](https://technet.microsoft.com/de-de/library/security/ms15-091)
</td>
<td style="border:1px solid black;">
[**MS15-092**](https://technet.microsoft.com/de-de/library/security/ms15-092)
</td>
<td style="border:1px solid black;">
[**MS15-093**](https://technet.microsoft.com/de-de/library/security/ms15-093)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Mittel**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
(Hoch)
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3087985)  
(Mittel)  
Internet Explorer 9  
(3087985)  
(Mittel)  
Internet Explorer 10  
(3087985)  
(Mittel)  
Internet Explorer 11  
(3087985)  
(Mittel)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3087985)  
(Mittel)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 8 und Windows 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-091**](https://technet.microsoft.com/de-de/library/security/ms15-091)
</td>
<td style="border:1px solid black;">
[**MS15-092**](https://technet.microsoft.com/de-de/library/security/ms15-092)
</td>
<td style="border:1px solid black;">
[**MS15-093**](https://technet.microsoft.com/de-de/library/security/ms15-093)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083184)  
(Hoch)
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087985)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083184)  
(Hoch)
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087985)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083185)  
(Hoch)
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087985)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083185)  
(Hoch)
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087985)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows Server 2012 und Windows Server 2012 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-091**](https://technet.microsoft.com/de-de/library/security/ms15-091)
</td>
<td style="border:1px solid black;">
[**MS15-092**](https://technet.microsoft.com/de-de/library/security/ms15-092)
</td>
<td style="border:1px solid black;">
[**MS15-093**](https://technet.microsoft.com/de-de/library/security/ms15-093)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Mittel**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083184)  
(Hoch)
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087985)  
(Mittel)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083185)  
(Hoch)
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087985)  
(Mittel)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows RT und Windows RT 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-091**](https://technet.microsoft.com/de-de/library/security/ms15-091)
</td>
<td style="border:1px solid black;">
[**MS15-092**](https://technet.microsoft.com/de-de/library/security/ms15-092)
</td>
<td style="border:1px solid black;">
[**MS15-093**](https://technet.microsoft.com/de-de/library/security/ms15-093)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083184)  
(Hoch)
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3087985)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083185)  
(Hoch)
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3087985)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Windows 10**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-091**](https://technet.microsoft.com/de-de/library/security/ms15-091)
</td>
<td style="border:1px solid black;">
[**MS15-092**](https://technet.microsoft.com/de-de/library/security/ms15-092)
</td>
<td style="border:1px solid black;">
[**MS15-093**](https://technet.microsoft.com/de-de/library/security/ms15-093)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3081436)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3081436)  
(Hoch)
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3081444)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3081436)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3081436)  
(Hoch)
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3081444)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Server Core-Installationsoption**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-091**](https://technet.microsoft.com/de-de/library/security/ms15-091)
</td>
<td style="border:1px solid black;">
[**MS15-092**](https://technet.microsoft.com/de-de/library/security/ms15-092)
</td>
<td style="border:1px solid black;">
[**MS15-093**](https://technet.microsoft.com/de-de/library/security/ms15-093)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083186)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083184)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3083185)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
</table>
 
### Microsoft Server-Software

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft System Center 2012 Operations Manager**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;" colspan="2">
[**MS15-086**](https://technet.microsoft.com/de-de/library/security/ms15-086)
</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/de-de/library/security/ms15-087)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;" colspan="2">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft System Center 2012 Operations Manager
</td>
<td style="border:1px solid black;" colspan="2">
Microsoft System Center 2012 Operations Manager  
(Installiert Updaterollup 8)  
(3071089)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft System Center 2012 Operations Manager Service Pack 1
</td>
<td style="border:1px solid black;" colspan="2">
Microsoft System Center 2012 Operations Manager Service Pack 1  
(Installiert Updaterollup 10)  
(3071088)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft System Center 2012 Operations Manager R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-086**](https://technet.microsoft.com/de-de/library/security/ms15-086)
</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/de-de/library/security/ms15-087)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
Microsoft System Center 2012 Operations Manager R2
</td>
<td style="border:1px solid black;">
Microsoft System Center 2012 Operations Manager R2  
(Installiert Updaterollup 7)  
(3064919)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft BizTalk Server**
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-086**](https://technet.microsoft.com/de-de/library/security/ms15-086)
</td>
<td style="border:1px solid black;">
[**MS15-087**](https://technet.microsoft.com/de-de/library/security/ms15-087)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
Microsoft BizTalk Server 2010
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft BizTalk Server 2010  
(3087119)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
Microsoft BizTalk Server 2013
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft BizTalk Server 2013  
(3087119)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
Microsoft BizTalk Server 2013 R2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft BizTalk Server 2013 R2  
(3087119)  
(Hoch)
</td>
</tr>
</table>
 
**Hinweis zu MS15-087**

Dieses Bulletin umfasst mehr als eine Softwarekategorie. Zusätzliche betroffene Software finden Sie in den anderen Tabellen in diesem Abschnitt.

### Microsoft Office Suites und Software

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2007**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/de-de/library/security/ms15-080)
</td>
<td style="border:1px solid black;">
[**MS15-081**](https://technet.microsoft.com/de-de/library/security/ms15-081)
</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/de-de/library/security/ms15-084)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3054890)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(2687409)  
(Hoch)  
Microsoft Office 2007 Service Pack 3  
(3054888)  
(Kritisch)  
Microsoft Office 2007 Service Pack 3  
(2596650)  
(Kritisch)  
Microsoft Office 2007 Service Pack 3  
(2837610)  
(Hoch)  
Microsoft Excel 2007 Service Pack 3  
(3054992)  
(Hoch)  
Microsoft PowerPoint 2007 Service Pack 3  
(3055051)  
(Hoch)  
Microsoft Visio 2007 Service Pack 3  
(2965280)  
(Hoch)  
Microsoft Word 2007 Service Pack 3  
(3055052)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 5.0  
(2825645)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2010**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/de-de/library/security/ms15-080)
</td>
<td style="border:1px solid black;">
[**MS15-081**](https://technet.microsoft.com/de-de/library/security/ms15-081)
</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/de-de/library/security/ms15-084)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32-Bit-Editionen)  
(3054846)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32-Bit-Editionen)  
(2965310)  
(Hoch)  
Microsoft Office 2010 Service Pack 2 (32-Bit-Editionen)  
(3055037)  
(Hoch)  
Microsoft Office 2010 Service Pack 2 (32-Bit-Editionen)  
(2553313)  
(Kritisch)  
Microsoft Office 2010 Service Pack 2 (32-Bit-Editionen)  
(2598244)  
(Hoch)  
Microsoft Excel 2010 Service Pack 2 (32-Bit-Editionen)  
(3055044)  
(Hoch)  
Microsoft PowerPoint 2010 Service Pack 2 (32-Bit-Editionen)  
(3055033)  
(Hoch)  
Microsoft Visio 2010 Service Pack 2 (32-Bit-Editionen)  
(3054876)  
(Hoch)  
Microsoft Word 2010 Service Pack 2 (32-Bit-Editionen)  
(3055039)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64-Bit-Editionen)  
(3054846)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64-Bit-Editionen)  
(2965310)  
(Hoch)  
Microsoft Office 2010 Service Pack 2 (64-Bit-Editionen)  
(3055037)  
(Hoch)  
Microsoft Office 2010 Service Pack 2 (64-Bit-Editionen)  
(2553313)  
(Kritisch)  
Microsoft Office 2010 Service Pack 2 (64-Bit-Editionen)  
(2598244)  
(Hoch)  
Microsoft Excel 2010 Service Pack 2 (64-Bit-Editionen)  
(3055044)  
(Hoch)  
Microsoft PowerPoint 2010 Service Pack 2 (64-Bit-Editionen)  
(3055033)  
(Hoch)  
Microsoft Visio 2010 Service Pack 2 (64-Bit-Editionen)  
(3054876)  
(Hoch)  
Microsoft Word 2010 Service Pack 2 (64-Bit-Editionen)  
(3055039)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2013**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/de-de/library/security/ms15-080)
</td>
<td style="border:1px solid black;">
[**MS15-081**](https://technet.microsoft.com/de-de/library/security/ms15-081)
</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/de-de/library/security/ms15-084)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32-Bit-Editionen)  
(3039734)  
(Hoch)  
Microsoft Office 2013 Service Pack 1 (32-Bit-Editionen)  
(3039798)  
(Kritisch)  
Microsoft Office 2013 Service Pack 1 (32-Bit-Editionen)  
(3054816)  
(Hoch)  
Microsoft Excel 2013 Service Pack 1 (32-Bit-Editionen)  
(3054991)  
(Hoch)  
Microsoft PowerPoint 2013 Service Pack 1 (32-Bit-Editionen)  
(3055029)  
(Hoch)  
Microsoft Visio 2013 Service Pack 1 (32-Bit-Editionen)  
(3054929)  
(Hoch)  
Microsoft Word 2013 Service Pack 1 (32-Bit-Editionen)  
(3055030)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (64-Bit-Editionen)  
(3039734)  
(Hoch)  
Microsoft Office 2013 Service Pack 1 (64-Bit-Editionen)  
(3039798)  
(Kritisch)  
Microsoft Office 2013 Service Pack 1 (64-Bit-Editionen)  
(3054816)  
(Hoch)  
Microsoft Excel 2013 Service Pack 1 (64-Bit-Editionen)  
(3054991)  
(Hoch)  
Microsoft PowerPoint 2013 Service Pack 1 (64-Bit-Editionen)  
(3055029)  
(Hoch)  
Microsoft Visio 2013 Service Pack 1 (64-Bit-Editionen)  
(3054929)  
(Hoch)  
Microsoft Word 2013 Service Pack 1 (64-Bit-Editionen)  
(3055030)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2013 RT**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/de-de/library/security/ms15-080)
</td>
<td style="border:1px solid black;">
[**MS15-081**](https://technet.microsoft.com/de-de/library/security/ms15-081)
</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/de-de/library/security/ms15-084)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1  
(3039798)  
(Kritisch)  
Microsoft Office 2013 RT Service Pack 1  
(3054816)  
(Hoch)  
Microsoft Excel 2013 RT Service Pack 1  
(3054991)  
(Hoch)  
Microsoft PowerPoint 2013 RT Service Pack 1  
(3055029)  
(Hoch)  
Microsoft Visio 2013 RT Service Pack 1  
(3054929)  
(Hoch)  
Microsoft Word 2013 RT Service Pack 1  
(3055030)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office 2016**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/de-de/library/security/ms15-080)
</td>
<td style="border:1px solid black;">
[**MS15-081**](https://technet.microsoft.com/de-de/library/security/ms15-081)
</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/de-de/library/security/ms15-084)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (32-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (32-Bit-Editionen)  
(3085538)  
(Kritisch)  
Microsoft Visio 2016 (32-Bit-Editionen)  
(2920708)  
(Hoch)  
Microsoft Word 2016 (32-Bit-Editionen)  
(2920691)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft Office 2016 (64-Bit-Editionen)  
(3085538)  
(Kritisch)  
Microsoft Visio 2016 (64-Bit-Editionen)  
(2920708)  
(Hoch)  
Microsoft Word 2016 (64-Bit-Editionen)  
(2920691)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Microsoft Office für Mac**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/de-de/library/security/ms15-080)
</td>
<td style="border:1px solid black;">
[**MS15-081**](https://technet.microsoft.com/de-de/library/security/ms15-081)
</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/de-de/library/security/ms15-084)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office für Mac 2011
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft Office für Mac 2011  
(3081349)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office für Mac 2016
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft Office für Mac 2016  
(3082420)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="4">
**Weitere Office-Software**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/de-de/library/security/ms15-080)
</td>
<td style="border:1px solid black;">
[**MS15-081**](https://technet.microsoft.com/de-de/library/security/ms15-081)
</td>
<td style="border:1px solid black;">
[**MS15-084**](https://technet.microsoft.com/de-de/library/security/ms15-084)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 3
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack Service Pack 3  
(2986254)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3055053)  
(Hoch)  
Microsoft Word Viewer  
(3055054)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft InfoPath 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 5.0  
(2825645)  
(Hoch)
</td>
</tr>
</table>
 
**Hinweis zu MS15-080, MS15-081 und MS15-084**

Dieses Bulletin umfasst mehr als eine Softwarekategorie. Zusätzliche betroffene Software finden Sie in den anderen Tabellen in diesem Abschnitt. 

### Microsoft Office-Dienste und Web Apps

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2010**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-081**](https://technet.microsoft.com/de-de/library/security/ms15-081)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Word-Automatisierungsdienste  
(3054960)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2013**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-081**](https://technet.microsoft.com/de-de/library/security/ms15-081)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1
</td>
<td style="border:1px solid black;">
Word-Automatisierungsdienste  
(3054858)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2010**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-081**](https://technet.microsoft.com/de-de/library/security/ms15-081)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3054974)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Office Web Apps 2013**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-081**](https://technet.microsoft.com/de-de/library/security/ms15-081)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2013 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3055003)  
(Hoch)
</td>
</tr>
</table>
 
**Hinweis zu MS15-081**

Dieses Bulletin umfasst mehr als eine Softwarekategorie. Zusätzliche betroffene Software finden Sie in den anderen Tabellen in diesem Abschnitt.

### Microsoft Communications-Plattformen und -Software

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Live Meeting 2007**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/de-de/library/security/ms15-080)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007-Konsole
</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007-Konsole  
(3075591)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2010**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/de-de/library/security/ms15-080)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 Bit)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 Bit)  
(3075593)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 Bit)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 Bit)  
(3075593)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(Installation auf Benutzerebene)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(Installation auf Benutzerebene)  
(3075592)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(Installation auf Administratorebene)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(Installation auf Administratorebene)  
(3075590)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Lync 2013**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/de-de/library/security/ms15-080)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32-Bit)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32-Bit)  
(Skype for Business)  
(3055014)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32-Bit)
</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32-Bit)  
(Skype for Business Basic)  
(3055014)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64-Bit)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64-Bit)  
(Skype for Business)  
(3055014)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64-Bit)
</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64-Bit)  
(Skype for Business Basic)  
(3055014)  
(Kritisch)
</td>
</tr>
</table>
 
**Hinweis zu MS15-080**

Dieses Bulletin umfasst mehr als eine Softwarekategorie. Zusätzliche betroffene Software finden Sie in den anderen Tabellen in diesem Abschnitt.

### Microsoft Entwicklertools und Software

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Silverlight**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-080**](https://technet.microsoft.com/de-de/library/security/ms15-080)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
Microsoft Silverlight 5 bei Installation auf dem Mac  
(3080333)  
(Kritisch)  
Microsoft Silverlight 5 Developer Runtime bei Installation auf dem Mac  
(3080333)  
(Kritisch)  
Microsoft Silverlight 5 bei Installation unter allen Versionen von Microsoft Windows-Clients  
(3080333)  
(Kritisch)  
Microsoft Silverlight 5 Developer Runtime bei Installation unter allen unterstützten Versionen von Microsoft Windows-Clients  
(3080333)  
(Kritisch)  
Microsoft Silverlight 5 bei Installation unter allen unterstützten Versionen von Microsoft Windows-Servern  
(3080333)  
(Kritisch)  
Microsoft Silverlight 5 Developer Runtime bei Installation unter allen unterstützten Versionen von Microsoft Windows-Servern  
(3080333)  
(Kritisch)
</td>
</tr>
</table>
 
**Hinweis zu MS15-080**

Dieses Bulletin umfasst mehr als eine Softwarekategorie. Zusätzliche betroffene Software finden Sie in den anderen Tabellen in diesem Abschnitt.

Tools und Hinweise zur Erkennung und Bereitstellung von Sicherheitsupdates
--------------------------------------------------------------------------

Es stehen mehrere Ressourcen zur Verfügung, um Administratoren bei der Bereitstellung von Sicherheitsupdates zu helfen.

Der Microsoft Baseline Security Analyzer (MBSA) ermöglicht Administratoren die Überprüfung von lokalen und Remotesystemen im Hinblick auf fehlende Sicherheitsupdates sowie auf häufig falsch konfigurierte Sicherheitsparameter.

Windows Server Update Services (WSUS), Systems Management Server (SMS) und System Center Configuration Manager erleichtern Administratoren die Verteilung von Sicherheitsupdates.

Die im Anwendungskompatibilitäts-Toolkit enthaltenen Komponenten zur Updatekompatibilitätsbewertung helfen dabei, die Vereinbarkeit von Windows-Updates mit installierten Anwendungen zu testen und zu überprüfen.

Weitere Informationen zu diesen und weiteren verfügbaren Tools finden Sie unter [Sicherheitstools](http://technet.microsoft.com/de-de/security/cc297183).

Danksagung
----------

Microsoft würdigt die Bemühungen derjenigen Benutzer der Sicherheitscommunity, die uns dabei helfen, Kunden durch eine verantwortliche Offenlegung von Sicherheitsanfälligkeiten zu schützen. Weitere Informationen finden Sie unter [Danksagung](https://technet.microsoft.com/de-de/library/security/dn903755.aspx). 

Weitere Informationen
---------------------

### Microsoft Windows-Tool zum Entfernen bösartiger Software

Für die Veröffentlichung des Bulletins, die am zweiten Dienstag jedes Monats stattfindet, hat Microsoft eine aktualisierte Version des Microsofts Windows-Tool zum Entfernen schädlicher Software in Windows Update, Microsoft Update, den Windows Server Update Services und dem Download Center veröffentlicht. Für außerplanmäßige Veröffentlichungen des Security Bulletins ist keine aktualisierte Version des Microsoft Windows-Tool zum Entfernen schädlicher Software erhältlich.

### Nicht sicherheitsrelevante Updates unter MU, WU und WSUS:

Weitere Informationen zu nicht sicherheitsrelevanten Veröffentlichungen auf Windows-Update und Microsoft Update finden Sie unter:

-   [Microsoft Knowledge Base-Artikel 894199](https://support.microsoft.com/de-de/kb/894199): Beschreibung der Änderungen an den Inhalten von Software Update Services und Windows Server Update Services. Umfasst alle Windows-Inhalte.
-   [Updates für Windows Server Update Services aus den vergangenen Monaten](http://technet.microsoft.com/de-de/windowsserver/bb332157.aspx). Zeigt alle neuen, überarbeiteten und veröffentlichten Updates für andere Microsoft-Produkte als Microsoft Windows an.

### Microsoft Active Protections Program (MAPP)

Um den Sicherheitsschutz für Benutzer zu verbessern, stellt Microsoft den wichtigsten Sicherheitssoftwareanbietern vor der monatlichen Veröffentlichung der Sicherheitsupdates Informationen zu Sicherheitsanfälligkeiten bereit. Anbieter von Sicherheitssoftware können diese Informationen zu Sicherheitsanfälligkeiten dann verwenden, um Benutzern aktualisierten Schutz über ihre Sicherheitssoftware oder ihre Geräte bereitzustellen, z. B. Antivirus, netzwerkbasierte Angriffserkennungssysteme oder hostbasierte Angriffsverhinderungssysteme. Wenn Sie erfahren möchten, ob von den Sicherheitssoftwareanbietern aktiver Schutz verfügbar ist, besuchen Sie die von den Programmpartnern bereitgestellte Active Protections-Websites, die unter [MAPP-Partner (Microsoft Active Protections Program)](http://technet.microsoft.com/de-de/security/dn467918) aufgeführt sind.

### Sicherheitsstrategien und Community

**Updateverwaltungsstrategien**

Auf der Seite [Patchmanagement](http://technet.microsoft.com/de-de/library/bb466251.aspx) werden zusätzliche Informationen zu den empfohlenen Vorgehensweisen für die Anwendung von Sicherheitsupdates von Microsoft bereitgestellt.

**Weitere Sicherheitsupdates**

Updates für andere Sicherheitsanfälligkeiten sind unter den folgenden Adressen erhältlich:

-   Sicherheitsupdates sind im [Microsoft Download Center](http://www.microsoft.com/de-de/download/search.aspx?q=security%20update) verfügbar. Sie können am einfachsten durch eine Suche nach dem Begriff „security update“ ermittelt werden.
-   Updates für Benutzerplattformen sind auf [Microsoft Update](http://update.microsoft.com/microsoftupdate/v6/vistadefault.aspx?ln=de-de) verfügbar.
-   Die Sicherheitsupdates, die in diesem Monat über Windows Update veröffentlicht wurden, können Sie auch im „Security and Critical Releases ISO CD Image“ über Microsoft Download Center erhalten. Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 913086](https://support.microsoft.com/de-de/kb/913086).

**IT Pro Security Community**

Erfahren Sie, wie Sie die Sicherheit Ihrer IT-Umgebung erhöhen und Ihren IT-Betrieb optimieren können. Diskutieren Sie auf der [IT Pro Security Zone](http://technet.microsoft.com/de-de/security/cc136632.aspx) Website mit anderen IT-Profis über das Thema Sicherheit.

### Support

Die betroffene Software wurde getestet, um die betroffenen Versionen zu ermitteln. Andere Versionen haben das Ende ihrer Supportlebenszyklen erreicht. Besuchen Sie die Website [Microsoft Support Lifecycle](http://support.microsoft.com/lifecycle), um den Supportlebenszyklus für Ihre Softwareversion zu ermitteln.

Sicherheitslösungen für IT-Experten: [TechNet Security – Problembehandlung und Support](http://technet.microsoft.com/de-de/security/bb980617)

Hilfe beim Schützen des Computers, auf dem Windows ausgeführt wird, vor Viren und Schadsoftware: [Safety and Security Center](http://www.microsoft.com/de-de/security/default.aspx)

Lokaler Support entsprechend Ihrem Land: [Internationaler Support](http://support.microsoft.com/common/international.aspx?ln=de)

### Haftungsausschluss

Die Informationen in der Microsoft Knowledge Base werden wie besehen und ohne jede Gewährleistung bereitgestellt. Microsoft schließt alle anderen Garantien, gleich ob ausdrücklich oder konkludent, einschließlich der Garantien der Handelsüblichkeit oder Eignung für einen bestimmten Zweck aus. In keinem Fall kann Microsoft Corporation und/oder deren jeweilige Lieferanten haftbar gemacht werden für Schäden irgendeiner Art, einschließlich direkter, indirekter, zufällig entstandener Schäden, Folgeschäden, Folgen entgangenen Gewinns oder spezieller Schäden, selbst dann nicht, wenn Microsoft Corporation und/oder deren jeweilige Lieferanten auf die mögliche Entstehung dieser Schäden hingewiesen wurde. Weil in einigen Staaten/Rechtsordnungen der Ausschluss oder die Beschränkung einer Haftung für zufällig entstandene Schäden oder Folgeschäden nicht gestattet ist, gilt die obige Einschränkung eventuell nicht für Sie.

### Revisionen

-   V1.0 (11. August 2015): Bulletin Summary veröffentlicht.
-   V2.0 (18. August 2015): Das Bulletin Summary wurde überarbeitet, um das außerplanmäßige Bulletin MS15-093 der Veröffentlichung von Sicherheitsbulletins im August hinzuzufügen. Das zusätzliche Bulletin behandelt eine Sicherheitsanfälligkeit in Internet Explorer. Weitere Informationen finden Sie in MS15-093.
-   V3.0 (13. Oktober 2015): Für MS15-081 wurde das Bulletin Summary überarbeitet, um die Verfügbarkeit der Updatepakete für Microsoft Office 2016, Microsoft Visio 2016 und Microsoft Word 2016 bekannt zu geben. Kunden, die Microsoft Office 2016, Microsoft Visio 2016 oder Microsoft Word 2016 ausführen, sollten die betreffenden Updates installieren, um vor den in MS15-081 beschriebenen Sicherheitsanfälligkeiten geschützt zu sein. Die meisten Kunden haben automatische Updates aktiviert und müssen nichts weiter tun, weil die Updates automatisch heruntergeladen und installiert werden.
-   V3.1 (1. Dezember 2015): Das Bulletin Summary wurde überarbeitet, um die Benutzer über bekannte Probleme zu informieren, die den Microsoft Knowledge Base-Artikeln für die Updates zu MS15-085 (3071756) und MS15-090 (3060716) hinzugefügt wurden. Hyperlinks finden Sie in der Tabelle mit Kurzzusammenfassungen.

*Seite generiert am 01.12.2015 um 10:00Z-08:00.*
