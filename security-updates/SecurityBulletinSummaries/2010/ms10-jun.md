---
TOCTitle: 'MS10-JUN'
Title: Microsoft Security Bulletin Summary für Juni 2010
ms:assetid: 'ms10-jun'
ms:contentKeyID: 61225085
ms:mtpsurl: 'https://technet.microsoft.com/de-DE/library/ms10-jun(v=Security.10)'
---

Security Bulletin Summary

Microsoft Security Bulletin Summary für Juni 2010
=================================================

Veröffentlicht: Dienstag, 8. Juni 2010 | Aktualisiert: Dienstag, 13. September 2011

**Version:** 2.0

In diesem Bulletin Summary sind die im Juni 2010 veröffentlichten Security Bulletins aufgeführt.

Mit der Veröffentlichung der Bulletins für Juni 2010 ersetzt dieses Bulletin Summary die Bulletin Advance Notification, die erstmalig am 3. Juni 2010 veröffentlicht wurde. Weitere Informationen zum Bulletin Advance Notification-Service finden Sie unter [Microsoft Security Bulletin Advance Notification](http://technet.microsoft.com/security/bulletin/advance).

Weitere Informationen zum Erhalten automatischer Benachrichtigungen über die Veröffentlichung von Microsoft Security Bulletins finden Sie unter [Microsoft Technische Sicherheitsbenachrichtigungen](http://go.microsoft.com/fwlink/?linkid=21163).

Am Mittwoch, den 9. Juni 2010 um 11:00 Uhr pazifischer Zeit (USA & Kanada) stellt Microsoft einen Webcast bereit, um Kundenfragen zu diesen Bulletins zu beantworten. [Registrieren Sie sich jetzt für das Security Bulletin-Webcast im Juni.](https://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032427727&eventcategory=4&culture=en-us&countrycode=us) Ab diesem Datum steht dieser Webcast auf Anfrage zur Verfügung. Weitere Informationen dazu finden Sie unter [Microsoft Security Bulletin Zusammenfassungen und Webcasts.](http://technet.microsoft.com/security/bulletin/summary)

Microsoft stellt auch Informationen bereit, anhand derer Benutzer die Prioritäten für monatliche Sicherheitsupdates und alle nicht sicherheitsrelevanten wichtigen Updates festlegen können, die an demselben Tag veröffentlicht werden wie die monatlichen Sicherheitsupdates. Bitte lesen Sie den Abschnitt **Weitere Informationen**.

### Bulletin-Informationen

Kurzzusammenfassungen
---------------------

In der folgenden Tabelle sind die Security Bulletins für diesen Monat nach Schweregrad geordnet.

Weitere Informationen zu betroffener Software finden Sie im nächsten Abschnitt **Betroffene Software und Downloadadressen**.

<p> </p>
<table style="border:1px solid black;">
<thead>
<tr class="header">
<th style="border:1px solid black;" >Kennung des Bulletins</th>
<th style="border:1px solid black;" >Titel des Bulletins und Kurzzusammenfassung</th>
<th style="border:1px solid black;" >Bewertung des maximalen Schweregrads und Sicherheitsauswirkung</th>
<th style="border:1px solid black;" >Neustartanforderung</th>
<th style="border:1px solid black;" >Betroffene Software</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191065">MS10-033</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in der Mediendekomprimierung können Remotecodeausführung ermöglichen (979902)</strong><br />
<br />
Dieses Sicherheitsupdate behebt zwei vertraulich gemeldete Sicherheitsanfälligkeiten in Microsoft Windows. Diese Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Mediendatei öffnet oder speziell gestalteten Streaming-Inhalt von einer Website oder einer beliebigen Anwendung empfängt, die Webinhalte übermittelt. Ein Angreifer, der diese Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann die gleichen Benutzerrechte wie der lokale Benutzer erlangen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185159">MS10-034</a></td>
<td style="border:1px solid black;"><strong>Kumulatives Sicherheitsupdate von ActiveX-Kill Bits (980195)</strong><br />
<br />
Dieses Sicherheitsupdate behebt zwei vertraulich gemeldete Sicherheitsanfälligkeiten für Microsoft-Software. Dieses Sicherheitsupdate wird für alle unterstützten Editionen von Microsoft Windows 2000, Windows XP, Windows Vista und Windows 7 als Kritisch eingestuft und für alle unterstützten Editionen von Windows Server 2003, Windows Server 2008 und Windows Server 2008 R2 als Mittel.<br />
<br />
Diese Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Webseite anzeigt, die mit Internet Explorer ein bestimmtes ActiveX-Steuerelement instanziiert. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten. Dieses Update beinhaltet außerdem Kill Bits für vier ActiveX-Steuerelemente von Drittanbietern.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190898">MS10-035</a></td>
<td style="border:1px solid black;"><strong>Kumulatives Sicherheitsupdate für Internet Explorer (982381)</strong><br />
<br />
Dieses Sicherheitsupdate behebt fünf vertraulich gemeldete Sicherheitsanfälligkeiten und eine öffentlich gemeldete Sicherheitsanfälligkeit in Internet Explorer. Die schwerwiegendsten Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Webseite mit Internet Explorer anzeigt. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows, Internet Explorer</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=184917">MS10-032</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in Windows-Kernelmodustreibern können Erhöhung von Berechtigungen ermöglichen (979559)</strong><br />
<br />
Dieses Sicherheitsupdate behebt zwei öffentlich gemeldete Sicherheitsanfälligkeiten und eine vertraulich gemeldete Sicherheitsanfälligkeit in den Windows-Kernelmodustreibern. Die Sicherheitsanfälligkeiten können Erhöhung von Berechtigungen ermöglichen, wenn ein Benutzer Inhalte anzeigt, die in einer speziell gestalteten TrueType-Schriftart dargestellt werden.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Hoch</a><br />
Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190554">MS10-036</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in der COM-Überprüfung in Microsoft Office kann Remotecodeausführung ermöglichen (983235)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in der COM-Überprüfung in Microsoft Office. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Excel-, Word-, Visio-, Publisher- oder PowerPoint-Datei mit einer betroffenen Version von Microsoft Office öffnet. Die Sicherheitsanfälligkeit kann nicht automatisch über E-Mail ausgenutzt werden. Ein Benutzer muss eine zusammen mit einer E-Mail-Nachricht gesendete Dateianlage öffnen, damit ein Angriff erfolgreich ist.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Hoch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=190508">MS10-037</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit im OpenType CFF-Treiber (Compact Font Format) kann Erhöhung von Berechtigungen ermöglichen (980218)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit im Windows OpenType CFF-Treiber (Compact Font Format). Die Sicherheitsanfälligkeit kann Erhöhung von Berechtigungen ermöglichen, wenn ein Benutzer Inhalte anzeigt, die in einer speziell gestalteten CFF-Schriftart dargestellt werden. Ein Angreifer benötigt gültige Anmeldeinformationen und muss sich lokal anmelden können, um diese Sicherheitsanfälligkeit auszunutzen. Die Sicherheitsanfälligkeit kann nicht per Remotezugriff oder von anonymen Benutzern ausgenutzt werden.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Hoch</a><br />
Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191053">MS10-038</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in Microsoft Office Excel können Remotecodeausführung ermöglichen (2027452)</strong><br />
<br />
Dieses Sicherheitsupdate behebt vierzehn vertraulich gemeldete Sicherheitsanfälligkeiten in Microsoft Office. Die schwerwiegenderen Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Excel-Datei öffnet. Ein Angreifer, der diese Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann die gleichen Benutzerrechte wie der lokale Benutzer erlangen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Hoch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191905">MS10-039</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in Microsoft SharePoint können Erhöhung von Berechtigungen ermöglichen (2028554)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine öffentlich und zwei vertraulich gemeldete Sicherheitsanfälligkeiten in Microsoft SharePoint. Die schwerwiegendste Sicherheitsanfälligkeit kann Erhöhung von Berechtigungen ermöglichen, wenn ein Angreifer einen Benutzer einer SharePoint-Website, die angegriffen werden soll, dazu verleitet, auf einen speziell gestalteten Link zu klicken.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Hoch</a><br />
Erhöhung von Berechtigungen</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Office, Microsoft Server Software</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=191788">MS10-040</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in den Internetinformationsdiensten kann Remotecodeausführung ermöglichen (982666)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in den Internetinformationsdiensten (IIS). Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete HTTP-Anforderung empfängt. Nutzt ein Angreifer diese Sicherheitsanfälligkeit erfolgreich aus, kann er die vollständige Kontrolle über ein betroffenes System erlangen.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Hoch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=185042">MS10-041</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in Microsoft .NET Framework kann Manipulation ermöglichen (981343)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine öffentlich gemeldete Sicherheitsanfälligkeit in Microsoft .NET Framework. Die Sicherheitsanfälligkeit kann eine Manipulation signierter XML-Daten ermöglichen, die nicht erkannt wird. In benutzerdefinierten Anwendungen hängen die Sicherheitsauswirkungen davon ab, wie der signierte Inhalt in der spezifischen Anwendung verwendet wird. Szenarien, in denen signierte XML-Nachrichten über einen sicheren Kanal (wie z. B. SSL) übertragen werden, sind von dieser Sicherheitsanfälligkeit nicht betroffen.</td>
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=21140">Hoch</a><br />
Unerlaubte Änderungen</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft .NET Framework</td>
</tr>
</tbody>
</table>
  
Ausnutzbarkeitsindex  
--------------------
  
In der folgenden Tabelle wird eine Bewertung der Ausnutzbarkeit aller Sicherheitsanfälligkeiten bereitgestellt, die diesen Monat behoben werden. Die Sicherheitsanfälligkeiten sind nach absteigender Bewertung der Ausnutzbarkeit und dann CVE ID aufgeführt. Nur Sicherheitsanfälligkeiten, deren Schweregrad in diesem Bulletin als „Kritisch“ oder „Hoch“ eingestuft wurde, sind enthalten.
  
**Wie verwende ich diese Tabelle?**  
  
Verwenden Sie diese Tabelle, um etwas über die Wahrscheinlichkeit zu erfahren, dass für die einzelnen Sicherheitsupdates, die Sie möglicherweise installieren müssen, innerhalb von 30 Tagen funktionierender Angreifercode veröffentlicht wird. Sie sollten sich unter Berücksichtigung Ihrer konkreten Konfiguration jede der unten stehenden Bewertungen ansehen, um Prioritäten für Ihre Bereitstellung festzulegen. Weitere Informationen zur Bedeutung und Festlegung dieser Bewertungen finden Sie im [Microsoft-Ausnutzbarkeitsindex](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
| Kennung des Bulletins                                     | Titel der Sicherheitsanfälligkeit                                                                   | CVE-ID                                                                           | Ausnutzbarkeitsindex – Bewertung                                                                                     | Wichtige Hinweise                                                                                                                                             |  
|-----------------------------------------------------------|-----------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS10-032](http://go.microsoft.com/fwlink/?linkid=184917) | Sicherheitsanfälligkeit in Win32k bei Fenstererstellung                                             | [CVE-2010-0485](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0485) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                       |  
| [MS10-039](http://go.microsoft.com/fwlink/?linkid=191905) | Sicherheitsanfälligkeit in XSS bezüglich der Datei Help.aspx                                        | [CVE-2010-0817](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0817) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | Diese Sicherheitsanfälligkeit wurde erstmals in der [Microsoft-Sicherheitsempfehlung 983438](http://technet.microsoft.com/security/advisory/983438) gemeldet. |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Sicherheitsanfälligkeit in Excel bzgl. Überlaufs im Objektstapel                                    | [CVE-2010-0822](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0822) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                       |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Sicherheitsanfälligkeit in Excel bezüglich Speicherbeschädigung in Datensätzen                      | [CVE-2010-0824](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0824) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                       |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Sicherheitsanfälligkeit in Excel bezüglich Speicherbeschädigung in Datensätzen                      | [CVE-2010-1245](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1245) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                       |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Sicherheitsanfälligkeit in Excel-RTD bezüglich Speicherbeschädigung                                 | [CVE-2010-1246](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1246) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                       |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Sicherheitsanfälligkeit in Excel bezüglich Speicherbeschädigung                                     | [CVE-2010-1247](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1247) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                       |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Sicherheitsanfälligkeit in Excel-HFPicture bezüglich Speicherbeschädigung                           | [CVE-2010-1248](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1248) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                       |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Sicherheitsanfälligkeit in Excel bezüglich Speicherbeschädigung                                     | [CVE-2010-1249](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1249) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                       |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Sicherheitsanfälligkeit in Excel-EDG bezüglich Speicherbeschädigung                                 | [CVE-2010-1250](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1250) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                       |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Sicherheitsanfälligkeit im ADO-Objekt von Excel                                                     | [CVE-2010-1253](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1253) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                       |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Sicherheitsanfälligkeit in den Berechtigungen für Mac Office Open XML                               | [CVE-2010-1254](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1254) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                       |  
| [MS10-035](http://go.microsoft.com/fwlink/?linkid=190898) | Sicherheitsanfälligkeit bezüglich Speicherbeschädigung aufgrund von Nichtinitialisierung            | [CVE-2010-1259](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1259) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                       |  
| [MS10-035](http://go.microsoft.com/fwlink/?linkid=190898) | Sicherheitsanfälligkeit bezüglich Speicherbeschädigung                                              | [CVE-2010-1262](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1262) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                       |  
| [MS10-036](http://go.microsoft.com/fwlink/?linkid=190554) | Sicherheitsanfälligkeit bezüglich COM-Überprüfung                                                   | [CVE-2010-1263](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1263) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                       |  
| [MS10-033](http://go.microsoft.com/fwlink/?linkid=191065) | Sicherheitsanfälligkeit in Mediendekomprimierung                                                    | [CVE-2010-1879](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1879) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                       |  
| [MS10-035](http://go.microsoft.com/fwlink/?linkid=190898) | Sicherheitsanfälligkeit durch domänenübergreifende Offenlegung von Informationen                    | [CVE-2010-0255](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0255) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | Diese Sicherheitsanfälligkeit wurde erstmals in der [Microsoft-Sicherheitsempfehlung 980088](http://technet.microsoft.com/security/advisory/980088) gemeldet. |  
| [MS10-032](http://go.microsoft.com/fwlink/?linkid=184917) | Sicherheitsanfälligkeit in Win32k durch fehlerhafte Datenüberprüfung                                | [CVE-2010-0484](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0484) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                                                                                       |  
| [MS10-037](http://go.microsoft.com/fwlink/?linkid=190508) | Sicherheitsanfälligkeit im OpenType CFF-Treiber bezüglich Speicherbeschädigung                      | [CVE-2010-0819](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0819) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                                                                                       |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Sicherheitsanfälligkeit bezüglich Speicherbeschädigung beim Analysieren von Excel-Datensätzen       | [CVE-2010-0821](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0821) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                                                                                       |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Sicherheitsanfälligkeit in Excel bezüglich Speicherbeschädigung                                     | [CVE-2010-0823](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-0823) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                                                                                       |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Sicherheitsanfälligkeit im Excel-Datensatz bezüglich Stapelbeschädigung                             | [CVE-2010-1251](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1251) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                                                                                       |  
| [MS10-038](http://go.microsoft.com/fwlink/?linkid=191053) | Sicherheitsanfälligkeit in der Zeichenfolgenvariablen von Excel                                     | [CVE-2010-1252](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1252) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                                                                                       |  
| [MS10-032](http://go.microsoft.com/fwlink/?linkid=184917) | Sicherheitsanfälligkeit in Win32k bei der Analyse von TrueType-Schriftarten                         | [CVE-2010-1255](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1255) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                                                                                       |  
| [MS10-040](http://go.microsoft.com/fwlink/?linkid=191788) | Sicherheitsanfälligkeit bezüglich Speicherbeschädigung bei IIS-Authentifizierung                    | [CVE-2010-1256](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1256) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                                                                                       |  
| [MS10-033](http://go.microsoft.com/fwlink/?linkid=191065) | Sicherheitsanfälligkeit in MJPEG-Mediendekomprimierung                                              | [CVE-2010-1880](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1880) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                                                                                       |  
| [MS10-041](http://go.microsoft.com/fwlink/?linkid=185042) | Sicherheitsanfälligkeit durch Umgehung der Authentifizierung der XML-Signatur bei HMAC-Abschneidung | [CVE-2009-0217](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0217) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Funktionierender Angreifercode unwahrscheinlich | Dies ist eine Sicherheitsanfälligkeit bezüglich Spoofing und Manipulation.                                                                                    |  
| [MS10-035](http://go.microsoft.com/fwlink/?linkid=190898) | Sicherheitsanfälligkeit in toStaticHTML durch Offenlegung von Informationen                         | [CVE-2010-1257](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1257) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Funktionierender Angreifercode unwahrscheinlich | Diese Sicherheitsanfälligkeit betrifft auch [MS10-039](http://go.microsoft.com/fwlink/?linkid=191905)                                                         |  
| [MS10-039](http://go.microsoft.com/fwlink/?linkid=191905) | Sicherheitsanfälligkeit in toStaticHTML durch Offenlegung von Informationen                         | [CVE-2010-1257](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1257) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Funktionierender Angreifercode unwahrscheinlich | Diese Sicherheitsanfälligkeit betrifft auch [MS10-035](http://go.microsoft.com/fwlink/?linkid=190898)                                                         |  
| [MS10-039](http://go.microsoft.com/fwlink/?linkid=191905) | Sicherheitsanfälligkeit auf der Hilfeseite von SharePoint bezüglich Denial-of-Service               | [CVE-2010-1264](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2010-1264) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) - Funktionierender Angreifercode unwahrscheinlich | (Keine)                                                                                                                                                       |
  
Betroffene Software und Downloadadressen  
----------------------------------------
  
In den folgenden Tabellen sind die Bulletins nach Hauptsoftwarekategorie und Schweregrad aufgeführt.
  
**Wie verwende ich diese Tabellen?**  
  
In diesen Tabellen finden Sie Informationen zu Sicherheitsupdates, die Sie möglicherweise installieren sollten. Alle aufgeführten Softwareprogramme bzw. -komponenten sollten überprüft werden, um zu sehen, ob Sicherheitsupdates für Ihre Installation zutreffen. Wenn ein Softwareprogramm oder eine Komponente aufgeführt sind, dann ist das verfügbare Softwareupdate über einen Hyperlink verknüpft, und die Bewertung des Schweregrads des Softwareupdates ist ebenfalls aufgeführt.
  
**Hinweis:** Für eine Sicherheitsanfälligkeit müssen Sie möglicherweise mehrere Sicherheitsupdates installieren. Durchsuchen Sie in der gesamten Spalte die einzelnen Kennungen der aufgeführten Bulletins, um basierend auf den auf Ihrem System installierten Programmen oder Komponenten zu überprüfen, welche Updates Sie installieren müssen.
  
#### Systemkomponenten des Windows-Betriebssystems

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://go.microsoft.com/fwlink/?linkid=184917)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://go.microsoft.com/fwlink/?linkid=191065)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://go.microsoft.com/fwlink/?linkid=185159)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://go.microsoft.com/fwlink/?linkid=190898)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://go.microsoft.com/fwlink/?linkid=190508)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://go.microsoft.com/fwlink/?linkid=191788)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://go.microsoft.com/fwlink/?linkid=185042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=60c8579b-1540-40d8-80a0-956edadd63ce)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow) (DirectX 9)](http://www.microsoft.com/downloads/details.aspx?familyid=a51c53bd-f9c1-4d53-8ed2-034fd57bc75a)<sup>[1]</sup>
(KB975562)  
(Kritisch)  
[Windows Media Format Runtime 9](http://www.microsoft.com/downloads/details.aspx?familyid=8417c0ac-bb6d-48f1-8237-77a4bdd8ccb2)<sup>[2]</sup>
(KB978695)  
(Kritisch)  
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf)  
(KB979332)  
(Hoch)  
[Asycfilt.dll (COM-Komponente)](http://www.microsoft.com/downloads/details.aspx?familyid=1f929739-08a1-4faf-9ccf-5f1f43c5bb9e)  
(KB979482)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=d3955983-0079-476e-a488-99713097259c)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Internet Explorer 5.01 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=0a6c09e5-c655-41a0-a133-78d55267a527)  
(Keine Bewertung des Schweregrads)<sup>[1]</sup>
[Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=e2f27eeb-54be-40be-a00e-72867090b8e7)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=5d645891-31e9-42c4-b12b-eb351473fd0c)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(Hoch)  
[Microsoft .NET Framework 2.0 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://go.microsoft.com/fwlink/?linkid=184917)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://go.microsoft.com/fwlink/?linkid=191065)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://go.microsoft.com/fwlink/?linkid=185159)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://go.microsoft.com/fwlink/?linkid=190898)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://go.microsoft.com/fwlink/?linkid=190508)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://go.microsoft.com/fwlink/?linkid=191788)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://go.microsoft.com/fwlink/?linkid=185042)
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
Keine
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 und Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 und Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=023a777a-3d83-4a4e-8029-da8b095b074b)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=e77d5af8-e8e0-425c-a809-4cf274e17cc5)  
(KB975562)  
(Kritisch)  
Nur Windows XP Service Pack 2:  
[Windows Media Format Runtime 9, Windows Media Format Runtime 9.5 und Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=bf8b9b46-ba28-4f48-9dac-6a90b7d592d3)  
(KB978695)  
(Kritisch)  
Nur Windows XP Service Pack 3:  
[Windows Media Format Runtime 9, Windows Media Format Runtime 9.5 und Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=ebbccd82-c637-4c88-86ea-d39ae713c085)  
(KB978695)  
(Kritisch)  
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf)  
(KB979332)  
(Hoch)  
[Asycfilt.dll (COM-Komponente)](http://www.microsoft.com/downloads/details.aspx?familyid=55c05cb8-aa6c-460b-9aa7-084842dab280)  
(KB979482)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 und Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=8c3f2e81-c0ea-494a-a47c-4f8982effb49)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=bfe87761-ed9e-4fec-a393-d7fddb919db4)  
(Kritisch)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=fc02fc7e-ee85-4377-b54c-012fa60a8c9c)  
(Kritisch)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=9cff9aba-7743-4c33-87c7-37d06ed60a21)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 und Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=b42a17c5-997e-4504-ba5b-bfa62166b460)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nur Windows XP Media Center Edition 2005:  
[Microsoft .NET Framework 1.0 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=c658c108-abd3-4c24-898d-34d490151394)  
(KB979904)  
(Hoch)  
Nur Windows XP Media Center Edition 2005 und Windows XP Tablet PC Edition 2005:  
[Microsoft .NET Framework 1.0 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=c658c108-abd3-4c24-898d-34d490151394)  
(KB979904)  
(Hoch)  
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(Hoch)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(Hoch)  
[Microsoft .NET Framework 2.0 Service Pack 2 und Microsoft .NET 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=8e3aac9d-7747-435f-9678-f621e314e070)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=7914fdae-9a7a-4a10-8ce7-c621eb903452)  
(KB975562)  
(Kritisch)  
[Windows Media Format Runtime 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=b56839e3-e7d3-48da-b90c-d403d8dbeed2)  
(KB978695)  
(Kritisch)  
[Windows Media Format Runtime 9.5 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=80006082-55f2-4857-9d2c-276c758b5555)<sup>[3]</sup>
(KB978695)  
(Kritisch)  
[Windows Media Format Runtime 11](http://www.microsoft.com/downloads/details.aspx?familyid=d2887448-9d3c-472f-a0bd-ab083a65eafc)  
(KB978695)  
(Kritisch)  
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=94c654f0-f70f-4fbd-84de-797be20fc3b9)  
(KB979332)  
(Hoch)  
[Windows Media Encoder 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=2b7a3cb7-151c-4184-9865-f197ef6ee8e7)  
(KB979332)  
(Hoch)  
[Asycfilt.dll (COM-Komponente)](http://www.microsoft.com/downloads/details.aspx?familyid=c110d26e-9a1e-4e47-9ce2-4068f2733a2f)  
(KB979482)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f3e462fb-df95-4b79-a8bc-5359c2967503)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=7780af61-a206-49aa-a805-a49bdcbb5419)  
(Kritisch)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=6c7cda29-161e-49b4-976a-c718c0aa11a0)  
(Kritisch)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=37cd7533-ddad-4d0d-85c0-1491308e1ff8)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=dc835b94-3368-4c1c-8f29-40517c73540e)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(Hoch)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(Hoch)  
[Microsoft .NET Framework 2.0 Service Pack 2 und Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad) (KB979909)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://go.microsoft.com/fwlink/?linkid=184917)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://go.microsoft.com/fwlink/?linkid=191065)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://go.microsoft.com/fwlink/?linkid=185159)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://go.microsoft.com/fwlink/?linkid=190898)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://go.microsoft.com/fwlink/?linkid=190508)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://go.microsoft.com/fwlink/?linkid=191788)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://go.microsoft.com/fwlink/?linkid=185042)
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
<td style="border:1px solid black;">
[**Mittel**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Mittel**](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=79a11dcd-5d88-4d83-beae-6580ef6fc2c0)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=fc15c43b-d48f-4872-8f9d-ed973170db9a)  
(KB975562)  
(Kritisch)  
[Windows Media Format Runtime 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=bb580e94-8c02-46f1-b7f6-e7d4373cb1c5)  
(KB978695)  
(Kritisch)  
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=5b5398c1-5b30-4162-95b6-948d9be103bf)  
(KB979332)  
(Hoch)  
[Asycfilt.dll (COM-Komponente)](http://www.microsoft.com/downloads/details.aspx?familyid=0ddf95ac-dd49-4cb1-b6f6-bd4e987b0f06)  
(KB979482)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3c0bd349-aa77-47de-ba1d-1fcc72dcad28)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=bfb9acdb-2d9c-4c22-963c-8b9ce247350f)  
(Mittel)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=f0187b69-3ed9-494c-89f1-90a35e22078c)  
(Mittel)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=ebab6101-fcf1-4842-b22d-893a20c1c10f)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ca49b5b5-db8e-4ebc-9a3c-b1ace09ac3c0)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Internetinformationsdienste 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=0761c207-5465-4f42-b61f-bd02efcef27d)<sup>[1]</sup>  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=f82e1b73-7f8b-4f4c-8187-4050a11db44c)  
(KB979907)  
(Hoch)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(Hoch)  
[Microsoft .NET Framework 2.0 Service Pack 2 und Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=f42cc5d4-1bea-4a4a-8a08-b3eb92503588)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=d28ecdf7-9fd4-437e-9db7-c6b579248abe)  
(KB975562)  
(Kritisch)  
[Windows Media Format Runtime 9.5](http://www.microsoft.com/downloads/details.aspx?familyid=41faf16f-c7a8-4ce0-b388-a65478576163)  
(KB978695)  
(Kritisch)  
[Windows Media Format Runtime 9.5 x64 Edition](http://www.microsoft.com/downloads/details.aspx?familyid=80006082-55f2-4857-9d2c-276c758b5555)<sup>[3]</sup>  
(KB978695)  
(Kritisch)  
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=94c654f0-f70f-4fbd-84de-797be20fc3b9)  
(KB979332)  
(Hoch)  
[Windows Media Encoder 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=2b7a3cb7-151c-4184-9865-f197ef6ee8e7)  
(KB979332)  
(Hoch)  
[Asycfilt.dll (COM-Komponente)](http://www.microsoft.com/downloads/details.aspx?familyid=77b1d55c-b015-4863-aab0-6463b90d4bf7)  
(KB979482)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4aa0ec4f-5502-4f2a-9732-975518c34444)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=81644c43-22c0-4c61-b395-3264516516a6)  
(Mittel)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=50b8ee2e-31f8-473d-83d1-822c89c28070)  
(Mittel)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=87e13912-f861-4985-ab9d-260a5898dfd4)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=b0794e7e-c925-4672-b7a5-4bb3f847f045)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Internetinformationsdienste 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=023572ff-ce5d-4428-a96b-1245db6ff312)<sup>[1]</sup>  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(Hoch)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(Hoch)  
[Microsoft .NET Framework 2.0 Service Pack 2 und Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 mit SP2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=50efb1cf-9d89-4522-929d-f87fd98d6fe8)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=7f101f4c-dcc8-474c-a844-fe0c45d6697c)  
(KB975562)  
(Kritisch)  
[Asycfilt.dll (COM-Komponente)](http://www.microsoft.com/downloads/details.aspx?familyid=f34bc115-022b-46b0-9517-806bd0fc73c5)  
(KB979482)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=55d9d7f0-f9d9-4833-b5cc-eb87a62da6a8)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=abcdc3bb-4659-4b63-a9bd-e448f8bed90a)  
(Mittel)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=123bf547-9005-451f-9eba-97a68037304e)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=6e76ebea-bde1-4352-a283-dd71c2cc51a1)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Internetinformationsdienste 6.0](http://www.microsoft.com/downloads/details.aspx?familyid=f1f3e524-8ac6-4210-a3a8-4ffc58a606ea)<sup>[1]</sup>  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(Hoch)  
[Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=1b41e880-d774-4292-b2aa-2a66568142c9)  
(KB982865)  
(Hoch)  
[Microsoft .NET Framework 2.0 Service Pack 2 und Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=43810ead-1fcc-4a97-ad82-00ee42c27bad)  
(KB979909)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://go.microsoft.com/fwlink/?linkid=184917)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://go.microsoft.com/fwlink/?linkid=191065)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://go.microsoft.com/fwlink/?linkid=185159)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://go.microsoft.com/fwlink/?linkid=190898)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://go.microsoft.com/fwlink/?linkid=190508)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://go.microsoft.com/fwlink/?linkid=191788)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://go.microsoft.com/fwlink/?linkid=185042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
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
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
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
Windows Vista Service Pack 1 und Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 und Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7cb64633-d2a0-4e38-be35-ec32ea655a04)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nur Windows Vista Service Pack 1:  
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=b64107f2-990a-42df-a75a-5bf371709fd6)  
(KB975562)  
(Kritisch)  
[Asycfilt.dll (COM-Komponente)](http://www.microsoft.com/downloads/details.aspx?familyid=75e4c9cb-a55a-4e2a-9c97-60a40353cae3)  
(KB979482)  
(Kritisch)  
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=9fab91da-1528-4df9-a2dd-90e57a3c24cf)  
(KB979332)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 und Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=2ddaa4b3-1a98-4183-94af-ebdae4e7b76a)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=661c9528-917d-4df6-a330-c89f39dc5ce4)  
(Kritisch)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=640f9216-3e99-46b6-aac8-cd051eedad3c)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Vista Service Pack 1 und Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=363b503a-2e1e-4284-a029-9695d2acfcb6)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Internetinformationsdienste 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=01382926-2313-4769-a0a5-262c4f9f18a1)<sup>[1]</sup>  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(Hoch)  
Nur Windows Vista Service Pack 1:  
[Microsoft .NET Framework 2.0 Service Pack 1 und Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)  
(KB979913)  
(Hoch)  
Nur Windows Vista Service Pack 1:  
[Microsoft .NET Framework 2.0 Service Pack 2 und Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)  
(KB979911)  
(Hoch)  
Nur Windows Vista Service Pack 2:  
[Microsoft .NET Framework 2.0 Service Pack 2 und Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb) (KB979910)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1 und Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 und Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bbfc4d80-67eb-4deb-9595-cb67942a0df2)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nur Windows Vista x64 Edition Service Pack 1:  
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=0754addb-2f04-45c9-8594-174b8b8b297c)  
(KB975562)  
(Kritisch)  
[Asycfilt.dll (COM-Komponente)](http://www.microsoft.com/downloads/details.aspx?familyid=c9f033f6-f587-494d-b968-1316f1deed06)  
(KB979482)  
(Kritisch)  
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=63bba49e-6d80-47b3-b109-fa9b2392af4f)  
(KB979332)  
(Hoch)  
[Windows Media Encoder 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=e19aeef8-6bef-45ee-bc9f-3e4b81a58e33)  
(KB979332)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 und Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=ddf55e74-dbaa-45f7-ac5b-ae3da24e0e33)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=d9f5feb0-fa1a-40c1-9971-9b8af6f0b4a5)  
(Kritisch)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=3076d1ea-7716-4b54-8ec4-660374f14dcb)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition Service Pack 1 und Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=3f512b86-3a99-47f7-a90e-1ae9b291385c)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Internetinformationsdienste 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=7fb6f2b8-c7a6-4239-99f3-cf3aacf89b0f)<sup>[1]</sup>  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(Hoch)  
Nur Windows Vista x64 Edition Service Pack 1:  
[Microsoft .NET Framework 2.0 Service Pack 1 und Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)  
(KB979913)  
(Hoch)  
Nur Windows Vista x64 Edition Service Pack 1:  
[Microsoft .NET Framework 2.0 Service Pack 2 und Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)  
(KB979911)  
(Hoch)  
Nur Windows Vista x64 Edition Service Pack 2:  
[Microsoft .NET Framework 2.0 Service Pack 2 und Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb)  
(KB979910)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://go.microsoft.com/fwlink/?linkid=184917)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://go.microsoft.com/fwlink/?linkid=191065)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://go.microsoft.com/fwlink/?linkid=185159)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://go.microsoft.com/fwlink/?linkid=190898)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://go.microsoft.com/fwlink/?linkid=190508)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://go.microsoft.com/fwlink/?linkid=191788)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://go.microsoft.com/fwlink/?linkid=185042)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Mittel**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Mittel**](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme und Windows Server 2008 für 32-Bit-Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme und Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=22d550fe-ba35-4750-a9d6-624858b67c94)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
Nur Windows Server 2008 für 32-Bit-Systeme:  
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=18fd814b-51f3-470b-a5bd-97be752298d9)\*\*  
(KB975562)  
(Kritisch)  
[Asycfilt.dll (COM-Komponente)](http://www.microsoft.com/downloads/details.aspx?familyid=5c5e2dfc-0078-4f2a-9c2e-75e45bb7638e)\*  
(KB979482)  
(Kritisch)  
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=1ce1e47f-b1c3-4480-bafd-74f8b12e2171)\*\*  
(KB979332)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme und Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a06b9f42-47ac-4ff2-ac32-e4958cdb611e)\*\*  
(Mittel)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=bed14484-7fc5-455d-b996-3192467543cc)\*\*  
(Mittel)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=24ed08c7-a474-4458-8269-3b9de5e22385)\*\*  
(Mittel)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme und Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=e78ad607-d209-48c4-b0f3-ed4c70993174)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
[Internetinformationsdienste 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=84a54246-5d9e-49e2-8170-af48b43f984d)\*<sup>[1]</sup>  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)\*\*  
(KB979906)  
(Hoch)  
Nur Windows Server 2008 für 32-Bit-Systeme:  
[Microsoft .NET Framework 2.0 Service Pack 1 und Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)\*\*  
(KB979913)  
(Hoch)  
Nur Windows Server 2008 für 32-Bit-Systeme:  
[Microsoft .NET Framework 2.0 Service Pack 2 und Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)\*\*  
(KB979911)  
(Hoch)  
Nur Windows Server 2008 für 32-Bit-Systeme Service Pack 2:  
[Microsoft .NET Framework 2.0 Service Pack 2 und Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb)\*\*  
(KB979910)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für x64-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=09025626-4116-4a31-8700-215382898ee2)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
Nur Windows Server 2008 für x64-basierte Systeme:  
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=4e40da51-23ee-44f0-9ea0-99bda8cca731)\*\*  
(KB975562)  
(Kritisch)  
[Asycfilt.dll (COM-Komponente)](http://www.microsoft.com/downloads/details.aspx?familyid=bfc0b62c-2d79-48dd-896f-d05057c02e8c)\*  
(KB979482)  
(Kritisch)  
[Windows Media Encoder 9 x86](http://www.microsoft.com/downloads/details.aspx?familyid=93cc5ace-6382-4a2f-875b-9348b7e198a6)\*\*  
(KB979332)  
(Hoch)  
[Windows Media Encoder 9 x64](http://www.microsoft.com/downloads/details.aspx?familyid=d650a7d7-5620-4bb7-a7ad-0848dd28dae3)\*\*  
(KB979332)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6d0a3f7c-2617-4bc6-a4c7-cda26c6471e1)\*\*  
(Mittel)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=a24554e8-213b-4c24-b062-ec424d64128e)\*\*  
(Mittel)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=cf84469b-ce6d-45e8-8336-7b4501c6cf91)\*\*  
(Mittel)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=85f6fc5d-efd1-4351-b4c0-b9b7080e6173)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
[Internetinformationsdienste 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=38286e43-89a6-4895-8ff9-69452df38706)\*<sup>[1]</sup>  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)\*\*  
(KB979906)  
(Hoch)  
Nur Windows Server 2008 für x64-basierte Systeme:  
[Microsoft .NET Framework 2.0 Service Pack 1 und Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)\*\*  
(KB979913)  
(Hoch)  
Nur Windows Server 2008 für x64-basierte Systeme:  
[Microsoft .NET Framework 2.0 Service Pack 2 und Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)\*\*  
(KB979911)  
(Hoch)  
Nur Windows Server 2008 für x64-basierte Systeme Service Pack 2:  
[Microsoft .NET Framework 2.0 Service Pack 2 und Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb)\*\*  
(KB979910)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme und Windows Server 2008 für Itanium-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für Itanium-basierte Systeme und Windows Server 2008 für Itanium-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=0035cfe2-d38d-41cd-b704-ec1feda307d8)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nur Windows Server 2008 für Itanium-basierte Systeme:  
[Quartz.dll (DirectShow)](http://www.microsoft.com/downloads/details.aspx?familyid=120c68f5-4575-4e2a-912a-eed52736c403)  
(KB975562)  
(Kritisch)  
[Asycfilt.dll (COM-Komponente)](http://www.microsoft.com/downloads/details.aspx?familyid=6e5753ab-848d-475f-917d-ba70f70b65f5)  
(KB979482)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für Itanium-basierte Systeme und Windows Server 2008 für Itanium-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=38347fa6-5946-4bb5-9fea-a5b2f4e7c1f2)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=dee5c0c0-b844-490d-8daf-6e6ec8a39e35)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für Itanium-basierte Systeme und Windows Server 2008 für Itanium-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c6f1aae5-e8fd-4121-89b2-b97c571e8223)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Internetinformationsdienste 7.0](http://www.microsoft.com/downloads/details.aspx?familyid=8ad19eba-9821-48b4-a942-4ee4f002f913)<sup>[1]</sup>  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 1.1 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=5e55ee58-f00a-4237-bddc-492b63a18b96)  
(KB979906)  
(Hoch)  
Nur Windows Server 2008 für Itanium-basierte Systeme:  
[Microsoft .NET Framework 2.0 Service Pack 1 und Microsoft .NET Framework 3.5](http://www.microsoft.com/downloads/details.aspx?familyid=3ffa2aa2-96a6-4317-8a81-c0ab6d570778)  
(KB979913)  
(Hoch)  
Nur Windows Server 2008 für Itanium-basierte Systeme:  
[Microsoft .NET Framework 2.0 Service Pack 2 und Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=818acb7e-f984-4793-9418-bb01ed8cfb68)  
(KB979911)  
(Hoch)  
Nur Windows Server 2008 für Itanium-basierte Systeme Service Pack 2:  
[Microsoft .NET Framework 2.0 Service Pack 2 und Microsoft .NET Framework 3.5 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=14c2fa85-f73e-4b62-84ca-d5ea7439aebb)  
(KB979910)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://go.microsoft.com/fwlink/?linkid=184917)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://go.microsoft.com/fwlink/?linkid=191065)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://go.microsoft.com/fwlink/?linkid=185159)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://go.microsoft.com/fwlink/?linkid=190898)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://go.microsoft.com/fwlink/?linkid=190508)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://go.microsoft.com/fwlink/?linkid=191788)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://go.microsoft.com/fwlink/?linkid=185042)
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
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
[Windows 7 für 32-Bit-Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=3e0ff389-4612-4c92-bbff-bb45b5bdfc6a)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Asycfilt.dll (COM-Komponente)](http://www.microsoft.com/downloads/details.aspx?familyid=63567e99-087d-4804-953a-f23bdeba7772)  
(KB979482)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows 7 für 32-Bit-Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=5bce87fe-dcbb-4638-b248-3f0755537b00)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5c835885-9375-4882-a92f-4d4cfcacc005)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows 7 für 32-Bit-Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=969af8d6-f6da-4dd1-a7d7-2de54a5a8978)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Internetinformationsdienste 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=588167cb-f62a-4fb8-8a18-ac15dc322495)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764)  
(KB979916)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
[Windows 7 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=2b1e4aff-605a-4e94-88f9-135ce35f0646)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Asycfilt.dll (COM-Komponente)](http://www.microsoft.com/downloads/details.aspx?familyid=6c261dbf-14c6-4071-8523-e8ba8059fa54)  
(KB979482)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows 7 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=ee68ecd0-5b8a-4c1e-bdee-bd8616558d43)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=5cfc5776-0c6b-4092-bc98-94df077c60d8)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows 7 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=b069e5b2-aa2d-452e-b687-8734b5ba0051)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Internetinformationsdienste 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=1c45d0c8-1629-470b-8167-c6bf66054595)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764)  
(KB979916)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="8" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS10-032**](http://go.microsoft.com/fwlink/?linkid=184917)
</td>
<td style="border:1px solid black;">
[**MS10-033**](http://go.microsoft.com/fwlink/?linkid=191065)
</td>
<td style="border:1px solid black;">
[**MS10-034**](http://go.microsoft.com/fwlink/?linkid=185159)
</td>
<td style="border:1px solid black;">
[**MS10-035**](http://go.microsoft.com/fwlink/?linkid=190898)
</td>
<td style="border:1px solid black;">
[**MS10-037**](http://go.microsoft.com/fwlink/?linkid=190508)
</td>
<td style="border:1px solid black;">
[**MS10-040**](http://go.microsoft.com/fwlink/?linkid=191788)
</td>
<td style="border:1px solid black;">
[**MS10-041**](http://go.microsoft.com/fwlink/?linkid=185042)
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
<td style="border:1px solid black;">
[**Mittel**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
[**Mittel**](http://go.microsoft.com/fwlink/?linkid=21140)
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
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=4272277f-b2dd-4406-8bbd-bc461c9923b8)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
[Asycfilt.dll (COM-Komponente)](http://www.microsoft.com/downloads/details.aspx?familyid=1331f2bc-7479-4be7-a413-52afb488a330)\*  
(KB979482)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=901f7c89-02af-4f87-8592-dad318997d77)\*\*  
(Mittel)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=7c4ff5ae-eadd-431e-b982-d5f179efb8c0)\*\*  
(Mittel)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=45242c7c-3752-44bf-a766-024ad7d28f53)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
[Internetinformationsdienste 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=5d9b7705-6280-4d2e-94fa-3160b3ce5cfa)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764)\*  
(KB979916)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=7d636f82-e828-468c-ac36-808ff9d37c7f)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Asycfilt.dll (COM-Komponente)](http://www.microsoft.com/downloads/details.aspx?familyid=7a1ee54f-3f73-4557-9071-5af236e70937)  
(KB979482)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=4958b221-2776-43d7-9e1c-1e1cb318a694)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=52c04d85-911f-47be-852e-c9bb4934744d)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 R2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=0a271fb5-da5b-4a17-9593-e56b9a843b8f)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Internetinformationsdienste 7.5](http://www.microsoft.com/downloads/details.aspx?familyid=869e900a-0063-4d8b-9b7c-7d12f6be12cd)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft .NET Framework 3.5.1](http://www.microsoft.com/downloads/details.aspx?familyid=a49532d7-53f6-4190-aaf6-b1a818924764)  
(KB979916)  
(Hoch)
</td>
</tr>
</table>
 
**Hinweise für Windows Server 2008 und Windows Server 2008 R2**

**\*Die Server Core-Installation ist betroffen.** Dieses Update gilt, mit der gleichen Bewertung des Schweregrads, wie angezeigt auch für unterstützte Editionen von Windows Server 2008 oder Windows Server 2008 R2, unabhängig davon, ob bei der Installation die Server Core-Installationsoption verwendet wurde oder nicht. Weitere Informationen zu dieser Installationsoption finden Sie in den MSDN-Artikeln [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) und [Server Core für Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx). Beachten Sie, dass die Server Core-Installationsoption für bestimmte Editionen von Windows Server 2008 und Windows Server 2008 R2 nicht gilt; siehe dazu [Vergleichen von Server Core-Installationsoptionen](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**\*\*Die Server Core-Installation ist nicht betroffen.** Die durch dieses Update behobenen Sicherheitsanfälligkeiten betreffen unterstützte Editionen von Windows Server 2008 oder Windows Server 2008 R2 wie angegeben nicht, wenn diese mit der Server Core-Installationsoption installiert wurden. Weitere Informationen zu dieser Installationsoption finden Sie in den MSDN-Artikeln [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) und [Server Core für Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx). Beachten Sie, dass die Server Core-Installationsoption für bestimmte Editionen von Windows Server 2008 und Windows Server 2008 R2 nicht gilt; siehe dazu [Vergleichen von Server Core-Installationsoptionen](http://www.microsoft.com/windowsserver2008/en/us/compare-core-installation.aspx).

**Hinweis für MS10-033**

<sup>[1]</sup>Das Update für Quartz.dll (DirectShow) (DirectX 9) gilt auch für DirectX 9.0a, DirectX 9.0b und DirectX 9.0c.

<sup>[2]</sup>Dieses Updatepaket gilt für Windows Media Format Runtime 9 SDK unter Microsoft Windows 2000 mit dem Update für DRM-fähige Media Player (KB891122). Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 974316](http://support.microsoft.com/kb/974316).

<sup>[3]</sup>Wenn Sie Windows Media Format Runtime 9.5 x64 Edition installiert haben, müssen Sie die Sicherheitsupdates für Windows Media Format Runtime 9.5 und Windows Media Format Runtime 9.5 x64 Edition installieren, um vollständig vor der in MS10-033 diskutierten Sicherheitsanfälligkeit geschützt zu sein.

**Hinweis für MS10-035**

<sup>[1]</sup>Bewertungen des Schweregrads treffen nicht auf dieses Update zu, da diese Software nicht von der Sicherheitsanfälligkeit betroffen ist, die in diesem Bulletin erörtert wird. Dieses Update wird jedoch angeboten, um ein Regressionsproblem zu beheben, das aus [MS09-054](http://go.microsoft.com/fwlink/?linkid=163979) entstanden ist. Weitere Informationen finden Sie unter [MS10-035](http://go.microsoft.com/fwlink/?linkid=190898).

**Hinweis für MS10-040**

<sup>[1]</sup>Dieses Betriebssystem ist nur betroffen, wenn der erweiterte Authentifizierungsschutz installiert wurde. Siehe [Microsoft Knowledge Base-Artikel 973917](http://support.microsoft.com/kb/973917).

#### Microsoft Office Suites und Software

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Microsoft Office Suites, Systeme und Komponenten
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS10-036**](http://go.microsoft.com/fwlink/?linkid=190554)
</td>
<td style="border:1px solid black;">
[**MS10-038**](http://go.microsoft.com/fwlink/?linkid=191053)
</td>
<td style="border:1px solid black;">
[**MS10-039**](http://go.microsoft.com/fwlink/?linkid=191905)
</td>
</tr>
<tr class="alternateRow">
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
Keine
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3
</td>
<td style="border:1px solid black;">
Microsoft Office XP Service Pack 3<sup>[1]</sup>
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=fec14a92-79a1-4281-8ee2-659b2dfd283f)  
(KB982299)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=80fdd134-2a86-4115-aea1-841f19af92e3)  
(KB982311)  
(Hoch)  
[Microsoft Office Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=757b5d8f-ade5-4896-b152-43f76516bcf1)<sup>[2]</sup>
(KB982133)  
(Hoch)  
[Microsoft Office PowerPoint 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=6b6204c1-559f-45a5-8f6c-a1e216192efc)<sup>[2]</sup>
(KB982157)  
(Hoch)  
[Microsoft Office Publisher 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=87bac893-81ec-4ede-aca1-a9aa48b92cd4)<sup>[2]</sup>
(KB982122)  
(Hoch)  
[Microsoft Office Visio 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=1595ada3-bb4f-40f6-8137-23eba918bc8a)<sup>[2]</sup>
(KB982126)  
(Hoch)  
[Microsoft Office Word 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=d2c40eb5-1149-4466-840c-84f406f64245)<sup>[2]</sup>
(KB982134)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=757b5d8f-ade5-4896-b152-43f76516bcf1)  
(KB982133)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office System 2007 Service Pack 1 und Microsoft Office System 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Office System 2007 Service Pack 1 und Microsoft Office System 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6deb4fb0-cbfc-40df-8f62-35fa1db0e167)  
(KB982312)  
(Hoch)  
[Microsoft Office Excel 2007 Service Pack 1 und Microsoft Office Excel 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1b2599f0-1e5d-463c-b100-6c6a1b17b2ec)<sup>[3]</sup>
(KB982308)  
(Hoch)  
[Microsoft Office PowerPoint 2007 Service Pack 1 und Microsoft Office PowerPoint 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=decb834d-3958-45cc-a5ae-4283adb2462a)<sup>[3]</sup>
(KB982158)  
(Hoch)  
[Microsoft Office Publisher 2007 Service Pack 1 und Microsoft Office Publisher 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=6a74b986-1e99-4aa1-828f-757a36896f65)<sup>[3]</sup>
(KB982124)  
(Hoch)  
[Microsoft Office Visio 2007 Service Pack 1 und Microsoft Office Visio 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=d5df052e-1f38-4308-bcca-296cff22729b)<sup>[3]</sup>
(KB982127)  
(Hoch)  
[Microsoft Office Word 2007 Service Pack 1 und Microsoft Office Word 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7e9708f0-8cd6-4f0b-8585-bccc54fa2755)<sup>[3]</sup>
(KB982135)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 Service Pack 1 und Microsoft Office Excel 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1b2599f0-1e5d-463c-b100-6c6a1b17b2ec)<sup>[1]</sup>
(KB982308)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Microsoft Office für Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS10-036**](http://go.microsoft.com/fwlink/?linkid=190554)
</td>
<td style="border:1px solid black;">
[**MS10-038**](http://go.microsoft.com/fwlink/?linkid=191053)
</td>
<td style="border:1px solid black;">
[**MS10-039**](http://go.microsoft.com/fwlink/?linkid=191905)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
<td style="border:1px solid black;">
Keine
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 für Mac
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 für Mac](http://www.microsoft.com/downloads/details.aspx?familyid=16c71ab8-9284-407a-856a-93c67995f125)  
(KB2028866)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 für Mac
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 für Mac](http://www.microsoft.com/downloads/details.aspx?familyid=d46255bd-6470-4106-9fe2-ea67acd3f1bd)  
(KB2028864)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Open XML-Dateiformatkonverter für Mac
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Open XML-Dateiformatkonverter für Mac](http://www.microsoft.com/downloads/details.aspx?familyid=b6ca7b05-cf97-43a2-95eb-7b5caf7c1528)  
(KB2078051)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="4" style="border:1px solid black;">
Weitere Office-Software
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS10-036**](http://go.microsoft.com/fwlink/?linkid=190554)
</td>
<td style="border:1px solid black;">
[**MS10-038**](http://go.microsoft.com/fwlink/?linkid=191053)
</td>
<td style="border:1px solid black;">
[**MS10-039**](http://go.microsoft.com/fwlink/?linkid=191905)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
Keine
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
Microsoft Excel Viewer Service Pack 1 und Microsoft Office Excel Viewer Service Pack 2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer Service Pack 1 und Microsoft Office Excel Viewer Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=033b3bf3-7826-4064-b001-11e4dce2d91a)  
(KB982333)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack für die Dateiformate von Word, Excel und PowerPoint 2007 Service Pack 1 und Microsoft Office Compatibility Pack für die Dateiformate von Word, Excel und PowerPoint 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Office Compatibility Pack für die Dateiformate von Word, Excel und PowerPoint 2007 Service Pack 1 und Microsoft Office Compatibility Pack für die Dateiformate von Word, Excel und PowerPoint 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=7f89a734-cda4-4abb-9a10-f6dfe560e8d0)  
(KB982331)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office InfoPath 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Office InfoPath 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=4f79d376-0ea2-4218-9200-3c34c83ba336)  
(KB980923)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office InfoPath 2007 Service Pack 1 und Microsoft Office InfoPath 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Office InfoPath 2007 Service Pack 1 und Microsoft Office InfoPath 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=bfa8765a-7970-4feb-996c-7c27d71c97c6)  
(KB979441)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 Service Pack 1 und Microsoft Office SharePoint Server 2007 Service Pack 2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Office SharePoint Server 2007 Service Pack 1 (32-Bit-Editionen)](http://www.microsoft.com/downloads/details.aspx?familyid=52a55423-f33b-4cd1-919d-806972a553df)<sup>[1]</sup>
(KB979445)  
(Hoch)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (32-Bit-Editionen)](http://www.microsoft.com/downloads/details.aspx?familyid=52a55423-f33b-4cd1-919d-806972a553df)<sup>[1]</sup>
(KB979445)  
(Hoch)  
[Microsoft Office SharePoint Server 2007 Service Pack 1 (64-Bit-Editionen)](http://www.microsoft.com/downloads/details.aspx?familyid=4d84a25b-532f-4319-9ab2-90e5b82ebd90)<sup>[1]</sup>
(KB979445)  
(Hoch)  
[Microsoft Office SharePoint Server 2007 Service Pack 2 (64-Bit-Editionen)](http://www.microsoft.com/downloads/details.aspx?familyid=4d84a25b-532f-4319-9ab2-90e5b82ebd90)<sup>[1]</sup>
(KB979445)  
(Hoch)
</td>
</tr>
</table>
 
**Hinweise für MS10-036**

<sup>[1]</sup>Kein Update verfügbar. Weitere Informationen finden Sie im Bulletin.

<sup>[2]</sup>Zusätzlich zu diesem Update müssen Benutzer auch das Update für Microsoft Office 2003 Service Pack 3 (KB982311) installieren, um vor der in diesem Bulletin beschriebenen Sicherheitsanfälligkeit geschützt zu sein.

<sup>[3]</sup>Zusätzlich zu diesem Update müssen Benutzer auch das Update für Microsoft Office 2007 Service Pack 1 und Microsoft Office 2007 Service Pack 2 (KB982312) installieren, um vor der in diesem Bulletin beschriebenen Sicherheitsanfälligkeit geschützt zu sein.

**Hinweis für MS10-038**

<sup>[1]</sup>Zusätzlich zu diesem Update müssen Benutzer auch das Sicherheitsupdate für Microsoft Office Compatibility Pack für die Dateiformate von Word, Excel und PowerPoint 2007 Service Pack 1 und Microsoft Office Compatibility Pack für die Dateiformate von Word, Excel und PowerPoint 2007 Service Pack 2 (KB982308) installieren, um vor den in diesem Bulletin beschriebenen Sicherheitsanfälligkeiten geschützt zu sein.

**Hinweise für MS10-039**

<sup>[1]</sup>Bei unterstützten Editionen von Microsoft Office SharePoint Server 2007 müssen Benutzer zusätzlich zum Sicherheitsupdatepaket KB979445 auch das Sicherheitsupdate für Microsoft Windows SharePoint Services 3.0 (KB983444) installieren, um vor den in diesem Bulletin beschriebenen Sicherheitsanfälligkeiten geschützt zu sein.

Weitere Updatedateien finden Sie außerdem unter anderen Softwarekategorien im Abschnitt **Betroffene Software und Downloadadressen** unter der gleichen Kennung des Bulletins. Dieses Bulletin umfasst mehr als eine Softwarekategorie.

#### Microsoft Server-Software

<p> </p>
<table style="border:1px solid black;">
<tr class="thead">
<th style="border:1px solid black;" >
</th>
<th style="border:1px solid black;" >
</th>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Windows SharePoint Services
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS10-039**](http://go.microsoft.com/fwlink/?linkid=191905)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://go.microsoft.com/fwlink/?linkid=21140)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows SharePoint Services 3.0 Service Pack 1 und Microsoft Windows SharePoint Services 3.0 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft Windows SharePoint Services 3.0 Service Pack 1 und Microsoft Windows SharePoint Services 3.0 Service Pack 2 (32-Bit-Versionen)](http://www.microsoft.com/downloads/details.aspx?familyid=3841ceda-d0af-4e5e-8a1a-7dd954850783)  
(KB983444)  
(Hoch)  
[Microsoft Windows SharePoint Services 3.0 Service Pack 1 und Microsoft Windows SharePoint Services 3.0 Service Pack 2 (64-Bit-Versionen)](http://www.microsoft.com/downloads/details.aspx?familyid=94bc76d4-78e4-4bda-8922-36c3a9d3854f)  
(KB983444)  
(Hoch)
</td>
</tr>
</table>
 
**Hinweis für MS10-039**

Weitere Updatedateien finden Sie außerdem unter anderen Softwarekategorien im Abschnitt **Betroffene Software und Downloadadressen** unter der gleichen Kennung des Bulletins. Dieses Bulletin umfasst mehr als eine Softwarekategorie.

Tools und Anleitungen zur Erkennung und Bereitstellung
------------------------------------------------------

**Sicherheitsportal:**

Verwalten Sie die Software und die Sicherheitsupdates, die Sie den Servern, Desktops und mobilen Computer in Ihrer Organisation bereitstellen müssen. Weitere Informationen finden Sie im [TechNet Update Management Center](http://go.microsoft.com/fwlink/?linkid=69903). Im [TechNet Sicherheits-Center](http://go.microsoft.com/fwlink/?linkid=21171) werden zusätzliche Informationen zur Sicherheit in Microsoft-Produkten zur Verfügung gestellt. Verbraucher können die Seite [Sicherheit zu Hause](http://go.microsoft.com/fwlink/?linkid=85102) besuchen, wo diese Informationen auch durch einen Klick auf „Die neuesten Sicherheitsupdates“ verfügbar sind.

Sicherheitsupdates sind unter [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) und [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130) verfügbar. Sicherheitsupdates sind auch im [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129) verfügbar. Sie können am einfachsten durch eine Suche nach dem Begriff „security update“ ermittelt werden.

Außerdem können Sicherheitsupdates vom [Windows Update-Katalog](http://go.microsoft.com/fwlink/?linkid=96155) heruntergeladen werden. Der Microsoft Update-Katalog stellt einen durchsuchbaren Katalog der Inhalte bereit, die über Windows Update und Microsoft Update zur Verfügung gestellt werden, einschließlich Sicherheitsupdates, Treiber und Service Packs. Indem Sie mit der Nummer des Security Bulletins suchen (z. B. „MS07-036“), können Sie Ihrem Warenkorb alle anwendbaren Updates (einschließlich verschiedener Sprachen für ein Update) hinzufügen und in den Ordner Ihrer Wahl herunterladen. Weitere Informationen zum Microsoft Update-Katalog, finden Sie unter [Häufig gestellte Fragen zum Microsoft Update-Katalog](http://go.microsoft.com/fwlink/?linkid=97900).

**Hinweis:** Am 1. August 2009 hat Microsoft den Support für Office Update und das Inventurprogramm für Office-Update eingestellt. Verwenden Sie [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), um weiterhin die aktuellen Updates für Microsoft Office-Produkte zu erhalten. Weitere Informationen finden Sie in [Informationen zum Microsoft Office Update: Häufig gestellte Fragen (FAQs)](http://office.microsoft.com/en-us/downloads/fx010402221033.aspx).

**Anleitungen zur Erkennung und Bereitstellung**

Microsoft stellt Anleitungen zur Erkennung und Bereitstellung von Sicherheitsupdates bereit. Diese Anleitungen enthalten Empfehlungen und Informationen, anhand derer IT-Experten verstehen können, wie die verschiedenen Tools für die Erkennung und Bereitstellung der Sicherheitsupdates verwendet werden. Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 961747](http://support.microsoft.com/kb/961747).

**Microsoft Baseline Security Analyzer**

Der Microsoft Baseline Security Analyzer (MBSA) ermöglicht Administratoren die Überprüfung von lokalen und Remotesystemen im Hinblick auf fehlende Sicherheitsupdates sowie auf häufig falsch konfigurierte Sicherheitsparameter. Weitere Informationen zu MBSA finden Sie auf der Website [Microsoft Baseline Security Analyzer](http://go.microsoft.com/fwlink/?linkid=21134).

**Windows Server Update Services**

Mithilfe der Windows Server Update Services (WSUS) können Administratoren die neuesten wichtigen Aktualisierungen und Sicherheitsupdates für Microsoft Windows 2000 und neuere Betriebssysteme, Office XP und höher, Exchange Server 2003 und SQL Server 2000 bis Microsoft Windows 2000 und neuere Betriebssysteme schnell und sicher bereitstellen.

Weitere Informationen zum Bereitstellen dieses Sicherheitsupdates mithilfe der Windows Server Update Services finden Sie auf der [Windows Server Update Services Website](http://go.microsoft.com/fwlink/?linkid=50120).

**Systems Management Server**

Der Systems Management Server von Microsoft stellt eine wertvolle Hilfe beim Bereitstellen von Sicherheitsupdates in Ihrer IT-Umgebung dar. Durch die Verwendung von SMS können Administratoren auf Windows basierte Systeme identifizieren, für die Sicherheitsupdates erforderlich sind, und für eine kontrollierte Bereitstellung dieser Updates im gesamten Unternehmen bei minimalen Unterbrechungen für Endbenutzer sorgen. Die nächste Version von SMS, System Center Configuration Manager 2007, ist jetzt verfügbar (siehe auch [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)). Weitere Informationen zur Verwendung von SMS 2003 durch Administratoren für die Bereitstellung von Sicherheitsupdates finden Sie unter [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). Benutzer von SMS 2.0 können auch das Sicherheitsupdate-Inventurprogramm (SUIT) verwenden, um Hilfe bei der Bereitstellung von Sicherheitsupdates zu erhalten. Weitere Informationen zu SMS finden Sie auf der Website [Microsoft Systems Management Server](http://go.microsoft.com/fwlink/?linkid=21158).

**Hinweis:** SMS verwendet den Microsoft Baseline Security Analyzer für eine breite Unterstützung bei der Erkennung und der Bereitstellung von Security Bulletin-Updates. Einige Softwareupdates werden von diesen Tools möglicherweise nicht erkannt. Administratoren können in diesen Fällen die Inventurfunktionen von SMS nutzen, um Updates auf ausgewählten Systemen zu installieren. Weitere Informationen zu diesem Verfahren finden Sie auf der Website [Bereitstellen von Softwareupdates mit der Funktion zur Softwareverteilung von SMS](http://go.microsoft.com/fwlink/?linkid=33341). Bei einigen Sicherheitsupdates, die einen Neustart des Systems erfordern, sind unter Umständen administrative Rechte nötig. Administratoren können diese Updates mit dem Elevated Rights Deployment Tool (im [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161) verfügbar) installieren.

**Updatekompatibilitätsbewertung und Microsoft Application Compatibility Toolkit**

Updates bearbeiten oft dieselben Dateien und Registrierungseinstellungen, die zum Ausführen Ihrer Anwendungen benötigt werden. Dies kann eine Inkompatibilität auslösen und die Bereitstellung von Sicherheitsupdates verzögern. Mit den Komponenten zur [Updatekompatibilitätsbewertung](http://technet2.microsoft.com/windowsvista/en/library/4279e239-37a4-44aa-aec5-4e70fe39f9de1033.mspx?mfr=true), die im [Anwendungskompatibilitäts-Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) enthalten sind, können Sie die Vereinbarkeit von Windows-Updates mit installierten Anwendungen testen und überprüfen.

Das Microsoft Application Compatibility Toolkit (ACT) enthält alle notwendigen Tools und Dokumentationen, um die Anwendungskompatibilität zu prüfen und eventuelle Probleme zu beheben, bevor Microsoft Windows Vista, ein Windows-Update, ein Microsoft-Sicherheitsupdate oder eine neue Version von Windows Internet Explorer in Ihrer Umgebung bereitgestellt wird.

### Weitere Informationen:

#### Windows-Tool zum Entfernen schädlicher Software

Microsoft hat eine aktualisierte Version des Microsoft Windows-Tools zum Entfernen bösartiger Software in Windows Update, Microsoft Update, Windows Server Update Services und dem Download Center veröffentlicht.

#### Nicht sicherheitsrelevante, wichtige Updates unter MU, WU und WSUS:

Weitere Informationen zu nicht sicherheitsrelevanten Veröffentlichungen auf Windows-Update und Microsoft Update finden Sie unter:

-   [Microsoft Knowledge Base-Artikel 894199](http://support.microsoft.com/kb/894199): Beschreibung der Änderungen an den Inhalten von Software Update Services und Windows Server Update Services. Umfasst alle Windows-Inhalte.
-   [Updates für Windows Server Update Services aus den vergangenen Monaten](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Zeigt alle neuen, überarbeiteten und veröffentlichten Updates für andere Microsoft-Produkte als Microsoft Windows an.

#### Microsoft Active Protections Program (MAPP)

Um den Sicherheitsschutz für Benutzer zu verbessern, stellt Microsoft den wichtigsten Sicherheitssoftwareanbietern vor der monatlichen Veröffentlichung der Sicherheitsupdates Informationen zu Sicherheitsanfälligkeiten bereit. Anbieter von Sicherheitssoftware können diese Informationen zu Sicherheitsanfälligkeiten dann verwenden, um Benutzern aktualisierten Schutz über ihre Sicherheitssoftware oder ihre Geräte bereitzustellen, z. B. Antivirus, netzwerkbasierte Angriffserkennungssysteme oder hostbasierte Angriffsverhinderungssysteme. Wenn Sie erfahren möchten, ob von den Sicherheitssoftwareanbietern aktiver Schutz verfügbar ist, besuchen Sie die von den Programmpartnern bereitgestellte Active Protections-Websites, die unter [MAPP-Partner (Microsoft Active Protections Program)](http://www.microsoft.com/security/msrc/mapp/partners.mspx) aufgeführt sind.

#### Sicherheitsstrategien und Community

**Strategien für die Verwaltung von Sicherheitspatches:**

Auf der Seite [Patchmanagement](http://go.microsoft.com/fwlink/?linkid=21168) werden zusätzliche Informationen zu den empfohlenen Vorgehensweisen für die Anwendung von Sicherheitsupdates von Microsoft bereitgestellt.

**Weitere Sicherheitsupdates**

Updates für andere Sicherheitsrisiken sind unter den folgenden Adressen erhältlich:

-   Sicherheitsupdates sind im [Microsoft Download Center](http://go.microsoft.com/fwlink/?linkid=21129) verfügbar. Sie können am einfachsten durch eine Suche nach dem Begriff „security update“ ermittelt werden.
-   Updates für Benutzerplattformen sind auf [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) verfügbar.
-   Die Sicherheitsupdates, die in diesem Monat über Windows Update veröffentlicht wurden, können Sie auch im „Security and Critical Releases ISO CD Image“ über Microsoft Download Center erhalten. Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 913086](http://support.microsoft.com/kb/913086).

**IT Pro Security Community:**

Erfahren Sie, wie Sie die Sicherheit Ihrer IT-Umgebung erhöhen und Ihren IT-Betrieb optimieren können. Diskutieren Sie auf der [IT Pro Security Zone](http://go.microsoft.com/fwlink/?linkid=21164) Website mit anderen IT-Profis über das Thema Sicherheit.

#### Danksagungen

Microsoft [dankt](http://go.microsoft.com/fwlink/?linkid=21127) den folgenden Personen, dass sie zum Schutz unserer Kunden mit uns zusammengearbeitet haben:

-   Sebastien Renaud vom [VUPEN Vulnerability Research Team](http://www.vupen.com/) für den Hinweis auf ein in MS10-032 beschriebenes Problem
-   [Secunia Research](http://secunia.com/) für die Zusammenarbeit mit uns an einem in MS10-032 beschriebenen Problem
-   Yamata Li von [Palo Alto Networks](http://www.paloaltonetworks.com/) für den Hinweis auf zwei in MS10-033 beschriebene Probleme
-   Shaun Colley von [NGS Software](http://www.ngssoftware.com/) für den Hinweis auf ein in MS10-034 beschriebenes Problem
-   Chris Ries von Carnegie Mellon University Computing Services für den Hinweis auf ein in MS10-034 beschriebenes Problem
-   Chris Weber von [Casaba Security](http://www.casabasecurity.com/) für den Hinweis auf ein in MS10-035 und MS10-039 beschriebenes Problem
-   Takeshi Terada von [Mitsui Bussan Secure Directions, Inc.](http://www.mbsd.jp/) für den Hinweis auf ein in MS10-035 beschriebenes Problem
-   Michal Zalewski von [Google Inc.](http://www.google.com/) für den Hinweis auf ein in MS10-035 beschriebenes Problem
-   Chris Rohlf von [Matasano Security](http://www.matasano.com/) für den Hinweis auf zwei in MS10-035 beschriebene Probleme
-   Peter Vreugdenhil in Zusammenarbeit mit [Zero Day Initiative](http://www.zerodayinitiative.com/) von [TippingPoint](http://www.tippingpoint.com/) für den Hinweis auf ein in MS10-035 beschriebenes Problem
-   David Dewey von [IBM ISS X-Force](http://www.iss.net/) und Ryan Smith von [Accuvant](http://www.accuvant.com/), vormals von [VeriSign iDefense Labs](http://labs.idefense.com/), für die Zusammenarbeit bei den in MS10-036 enthaltenen Tiefenverteidigungsänderungen
-   Chris Carton von Laserforce International in Zusammenarbeit mit [Secunia](http://secunia.com/) für den Hinweis auf ein in MS10-037 beschriebenes Problem
-   Einer Person, die mit [Zero Day Initiative](http://www.zerodayinitiative.com/) von [TippingPoint](http://www.tippingpoint.com/) zusammenarbeitet, aber anonym bleiben möchte, für den Hinweis auf ein in MS10-038 beschriebenes Problem
-   Nicolas Joly vom [VUPEN Vulnerability Research Team](http://www.vupen.com/) für den Hinweis auf acht in MS10-038 beschriebene Probleme
-   Bing Liu von [Fortinets FortiGuard Labs](http://www.fortiguard.com/) für den Hinweis auf ein in MS10-038 beschriebenes Problem
-   Carsten Eiram von [Secunia](http://secunia.com/) für den Hinweis auf zwei in MS10-038 beschriebene Probleme
-   Einer Person, die mit [Zero Day Initiative](http://www.zerodayinitiative.com/) von [TippingPoint](http://www.tippingpoint.com/) zusammenarbeitet, aber anonym bleiben möchte, für den Hinweis auf ein in MS10-038 beschriebenes Problem
-   Rick Glaspie von Gilbert Public Schools in Gilbert, Arizona, für den Hinweis auf ein in MS10-038 beschriebenes Problem
-   Rik Jones vom Dallas County Community College District für den Hinweis auf ein in MS10-039 beschriebenes Problem
-   Arian Evans von [WhiteHat Security](http://www.whitehatsec.com) für den Hinweis auf das Umgehungsproblem bei der ASP.NET-Anforderungsüberprüfung, das in MS10-041 durch eine Tiefenverteidigungsänderung behoben wird

#### Support

-   Die betroffene Software wurde getestet, um die betroffenen Versionen zu ermitteln. Andere Versionen haben das Ende ihrer Supportlebenszyklen erreicht. Besuchen Sie die Website [Microsoft Support Lifecycle](http://go.microsoft.com/fwlink/?linkid=21742), um den Supportlebenszyklus für Ihre Softwareversion zu ermitteln.
-   Technischer Support ist über den [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) erhältlich. Supportanrufe zu Sicherheitsupdates sind kostenlos. Weitere Informationen zu verfügbaren Supportoptionen finden Sie auf der [Microsoft-Website „Hilfe und Support“](http://support.microsoft.com/).
-   Kunden außerhalb der USA erhalten Support bei ihren regionalen Microsoft-Niederlassungen. Supportanfragen zu Sicherheitsupdates sind kostenlos. Weitere Informationen dazu, wie Sie Microsoft in Bezug auf Supportfragen kontaktieren können, finden Sie auf der Website [Internationale Hilfe und Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Haftungsausschluss

Die Informationen der Microsoft Knowledge Base werden wie besehen und ohne jede Gewährleistung bereitgestellt. Microsoft schließt alle anderen Garantien, gleich ob ausdrücklich oder konkludent, einschließlich der Garantien der Handelsüblichkeit oder Eignung für einen bestimmten Zweck aus. In keinem Fall kann Microsoft Corporation und/oder deren jeweilige Lieferanten haftbar gemacht werden für Schäden irgendeiner Art, einschließlich direkter, indirekter, zufällig entstandener Schäden, Folgeschäden, Folgen entgangenen Gewinns oder spezieller Schäden, selbst dann nicht, wenn Microsoft Corporation und/oder deren jeweilige Lieferanten auf die mögliche Entstehung dieser Schäden hingewiesen wurde. Weil in einigen Staaten/Rechtsordnungen der Ausschluss oder die Beschränkung einer Haftung für zufällig entstandene Schäden oder Folgeschäden nicht gestattet ist, gilt die obige Einschränkung eventuell nicht für Sie.

#### Revisionen

-   V1.0 (8. Juni 2010): Bulletin Summary veröffentlicht.
-   V1.1 (9. Juni 2010): Die Hinweise für MS10-033 im Abschnitt **Betroffene Software und Downloadadressen** wurden überarbeitet.
-   V2.0 (13. September 2011): Das Bulletin MS10-035 wurde erneut veröffentlicht, um die Updates für Internet Explorer unter Microsoft Windows 2000 und Windows XP erneut anzubieten, um ein Erkennungsproblem zu beheben. Die Dateien des Sicherheitsupdates wurden nicht verändert. Benutzer, die ihre Systeme bereits erfolgreich aktualisiert haben, müssen keine Maßnahmen ergreifen.

*Built at 2014-04-18T01:50:00Z-07:00*
