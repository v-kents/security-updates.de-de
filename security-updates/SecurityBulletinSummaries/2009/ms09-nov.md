---
TOCTitle: 'MS09-NOV'
Title: Microsoft Security Bulletin Summary für November 2009
ms:assetid: 'ms09-nov'
ms:contentKeyID: 61225076
ms:mtpsurl: 'https://technet.microsoft.com/de-DE/library/ms09-nov(v=Security.10)'
---

Security Bulletin Summary

Microsoft Security Bulletin Summary für November 2009
=====================================================

Veröffentlicht: Dienstag, 10. November 2009 | Aktualisiert: Mittwoch, 25. November 2009

**Version:** 1.1

In diesem Bulletin Summary sind die im November 2009 veröffentlichten Security Bulletins aufgeführt.

Mit der Veröffentlichung der Bulletins für November 2009 ersetzt dieses Bulletin Summary die Bulletin Advance Notification, die erstmalig am 5. November 2009 veröffentlicht wurde. Weitere Informationen zum Bulletin Advance Notification-Service finden Sie unter [Microsoft Security Bulletin Advance Notification.](http://www.microsoft.com/germany/technet/sicherheit/bulletins/bulletinadvance.mspx)

Weitere Informationen zum Erhalten automatischer Benachrichtigungen über die Veröffentlichung von Microsoft Security Bulletins finden Sie unter [Microsoft Technische Sicherheitsbenachrichtigungen](http://www.microsoft.com/germany/technet/sicherheit/bulletins/notify.mspx).

Am Mittwoch, den 11. November 2009 um 11:00 Uhr pazifischer Zeit (USA & Kanada) stellt Microsoft einen Webcast bereit, um Kundenfragen zu diesen Bulletins zu beantworten. [Registrieren Sie sich jetzt für das Security Bulletin-Webcast im November.](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032407490&culture=en-us) Ab diesem Datum steht dieser Webcast auf Anfrage zur Verfügung. Weitere Informationen dazu finden Sie unter [Microsoft Security Bulletin Zusammenfassungen und Webcasts.](http://technet.microsoft.com/security/bulletin/summary)

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
<th style="border:1px solid black;" >Neustartanforderung:</th>
<th style="border:1px solid black;" >Betroffene Software</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163840">MS09-063</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit der Webdienste auf Geräte-API kann Remotecodeausführung ermöglichen (973565)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Webdiensten auf Geräte-Anwendungsprogrammierschnittstellen (WSDAPI) im Windows-Betriebssystem. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein betroffenes Windows-System ein speziell gestaltetes Paket erhält. Diese Sicherheitsanfälligkeit kann nur von Angreifern im lokalen Subnetz ausgenutzt werden.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163841">MS09-064</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit im Lizenzprotokollierserver kann Remotecodeausführung ermöglichen (974783)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Windows 2000. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Angreifer eine speziell gestaltete Netzwerknachricht an einen Computer sendet, auf dem der Lizenzprotokollierserver ausgeführt wird. Wenn ein Angreifer diese Sicherheitsanfälligkeit erfolgreich ausnutzt, kann er vollständige Kontrolle über das betroffene System erlangen. Mithilfe empfohlener Vorgehensweisen für die Firewall und standardisierten Firewallkonfigurationen können Netzwerke vor Remoteangriffen von außerhalb des Unternehmens geschützt werden.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=162428">MS09-065</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in Windows-Kernelmodustreibern können Remotecodeausführung ermöglichen (969947)</strong><br />
<br />
Dieses Sicherheitsupdate behebt mehrere vertraulich gemeldete Sicherheitsanfälligkeiten im Windows-Kernel. Die schwerste dieser Sicherheitsanfälligkeiten kann Remotecodeausführung ermöglichen, wenn ein Benutzer Inhalte anzeigt, die in einer speziell gestalteten EOT-Schriftart (Embedded OpenType) dargestellt wurden. In einem webbasierten Angriffsszenario muss ein Angreifer eine Website mit speziell gestalteten eingebetteten Schriftarten einrichten, durch die diese Sicherheitsanfälligkeit ausgenutzt wird. Außerdem können manipulierte Websites und Websites, die von Benutzern bereitgestellte Inhalte akzeptieren oder hosten, speziell gestaltete Inhalte enthalten, über die diese Sicherheitsanfälligkeit ausgenutzt werden kann. Ein Angreifer kann Benutzer nicht zum Besuch einer speziell gestalteten Website zwingen. Stattdessen muss der Angreifer den Benutzer zu einem Besuch dieser Website verleiten. Zu diesem Zweck wird der Benutzer normalerweise dazu gebracht, auf einen Link in einer E-Mail-Nachricht oder Instant Messenger-Nachricht zu klicken, die den Benutzer zur Site des Angreifers führt.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=157862">MS09-066</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in Active Directory kann Denial-of-Service ermöglichen (973309)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit im Active Directory-Verzeichnisdienst, Active Directory Application Mode (ADAM) und Active Directory Lightweight Directory Service (AD LDS). Die Sicherheitsanfälligkeit kann Denial-of-Service ermöglichen, wenn bei der Ausführung bestimmter Arten von LDAP- oder LDAPS-Anforderungen Stackspeicher ausgelastet wird. Diese Sicherheitsanfälligkeit betrifft nur Domänencontroller und Systeme, die für die Ausführung von ADAM oder AD LDS konfiguriert sind.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Hoch</a><br />
DoS (Denial of Service)</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=165431">MS09-067</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in Microsoft Office Excel können Remotecodeausführung ermöglichen (972652)</strong><br />
<br />
Dieses Sicherheitsupdate behebt mehrere vertraulich gemeldete Sicherheitsanfälligkeiten in Microsoft Office Excel. Die Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Excel-Datei öffnet. Ein Angreifer, der diese Sicherheitsanfälligkeiten erfolgreich ausnutzt, kann die gleichen Benutzerrechte wie der lokale Benutzer erlangen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Hoch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=165890">MS09-068</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in Microsoft Office Word kann Remotecodeausführung ermöglichen (976307)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit, die Remotecodeausführung ermöglichen kann, wenn ein Benutzer eine speziell gestaltete Word-Datei öffnet. Nutzt ein Angreifer diese Sicherheitsanfälligkeit erfolgreich aus, kann er die vollständige Kontrolle über ein betroffenes System erlangen. Ein Angreifer kann dann Programme installieren, Daten anzeigen, ändern oder löschen oder neue Konten mit sämtlichen Benutzerrechten erstellen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Hoch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
</tbody>
</table>
  
Ausnutzbarkeitsindex  
--------------------
  
In der folgenden Tabelle wird eine Bewertung der Ausnutzbarkeit aller Sicherheitsanfälligkeiten bereitgestellt, die diesen Monat behoben werden. Die Sicherheitsanfälligkeiten sind nach Kennung des Bulletins und CVE-ID geordnet.
  
**Wie verwende ich diese Tabelle?**  
  
Verwenden Sie diese Tabelle, um etwas über die Wahrscheinlichkeit zu erfahren, dass für die einzelnen Sicherheitsupdates, die Sie möglicherweise installieren müssen, funktionierender Angreifercode veröffentlicht wird. Sie sollten sich unter Berücksichtigung Ihrer konkreten Konfiguration jede der unten stehenden Bewertungen ansehen, um Prioritäten für Ihre Bereitstellung festzulegen. Weitere Informationen zur Bedeutung und Festlegung dieser Bewertungen finden Sie im [Microsoft-Ausnutzbarkeitsindex](http://technet.microsoft.com/en-us/security/cc998259.aspx).
  
| Kennung des Bulletins                                     | Titel der Sicherheitsanfälligkeit                                                                      | CVE-ID                                                                           | Ausnutzbarkeitsindex – Bewertung                                                                                     | Wichtige Hinweise                                                                                                                                                                           |  
|-----------------------------------------------------------|--------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-063](http://go.microsoft.com/fwlink/?linkid=163840) | Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Webdiensten auf Geräte-API                   | [CVE-2009-2512](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2512) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | Das Szenario lässt einen möglichen, begrenzten Denial-of-Service-Angriff zu.                                                                                                                |  
| [MS09-064](http://go.microsoft.com/fwlink/?linkid=163841) | Sicherheitsanfälligkeit bezüglich Heapüberlaufs im Lizenzprotokollierserver                            | [CVE-2009-2523](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2523) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | Für den Angriff ist eine Racebedingung erforderlich, die schwierig auszunutzen ist. Bei allen Angriffsmethoden außer Denial-of-Service wird davon ausgegangen, dass sie unzuverlässig sind. |  
| [MS09-065](http://go.microsoft.com/fwlink/?linkid=162428) | Sicherheitsanfälligkeit in Win32k bezüglich NULL-Zeigerdereferenzierung                                | [CVE-2009-1127](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1127) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                                                                                                                     |  
| [MS09-065](http://go.microsoft.com/fwlink/?linkid=162428) | Sicherheitsanfälligkeit in Win32k bezüglich unzureichender Datenüberprüfung                            | [CVE-2009-2513](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2513) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                                                     |  
| [MS09-065](http://go.microsoft.com/fwlink/?linkid=162428) | Sicherheitsanfälligkeit in Win32k bezüglich EOT-Analyse                                                | [CVE-2009-2514](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2514) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                                                     |  
| [MS09-066](http://go.microsoft.com/fwlink/?linkid=157862) | Sicherheitsanfälligkeit in LSASS bezüglich rekursiven Stapelüberlaufs                                  | [CVE-2009-1928](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-1928) | [**3**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Funktionierender Angreifercode unwahrscheinlich | Die Bedingung für Denial-of-Service ist vorhanden.                                                                                                                                          |  
| [MS09-067](http://go.microsoft.com/fwlink/?linkid=165431) | Sicherheitsanfälligkeit bezüglich Beschädigung des Cachespeichers in Excel                             | [CVE-2009-3127](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3127) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                                                                                                                     |  
| [MS09-067](http://go.microsoft.com/fwlink/?linkid=165431) | Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Excel SxView                                 | [CVE-2009-3128](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3128) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                                                                                                                     |  
| [MS09-067](http://go.microsoft.com/fwlink/?linkid=165431) | Sicherheitsanfälligkeit bezüglich Speicherbeschädigung im Featheader-Datensatz von Excel               | [CVE-2009-3129](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3129) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                                                     |  
| [MS09-067](http://go.microsoft.com/fwlink/?linkid=165431) | Sicherheitsanfälligkeit bezüglich Heapüberlaufs beim Analysieren von Excel-Dokumenten                  | [CVE-2009-3130](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3130) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                                                     |  
| [MS09-067](http://go.microsoft.com/fwlink/?linkid=165431) | Sicherheitsanfälligkeit bezüglich Speicherbeschädigung beim Analysieren von Excel-Formeln              | [CVE-2009-3131](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3131) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                                                     |  
| [MS09-067](http://go.microsoft.com/fwlink/?linkid=165431) | Sicherheitsanfälligkeit in Excel beim Analysieren des Index                                            | [CVE-2009-3132](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3132) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                                                                                                                     |  
| [MS09-067](http://go.microsoft.com/fwlink/?linkid=165431) | Sicherheitsanfälligkeit bezüglich Speicherbeschädigung beim Analysieren von Excel-Dokumenten           | [CVE-2009-3133](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3133) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                                                                                                                     |  
| [MS09-067](http://go.microsoft.com/fwlink/?linkid=165431) | Sicherheitsanfälligkeit in Excel bei Feldbereinigung                                                   | [CVE-2009-3134](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3134) | [**2**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                                                                                                                     |  
| [MS09-068](http://go.microsoft.com/fwlink/?linkid=165890) | Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in Dateiinformationen von Microsoft Office Word | [CVE-2009-3135](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3135) | [**1**](http://technet.microsoft.com/en-us/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                                                     |
  
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
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-063**](http://go.microsoft.com/fwlink/?linkid=163840)
</td>
<td style="border:1px solid black;">
[**MS09-064**](http://go.microsoft.com/fwlink/?linkid=163841)
</td>
<td style="border:1px solid black;">
[**MS09-065**](http://go.microsoft.com/fwlink/?linkid=162428)
</td>
<td style="border:1px solid black;">
[**MS09-066**](http://go.microsoft.com/fwlink/?linkid=157862)
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
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Server Service Pack 4:](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=365a8dff-2383-42f6-b567-e545461fd135)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=45db8bb1-c81b-4d3f-a658-74f5fa445f81)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Active Directory unter Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=297158cf-374c-45d9-b213-978e1f54d244)  
(KB973037)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-063**](http://go.microsoft.com/fwlink/?linkid=163840)
</td>
<td style="border:1px solid black;">
[**MS09-064**](http://go.microsoft.com/fwlink/?linkid=163841)
</td>
<td style="border:1px solid black;">
[**MS09-065**](http://go.microsoft.com/fwlink/?linkid=162428)
</td>
<td style="border:1px solid black;">
[**MS09-066**](http://go.microsoft.com/fwlink/?linkid=157862)
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
Keine
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2 und Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 und Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=916abdad-44b7-4f9d-986a-0c3558fb8e06)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=cbe09780-f288-457a-b254-58c9c8744055)  
(KB973039)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=1d0464c6-5ed8-4064-887e-618a2db09236)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?familyid=b65ddf36-a02d-4aa2-9b4f-7416dbf59e2a)  
(KB973039)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-063**](http://go.microsoft.com/fwlink/?linkid=163840)
</td>
<td style="border:1px solid black;">
[**MS09-064**](http://go.microsoft.com/fwlink/?linkid=163841)
</td>
<td style="border:1px solid black;">
[**MS09-065**](http://go.microsoft.com/fwlink/?linkid=162428)
</td>
<td style="border:1px solid black;">
[**MS09-066**](http://go.microsoft.com/fwlink/?linkid=157862)
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
Keine
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=5cd62750-e269-44ae-8c7c-c335e8545b9a)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=28f1c494-4e16-43b6-93d2-49e15f142ac9)  
(KB973037)  
(Hoch)  
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=44cb9029-4b19-4bad-8fc9-3efe285adb0e)  
(KB973039)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=04a7f817-f330-4003-8b25-d3e744905b12)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=509aeec0-112b-44ab-8686-43f381b61940)  
(KB973037)  
(Hoch)  
[Active Directory Application Mode (ADAM)](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=87f2109e-5129-467c-930f-70af31ebf5de)  
(KB973039)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 mit SP2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=b95daac0-4c99-47a4-b0ca-9429997ea3d9)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Active Directory](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=040e691b-1ef0-4b73-bef7-a1d77b84b0ca)  
(KB973037)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-063**](http://go.microsoft.com/fwlink/?linkid=163840)
</td>
<td style="border:1px solid black;">
[**MS09-064**](http://go.microsoft.com/fwlink/?linkid=163841)
</td>
<td style="border:1px solid black;">
[**MS09-065**](http://go.microsoft.com/fwlink/?linkid=162428)
</td>
<td style="border:1px solid black;">
[**MS09-066**](http://go.microsoft.com/fwlink/?linkid=157862)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista, Windows Vista Service Pack 1 und Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 und Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=ebf0c294-cd99-445a-a741-78253e47189f)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Vista, Windows Vista Service Pack 1 und Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=54562103-1d99-42d7-8f7f-c0cbcdce90db)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 und Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 und Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=d9645fc9-f524-43f1-8b8c-94b3b4312158)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 und Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=fcb87cc8-6fd7-4f16-93d6-552999462fb1)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-063**](http://go.microsoft.com/fwlink/?linkid=163840)
</td>
<td style="border:1px solid black;">
[**MS09-064**](http://go.microsoft.com/fwlink/?linkid=163841)
</td>
<td style="border:1px solid black;">
[**MS09-065**](http://go.microsoft.com/fwlink/?linkid=162428)
</td>
<td style="border:1px solid black;">
[**MS09-066**](http://go.microsoft.com/fwlink/?linkid=157862)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme und Windows Server 2008 für 32-Bit-Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme und Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=d6a60883-b103-459a-a91b-cd6ed946cefe)\*  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme und Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=b97d48de-0f6d-4bca-b990-acf543fdb8b7)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
[Active Directory und Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=701abf15-7f93-41de-8d09-13404fd79a7e)\*  
(KB973037)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für x64-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=3dde1587-42d3-438f-8344-696a5657b9b1)\*  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=0e2b8607-10fa-406a-96a5-18290f479c48)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
[Active Directory und Active Directory Lightweight Directory Service (AD LDS)](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=17f5f9e0-5869-41da-9b3b-6e67540af1f0)\*  
(KB973037)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme und Windows Server 2008 für Itanium-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für Itanium-basierte Systeme und Windows Server 2008 für Itanium-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=841a027f-22fa-42de-93b3-57a3fe92a1d3)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für Itanium-basierte Systeme und Windows Server 2008 für Itanium-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=28eba3f3-99a5-424c-bc8d-a718c716699e)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
</table>
 
**Hinweis für Windows Server 2008 und Windows Server 2008 R2**

**\*Die Server Core-Installation ist betroffen.** Dieses Update gilt, mit der gleichen Bewertung des Schweregrads, wie angezeigt auch für unterstützte Editionen von Windows Server 2008 oder Windows Server 2008 R2, unabhängig davon, ob bei der Installation die Server Core-Installationsoption verwendet wurde oder nicht. Weitere Informationen zu dieser Installationsoption finden Sie in den MSDN-Artikeln [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) und [Server Core für Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx). Beachten Sie, dass die Server Core-Installationsoption für bestimmte Editionen von Windows Server 2008 und Windows Server 2008 R2 nicht gilt; siehe dazu [Vergleichen von Server Core-Installationsoptionen](http://www.microsoft.com/germany/windowsserver2008/editionen/r2-vergleich-server-core.mspx).

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
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office Suites, Systeme und Komponenten
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-067**](http://go.microsoft.com/fwlink/?linkid=165431)
</td>
<td style="border:1px solid black;">
[**MS09-068**](http://go.microsoft.com/fwlink/?linkid=165890)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=5672c8fc-8509-4962-ad86-ebc0f2575043)  
(KB973471)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2002 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=0369fae5-958b-4eba-83a4-9c07e701c273&displaylang=de)  
(KB973444)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=6a6a0f5d-17dc-4a34-b9a0-0774aa287ba5)  
(KB973475)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Office Word 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=6b77bc62-bcbb-4b9a-97d1-a49ca0582e54)  
(KB973443)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office System 2007
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel 2007 Service Pack 1 und Microsoft Office Excel 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=322b24ca-aff6-4ca0-acf1-440cae0f9693)<sup>[1]</sup>
(KB973593)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Office für Mac
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-067**](http://go.microsoft.com/fwlink/?linkid=165431)
</td>
<td style="border:1px solid black;">
[**MS09-068**](http://go.microsoft.com/fwlink/?linkid=165890)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 für Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 für Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=8f115b1c-1e28-4ecf-937c-99c4b60c7c8e)  
(KB976830)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2004 für Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=8f115b1c-1e28-4ecf-937c-99c4b60c7c8e)  
(KB976830)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2008 für Mac
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 für Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=b84fe57d-ddda-451e-9ead-69e10aee7928)  
(KB976828)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Office 2008 für Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=b84fe57d-ddda-451e-9ead-69e10aee7928)  
(KB976828)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Open XML-Dateiformatkonverter für Mac
</td>
<td style="border:1px solid black;">
[Open XML-Dateiformatkonverter für Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=4dd4bc05-1217-497e-8f65-4347f2544ed6)  
(KB976831)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Open XML-Dateiformatkonverter für Mac](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=4dd4bc05-1217-497e-8f65-4347f2544ed6)  
(KB976831)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Andere Microsoft Office-Software
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-067**](http://go.microsoft.com/fwlink/?linkid=165431)
</td>
<td style="border:1px solid black;">
[**MS09-068**](http://go.microsoft.com/fwlink/?linkid=165890)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Excel Viewer 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=19151e22-5642-456c-bd39-298574369cdb)  
(KB973484)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Excel Viewer
</td>
<td style="border:1px solid black;">
[Microsoft Office Excel Viewer Service Pack 1 und Microsoft Office Excel Viewer Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=fb36df5e-ebef-46bf-9edd-67f2c76dbdb3)  
(KB973707)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Word Viewer 2003
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=4cc5e6c5-7efb-4180-9a9b-0788115c91e1)  
(KB973866)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Word Viewer
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Office Word Viewer](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=4cc5e6c5-7efb-4180-9a9b-0788115c91e1)  
(KB973866)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack für die Dateiformate von Word, Excel und PowerPoint 2007
</td>
<td style="border:1px solid black;">
[Microsoft Office Compatibility Pack für die Dateiformate von Word, Excel und PowerPoint 2007 Service Pack 1 und Microsoft Office Compatibility Pack für die Dateiformate von Word, Excel und PowerPoint 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=c4c92d2e-e87d-446f-8d3e-8f4be10c70aa)  
(KB973704)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
</table>
 
**Hinweis für MS09-067**

<sup>[1]</sup>Für Microsoft Office Excel 2007 Service Pack 1 und Microsoft Office Excel 2007 Service Pack 2 müssen Benutzer zusätzlich zum Sicherheitsupdatepaket KB973593 auch das Sicherheitsupdate für [Microsoft Office Compatibility Pack für die Dateiformate von Word, Excel und PowerPoint 2007 Service Pack 1 und Microsoft Office Compatibility Pack für die Dateiformate von Word, Excel und PowerPoint 2007 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=c4c92d2e-e87d-446f-8d3e-8f4be10c70aa) (KB973704) installieren, um vor den in diesem Bulletin beschriebenen Sicherheitsanfälligkeiten geschützt zu sein.

Tools und Anleitungen zur Erkennung und Bereitstellung
------------------------------------------------------

**Sicherheitsportal:**

Verwalten Sie die Software und die Sicherheitsupdates, die Sie den Servern, Desktops und mobilen Computer in Ihrer Organisation bereitstellen müssen. Weitere Informationen finden Sie im [TechNet Update Management Center](http://technet.microsoft.com/de-de/updatemanagement/default.aspx). Im [TechNet Sicherheits-Center](http://www.microsoft.com/germany/technet/sicherheit/default.mspx) werden zusätzliche Informationen zur Sicherheit in Microsoft-Produkten zur Verfügung gestellt. Verbraucher können die Seite [Sicherheit zu Hause](http://www.microsoft.com/germany/athome/security/default.mspx) besuchen, wo diese Informationen auch durch einen Klick auf „Die neuesten Sicherheitsupdates“ verfügbar sind.

Sicherheitsupdates sind unter [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) und [Windows-Update](http://go.microsoft.com/fwlink/?linkid=21130) verfügbar. Sicherheitsupdates sind auch im [Microsoft Download Center](http://www.microsoft.com/downloads/results.aspx?displaylang=de&freetext=sicherheitsupdate) verfügbar. Sie können am einfachsten durch eine Suche nach dem Begriff „security update“ ermittelt werden.

Außerdem können Sicherheitsupdates vom [Windows Update-Katalog](http://go.microsoft.com/fwlink/?linkid=96155) heruntergeladen werden. Der Microsoft Update-Katalog stellt einen durchsuchbaren Katalog der Inhalte bereit, die über Windows Update und Microsoft Update zur Verfügung gestellt werden, einschließlich Sicherheitsupdates, Treiber und Service Packs. Indem Sie mit der Nummer des Security Bulletins suchen (z. B. „MS07-036“), können Sie Ihrem Warenkorb alle anwendbaren Updates (einschließlich verschiedener Sprachen für ein Update) hinzufügen und in den Ordner Ihrer Wahl herunterladen. Weitere Informationen zum Microsoft Update-Katalog, finden Sie unter [Häufig gestellte Fragen zum Microsoft Update-Katalog](http://catalog.update.microsoft.com/v7/site/faq.aspx).

**Hinweis:** Am 1. August 2009 hat Microsoft den Support für Office Update und das Inventurprogramm für Office-Update eingestellt. Verwenden Sie [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), um weiterhin die aktuellen Updates für Microsoft Office-Produkte zu erhalten. Weitere Informationen finden Sie in [Informationen zum Microsoft Office Update: Häufig gestellte Fragen (FAQs)](http://office.microsoft.com/de-de/downloads/fx010402221031.aspx).

**Anleitungen zur Erkennung und Bereitstellung**

Microsoft stellt Anleitungen zur Erkennung und Bereitstellung von Sicherheitsupdates bereit. Diese Anleitungen enthalten Empfehlungen und Informationen, anhand derer IT-Experten verstehen können, wie die verschiedenen Tools für die Erkennung und Bereitstellung der Sicherheitsupdates verwendet werden. Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 961747](http://support.microsoft.com/kb/961747/de).

**Microsoft Baseline Security Analyzer**

Der Microsoft Baseline Security Analyzer (MBSA) ermöglicht Administratoren die Überprüfung von lokalen und Remotesystemen im Hinblick auf fehlende Sicherheitsupdates sowie auf häufig falsch konfigurierte Sicherheitsparameter. Weitere Informationen zu MBSA finden Sie auf der Website [Microsoft Baseline Security Analyzer](http://www.microsoft.com/germany/technet/sicherheit/tools/mbsa/2_0.mspx).

**Windows Server Update Services**

Mithilfe der Windows Server Update Services (WSUS), können Administratoren die neuesten wichtigen Aktualisierungen und Sicherheitsupdates für Windows 2000 und höher, Office XP und höher, Exchange Server 2003 und SQL Server 2000 für Windows 2000 und neuere Betriebssysteme schnell und zuverlässig bereitstellen.

Weitere Informationen zum Bereitstellen dieses Sicherheitsupdates mithilfe der Windows Server Update Services finden Sie auf der [Windows Server Update Services Website](http://www.microsoft.com/germany/technet/prodtechnol/windowsserver/wsus/default.mspx).

**Systems Management Server**

Der Systems Management Server von Microsoft stellt eine wertvolle Hilfe beim Bereitstellen von Sicherheitsupdates in Ihrer IT-Umgebung dar. Durch die Verwendung von SMS können Administratoren auf Windows basierte Systeme identifizieren, für die Sicherheitsupdates erforderlich sind, und für eine kontrollierte Bereitstellung dieser Updates im gesamten Unternehmen bei minimalen Unterbrechungen für Endbenutzer sorgen. Die nächste Version von SMS, System Center Configuration Manager 2007, ist jetzt verfügbar (siehe auch [System Center Configuration Manager 2007](http://technet.microsoft.com/en-us/library/bb735860.aspx)). Weitere Informationen zur Verwendung von SMS 2003 durch Administratoren für die Bereitstellung von Sicherheitsupdates finden Sie unter [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). Benutzer von SMS 2.0 können auch das Sicherheitsupdate-Inventurprogramm (SUIT) verwenden, um Hilfe bei der Bereitstellung von Sicherheitsupdates zu erhalten. Weitere Informationen zu SMS finden Sie auf der Website [Microsoft Systems Management Server](http://www.microsoft.com/germany/systemcenter/sccm/default.mspx).

**Hinweis:** SMS verwendet den Microsoft Baseline Security Analyzer für eine breite Unterstützung bei der Erkennung und der Bereitstellung von Security Bulletin-Updates. Einige Softwareupdates werden von diesen Tools möglicherweise nicht erkannt. Administratoren können in diesen Fällen die Inventurfunktionen von SMS nutzen, um Updates auf ausgewählten Systemen zu installieren. Weitere Informationen zu diesem Verfahren finden Sie auf der Website [Bereitstellen von Softwareupdates mit der Funktion zur Softwareverteilung von SMS](http://www.microsoft.com/technet/sms/2003/patchupdate.mspx). Bei einigen Sicherheitsupdates, die einen Neustart des Systems erfordern, sind unter Umständen administrative Rechte nötig. Administratoren können das im [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=de) und im [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161) enthaltene Elevated Rights Deployment Tool verwenden, um diese Updates zu installieren.

**Updatekompatibilitätsbewertung und Microsoft Application Compatibility Toolkit**

Updates bearbeiten oft dieselben Dateien und Registrierungseinstellungen, die zum Ausführen Ihrer Anwendungen benötigt werden. Dies kann eine Inkompatibilität auslösen und die Bereitstellung von Sicherheitsupdates verzögern. Mit den Komponenten zur [Updatekompatibilitätsbewertung](http://technet.microsoft.com/de-de/library/cc766043(ws.10).aspx), die im [Anwendungskompatibilitäts-Toolkit](http://www.microsoft.com/downloads/details.aspx?familyid=24da89e9-b581-47b0-b45e-492dd6da2971&displaylang=en) enthalten sind, können Sie die Vereinbarkeit von Windows-Updates mit installierten Anwendungen testen und überprüfen.

Das Microsoft Application Compatibility Toolkit (ACT) enthält alle notwendigen Tools und Dokumentationen, um die Anwendungskompatibilität zu prüfen und eventuelle Probleme zu beheben, bevor Microsoft Windows Vista, ein Windows-Update, ein Microsoft-Sicherheitsupdate oder eine neue Version von Windows Internet Explorer in Ihrer Umgebung bereitgestellt wird.

### Weitere Informationen:

#### Windows-Tool zum Entfernen schädlicher Software

Microsoft hat eine aktualisierte Version des Microsoft Windows-Tools zum Entfernen bösartiger Software in Windows Update, Microsoft Update, Windows Server Update Services und dem Download Center veröffentlicht.

#### Nicht sicherheitsrelevante, wichtige Updates unter MU, WU und WSUS:

Weitere Informationen zu nicht sicherheitsrelevanten Veröffentlichungen auf Windows-Update und Microsoft Update finden Sie unter:

-   [Microsoft Knowledge Base-Artikel 894199](http://support.microsoft.com/kb/894199/de): Beschreibung der Änderungen an den Inhalten von Software Update Services und Windows Server Update Services. Umfasst alle Windows-Inhalte.
-   [Updates für Windows Server Update Services aus den vergangenen Monaten](http://technet.microsoft.com/en-us/wsus/bb456965.aspx). Zeigt alle neuen, überarbeiteten und veröffentlichten Updates für andere Microsoft-Produkte als Microsoft Windows an.

#### Microsoft Active Protections Program (MAPP)

Um den Sicherheitsschutz für Benutzer zu verbessern, stellt Microsoft den wichtigsten Sicherheitssoftwareanbietern vor der monatlichen Veröffentlichung der Sicherheitsupdates Informationen zu Sicherheitsanfälligkeiten bereit. Anbieter von Sicherheitssoftware können diese Informationen zu Sicherheitsanfälligkeiten dann verwenden, um Benutzern aktualisierten Schutz über ihre Sicherheitssoftware oder ihre Geräte bereitzustellen, z. B. Antivirus, netzwerkbasierte Angriffserkennungssysteme oder hostbasierte Angriffsverhinderungssysteme. Wenn Sie erfahren möchten, ob von den Sicherheitssoftwareanbietern aktiver Schutz verfügbar ist, besuchen Sie die von den Programmpartnern bereitgestellte Active Protections-Websites, die unter [MAPP-Partner (Microsoft Active Protections Program)](http://www.microsoft.com/security/msrc/mapp/partners.mspx) aufgeführt sind.

#### Sicherheitsstrategien und Community

**Strategien für die Verwaltung von Sicherheitspatches:**

Auf der Seite [Patchmanagement](http://www.microsoft.com/germany/technet/sicherheit/themen/patchmanagement.mspx) werden zusätzliche Informationen zu den empfohlenen Vorgehensweisen für die Anwendung von Sicherheitsupdates von Microsoft bereitgestellt.

**Weitere Sicherheitsupdates**

Updates für andere Sicherheitsrisiken sind unter den folgenden Adressen erhältlich:

-   Sicherheitsupdates sind im [Microsoft Download Center](http://www.microsoft.com/downloads/results.aspx?displaylang=de&freetext=sicherheitsupdate) verfügbar. Sie können am einfachsten durch eine Suche nach dem Begriff „security update“ ermittelt werden.
-   Updates für Benutzerplattformen sind auf [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747) verfügbar.
-   Die Sicherheitsupdates, die in diesem Monat über Windows Update veröffentlicht wurden, können Sie auch im „Security and Critical Releases ISO CD Image“ über Microsoft Download Center erhalten. Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 913086](http://support.microsoft.com/kb/913086/de).

**IT Pro Security Community:**

Erfahren Sie, wie Sie die Sicherheit Ihrer IT-Umgebung erhöhen und Ihren IT-Betrieb optimieren können. Diskutieren Sie auf der [IT Pro Security Zone](http://go.microsoft.com/fwlink/?linkid=21164) Website mit anderen IT-Profis über das Thema Sicherheit.

#### Danksagungen

Microsoft [dankt](http://www.microsoft.com/germany/technet/sicherheit/bulletins/policy.mspx) den folgenden Personen, dass sie zum Schutz unserer Kunden mit uns zusammengearbeitet haben:

-   Neel Mehta von [Google Inc.](http://www.google.com/) für den Hinweis auf ein in MS09-063 beschriebenes Problem.
-   Cody Pierce von [TippingPoint DVLabs](http://dvlabs.tippingpoint.com/) für den Hinweis auf ein in MS09-064 beschriebenes Problem.
-   Agin Sun für den Hinweis auf ein in MS09-065 beschriebenes Problem.
-   Tavis Ormandy von [Google Inc.](http://www.google.com/) für den Hinweis auf ein in MS09-065 beschriebenes Problem.
-   Bing Liu von [Fortinets FortiGuard Labs](http://www.fortiguard.com/) für den Hinweis auf drei in MS09-067 beschriebene Probleme.
-   [TippingPoint](http://www.tippingpoint.com/) und [Zero Day Initiative](http://www.zerodayinitiative.com/) für den Hinweis auf ein in MS09-067 beschriebenes Problem.
-   Sean Larsson von [VeriSign iDefense Labs](http://labs.idefense.com/) für den Hinweis auf ein in MS09-067 beschriebenes Problem.
-   Einer Person, die mit [TippingPoint](http://www.tippingpoint.com/) und [Zero Day Initiative](http://www.zerodayinitiative.com/) zusammenarbeitet, aber anonym bleiben möchte, für den Hinweis auf ein in MS09-067 beschriebenes Problem.
-   Nicolas Joly von [VUPEN Security](http://www.vupen.com/) für den Hinweis auf ein in MS09-067 beschriebenes Problem.
-   Jun Mao von [VeriSign iDefense Labs](http://labs.idefense.com/) für den Hinweis auf ein in MS09-068 beschriebenes Problem.

#### Support

-   Die betroffene Software wurde getestet, um die betroffenen Versionen zu ermitteln. Andere Versionen haben das Ende ihrer Supportlebenszyklen erreicht. Besuchen Sie die Website [Microsoft Support Lifecycle](http://support.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle), um den Supportlebenszyklus für Ihre Softwareversion zu ermitteln.
-   Technischer Support ist über den [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) erhältlich. Supportanrufe zu Sicherheitsupdates sind kostenlos. Weitere Informationen zu verfügbaren Supportoptionen finden Sie auf der [Microsoft-Website „Hilfe und Support“](http://support.microsoft.com/).
-   Kunden außerhalb der USA erhalten Support bei ihren regionalen Microsoft-Niederlassungen. Supportanfragen zu Sicherheitsupdates sind kostenlos. Weitere Informationen dazu, wie Sie Microsoft in Bezug auf Supportfragen kontaktieren können, finden Sie auf der Website [Internationale Hilfe und Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Haftungsausschluss

Die Informationen der Microsoft Knowledge Base werden wie besehen und ohne jede Gewährleistung bereitgestellt. Microsoft schließt alle anderen Garantien, gleich ob ausdrücklich oder konkludent, einschließlich der Garantien der Handelsüblichkeit oder Eignung für einen bestimmten Zweck aus. In keinem Fall kann Microsoft Corporation und/oder deren jeweilige Lieferanten haftbar gemacht werden für Schäden irgendeiner Art, einschließlich direkter, indirekter, zufällig entstandener Schäden, Folgeschäden, Folgen entgangenen Gewinns oder spezieller Schäden, selbst dann nicht, wenn Microsoft Corporation und/oder deren jeweilige Lieferanten auf die mögliche Entstehung dieser Schäden hingewiesen wurde. Weil in einigen Staaten/Rechtsordnungen der Ausschluss oder die Beschränkung einer Haftung für zufällig entstandene Schäden oder Folgeschäden nicht gestattet ist, gilt die obige Einschränkung eventuell nicht für sie.

#### Revisionen

-   V1.0 (10. November 2009): Bulletin Summary veröffentlicht.
-   V1.1 (25. November 2009): Dem Ausnutzbarkeitsindex für CVE-2009-2523 wurde ein wichtiger Hinweis hinzugefügt.

*Built at 2014-04-18T01:50:00Z-07:00*
