---
TOCTitle: 'MS16-APR'
Title: Microsoft Security Bulletin Summary für April 2016
ms:assetid: 'ms16-apr'
ms:contentKeyID: 72785318
ms:mtpsurl: 'https://technet.microsoft.com/de-DE/library/ms16-apr(v=Security.10)'
---

Microsoft Security Bulletin Summary für April 2016
==================================================

Veröffentlicht: 12. April 2016 | Aktualisiert: 11. April 2017

**Version:** 3.0

In diesem Bulletin Summary sind die im April 2016 veröffentlichten Sicherheitsbulletins aufgeführt.

Weitere Informationen zum Erhalten automatischer Benachrichtigungen über die Veröffentlichung von Microsoft-Sicherheitsbulletins finden Sie unter [Microsoft Technische Sicherheitsbenachrichtigungen](http://go.microsoft.com/fwlink/?linkid=21163).

Microsoft stellt auch Informationen bereit, anhand derer Benutzer die Prioritäten für monatliche Sicherheitsupdates und alle nicht sicherheitsrelevanten Updates festlegen können, die an demselben Tag veröffentlicht werden wie die monatlichen Sicherheitsupdates. Bitte lesen Sie den Abschnitt **Weitere Informationen**.

Kurzzusammenfassungen
---------------------

In der folgenden Tabelle sind die Sicherheitsbulletins für diesen Monat nach Schweregrad geordnet.

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
und Sicherheitsauswirkung</strong></td>
<td style="border:1px solid black;"><strong>Neustartanforderung</strong></td>
<td style="border:1px solid black;"><strong>Bekannte<br />
Probleme</strong></td>
<td style="border:1px solid black;"><strong>Betroffene Software</strong></td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=746891">MS16-037</a></td>
<td style="border:1px solid black;"><strong>Kumulatives Sicherheitsupdate für Internet Explorer (3148531)<br />
</strong>Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Internet Explorer. Die schwerwiegendste dieser Sicherheitsanfälligkeiten kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Webseite mit Internet Explorer anzeigt. Ein Angreifer, der die Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann die gleichen Benutzerrechte erlangen wie der aktuelle Benutzer. Wenn der aktuelle Benutzer mit Administratorrechten angemeldet ist, kann ein Angreifer die Kontrolle über ein betroffenes System übernehmen. Der Angreifer könnte dann Programme installieren, Daten anzeigen, ändern oder löschen oder neue Benutzerkonten mit uneingeschränkten Rechten erstellen.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Internet Explorer</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=746894">MS16-038</a></td>
<td style="border:1px solid black;"><strong>Kumulatives Sicherheitsupdate für Microsoft Edge (3148532)<br />
</strong>Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft Edge. Die schwerwiegendste dieser Sicherheitsanfälligkeiten kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Webseite mit Microsoft Edge anzeigt. Ein Angreifer, der die Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann die gleichen Benutzerrechte erlangen wie der aktuelle Benutzer. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für jene, die mit Administratorrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft Edge</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=746883">MS16-039</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für Microsoft-Grafikkomponente (3148522)</strong><br />
Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft Windows, Microsoft .NET Framework, Microsoft Office, Skype for Business und Microsoft Lync. Die schwerwiegendste dieser Sicherheitsanfälligkeiten kann Remotecodeausführung ermöglichen, wenn ein Benutzer ein speziell gestaltetes Dokument öffnet oder eine Webseite besucht, in das bzw. die OpenType-Schriftartdateien eingebettet sind.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;"><a href="http://support.microsoft.com/de-de/kb/3148522">3148522</a></td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework,<br />
Microsoft Office, Skype for Business,<br />
Microsoft Lync.</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=746897">MS16-040</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für Microsoft XML Core Services (3148541)</strong><br />
Dieses Sicherheitsupdate behebt eine Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer auf einen speziell gestalteten Link klickt, der einem Angreifer die Remoteausführung von schädlichem Code ermöglicht, mit dem er die Kontrolle über das System des Benutzers erlangen kann. Ein Angreifer hat jedoch keinesfalls die Möglichkeit, Benutzer zum Klicken auf einen speziell gestalteten Link zu zwingen. Vielmehr muss ein Angreifer den Benutzer dazu verleiten, auf den Link zu klicken. Zu diesem Zweck wird der Benutzer normalerweise dazu gebracht, auf einen Link in einer E-Mail-Nachricht oder einer Instant Messenger-Nachricht zu klicken.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=746929">MS16-041</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für .NET Framework (3148789)</strong><br />
Dieses Sicherheitsupdate behebt eine Sicherheitsanfälligkeit in Microsoft .NET Framework. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Angreifer auf ein lokales System zugreift und eine schädliche Anwendung ausführt.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Hoch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Microsoft .NET Framework</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=746928">MS16-042</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für Microsoft Office (3148775)</strong><br />
Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft Office. Die schwerwiegendste dieser Sicherheitsanfälligkeiten kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Microsoft Office-Datei öffnet. Ein Angreifer, der die Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann beliebigen Code im Kontext des aktuellen Benutzers ausführen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit Administratorrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;"><a href="http://support.microsoft.com/de-de/kb/3148775">3148775</a></td>
<td style="border:1px solid black;">Microsoft Office,<br />
Microsoft Office-Dienste und Web Apps</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=747040">MS16-044</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für Windows OLE (3146706)</strong><br />
Dieses Sicherheitsupdate behebt eine Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn Windows OLE Benutzereingaben nicht ordnungsgemäß überprüft. Angreifer können die Sicherheitsanfälligkeit ausnutzen, um schädlichen Code auszuführen. Allerdings muss ein Angreifer einen Benutzer zunächst dazu verleiten, eine speziell gestaltete Datei oder ein speziell gestaltetes Programm auf einer Webseite oder in einer E-Mail-Nachricht zu öffnen.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Hoch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;"><a href="http://support.microsoft.com/de-de/kb/3146706">3146706</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=733440">MS16-045</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für Windows Hyper-V (3143118)</strong><br />
Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Microsoft Windows. Die schwerwiegendste dieser Sicherheitsanfälligkeiten kann Remotecodeausführung ermöglichen, wenn ein authentifizierter Angreifer auf einem Gastbetriebssystem eine speziell gestaltete Anwendung ausführt, die bewirkt, dass das Betriebssystem des Hyper-V-Hosts beliebigen Code ausführt. Endbenutzer, die die Hyper-V-Rolle nicht aktiviert haben, sind nicht betroffen.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Hoch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=746896">MS16-046</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für sekundäre Anmeldung (3148538)</strong><br />
Dieses Sicherheitsupdate behebt eine Sicherheitsanfälligkeit in Microsoft Windows. Ein Angreifer, der diese Sicherheitsanfälligkeit erfolgreich ausnutzt, kann beliebigen Code als Administrator ausführen.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Hoch</a> <br />
Rechteerweiterungen</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=746885">MS16-047</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für SAM- und LSAD-Remoteprotokolle (3148527)<br />
</strong>Dieses Sicherheitsupdate behebt eine Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit kann eine Erhöhung von Berechtigungen ermöglichen, wenn ein Angreifer einen Man-in-the-Middle-Angriff ausführt. Ein Angreifer könnte dann eine Herabstufung der Authentifizierungsebene der SAM- und LSAD-Kanäle erzwingen und die Identität des authentifizierten Benutzers annehmen.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Hoch</a> <br />
Rechteerweiterungen</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=746886">MS16-048</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für CSRSS (3148528)<br />
</strong>Dieses Sicherheitsupdate behebt eine Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit kann die Umgehung von Sicherheitsfunktionen ermöglichen, wenn sich ein Angreifer bei einem Zielsystem anmeldet und eine speziell gestaltete Anwendung ausführt.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Hoch</a> <br />
Umgehung von Sicherheitsfunktionen</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;"><a href="http://support.microsoft.com/de-de/kb/3146723">3146723</a></td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=746932">MS16-049</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für HTTP.sys (3148795)<br />
</strong>Dieses Sicherheitsupdate behebt eine Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit kann einen Denial-of-Service-Angriff ermöglichen, wenn ein Angreifer ein speziell gestaltetes HTTP-Paket an ein Zielsystem sendet.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Hoch</a> <br />
Denial-of-Service</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=785154">MS16-050</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsupdate für Adobe Flash Player (3154132)</strong><br />
Dieses Sicherheitsupdate behebt Sicherheitsanfälligkeiten in Adobe Flash Player bei der Installation unter allen unterstützten Editionen von Windows 8.1, Windows Server 2012, Windows Server 2012 R2, Windows RT 8.1 und Windows 10.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisch</a> <br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">---------</td>
<td style="border:1px solid black;">Microsoft Windows,<br />
Adobe Flash Player</td>
</tr>
</tbody>
</table>
 

Ausnutzbarkeitsindex
--------------------

In der folgenden Tabelle wird eine Bewertung der Ausnutzbarkeit aller Sicherheitsanfälligkeiten bereitgestellt, die diesen Monat behoben werden. Die Sicherheitsanfälligkeiten sind nach Kennung des Bulletins und dann nach CVE-ID geordnet. Im Ausnutzbarkeitsindex sind nur Sicherheitsanfälligkeiten enthalten, deren Schweregrad in diesem Bulletin als „Kritisch“ oder „Hoch“ eingestuft wurde.

**Wie verwende ich diese Tabelle?**  

Verwenden Sie diese Tabelle, um etwas über die Wahrscheinlichkeit zu erfahren, dass für die einzelnen Sicherheitsupdates, die Sie möglicherweise installieren müssen, innerhalb von 30 Tagen nach der Veröffentlichung des Sicherheitsbulletins Angriffe durch Codeausführung und Denial-of-Service stattfinden. Sehen Sie sich unter Berücksichtigung Ihrer konkreten Konfiguration jede der unten stehenden Bewertungen an, um Prioritäten für die Bereitstellung der Updates dieses Monats festzulegen. Weitere Informationen zur Bedeutung und Festlegung dieser Bewertungen finden Sie im [Microsoft-Ausnutzbarkeitsindex](http://technet.microsoft.com/de-de/security/cc998259).

In den nachfolgenden Spalten bezieht sich „Aktuelle Softwareversion“ auf die Themensoftware und „Ältere Softwareversionen“ auf alle älteren, unterstützten Versionen der Themensoftware, wie sie in den Tabellen „Betroffene Software“ und „Nicht betroffene Software“ im Bulletin aufgeführt ist.

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;">
**CVE-ID**                    
</td>
<td style="border:1px solid black;">
**Titel der Sicherheitsanfälligkeit**
</td>
<td style="border:1px solid black;">
**Bewertung der Ausnutzbarkeit für  
aktuelle Softwareversionen**
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
[**MS16-037: Kumulatives Sicherheitsupdate für Internet Explorer (3148531)**](http://go.microsoft.com/fwlink/?linkid=746891)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0154](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0154)
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
[CVE-2016-0159](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0159)
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
[CVE-2016-0160](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0160)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit beim Laden von DLL-Dateien bezüglich Remotecodeausführung
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
[CVE-2016-0162](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0162)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Internet Explorer durch Offenlegung von Informationen
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
[CVE-2016-0164](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0164)
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
[CVE-2016-0166](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0166)
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
<td style="border:1px solid black;" colspan="5">
[**MS16-038: Kumulatives Sicherheitsupdate für Microsoft Edge (3148532)**](http://go.microsoft.com/fwlink/?linkid=746894)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0154](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0154)
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
[CVE-2016-0155](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0155)
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
[CVE-2016-0156](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0156)
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
[CVE-2016-0157](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0157)
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
[CVE-2016-0158](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0158)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Edge bezüglich Erhöhung von Berechtigungen
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
[CVE-2016-0161](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0161)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Edge bezüglich Erhöhung von Berechtigungen
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
[**MS16-039: Sicherheitsupdate für Microsoft-Grafikkomponente (3148522)**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0143](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0143)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Win32k bezüglich der Erhöhung von Berechtigungen
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
[CVE-2016-0145](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0145)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit durch Grafikspeicherbeschädigung
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
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
[CVE-2016-0165](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0165)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Win32k bezüglich der Erhöhung von Berechtigungen
</td>
<td style="border:1px solid black;">
0 – Ausnutzung erkannt
</td>
<td style="border:1px solid black;">
0 – Ausnutzung erkannt
</td>
<td style="border:1px solid black;">
Dauerhaft
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0167](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0167)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Win32k bezüglich der Erhöhung von Berechtigungen
</td>
<td style="border:1px solid black;">
0 – Ausnutzung erkannt
</td>
<td style="border:1px solid black;">
0 – Ausnutzung erkannt
</td>
<td style="border:1px solid black;">
Dauerhaft
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-040: Sicherheitsupdate für Microsoft XML Core Services (3148541)**](http://go.microsoft.com/fwlink/?linkid=746897)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0147](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0147)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in MSXML 3.0 bezüglich Remotecodeausführung
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
[**MS16-041: Sicherheitsupdate für .NET Framework (3148789)**](http://go.microsoft.com/fwlink/?linkid=746929)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0148](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0148)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in .NET Framework bezüglich Remotecodeausführung
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
[**MS16-042: Sicherheitsupdate für Microsoft Office (3148775)**](http://go.microsoft.com/fwlink/?linkid=746928)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0122](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0122)
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
[CVE-2016-0127](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0127)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Microsoft Office bezüglich Speicherbeschädigung
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
[CVE-2016-0136](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0136)
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
[CVE-2016-0139](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0139)
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
[**MS16-044: Sicherheitsupdate für Windows OLE (3146706)**](http://go.microsoft.com/fwlink/?linkid=747040)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0153](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0153)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Windows OLE bezüglich Remotecodeausführung
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
[**MS16-045: Sicherheitsupdate für Windows Hyper-V (3143118)**](http://go.microsoft.com/fwlink/?linkid=733440)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0088](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0088)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Hyper-V bezüglich Remotecodeausführung
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
3 – Ausnutzung unwahrscheinlich
</td>
<td style="border:1px solid black;">
Dauerhaft
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0089](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0089)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Hyper-V bezüglich Offenlegung von Informationen
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
3 – Ausnutzung unwahrscheinlich
</td>
<td style="border:1px solid black;">
Dauerhaft
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0090](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0090)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Hyper-V bezüglich Offenlegung von Informationen
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
3 – Ausnutzung unwahrscheinlich
</td>
<td style="border:1px solid black;">
Dauerhaft
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-046: Sicherheitsupdate für sekundären Anmeldedienst (3148538)**](http://go.microsoft.com/fwlink/?linkid=746896)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0135](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0135)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in sekundärem Anmeldedienst bezüglich der Erhöhung von Berechtigungen
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
2 – Ausnutzung weniger wahrscheinlich
</td>
<td style="border:1px solid black;">
Dauerhaft
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-047: Sicherheitsupdate für SAM- und LSAD-Remoteprotokolle (3148527)**](http://go.microsoft.com/fwlink/?linkid=746885)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0128](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0128)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit in Windows bezüglich SAM- und LSAD-Herabstufung
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
<td style="border:1px solid black;" colspan="5">
[**MS16-048: Sicherheitsupdate für CSRSS (3148528)**](http://go.microsoft.com/fwlink/?linkid=746886)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0151](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0151)
</td>
<td style="border:1px solid black;">
Sicherheitsumgebung durch Umgehung von Sicherheitsfunktionen in Windows CSRSS
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
[**MS16-049: Sicherheitsupdate für HTTP.sys (3148795)**](http://go.microsoft.com/fwlink/?linkid=746932)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[CVE-2016-0150](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2016-0150)
</td>
<td style="border:1px solid black;">
Sicherheitsanfälligkeit HTTP.sys bezüglich Denial-of-Service
</td>
<td style="border:1px solid black;">
3 – Ausnutzung unwahrscheinlich
</td>
<td style="border:1px solid black;">
4 – Nicht betroffen
</td>
<td style="border:1px solid black;">
Dauerhaft
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="5">
[**MS16-050: Sicherheitsupdate für Adobe Flash Player 3154132**](http://go.microsoft.com/fwlink/?linkid=785154)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
[APSB16-10](http://helpx.adobe.com/de/security/products/flash-player/apsb16-10.html)
</td>
<td style="border:1px solid black;">
Die Bewertungen des Schweregrads und der Updatepriorität finden Sie unter [Adobe Security Bulletin APSB16-10](http://helpx.adobe.com/de/security/products/flash-player/apsb16-10.html).
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
<td style="border:1px solid black;" colspan="7">
**Windows Vista**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS16-037**](http://go.microsoft.com/fwlink/?linkid=746891)
</td>
<td style="border:1px solid black;">
[**MS16-038**](http://go.microsoft.com/fwlink/?linkid=746894)
</td>
<td style="border:1px solid black;">
[**MS16-039**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
<td style="border:1px solid black;">
[**MS16-040**](http://go.microsoft.com/fwlink/?linkid=746897)
</td>
<td style="border:1px solid black;">
[**MS16-041**](http://go.microsoft.com/fwlink/?linkid=746929)
</td>
<td style="border:1px solid black;">
[**MS16-044**](http://go.microsoft.com/fwlink/?linkid=747040)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4014661)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3145739)  
(Kritisch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3142041)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3143693)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3146706)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4014661)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3145739)  
(Kritisch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3142041)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3143693)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3146706)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS16-037**](http://go.microsoft.com/fwlink/?linkid=746891)
</td>
<td style="border:1px solid black;">
[**MS16-038**](http://go.microsoft.com/fwlink/?linkid=746894)
</td>
<td style="border:1px solid black;">
[**MS16-039**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
<td style="border:1px solid black;">
[**MS16-040**](http://go.microsoft.com/fwlink/?linkid=746897)
</td>
<td style="border:1px solid black;">
[**MS16-041**](http://go.microsoft.com/fwlink/?linkid=746929)
</td>
<td style="border:1px solid black;">
[**MS16-044**](http://go.microsoft.com/fwlink/?linkid=747040)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Mittel**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4014661)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(3145739)  
(Kritisch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3142041)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3143693)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(3146706)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Internet Explorer 9  
(4014661)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(3145739)  
(Kritisch)  
Microsoft .NET Framework 3.0 Service Pack 2  
(3142041)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6  
(3143693)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(3146706)  
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
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(3145739)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(3146706)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 7**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS16-037**](http://go.microsoft.com/fwlink/?linkid=746891)
</td>
<td style="border:1px solid black;">
[**MS16-038**](http://go.microsoft.com/fwlink/?linkid=746894)
</td>
<td style="border:1px solid black;">
[**MS16-039**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
<td style="border:1px solid black;">
[**MS16-040**](http://go.microsoft.com/fwlink/?linkid=746897)
</td>
<td style="border:1px solid black;">
[**MS16-041**](http://go.microsoft.com/fwlink/?linkid=746929)
</td>
<td style="border:1px solid black;">
[**MS16-044**](http://go.microsoft.com/fwlink/?linkid=747040)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4014661)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(3145739)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(3142042)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6/4.6.1  
(3143693)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(3146706)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4014661)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(3145739)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(3142042)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6/4.6.1  
(3143693)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(3146706)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS16-037**](http://go.microsoft.com/fwlink/?linkid=746891)
</td>
<td style="border:1px solid black;">
[**MS16-038**](http://go.microsoft.com/fwlink/?linkid=746894)
</td>
<td style="border:1px solid black;">
[**MS16-039**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
<td style="border:1px solid black;">
[**MS16-040**](http://go.microsoft.com/fwlink/?linkid=746897)
</td>
<td style="border:1px solid black;">
[**MS16-041**](http://go.microsoft.com/fwlink/?linkid=746929)
</td>
<td style="border:1px solid black;">
[**MS16-044**](http://go.microsoft.com/fwlink/?linkid=747040)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Mittel**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4014661)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(3145739)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(3142042)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6/4.6.1  
(3143693)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(3146706)  
(Hoch)
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
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(3145739)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(3146706)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS16-037**](http://go.microsoft.com/fwlink/?linkid=746891)
</td>
<td style="border:1px solid black;">
[**MS16-038**](http://go.microsoft.com/fwlink/?linkid=746894)
</td>
<td style="border:1px solid black;">
[**MS16-039**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
<td style="border:1px solid black;">
[**MS16-040**](http://go.microsoft.com/fwlink/?linkid=746897)
</td>
<td style="border:1px solid black;">
[**MS16-041**](http://go.microsoft.com/fwlink/?linkid=746929)
</td>
<td style="border:1px solid black;">
[**MS16-044**](http://go.microsoft.com/fwlink/?linkid=747040)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4014661)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme  
(3145739)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3142045)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme  
(3146706)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4014661)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme  
(3145739)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3142045)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme  
(3146706)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 und Windows Server 2012 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS16-037**](http://go.microsoft.com/fwlink/?linkid=746891)
</td>
<td style="border:1px solid black;">
[**MS16-038**](http://go.microsoft.com/fwlink/?linkid=746894)
</td>
<td style="border:1px solid black;">
[**MS16-039**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
<td style="border:1px solid black;">
[**MS16-040**](http://go.microsoft.com/fwlink/?linkid=746897)
</td>
<td style="border:1px solid black;">
[**MS16-041**](http://go.microsoft.com/fwlink/?linkid=746929)
</td>
<td style="border:1px solid black;">
[**MS16-044**](http://go.microsoft.com/fwlink/?linkid=747040)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Mittel**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Internet Explorer 10  
(4014661)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3145739)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3142043)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3146706)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4014661)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3145739)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3142045)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3146706)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS16-037**](http://go.microsoft.com/fwlink/?linkid=746891)
</td>
<td style="border:1px solid black;">
[**MS16-038**](http://go.microsoft.com/fwlink/?linkid=746894)
</td>
<td style="border:1px solid black;">
[**MS16-039**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
<td style="border:1px solid black;">
[**MS16-040**](http://go.microsoft.com/fwlink/?linkid=746897)
</td>
<td style="border:1px solid black;">
[**MS16-041**](http://go.microsoft.com/fwlink/?linkid=746929)
</td>
<td style="border:1px solid black;">
[**MS16-044**](http://go.microsoft.com/fwlink/?linkid=747040)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows RT 8.1
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(4014661)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3145739)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3146706)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 10**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS16-037**](http://go.microsoft.com/fwlink/?linkid=746891)
</td>
<td style="border:1px solid black;">
[**MS16-038**](http://go.microsoft.com/fwlink/?linkid=746894)
</td>
<td style="border:1px solid black;">
[**MS16-039**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
<td style="border:1px solid black;">
[**MS16-040**](http://go.microsoft.com/fwlink/?linkid=746897)
</td>
<td style="border:1px solid black;">
[**MS16-041**](http://go.microsoft.com/fwlink/?linkid=746929)
</td>
<td style="border:1px solid black;">
[**MS16-044**](http://go.microsoft.com/fwlink/?linkid=747040)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Internet Explorer 11  
(3147461)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3147461)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 10 für 32-Bit-Systeme  
(3147461)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3147461)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3147461)  
(Kritisch)
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
Internet Explorer 11  
(3147461)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3147461)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme  
(3147461)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3147461)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3147461)  
(Kritisch)
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
Windows 10 Version 1511 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3147458)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3147458)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 für 32-Bit-Systeme  
(3147458)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3147458)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3147458)  
(Kritisch)
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
Windows 10 Version 1511 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Internet Explorer 11  
(3147458)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft Edge  
(3147458)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 für x64-basierte Systeme  
(3147458)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3147458)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3147458)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Server Core-Installationsoption**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS16-037**](http://go.microsoft.com/fwlink/?linkid=746891)
</td>
<td style="border:1px solid black;">
[**MS16-038**](http://go.microsoft.com/fwlink/?linkid=746894)
</td>
<td style="border:1px solid black;">
[**MS16-039**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
<td style="border:1px solid black;">
[**MS16-040**](http://go.microsoft.com/fwlink/?linkid=746897)
</td>
<td style="border:1px solid black;">
[**MS16-041**](http://go.microsoft.com/fwlink/?linkid=746929)
</td>
<td style="border:1px solid black;">
[**MS16-044**](http://go.microsoft.com/fwlink/?linkid=747040)
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
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)  
(3145739)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2 (Server Core-Installation)  
(3146706)  
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
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)  
(3145739)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2 (Server Core-Installation)  
(3146706)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)  
(3145739)  
(Kritisch)  
Microsoft .NET Framework 3.5.1  
(3142042)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft .NET Framework 4.6/4.6.1  
(3143693)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1 (Server Core-Installation)  
(3146706)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core-Installation)  
3145739)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3142043)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 (Server Core-Installation)  
(3146706)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core-Installation)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core-Installation)  
3145739)  
(Kritisch)  
Microsoft .NET Framework 3.5  
(3142045)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0  
(3146963)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2 (Server Core-Installation)  
(3146706)  
(Hoch)
</td>
</tr>
</table>
 
**Hinweise zu MS16-039**

Dieses Bulletin umfasst mehr als eine Softwarekategorie. Zusätzliche betroffene Software finden Sie in den anderen Tabellen in diesem Abschnitt. 

### Windows-Betriebssysteme und Komponenten (Tabelle 2 von 2)

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Vista**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS16-045**](http://go.microsoft.com/fwlink/?linkid=733440)
</td>
<td style="border:1px solid black;">
[**MS16-046**](http://go.microsoft.com/fwlink/?linkid=746896)
</td>
<td style="border:1px solid black;">
[**MS16-047**](http://go.microsoft.com/fwlink/?linkid=746885)
</td>
<td style="border:1px solid black;">
[**MS16-048**](http://go.microsoft.com/fwlink/?linkid=746886)
</td>
<td style="border:1px solid black;">
[**MS16-049**](http://go.microsoft.com/fwlink/?linkid=746932)
</td>
<td style="border:1px solid black;">
[**MS16-050**](http://go.microsoft.com/fwlink/?linkid=785154)
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
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Vista Service Pack 2  
(3149090)  
(Hoch)
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
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2  
(3149090)  
(Hoch)
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
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS16-045**](http://go.microsoft.com/fwlink/?linkid=733440)
</td>
<td style="border:1px solid black;">
[**MS16-046**](http://go.microsoft.com/fwlink/?linkid=746896)
</td>
<td style="border:1px solid black;">
[**MS16-047**](http://go.microsoft.com/fwlink/?linkid=746885)
</td>
<td style="border:1px solid black;">
[**MS16-048**](http://go.microsoft.com/fwlink/?linkid=746886)
</td>
<td style="border:1px solid black;">
[**MS16-049**](http://go.microsoft.com/fwlink/?linkid=746932)
</td>
<td style="border:1px solid black;">
[**MS16-050**](http://go.microsoft.com/fwlink/?linkid=785154)
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
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 für 32-Bit-Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(3149090)  
(Hoch)
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
Windows Server 2008 für x64-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(3149090)  
(Hoch)
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
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2  
(3149090)  
(Hoch)
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
<td style="border:1px solid black;" colspan="7">
**Windows 7**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS16-045**](http://go.microsoft.com/fwlink/?linkid=733440)
</td>
<td style="border:1px solid black;">
[**MS16-046**](http://go.microsoft.com/fwlink/?linkid=746896)
</td>
<td style="border:1px solid black;">
[**MS16-047**](http://go.microsoft.com/fwlink/?linkid=746885)
</td>
<td style="border:1px solid black;">
[**MS16-048**](http://go.microsoft.com/fwlink/?linkid=746886)
</td>
<td style="border:1px solid black;">
[**MS16-049**](http://go.microsoft.com/fwlink/?linkid=746932)
</td>
<td style="border:1px solid black;">
[**MS16-050**](http://go.microsoft.com/fwlink/?linkid=785154)
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
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows 7 für 32-Bit-Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme Service Pack 1  
(3149090)  
(Hoch)
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
Windows 7 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme Service Pack 1  
(3149090)  
(Hoch)
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
<td style="border:1px solid black;" colspan="7">
**Windows Server 2008 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS16-045**](http://go.microsoft.com/fwlink/?linkid=733440)
</td>
<td style="border:1px solid black;">
[**MS16-046**](http://go.microsoft.com/fwlink/?linkid=746896)
</td>
<td style="border:1px solid black;">
[**MS16-047**](http://go.microsoft.com/fwlink/?linkid=746885)
</td>
<td style="border:1px solid black;">
[**MS16-048**](http://go.microsoft.com/fwlink/?linkid=746886)
</td>
<td style="border:1px solid black;">
[**MS16-049**](http://go.microsoft.com/fwlink/?linkid=746932)
</td>
<td style="border:1px solid black;">
[**MS16-050**](http://go.microsoft.com/fwlink/?linkid=785154)
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
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(3149090)  
(Hoch)
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
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1  
(3149090)  
(Hoch)
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
<td style="border:1px solid black;" colspan="7">
**Windows 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS16-045**](http://go.microsoft.com/fwlink/?linkid=733440)
</td>
<td style="border:1px solid black;">
[**MS16-046**](http://go.microsoft.com/fwlink/?linkid=746896)
</td>
<td style="border:1px solid black;">
[**MS16-047**](http://go.microsoft.com/fwlink/?linkid=746885)
</td>
<td style="border:1px solid black;">
[**MS16-048**](http://go.microsoft.com/fwlink/?linkid=746886)
</td>
<td style="border:1px solid black;">
[**MS16-049**](http://go.microsoft.com/fwlink/?linkid=746932)
</td>
<td style="border:1px solid black;">
[**MS16-050**](http://go.microsoft.com/fwlink/?linkid=785154)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme  
(3149090)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8.1 für 32-Bit-Systeme  
(3146723)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme  
(3135456)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme  
(3149090)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 8.1 für x64-basierte Systeme  
(3146723)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows Server 2012 und Windows Server 2012 R2**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS16-045**](http://go.microsoft.com/fwlink/?linkid=733440)
</td>
<td style="border:1px solid black;">
[**MS16-046**](http://go.microsoft.com/fwlink/?linkid=746896)
</td>
<td style="border:1px solid black;">
[**MS16-047**](http://go.microsoft.com/fwlink/?linkid=746885)
</td>
<td style="border:1px solid black;">
[**MS16-048**](http://go.microsoft.com/fwlink/?linkid=746886)
</td>
<td style="border:1px solid black;">
[**MS16-049**](http://go.microsoft.com/fwlink/?linkid=746932)
</td>
<td style="border:1px solid black;">
[**MS16-050**](http://go.microsoft.com/fwlink/?linkid=785154)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Mittel**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3135456)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3149090)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(3146723)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
(Mittel)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2012 R2
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3135456)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3149090)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(3146723)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
(Mittel)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows RT 8.1**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS16-045**](http://go.microsoft.com/fwlink/?linkid=733440)
</td>
<td style="border:1px solid black;">
[**MS16-046**](http://go.microsoft.com/fwlink/?linkid=746896)
</td>
<td style="border:1px solid black;">
[**MS16-047**](http://go.microsoft.com/fwlink/?linkid=746885)
</td>
<td style="border:1px solid black;">
[**MS16-048**](http://go.microsoft.com/fwlink/?linkid=746886)
</td>
<td style="border:1px solid black;">
[**MS16-049**](http://go.microsoft.com/fwlink/?linkid=746932)
</td>
<td style="border:1px solid black;">
[**MS16-050**](http://go.microsoft.com/fwlink/?linkid=785154)
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
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3149090)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows RT 8.1  
(3146723)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Windows 10**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS16-045**](http://go.microsoft.com/fwlink/?linkid=733440)
</td>
<td style="border:1px solid black;">
[**MS16-046**](http://go.microsoft.com/fwlink/?linkid=746896)
</td>
<td style="border:1px solid black;">
[**MS16-047**](http://go.microsoft.com/fwlink/?linkid=746885)
</td>
<td style="border:1px solid black;">
[**MS16-048**](http://go.microsoft.com/fwlink/?linkid=746886)
</td>
<td style="border:1px solid black;">
[**MS16-049**](http://go.microsoft.com/fwlink/?linkid=746932)
</td>
<td style="border:1px solid black;">
[**MS16-050**](http://go.microsoft.com/fwlink/?linkid=785154)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows 10 für 32-Bit-Systeme  
(3147461)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 10 für 32-Bit-Systeme  
(3147461)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 10 für 32-Bit-Systeme  
(3147461)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 10 für 32-Bit-Systeme  
(3147461)  
(Hoch)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme  
(3147461)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme  
(3147461)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme  
(3147461)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme  
(3147461)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 10 für x64-basierte Systeme  
(3147461)  
(Hoch)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 für 32-Bit-Systeme  
(3147458)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 für 32-Bit-Systeme  
(3147458)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 für 32-Bit-Systeme  
(3147458)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 für 32-Bit-Systeme  
(3147458)  
(Hoch)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 10 Version 1511 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 für x64-basierte Systeme  
(3147458)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 für x64-basierte Systeme  
(3147458)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 für x64-basierte Systeme  
(3147458)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows 10 Version 1511 für x64-basierte Systeme  
(3147458)  
(Hoch)
</td>
<td style="border:1px solid black;">
Adobe Flash Player  
(3154132)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="7">
**Server Core-Installationsoption**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS16-045**](http://go.microsoft.com/fwlink/?linkid=733440)
</td>
<td style="border:1px solid black;">
[**MS16-046**](http://go.microsoft.com/fwlink/?linkid=746896)
</td>
<td style="border:1px solid black;">
[**MS16-047**](http://go.microsoft.com/fwlink/?linkid=746885)
</td>
<td style="border:1px solid black;">
[**MS16-048**](http://go.microsoft.com/fwlink/?linkid=746886)
</td>
<td style="border:1px solid black;">
[**MS16-049**](http://go.microsoft.com/fwlink/?linkid=746932)
</td>
<td style="border:1px solid black;">
[**MS16-050**](http://go.microsoft.com/fwlink/?linkid=785154)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
**Keine**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Server 2008 für 32-Bit-Systeme Service Pack 2  
(Server Core-Installation)  
(3149090)  
(Hoch)
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
Windows Server 2008 für x64-basierte Systeme Service Pack 2  
(Server Core-Installation)  
(3149090)  
(Hoch)
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
Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1  
(Server Core-Installation)  
(3149090)  
(Hoch)
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
Windows Server 2012  
(Server Core-Installation)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core-Installation)  
(3135456)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core-Installation)  
(3149090)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2012  
(Server Core-Installation)  
(3146723)  
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
Windows Server 2012 R2  
(Server Core-Installation)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core-Installation)  
(3135456)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core-Installation)  
(3149090)  
(Hoch)
</td>
<td style="border:1px solid black;">
Windows Server 2012 R2  
(Server Core-Installation)  
(3146723)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
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
[**MS16-039**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
<td style="border:1px solid black;">
[**MS16-042**](http://go.microsoft.com/fwlink/?linkid=746928)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office 2007 Service Pack 3  
(3114542)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft Excel 2007 Service Pack 3  
(3114892)  
(Hoch)  
Microsoft Word 2007 Service Pack 3  
(3114983)  
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
[**MS16-039**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
<td style="border:1px solid black;">
[**MS16-042**](http://go.microsoft.com/fwlink/?linkid=746928)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32-Bit-Editionen)  
(3114566)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (32-Bit-Editionen)  
(3114990)  
(Kritisch)  
Microsoft Excel 2010 Service Pack 2 (32-Bit-Editionen)  
(3114888)  
(Hoch)  
Microsoft Word 2010 Service Pack 2 (32-Bit-Editionen)  
(3114993)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64-Bit-Editionen)  
(3114566)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft Office 2010 Service Pack 2 (64-Bit-Editionen)  
(3114990)  
(Kritisch)  
Microsoft Excel 2010 Service Pack 2 (64-Bit-Editionen)  
(3114888)  
(Hoch)  
Microsoft Word 2010 Service Pack 2 (64-Bit-Editionen)  
(3114993)  
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
[**MS16-039**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
<td style="border:1px solid black;">
[**MS16-042**](http://go.microsoft.com/fwlink/?linkid=746928)
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
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Microsoft Excel 2013 Service Pack 1 (32-Bit-Editionen)  
(3114947)  
(Hoch)  
Microsoft Word 2013 Service Pack 1 (32-Bit-Editionen)  
(3114937)  
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
Microsoft Excel 2013 Service Pack 1 (64-Bit-Editionen)  
(3114947)  
(Hoch)  
Microsoft Word 2013 Service Pack 1 (64-Bit-Editionen)  
(3114937)  
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
[**MS16-039**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
<td style="border:1px solid black;">
[**MS16-042**](http://go.microsoft.com/fwlink/?linkid=746928)
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
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Microsoft Excel 2013 RT Service Pack 1  
(3114947)  
(Hoch)  
Microsoft Word 2013 RT Service Pack 1  
(3114937)  
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
[**MS16-039**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
<td style="border:1px solid black;">
[**MS16-042**](http://go.microsoft.com/fwlink/?linkid=746928)
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
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (32-Bit-Edition)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (32-Bit-Edition)  
(3114964)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2016 (64-Bit-Edition)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Microsoft Excel 2016 (64-Bit-Edition)  
(3114964)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office für Mac 2011**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS16-039**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
<td style="border:1px solid black;">
[**MS16-042**](http://go.microsoft.com/fwlink/?linkid=746928)
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
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Microsoft Word für Mac 2011  
(3154208)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;" colspan="3">
**Microsoft Office 2016 für Mac**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS16-039**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
<td style="border:1px solid black;">
[**MS16-042**](http://go.microsoft.com/fwlink/?linkid=746928)
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
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Microsoft Word 2016 für Mac  
(3142577)  
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
[**MS16-039**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
<td style="border:1px solid black;">
[**MS16-042**](http://go.microsoft.com/fwlink/?linkid=746928)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
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
(3114982)  
(Kritisch)  
Microsoft Office Compatibility Pack Service Pack 3  
(3114895)  
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
(3114898)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer
</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114985)  
(Hoch)
</td>
<td style="border:1px solid black;">
Microsoft Word Viewer  
(3114987)  
(Kritisch)
</td>
</tr>
</table>
 
**Hinweise zu MS16-039 und MS16-042**

Dieses Bulletin umfasst mehr als eine Softwarekategorie. Zusätzliche betroffene Software finden Sie in den anderen Tabellen in diesem Abschnitt. 

### Microsoft Office-Dienste und Web Apps

<p> </p>
<table style="border:1px solid black;">
<tr>
<td style="border:1px solid black;" colspan="2">
**Microsoft SharePoint Server 2007**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS16-042**](http://go.microsoft.com/fwlink/?linkid=746928)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (32-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Excel Services  
(3114897)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2007 Service Pack 3 (64-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Excel Services  
(3114897)  
(Hoch)
</td>
</tr>
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
[**MS16-042**](http://go.microsoft.com/fwlink/?linkid=746928)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Excel Services  
(3114871)  
(Hoch)  
Word Automation Services  
(3114988)  
(Kritisch)
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
[**MS16-042**](http://go.microsoft.com/fwlink/?linkid=746928)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft SharePoint Server 2013 Service Pack 1
</td>
<td style="border:1px solid black;">
Word-Automatisierungsdienste  
(3114927)  
(Kritisch)
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
[**MS16-042**](http://go.microsoft.com/fwlink/?linkid=746928)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps 2010 Service Pack 2  
(3114994)  
(Kritisch)
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
[**MS16-042**](http://go.microsoft.com/fwlink/?linkid=746928)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1
</td>
<td style="border:1px solid black;">
Microsoft Office Web Apps Server 2013 Service Pack 1  
(3114934)  
(Kritisch)
</td>
</tr>
</table>
 
**Hinweise zu MS16-042**

Dieses Bulletin umfasst mehr als eine Softwarekategorie. Zusätzliche betroffene Software finden Sie in den anderen Tabellen in diesem Abschnitt. 

### Microsoft Communications-Plattformen und -Software

<p> </p>
<table style="border:1px solid black;">
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
[**MS16-039**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business 2016 (32-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Skype for Business 2016 (32-Bit-Editionen)  
(3114960)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (32-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (32-Bit-Editionen)  
(3114960)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business 2016 (64-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Skype for Business 2016 (64-Bit-Editionen)  
(3114960)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (64-Bit-Editionen)
</td>
<td style="border:1px solid black;">
Skype for Business Basic 2016 (64-Bit-Editionen)  
(3114960)  
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
[**MS16-039**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
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
(3114944)  
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
(3114944)  
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
(3114944)  
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
(3114944)  
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
[**MS16-039**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32 Bit)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (32-Bit)  
(3144427)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64-Bit)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 (64-Bit)  
(3144427)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(Installation auf Benutzerebene)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(Installation auf Benutzerebene)  
(3144428)  
(Kritisch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(Installation auf Administratorebene)
</td>
<td style="border:1px solid black;">
Microsoft Lync 2010 Attendee  
(Installation auf Administratorebene)  
(3144429)  
(Kritisch)
</td>
</tr>
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
[**MS16-039**](http://go.microsoft.com/fwlink/?linkid=746883)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007-Konsole
</td>
<td style="border:1px solid black;">
Microsoft Live Meeting 2007-Konsole  
(3144432)  
(Kritisch)
</td>
</tr>
</table>
 
**Hinweise zu MS16-039**

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

Microsoft würdigt die Bemühungen derjenigen Benutzer der Sicherheitscommunity, die uns dabei helfen, Kunden durch eine verantwortliche Offenlegung von Sicherheitsanfälligkeiten zu schützen. Weitere Informationen finden Sie unter [Danksagung](https://technet.microsoft.com/de-de/library/security/mt674627.aspx). 

Weitere Informationen
---------------------

### Microsoft Windows-Tool zum Entfernen bösartiger Software

Für die Veröffentlichung des Bulletins, die am zweiten Dienstag jedes Monats stattfindet, hat Microsoft eine aktualisierte Version des Microsofts Windows-Tool zum Entfernen schädlicher Software in Windows Update, Microsoft Update, den Windows Server Update Services und dem Download Center veröffentlicht. Für außerplanmäßige Veröffentlichungen von Sicherheitsbulletins ist keine aktualisierte Version des Microsoft Windows-Tools zum Entfernen schädlicher Software erhältlich.

### Nicht sicherheitsrelevante Updates unter MU, WU und WSUS:

Weitere Informationen zu nicht sicherheitsrelevanten Veröffentlichungen auf Windows-Update und Microsoft Update finden Sie unter:

-   [Microsoft Knowledge Base-Artikel 894199](https://support.microsoft.com/de-de/kb/894199): Beschreibung der Änderungen an den Inhalten von Software Update Services und Windows Server Update Services. Umfasst alle Windows-Inhalte.
-   [Updates für Windows Server Update Services aus den vergangenen Monaten](http://technet.microsoft.com/de-de/wsus/bb456965). Zeigt alle neuen, überarbeiteten und veröffentlichten Updates für andere Microsoft-Produkte als Microsoft Windows an.

### Microsoft Active Protections Program (MAPP)

Um den Sicherheitsschutz für Benutzer zu verbessern, stellt Microsoft den wichtigsten Sicherheitssoftwareanbietern vor der monatlichen Veröffentlichung der Sicherheitsupdates Informationen zu Sicherheitsanfälligkeiten bereit. Anbieter von Sicherheitssoftware können diese Informationen zu Sicherheitsanfälligkeiten dann verwenden, um Benutzern aktualisierten Schutz über ihre Sicherheitssoftware oder ihre Geräte bereitzustellen, z. B. Antivirus, netzwerkbasierte Angriffserkennungssysteme oder hostbasierte Angriffsverhinderungssysteme. Wenn Sie erfahren möchten, ob von den Sicherheitssoftwareanbietern aktiver Schutz verfügbar ist, besuchen Sie die von den Programmpartnern bereitgestellte Active Protections-Websites, die unter [MAPP-Partner (Microsoft Active Protections Program)](http://go.microsoft.com/fwlink/?linkid=215201) aufgeführt sind.

### Sicherheitsstrategien und Community

**Updateverwaltungsstrategien**

Auf der Seite [Patchmanagement](http://go.microsoft.com/fwlink/?linkid=21168) werden zusätzliche Informationen zu den empfohlenen Vorgehensweisen für die Anwendung von Sicherheitsupdates von Microsoft bereitgestellt.

**Weitere Sicherheitsupdates**

Updates für andere Sicherheitsanfälligkeiten sind unter den folgenden Adressen erhältlich:

-   Sicherheitsupdates sind im [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129) verfügbar. Sie können am einfachsten durch eine Suche nach dem Begriff „security update“ ermittelt werden.
-   Updates für Benutzerplattformen sind auf [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) verfügbar.
-   Die Sicherheitsupdates, die in diesem Monat über Windows Update veröffentlicht wurden, können Sie auch im „Security and Critical Releases ISO CD Image“ über Microsoft Download Center erhalten. Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 913086](https://support.microsoft.com/de-de/kb/913086).

**IT Pro Security Community**

Erfahren Sie, wie Sie die Sicherheit Ihrer IT-Umgebung erhöhen und Ihren IT-Betrieb optimieren können. Diskutieren Sie auf der [IT Pro Security Zone](http://go.microsoft.com/fwlink/?linkid=21164) Website mit anderen IT-Profis über das Thema Sicherheit.

### Support

Die betroffene Software wurde getestet, um die betroffenen Versionen zu ermitteln. Andere Versionen haben das Ende ihrer Supportlebenszyklen erreicht. Besuchen Sie die Website [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742), um den Supportlebenszyklus für Ihre Softwareversion zu ermitteln.

Sicherheitslösungen für IT-Profis: [TechNet Security – Problembehandlung und Support](http://technet.microsoft.com/de-de/security/bb980617)

Hilfe beim Schützen des Computers, auf dem Windows ausgeführt wird, vor Viren und Schadsoftware: [Safety and Security Center](http://support.microsoft.com/de-de/contactus/cu_sc_virsec_master)

Lokaler Support entsprechend Ihrem Land: [Internationaler Support](http://support.microsoft.com/de-de/common/international.aspx)

### Haftungsausschluss

Die Informationen in der Microsoft Knowledge Base werden wie besehen und ohne jede Gewährleistung bereitgestellt. Microsoft schließt alle anderen Garantien, gleichgültig, ob ausdrücklich oder konkludent, einschließlich der Garantien der Handelsüblichkeit oder Eignung für einen bestimmten Zweck aus. In keinem Fall kann die Microsoft Corporation und/oder deren jeweilige Lieferanten haftbar gemacht werden für Schäden irgendeiner Art, einschließlich direkter, indirekter, zufällig entstandener Schäden, Folgeschäden, Folgen entgangenen Gewinns oder spezieller Schäden, selbst dann nicht, wenn Microsoft Corporation und/oder deren jeweilige Lieferanten auf die mögliche Entstehung dieser Schäden hingewiesen wurde. Weil in einigen Staaten/Rechtsordnungen der Ausschluss oder die Beschränkung einer Haftung für zufällig entstandene Schäden oder Folgeschäden nicht gestattet ist, gilt die obige Einschränkung eventuell nicht für Sie.

### Revisionen

-   V1.0 (12. April 2016): Bulletin Summary veröffentlicht.
-   V1.1 (13. April 2016): Der Tabelle in der Kurzzusammenfassung für MS16-039 wurde ein Verweis auf ein bekanntes Problem hinzugefügt. Weitere Informationen finden Sie in [Microsoft Knowledge Base-Artikel 3148522](https://support.microsoft.com/de-de/kb/3148522). Der Tabelle in der Kurzzusammenfassung für MS16-042 wurde ein Verweis auf ein bekanntes Problem hinzugefügt. Weitere Informationen finden Sie in [Microsoft Knowledge Base-Artikel 3148775](https://support.microsoft.com/de-de/kb/3148775).
-   V1.2 (11. Mai 2016): Der Tabelle in der Kurzzusammenfassung für MS16-044 wurde ein Verweis auf ein bekanntes Problem hinzugefügt. Weitere Informationen finden Sie in [Microsoft Knowledge Base-Artikel 3146706](http://support.microsoft.com/de-de/kb/3146706). Der Tabelle in der Kurzzusammenfassung für MS16-042 wurde ein Verweis auf ein bekanntes Problem hinzugefügt. Weitere Informationen finden Sie in [Microsoft Knowledge Base-Artikel 3146723](http://support.microsoft.com/de-de/kb/3146723).
-   V2.0 (14. Juni 2016): Für MS16-039 wurde das Bulletin Summary überarbeitet, um die Neuveröffentlichung von Update 3144427 für betroffene Editionen von Microsoft Lync 2010 und Microsoft Lync 2010 Attendee bekannt zu geben Durch die Neuveröffentlichung werden Probleme behoben, die möglicherweise bei Benutzern beim Herunterladen des Updates 3144427 aufgetreten sind. Benutzer, die Microsoft Lync 2010 verwenden, sollten das Update installieren, um vor der Sicherheitsanfälligkeit umfassend geschützt zu sein. Weitere Informationen hierzu finden Sie im [Microsoft Knowledge Base-Artikel 3144427](https://support.microsoft.com/de-de/kb/3144427).
-   V3.0 (11. April 2017): Für MS16-037 wurde das Bulletin Summary überarbeitet, um die Veröffentlichung eines neuen kumulativen Updates für Internet Explorer (4014661) im Zusammenhang mit CVE-2016-0162 anzukündigen. Dieses Update wird der ursprünglichen Veröffentlichung hinzugefügt, um eine umfassende Lösung für CVE-2016-0162 anzubieten. Microsoft empfiehlt Kunden, die die betroffene Software verwenden, das Sicherheitsupdate zu installieren, um vollständig vor der in diesem Bulletin beschriebenen Sicherheitsanfälligkeit geschützt zu sein. Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 4014661](https://support.microsoft.com/de-de/kb/4014661).

*Seite generiert am 10.04.2017 um 16:29-07:00.*