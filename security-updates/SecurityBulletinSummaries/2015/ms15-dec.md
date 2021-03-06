---
TOCTitle: 'MS15-DEC'
Title: Microsoft Security Bulletin Summary für Dezember 2015
ms:assetid: 'ms15-dec'
ms:contentKeyID: 72045190
ms:mtpsurl: 'https://technet.microsoft.com/de-DE/library/ms15-dec(v=Security.10)'
---

Microsoft Security Bulletin Summary für Dezember 2015
=====================================================

Veröffentlicht: 8. Dezember 2015 | Aktualisiert: 16. Dezember 2015

**Version:** 1.2

In diesem Bulletin Summary sind die im Dezember 2015 veröffentlichten Security Bulletins aufgeführt.

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
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-124">MS15-124</a></td>
<td style="border:1px solid black;"><strong>Kumulatives Sicherheitsupdate für Internet Explorer (3116180)</strong> <br />
Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Internet Explorer. Die schwerwiegendste dieser Sicherheitsanfälligkeiten kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Webseite mit Internet Explorer anzeigt. Ein Angreifer, der die Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann die gleichen Benutzerrechte erlangen wie der aktuelle Benutzer. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;"><a href="https://support.microsoft.com/de-de/kb/3104002">3104002</a></td>
<td style="border:1px solid black;">Microsoft Windows, <br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-125">MS15-125</a></td>
<td style="border:1px solid black;"><strong>Kumulatives Sicherheitsupdate für Microsoft Edge (3116184) <br />
</strong>Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft Edge. Die schwerwiegendste dieser Sicherheitsanfälligkeiten kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Webseite mit Microsoft Edge anzeigt. Ein Angreifer, der die Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann die gleichen Benutzerrechte erlangen wie der aktuelle Benutzer. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows, <br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-126">MS15-126</a></td>
<td style="border:1px solid black;"><strong>Kumulatives Sicherheitsupdate für JScript und VBScript zum Unterbinden von Remotecodeausführung (3116178) <br />
</strong>Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten im VBScript-Skriptmodul in Microsoft Windows. Die schwerwiegenderen dieser Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn ein Angreifer eine speziell gestaltete Website hostet, die darauf ausgelegt ist, die Sicherheitsanfälligkeiten über Internet Explorer auszunutzen (oder eine manipulierte Website oder eine Website nutzt, die von Benutzern bereitgestellte Inhalte oder Werbung akzeptiert oder hostet) und dann Benutzer dazu verleitet, diese Website zu besuchen. Ein Angreifer kann auch ein als „initialisierungssicher“ gekennzeichnetes ActiveX-Steuerelement in eine Anwendung oder ein Microsoft Office-Dokument einbetten, die bzw. das das Grafikwiedergabemodul von Internet Explorer hostet, um den Benutzer zu der speziell gestalteten Website zu leiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-127">MS15-127</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für Microsoft Windows DNS zum Unterbinden von Remotecodeausführung (3100465)</strong> <br />
Dieses Sicherheitsupdate behebt eine Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Angreifer speziell gestaltete Anforderungen an einen DNS-Server sendet.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-128">MS15-128</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für Microsoft-Grafikkomponente zum Unterbinden von Remotecodeausführung (3104503)</strong> <br />
Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft Windows, .NET Framework, Microsoft Office, Skype for Business, Microsoft Lync und Silverlight. Die Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn ein Benutzer ein speziell gestaltetes Dokument öffnet oder eine Website besucht, in das bzw. die speziell gestaltete Schriftartdateien eingebettet sind.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows, <br />
Microsoft .NET Framework,<br />
Microsoft Office, <br />
Skype for Business, Microsoft Lync,<br />
Silverlight</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-129">MS15-129</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für Silverlight zum Unterbinden von Remotecodeausführung (3106614)</strong><br />
Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft Silverlight. Die schwerwiegendste dieser Sicherheitsanfälligkeiten kann Remotecodeausführung ermöglichen, wenn Microsoft Silverlight bestimmte Anforderungen zum Öffnen und Schließen, die zu Lese- und Schreibzugriffsverletzungen führen können, nicht ordnungsgemäß verarbeitet. Um diese Sicherheitsanfälligkeit auszunutzen, kann ein Angreifer eine Website hosten, die eine speziell gestaltete Silverlight-Anwendung enthält, und dann einen Benutzer dazu verleiten, eine manipulierte Website zu besuchen. Der Angreifer kann auch Websites ausnutzen, die speziell gestaltete Inhalte enthalten, darunter auch Websites, die Endbenutzern bereitgestellte Inhalte oder Werbemitteilungen akzeptieren oder hosten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert keinen Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Silverlight</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-130">MS15-130</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für Microsoft Uniscribe zum Unterbinden von Remotecodeausführung (3108670)</strong><br />
Dieses Sicherheitsupdate behebt eine Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer ein speziell gestaltetes Dokument öffnet oder eine nicht vertrauenswürdige Website besucht, das bzw. die speziell gestaltete Schriftarten enthält.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-131">MS15-131</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für Microsoft Office zum Unterbinden von Remotecodeausführung (3116111)</strong> <br />
Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft Office. Die schwerwiegendste Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Microsoft Office-Datei öffnet. Ein Angreifer, der die Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann beliebigen Code im Kontext des aktuellen Benutzers ausführen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Kritisch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-132">MS15-132</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für Microsoft Windows zum Unterbinden von Remotecodeausführung (3116162)</strong> <br />
Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft Windows. Die Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn ein Angreifer auf ein lokales System zugreift und eine speziell gestaltete Anwendung ausführt.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-133">MS15-133</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für Windows PGM zum Unterbinden der Erhöhung von Berechtigungen (3116130)</strong> <br />
Dieses Sicherheitsupdate behebt eine Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit kann eine Erhöhung von Berechtigungen ermöglichen, wenn sich ein Angreifer bei einem Zielsystem anmeldet und eine speziell gestaltete Anwendung ausführt, die unter Verwendung einer Racebedingung auf bereits freigegebene Speicherpositionen verweist. Nur Systeme, auf denen Microsoft Message Queuing (MSMQ) installiert und das Windows Pragmatic General Multicast-Protokoll (PGM) aktiviert ist, sind von dieser Sicherheitsanfälligkeit betroffen. In Standardkonfigurationen ist MSMQ nicht enthalten, und das PGM-Protokoll ist zwar verfügbar, aber standardmäßig deaktiviert, wenn MSMQ installiert ist.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a> <br />
Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-134">MS15-134</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für Windows Media Center Unterbinden von Remotecodeausführung (3108669)</strong><br />
Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft Windows. Die schwerwiegenderen dieser Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn in Windows Media Center eine speziell gestaltete Media Center-Linkdatei (MCL) geöffnet wird, die auf schädlichen Code verweist. Ein Angreifer, der diese Sicherheitsanfälligkeit erfolgreich ausnutzt, kann die gleichen Benutzerrechte wie der aktuelle Benutzer erlangen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="https://technet.microsoft.com/de-de/library/security/ms15-135">MS15-135</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für Windows-Kernelmodustreiber zum Unterbinden der Erhöhung von Berechtigungen (3119075)</strong> <br />
Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft Windows. Die Sicherheitsanfälligkeiten können eine Erhöhung von Berechtigungen ermöglichen, wenn sich ein Angreifer bei einem Zielsystem anmeldet und eine speziell gestaltete Anwendung ausführt.</td>
<td style="border:1px solid black;"><a href="http://technet.microsoft.com/de-de/security/gg309177.aspx">Hoch</a> <br />
Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
</tbody>
</table>
  
Ausnutzbarkeitsindex  
--------------------
  
In der folgenden Tabelle wird eine Bewertung der Ausnutzbarkeit aller Sicherheitsanfälligkeiten bereitgestellt, die diesen Monat behoben werden. Die Sicherheitsanfälligkeiten sind nach Kennung des Bulletins und dann nach CVE-ID geordnet. Im Ausnutzbarkeitsindex sind nur Sicherheitsanfälligkeiten enthalten, deren Schweregrad in diesem Bulletin als „Kritisch“ oder „Hoch“ eingestuft wurde.
  
**Wie verwende ich diese Tabelle?**  
  
Verwenden Sie diese Tabelle, um etwas über die Wahrscheinlichkeit zu erfahren, dass für die einzelnen Sicherheitsupdates, die Sie möglicherweise installieren müssen, innerhalb von 30 Tagen Angriffe durch Codeausführung und Denial-of-Service stattfinden. Sehen Sie sich unter Berücksichtigung Ihrer konkreten Konfiguration jede der unten stehenden Bewertungen an, um Prioritäten für die Bereitstellung der Updates dieses Monats festzulegen. Weitere Informationen zur Bedeutung und Festlegung dieser Bewertungen finden Sie im [Microsoft-Ausnutzbarkeitsindex](http://technet.microsoft.com/de-de/security/cc998259).
  
In den nachfolgenden Spalten bezieht sich „Aktuelle Softwareversion“ auf die Themensoftware und „Ältere Softwareversionen“ auf alle älteren, unterstützten Versionen der Themensoftware, wie sie in den Tabellen „Betroffene Software“ und „Nicht betroffene Software“ im Bulletin aufgeführt ist.

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE ID** 
</td>
<td style="border:1px solid black;">
**Titel der Sicherheitsanfälligkeit**
</td>
<td style="border:1px solid black;">
**Bewertung der Ausnutzbarkeit für  
aktuelle Softwareversion**
</td>
<td style="border:1px solid black;">
**Bewertung der Ausnutzbarkeit für  
ältere Softwareversionen**
</td>
<td style="border:1px solid black;">
**Bewertung der Ausnutzbarkeit  
durch Denial-of-Service**
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS15-124: Kumulatives Sicherheitsupdate für Internet Explorer (3116180)**](https://technet.microsoft.com/de-de/library/security/ms15-124)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6083](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6083)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6134](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6134)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6135](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6135)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Skriptmodul bezüglich der Offenlegung von Informationen
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6136](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6136)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Skriptmodul bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6138](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6138)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit durch Umgehung des XSS-Filters in Internet Explorer
</td>
<td style="border:1px solid black;">
3 – Ausnutzung unwahrscheinlich
</td>
<td style="border:1px solid black;">
3 – Ausnutzung unwahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6139](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6139)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft-Browser bezüglich Erhöhung von Berechtigungen
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6140](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6140)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Browser bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6141](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6141)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6142](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6142)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Browser bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6143](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6143)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6144](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6144)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit durch Umgehung des XSS-Filters in Microsoft-Browser
</td>
<td style="border:1px solid black;">
3 – Ausnutzung unwahrscheinlich
</td>
<td style="border:1px solid black;">
3 – Ausnutzung unwahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6145](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6145)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6146](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6146)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6147](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6147)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6148](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6148)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Browser bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6149](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6149)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6150](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6150)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6151](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6151)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Browser bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6152](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6152)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6153](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6153)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Browser bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6154](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6154)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Browser bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6155](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6155)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Browser bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6156](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6156)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6157](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6157)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Internet Explorer durch Offenlegung von Informationen
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6158](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6158)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Browser bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6159](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6159)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Browser bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6160](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6160)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6161](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6161)
</td>
<td style="border:1px solid black;">
ASLR-Umgehung durch Internet Explorer
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6162](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6162)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Internet Explorer bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6164](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6164)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit durch Umgehung des XSS-Filters in Internet Explorer
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS15-125: Kumulatives Sicherheitsupdate für Microsoft Edge (3116184)**](https://technet.microsoft.com/de-de/library/security/ms15-125)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6139](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6139)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft-Browser bezüglich Erhöhung von Berechtigungen
</td>
<td style="border:1px solid black;">
3 – Ausnutzung unwahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6140](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6140)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Browser bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
3 – Ausnutzung unwahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6142](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6142)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Browser bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
3 – Ausnutzung unwahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6148](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6148)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Browser bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
3 – Ausnutzung unwahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6151](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6151)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Browser bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
3 – Ausnutzung unwahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6153](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6153)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Edge bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
3 – Ausnutzung unwahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6154](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6154)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Browser bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
3 – Ausnutzung unwahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6155](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6155)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Browser bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6158](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6158)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Browser bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6159](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6159)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Browser bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
3 – Ausnutzung unwahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6161](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6161)
</td>
<td style="border:1px solid black;">
ASLR-Umgehung durch Microsoft Browser
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6168](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6168)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Edge bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6169](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6169)
</td>
<td style="border:1px solid black;">
Spoofing-Sicherheitsanfälligkeit in Microsoft Edge
</td>
<td style="border:1px solid black;">
3 – Ausnutzung unwahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6170](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6170)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Edge bezüglich Erhöhung von Berechtigungen
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6176](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6176)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit durch Umgehung des XSS-Filters in Microsoft Edge
</td>
<td style="border:1px solid black;">
3 – Ausnutzung unwahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS15-126: Kumulatives Sicherheitsupdate für JScript und VBScript zum Unterbinden von Remotecodeausführung (3116178)**](https://technet.microsoft.com/de-de/library/security/ms15-126)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6135](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6135)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Skriptmodul bezüglich der Offenlegung von Informationen
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6136](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6136)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Skriptmodul bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS15-127: Sicherheitsupdate für Microsoft Windows DNS zum Unterbinden von Remotecodeausführung (3100465)**](https://technet.microsoft.com/de-de/library/security/ms15-127)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6125](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6125)
</td>
<td style="border:1px solid black;">
Use-after-free-Sicherheitsanfälligkeit in Windows-DNS
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS15-128: Sicherheitsupdate für Microsoft-Grafikkomponente zum Unterbinden von Remotecodeausführung (3104503)**](https://technet.microsoft.com/de-de/library/security/ms15-128)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6106](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6106)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit durch Grafikspeicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6107](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6107)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit durch Grafikspeicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6108](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6108)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit durch Grafikspeicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS15-129: Sicherheitsupdate für Silverlight zum Unterbinden von Remotecodeausführung (3106614)**](https://technet.microsoft.com/de-de/library/security/ms15-129)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6114](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6114)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit durch Offenlegung von Informationen in Microsoft Silverlight
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6165](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6165)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit durch Offenlegung von Informationen in Microsoft Silverlight
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6166](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6166)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Silverlight bezüglich Remotecodeausführung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS15-130: Sicherheitsupdate für Microsoft Uniscribe zum Unterbinden von Remotecodeausführung (3108670)**](https://technet.microsoft.com/de-de/library/security/ms15-130)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6130](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6130)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Windows bzgl. Ganzzahlunterlauf
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
3 – Ausnutzung unwahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS15-131: Sicherheitsupdate für Microsoft Office zum Unterbinden von Remotecodeausführung (3116111)**](https://technet.microsoft.com/de-de/library/security/ms15-131)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6040](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6040)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Office bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6118](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6118)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Office bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6122](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6122)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Office bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6124](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6124)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Office bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6172](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6172)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Office bezüglich Remotecodeausführung
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6177](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6177)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Office bezüglich Speicherbeschädigung
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS15-132: Sicherheitsupdate für Microsoft Windows zum Unterbinden von Remotecodeausführung (3116162)**](https://technet.microsoft.com/de-de/library/security/ms15-132)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6128](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6128)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit beim Laden von Windows-Bibliothek bezüglich Remotecodeausführung
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6132](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6132)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit beim Laden von Windows-Bibliothek bezüglich Remotecodeausführung
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6133](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6133)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit beim Laden von Windows-Bibliothek bezüglich Remotecodeausführung
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS15-133: Sicherheitsupdate für Windows PGM zum Unterbinden der Erhöhung von Berechtigungen (3116130)**](https://technet.microsoft.com/de-de/library/security/ms15-133)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6126](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6126)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Windows PGM UAF bezüglich der Erhöhung von Berechtigungen
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS15-134: Sicherheitsupdate für Windows PGM zum Unterbinden der Erhöhung von Berechtigungen (3116130)**](https://technet.microsoft.com/de-de/library/security/ms15-134)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6127](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6127)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Windows Media Center bezüglich der Offenlegung von Informationen
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6131](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6131)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Media Center-Bibliotheksanalyse bezüglich Remotecodeausführung
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS15-135: Sicherheitsupdate für Windows-Kernelmodustreiber zum Unterbinden der Erhöhung von Berechtigungen (3119075)**](https://technet.microsoft.com/de-de/library/security/ms15-135)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6171](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6171)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit im Windows-Kernelspeicher bezüglich der Erhöhung von Berechtigungen
</td>
<td style="border:1px solid black;">
3 – Ausnutzung unwahrscheinlich
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Dauerhaft
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6173](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6173)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit im Windows-Kernelspeicher bezüglich der Erhöhung von Berechtigungen
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Dauerhaft
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6174](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6174)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit im Windows-Kernelspeicher bezüglich der Erhöhung von Berechtigungen
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
1 – Ausnutzung wahrscheinlich
</td>
<td style="border:1px solid black;">
Dauerhaft
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2015-6175](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2015-6175)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit im Windows-Kernelspeicher bezüglich der Erhöhung von Berechtigungen
</td>
<td style="border:1px solid black;">
0 – Ausnutzung erkannt
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
</table>
 

Betroffene Software
-------------------

In den folgenden Tabellen sind die Bulletins nach Hauptsoftwarekategorie und Schweregrad aufgeführt.

In diesen Tabellen finden Sie Informationen zu Sicherheitsupdates, die Sie möglicherweise installieren sollten. Alle aufgeführten Softwareprogramme bzw. -komponenten sollten überprüft werden, um zu sehen, ob Sicherheitsupdates für Ihre Installation zutreffen. Wenn ein Softwareprogramm oder eine Komponente aufgeführt ist, ist die Bewertung des Schweregrads des Softwareupdates ebenfalls aufgeführt.

**Hinweis** Für eine Sicherheitsanfälligkeit müssen möglicherweise mehrere Sicherheitsupdates installiert werden. Durchsuchen Sie in der gesamten Spalte die einzelnen Kennungen der aufgeführten Bulletins, um basierend auf den auf Ihrem System installierten Programmen oder Komponenten zu überprüfen, welche Updates Sie installieren müssen.

 

### Windows-Betriebssysteme und Komponenten (Tabelle 1 von 2)

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
[**MS15-124**](https://technet.microsoft.com/de-de/library/security/ms15-124)
</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/de-de/library/security/ms15-125)
</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/de-de/library/security/ms15-126)
</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/de-de/library/security/ms15-127)
</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/de-de/library/security/ms15-128)
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
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx) 
</td>
<td style="border:1px solid black;">
**Keine**
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
Internet Explorer 7  
(3104002)  
(Kritisch)  
Internet Explorer 8  
(3104002)  
(Kritisch)  
Internet Explorer 9  
(3104002)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3105579)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3109094)  
(Kritisch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3099860)  
(Kritisch)  
Microsoft .NET Framework 4  
(3099866)  
(Kritisch)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3099869)  
(Kritisch)  
Microsoft .NET Framework 4.6  
(3099874)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3104002)  
(Kritisch)  
Internet Explorer 8  
(3104002)  
(Kritisch)  
Internet Explorer 9  
(3104002)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3105579)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3109094)  
(Kritisch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3099860)  
(Kritisch)  
Microsoft .NET Framework 4  
(3099866)  
(Kritisch)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3099869)  
(Kritisch)  
Microsoft .NET Framework 4.6  
(3099874)  
(Kritisch)
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
[**MS15-124**](https://technet.microsoft.com/de-de/library/security/ms15-124)
</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/de-de/library/security/ms15-125)
</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/de-de/library/security/ms15-126)
</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/de-de/library/security/ms15-127)
</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/de-de/library/security/ms15-128)
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
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3104002)  
(Mittel)  
Internet Explorer 8  
(3104002)  
(Mittel)  
Internet Explorer 9  
(3104002)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3105579)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(3100465)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(3109094)  
(Kritisch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3099860)  
(Kritisch)  
Microsoft .NET Framework 4  
(3099866)  
(Kritisch)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3099869)  
(Kritisch)  
Microsoft .NET Framework 4.6  
(3099874)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3104002)  
(Mittel)  
Internet Explorer 8  
(3104002)  
(Mittel)  
Internet Explorer 9  
(3104002)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3105579)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(3100465)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(3109094)  
(Kritisch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3099860)  
(Kritisch)  
Microsoft .NET Framework 4  
(3099866)  
(Kritisch)  
Microsoft .NET Framework 4.5/4.5.1/4.5.2  
(3099869)  
(Kritisch)  
Microsoft .NET Framework 4.6  
(3099874)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 7  
(3104002)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3105579)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(3109094)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-124**](https://technet.microsoft.com/de-de/library/security/ms15-124)
</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/de-de/library/security/ms15-125)
</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/de-de/library/security/ms15-126)
</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/de-de/library/security/ms15-127)
</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/de-de/library/security/ms15-128)
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
**Keine**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
**Keine**
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
Internet Explorer 8  
(3104002)  
(Kritisch)  
Internet Explorer 9  
(3104002)  
(Kritisch)  
Internet Explorer 10  
(3104002)  
(Kritisch)  
Internet Explorer 11  
(3104002)  
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
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(3109094)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(3099862)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3104002)  
(Kritisch)  
Internet Explorer 9  
(3104002)  
(Kritisch)  
Internet Explorer 10  
(3104002)  
(Kritisch)  
Internet Explorer 11  
(3104002)  
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
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(3109094)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(3099862)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-124**](https://technet.microsoft.com/de-de/library/security/ms15-124)
</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/de-de/library/security/ms15-125)
</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/de-de/library/security/ms15-126)
</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/de-de/library/security/ms15-127)
</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/de-de/library/security/ms15-128)
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
**Keine**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3104002)  
(Mittel)  
Internet Explorer 9  
(3104002)  
(Mittel)  
Internet Explorer 10  
(3104002)  
(Mittel)  
Internet Explorer 11  
(3104002)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(3100465)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(3109094)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(3099862)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 8  
(3104002)  
(Mittel)
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
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(3109094)  
(Kritisch)
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
[**MS15-124**](https://technet.microsoft.com/de-de/library/security/ms15-124)
</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/de-de/library/security/ms15-125)
</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/de-de/library/security/ms15-126)
</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/de-de/library/security/ms15-127)
</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/de-de/library/security/ms15-128)
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
**Keine**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
**Keine**
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
Internet Explorer 10  
(3104002)  
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
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme  
(3109094)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3099863)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3104002)  
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
<td style="border:1px solid black;">
Windows 8 für x64-basierte Systeme  
(3109094)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3099863)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3104002)  
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
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme  
(3109094)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3099864)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3104002)  
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
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme  
(3109094)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3099864)  
(Kritisch)
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
[**MS15-124**](https://technet.microsoft.com/de-de/library/security/ms15-124)
</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/de-de/library/security/ms15-125)
</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/de-de/library/security/ms15-126)
</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/de-de/library/security/ms15-127)
</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/de-de/library/security/ms15-128)
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
**Keine**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3104002)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3100465)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3109094)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3099863)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3104002)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3100465)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3109094)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3099864)  
(Kritisch)
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
[**MS15-124**](https://technet.microsoft.com/de-de/library/security/ms15-124)
</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/de-de/library/security/ms15-125)
</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/de-de/library/security/ms15-126)
</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/de-de/library/security/ms15-127)
</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/de-de/library/security/ms15-128)
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
**Keine**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(3104002)  
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
<td style="border:1px solid black;">
Windows RT  
(3109094)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3104002)  
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
<td style="border:1px solid black;">
Windows RT 8.1  
(3109094)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 10**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-124**](https://technet.microsoft.com/de-de/library/security/ms15-124)
</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/de-de/library/security/ms15-125)
</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/de-de/library/security/ms15-126)
</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/de-de/library/security/ms15-127)
</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/de-de/library/security/ms15-128)
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
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3116869)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3116869)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 10 für 32-Bit-Systeme  
(3116869)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3116869)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3116869)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3116869)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme  
(3116869)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3116869)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3116900)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3116900)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 für 32-Bit-Systeme  
(3116900)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3116900)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3116900)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 für x64-basierte Systeme  
(3116900)  
(Kritisch)
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
[**MS15-124**](https://technet.microsoft.com/de-de/library/security/ms15-124)
</td>
<td style="border:1px solid black;">
[**MS15-125**](https://technet.microsoft.com/de-de/library/security/ms15-125)
</td>
<td style="border:1px solid black;">
[**MS15-126**](https://technet.microsoft.com/de-de/library/security/ms15-126)
</td>
<td style="border:1px solid black;">
[**MS15-127**](https://technet.microsoft.com/de-de/library/security/ms15-127)
</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/de-de/library/security/ms15-128)
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
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3105579)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(Server Core-Installation)  
(3100465)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(Server Core-Installation)  
(3109094)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
VBScript 5.7  
(3105579)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(Server Core-Installation)  
(3100465)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(Server Core-Installation)  
(3109094)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
VBScript 5.8  
(3105578)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(Server Core-Installation)  
(3100465)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(Server Core-Installation)  
(3109094)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(3099862)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core-Installation)
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
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core-Installation)  
(3100465)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core-Installation)  
(3109094)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3099863)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core-Installation)
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
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core-Installation)  
(3100465)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core-Installation)  
(3109094)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3099864)  
(Kritisch)
</td>
</tr>
</table>
 
**Hinweis zu MS15-128**

Dieses Bulletin umfasst mehr als eine Softwarekategorie. Zusätzliche betroffene Software finden Sie in den anderen Tabellen in diesem Abschnitt. 

 

### Windows-Betriebssysteme und Komponenten (Tabelle 2 von 2)

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
[**MS15-130**](https://technet.microsoft.com/de-de/library/security/ms15-130)
</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/de-de/library/security/ms15-132)
</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/de-de/library/security/ms15-133)
</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/de-de/library/security/ms15-134)
</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/de-de/library/security/ms15-135)
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
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3108371)  
(Hoch)  
Windows Vista Service Pack 2  
(3108381)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3109103)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3109094)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3108371)  
(Hoch)  
Windows Vista x64 Edition Service Pack 2  
(3108381)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3109103)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3109094)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Windows Server 2008**
</td>
<td style="border:1px solid black;" colspan="3">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-130**](https://technet.microsoft.com/de-de/library/security/ms15-130)
</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/de-de/library/security/ms15-132)
</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/de-de/library/security/ms15-133)
</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/de-de/library/security/ms15-134)
</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/de-de/library/security/ms15-135)
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
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(3108371)  
(Hoch)  
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(3108381)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(3109103)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(3109094)  
(Hoch)
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
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(3108371)  
(Hoch)  
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(3108381)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(3109103)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(3109094)  
(Hoch)
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
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(3108371)  
(Hoch)  
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(3108381)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(3109103)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(3109094)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 7**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-130**](https://technet.microsoft.com/de-de/library/security/ms15-130)
</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/de-de/library/security/ms15-132)
</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/de-de/library/security/ms15-133)
</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/de-de/library/security/ms15-134)
</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/de-de/library/security/ms15-135)
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
(3108670)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(3108371)  
(Hoch)  
Windows 7 für 32-Bit-Systeme Service Pack 1  
(3108381)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(3109103)
</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(3109094)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(3108670)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(3108371)  
(Hoch)  
Windows 7 für x64-basierte Systeme Service Pack 1  
(3108381)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(3109103)
</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(3109094)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows Server 2008 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-130**](https://technet.microsoft.com/de-de/library/security/ms15-130)
</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/de-de/library/security/ms15-132)
</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/de-de/library/security/ms15-133)
</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/de-de/library/security/ms15-134)
</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/de-de/library/security/ms15-135)
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
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(3108670)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(3108371)  
(Hoch)  
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(3108381)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(3109103)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(3109094)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(3108670)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(3108371)  
(Hoch)  
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(3108381)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(3109103)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(3109094)  
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
[**MS15-130**](https://technet.microsoft.com/de-de/library/security/ms15-130)
</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/de-de/library/security/ms15-132)
</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/de-de/library/security/ms15-133)
</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/de-de/library/security/ms15-134)
</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/de-de/library/security/ms15-135)
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
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme  
(3108347)  
(Hoch)  
Windows 8 für 32-Bit-Systeme  
(3108381)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme  
(3109103)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8 für 32-Bit-Systeme  
(3109094)  
(Hoch)
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
Windows 8 für x64-basierte Systeme  
(3108347)  
(Hoch)  
Windows 8 für x64-basierte Systeme  
(3108381)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8 für x64-basierte Systeme  
(3109103)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8 für x64-basierte Systeme  
(3109094)  
(Hoch)
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
Windows 8.1 für 32-Bit-Systeme  
(3108347)  
(Hoch)  
Windows 8.1 für 32-Bit-Systeme  
(3108381)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme  
(3109103)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme  
(3109094)  
(Hoch)
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
Windows 8.1 für x64-basierte Systeme  
(3108347)  
(Hoch)  
Windows 8.1 für x64-basierte Systeme  
(3108381)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme  
(3109103)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Media Center  
(3108669)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme  
(3109094)  
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
[**MS15-130**](https://technet.microsoft.com/de-de/library/security/ms15-130)
</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/de-de/library/security/ms15-132)
</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/de-de/library/security/ms15-133)
</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/de-de/library/security/ms15-134)
</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/de-de/library/security/ms15-135)
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
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3108347)  
(Hoch)  
Windows Server 2012  
(3108381)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3109103)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3109094)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3108347)  
(Hoch)  
Windows Server 2012 R2  
(3108381)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3109103)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3109094)  
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
[**MS15-130**](https://technet.microsoft.com/de-de/library/security/ms15-130)
</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/de-de/library/security/ms15-132)
</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/de-de/library/security/ms15-133)
</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/de-de/library/security/ms15-134)
</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/de-de/library/security/ms15-135)
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
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows RT  
(3108347)  
(Hoch)  
Windows RT  
(3108381)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows RT  
(3109103)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows RT  
(3109094)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3108347)  
(Hoch)  
Windows RT 8.1  
(3108381)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3109103)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3109094)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="6">
**Windows 10**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-130**](https://technet.microsoft.com/de-de/library/security/ms15-130)
</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/de-de/library/security/ms15-132)
</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/de-de/library/security/ms15-133)
</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/de-de/library/security/ms15-134)
</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/de-de/library/security/ms15-135)
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
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://technet.microsoft.com/de-de/security/gg309177.aspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 10 für 32-Bit-Systeme  
(3116869)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 10 für 32-Bit-Systeme  
(3116869)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 10 für 32-Bit-Systeme  
(3116869)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme  
(3116869)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme  
(3116869)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme  
(3116869)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 für 32-Bit-Systeme  
(3116900)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 für 32-Bit-Systeme  
(3116900)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 für 32-Bit-Systeme  
(3116900)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 für x64-basierte Systeme  
(3116900)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 für x64-basierte Systeme  
(3116900)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 für x64-basierte Systeme  
(3116900)  
(Hoch)
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
[**MS15-130**](https://technet.microsoft.com/de-de/library/security/ms15-130)
</td>
<td style="border:1px solid black;">
[**MS15-132**](https://technet.microsoft.com/de-de/library/security/ms15-132)
</td>
<td style="border:1px solid black;">
[**MS15-133**](https://technet.microsoft.com/de-de/library/security/ms15-133)
</td>
<td style="border:1px solid black;">
[**MS15-134**](https://technet.microsoft.com/de-de/library/security/ms15-134)
</td>
<td style="border:1px solid black;">
[**MS15-135**](https://technet.microsoft.com/de-de/library/security/ms15-135)
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
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(Server Core-Installation)  
(3108381)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(Server Core-Installation)  
(3109103)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(Server Core-Installation)  
(3109094)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(Server Core-Installation)  
(3108381)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(Server Core-Installation)  
(3109103)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(Server Core-Installation)  
(3109094)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(Server Core-Installation)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(Server Core-Installation)  
(3108670)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(Server Core-Installation)  
(3108381)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(Server Core-Installation)  
(3109103)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(Server Core-Installation)  
(3109094)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core-Installation)  
(3108347)  
(Hoch)  
Windows Server 2012  
(Server Core-Installation)  
(3108381)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core-Installation)  
(3109103)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core-Installation)  
(3109094)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core-Installation)  
(3108347)  
(Hoch)  
Windows Server 2012 R2  
(Server Core-Installation)  
(3108381)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core-Installation)  
(3109103)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core-Installation)  
(3109094)  
(Hoch)
</td>
</tr>
</table>
 
 

### Microsoft Office Suites und Software

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2007**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/de-de/library/security/ms15-128)
</td>
<td style="border:1px solid black;">
[**MS15-131**](https://technet.microsoft.com/de-de/library/security/ms15-131)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3085616)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3085549)  
(Hoch)  
Microsoft Excel 2007 Service Pack 3  
(3114422)  
(Hoch)  
Microsoft Word 2007 Service Pack 3  
(3114458)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2010**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/de-de/library/security/ms15-128)
</td>
<td style="border:1px solid black;">
[**MS15-131**](https://technet.microsoft.com/de-de/library/security/ms15-131)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32-Bit-Editionen)  
(3085612)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32-Bit-Editionen)  
(3085528)  
(Hoch)  
Microsoft Office 2010 Service Pack 2 (32-Bit-Editionen)  
(3114403)  
(Kritisch)  
Microsoft Excel 2010 Service Pack 2 (32-Bit-Editionen)  
(3114415)  
(Hoch)  
Microsoft Word 2010 Service Pack 2 (32-Bit-Editionen)  
(3101532)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64-Bit-Editionen)  
(3085612)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64-Bit-Editionen)  
(3085528)  
(Hoch)  
Microsoft Office 2010 Service Pack 2 (64-Bit-Editionen)  
(3114403)  
(Kritisch)  
Microsoft Excel 2010 Service Pack 2 (64-Bit-Editionen)  
(3114415)  
(Hoch)  
Microsoft Word 2010 Service Pack 2 (64-Bit-Editionen)  
(3101532)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/de-de/library/security/ms15-128)
</td>
<td style="border:1px solid black;">
[**MS15-131**](https://technet.microsoft.com/de-de/library/security/ms15-131)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 Service Pack 1 (32-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft Word 2013 Service Pack 1 (32-Bit-Editionen)  
(3114342)  
(Kritisch)
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
Microsoft Word 2013 Service Pack 1 (64-Bit-Editionen)  
(3114342)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2016**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/de-de/library/security/ms15-128)
</td>
<td style="border:1px solid black;">
[**MS15-131**](https://technet.microsoft.com/de-de/library/security/ms15-131)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft Word 2016 (32-Bit-Edition)  
(3114382)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft Word 2016 (64-Bit-Edition)  
(3114382)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2013 RT**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/de-de/library/security/ms15-128)
</td>
<td style="border:1px solid black;">
[**MS15-131**](https://technet.microsoft.com/de-de/library/security/ms15-131)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2013 RT Service Pack 1
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft Word 2013 RT Service Pack 1  
(3114342)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office für Mac**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/de-de/library/security/ms15-128)
</td>
<td style="border:1px solid black;">
[**MS15-131**](https://technet.microsoft.com/de-de/library/security/ms15-131)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office für Mac 2011
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft Excel für Mac 2011  
(3119517)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 für Mac
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 für Mac  
(3119518)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Weitere Office-Software**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/de-de/library/security/ms15-128)
</td>
<td style="border:1px solid black;">
[**MS15-131**](https://technet.microsoft.com/de-de/library/security/ms15-131)
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
(3114457)  
(Kritisch)  
Microsoft Office Compatibility Pack Service Pack 3  
(3114431)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel Viewer
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft Excel Viewer  
(3114433)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114478)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
</table>
 
**Hinweis zu MS15-128**

Dieses Bulletin umfasst mehr als eine Softwarekategorie. Zusätzliche betroffene Software finden Sie in den anderen Tabellen in diesem Abschnitt. 

 

### Microsoft Communications-Plattformen und -Software

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft Live Meeting 2007-Konsole**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/de-de/library/security/ms15-128)
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
(3115875)  
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
[**MS15-128**](https://technet.microsoft.com/de-de/library/security/ms15-128)
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
(3115871)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 Bit)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64 Bit)  
(3115871)  
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
(3115872)  
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
(3115873)  
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
[**MS15-128**](https://technet.microsoft.com/de-de/library/security/ms15-128)
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
(Skype for Business)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (32-Bit)  
(Skype for Business)  
(3114351)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32-Bit)  
(Skype for Business Basic)
</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (32-Bit)  
(Skype for Business Basic)  
(3114351)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64-Bit)  
(Skype for Business)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2013 Service Pack 1 (64-Bit)  
(Skype for Business)  
(3114351)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64-Bit)  
(Skype for Business Basic)
</td>
<td style="border:1px solid black;">
Microsoft Lync Basic 2013 Service Pack 1 (64-Bit)  
(Skype for Business Basic)  
(3114351)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="2">
**Skype for Business 2016**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/de-de/library/security/ms15-128)
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
Skype for Business 2016 (32 Bit)
</td>
<td style="border:1px solid black;">
Skype for Business 2016 (32 Bit)  
(3114372)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (32-Bit)
</td>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (32-Bit)  
(3114372)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business 2016 (64 Bit)
</td>
<td style="border:1px solid black;">
Skype for Business 2016 (64 Bit)  
(3114372)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (64-Bit)
</td>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (64-Bit)  
(3114372)  
(Kritisch)
</td>
</tr>
</table>
 
**Hinweis zu MS15-128**

Dieses Bulletin umfasst mehr als eine Softwarekategorie. Zusätzliche betroffene Software finden Sie in den anderen Tabellen in diesem Abschnitt. 

 

### Microsoft Entwicklertools und Software

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Silverlight**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS15-128**](https://technet.microsoft.com/de-de/library/security/ms15-128)
</td>
<td style="border:1px solid black;">
[**MS15-129**](https://technet.microsoft.com/de-de/library/security/ms15-129)
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
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Silverlight 5
</td>
<td style="border:1px solid black;">
Microsoft Silverlight 5 bei Installation auf dem Mac  
(3106614)  
(Kritisch)  
Microsoft Silverlight 5 Developer Runtime bei Installation auf dem Mac  
(3106614)  
(Kritisch)  
Microsoft Silverlight 5 bei Installation unter allen unterstützten Versionen von Microsoft Windows-Clients  
(3106614)  
(Kritisch)  
Microsoft Silverlight 5 Developer Runtime bei Installation unter allen unterstützten Versionen von Microsoft Windows-Clients  
(3106614)  
(Kritisch)  
Microsoft Silverlight 5 bei Installation unter allen unterstützten Versionen von Microsoft Windows-Servern  
(3106614)  
(Kritisch)  
Microsoft Silverlight 5 Developer Runtime bei Installation unter allen unterstützten Versionen von Microsoft Windows-Servern  
(3106614)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft Silverlight 5 bei Installation auf dem Mac  
(3106614)  
(Kritisch)  
Microsoft Silverlight 5 Developer Runtime bei Installation auf dem Mac  
(3106614)  
(Kritisch)  
Microsoft Silverlight 5 bei Installation unter allen unterstützten Versionen von Microsoft Windows-Clients  
(3106614)  
(Kritisch)  
Microsoft Silverlight 5 Developer Runtime bei Installation unter allen unterstützten Versionen von Microsoft Windows-Clients  
(3106614)  
(Kritisch)  
Microsoft Silverlight 5 bei Installation unter allen unterstützten Versionen von Microsoft Windows-Servern  
(3106614)  
(Kritisch)  
Microsoft Silverlight 5 Developer Runtime bei Installation unter allen unterstützten Versionen von Microsoft Windows-Servern  
(3106614)  
(Kritisch)
</td>
</tr>
</table>
 
**Hinweis zu MS15-128**

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

Sicherheitslösungen für IT-Profis: [TechNet Security – Problembehandlung und Support](http://technet.microsoft.com/de-de/security/bb980617)

Hilfe beim Schützen des Computers, auf dem Windows ausgeführt wird, vor Viren und Schadsoftware: [Safety and Security Center](http://www.microsoft.com/de-de/security/default.aspx)

Lokaler Support entsprechend Ihrem Land: [Internationaler Support](http://support.microsoft.com/common/international.aspx?ln=de)

### Haftungsausschluss

Die Informationen in der Microsoft Knowledge Base werden wie besehen und ohne jede Gewährleistung bereitgestellt. Microsoft schließt alle anderen Garantien, gleich ob ausdrücklich oder konkludent, einschließlich der Garantien der Handelsüblichkeit oder Eignung für einen bestimmten Zweck aus. In keinem Fall kann Microsoft Corporation und/oder deren jeweilige Lieferanten haftbar gemacht werden für Schäden irgendeiner Art, einschließlich direkter, indirekter, zufällig entstandener Schäden, Folgeschäden, Folgen entgangenen Gewinns oder spezieller Schäden, selbst dann nicht, wenn Microsoft Corporation und/oder deren jeweilige Lieferanten auf die mögliche Entstehung dieser Schäden hingewiesen wurde. Weil in einigen Staaten/Rechtsordnungen der Ausschluss oder die Beschränkung einer Haftung für zufällig entstandene Schäden oder Folgeschäden nicht gestattet ist, gilt die obige Einschränkung eventuell nicht für Sie.

### Revisionen

-   V1.0 (8. Dezember 2015): Bulletin Summary veröffentlicht.
-   V1.1 (9. Dezember 2015): Das Bulletin wurde überarbeitet, um die Bewertung der Ausnutzbarkeit von CVE-2015-6124 zu korrigieren. Dies ist lediglich eine Informationsänderung.
-   V1.2 (16. Dezember 2015): Das Bulletin Summary wurde überarbeitet, um der Tabelle in der Kurzzusammenfassung für 3104002 ein bekanntes Problem hinzuzufügen. Um das Problem zu beheben, installieren Sie Hotfix 3125446. Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 3104002](https://support.microsoft.com/de-de/kb/3104002).

*Seite generiert am 16.12.2015 um 17:23:00-08:00.*
