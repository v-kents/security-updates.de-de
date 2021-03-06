---
TOCTitle: 'MS09-DEC'
Title: Microsoft Security Bulletin Summary für Dezember 2009
ms:assetid: 'ms09-dec'
ms:contentKeyID: 61225069
ms:mtpsurl: 'https://technet.microsoft.com/de-DE/library/ms09-dec(v=Security.10)'
---

Security Bulletin Summary

Microsoft Security Bulletin Summary für Dezember 2009
=====================================================

Veröffentlicht: Dienstag, 8. Dezember 2009 | Aktualisiert: Mittwoch, 13. Januar 2010

**Version:** 2.0

In diesem Bulletin Summary sind die im Dezember 2009 veröffentlichten Security Bulletins aufgeführt.

Mit der Veröffentlichung der Bulletins für Dezember 2009 ersetzt dieses Bulletin Summary die Bulletin Advance Notification, die erstmalig am 3. Dezember 2009 veröffentlicht wurde. Weitere Informationen zum Bulletin Advance Notification-Service finden Sie unter [Microsoft Security Bulletin Advance Notification](http://www.microsoft.com/germany/technet/sicherheit/bulletins/bulletinadvance.mspx).

Weitere Informationen zum Erhalten automatischer Benachrichtigungen über die Veröffentlichung von Microsoft Security Bulletins finden Sie unter [Microsoft Technische Sicherheitsbenachrichtigungen](http://www.microsoft.com/germany/technet/sicherheit/bulletins/notify.mspx).

Am Mittwoch, den 9. Dezember 2009 um 11:00 Uhr pazifischer Zeit (USA & Kanada) stellt Microsoft einen Webcast bereit, um Kundenfragen zu diesen Bulletins zu beantworten. [Registrieren Sie sich jetzt für den Security Bulletin-Webcast im Dezember.](http://msevents.microsoft.com/cui/eventdetail.aspx?eventid=1032407802&culture=en-us) Ab diesem Datum steht dieser Webcast auf Anfrage zur Verfügung. Weitere Informationen dazu finden Sie unter [Microsoft Security Bulletin Zusammenfassungen und Webcasts.](http://technet.microsoft.com/security/bulletin/summary)

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
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=177727">MS09-071</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten im Internetauthentifizierungsdienst können Remotecodeausführung ermöglichen (974318)</strong><br />
<br />
Dieses Sicherheitsupdate behebt zwei vertraulich gemeldete Sicherheitsanfälligkeiten in Microsoft Windows. Die schwereren Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn vom Internetauthentifizierungsdienst-Server empfangene Nachrichten beim Verarbeiten von PEAP-Authentifizierungsversuchen falsch in den Speicher kopiert werden. Unter Windows Server 2008 wird der Internetauthentifizierungsdienst durch Netzwerkrichtlinienserver (NPS) ersetzt. Ein Angreifer, dem es gelingt, eine dieser Sicherheitsanfälligkeiten auszunutzen, kann vollständige Kontrolle über das betroffene System erlangen. Server mit Internetauthentifizierungsdienst oder Netzwerkrichtlinienserver sind nur betroffen, wenn PEAP mit MS-CHAP v2-Authentifizierung verwendet wird.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=141642">MS09-074</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in Microsoft Office Project kann Remotecodeausführung ermöglichen (967183)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Office Project. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Project-Datei öffnet. Nutzt ein Angreifer diese Sicherheitsanfälligkeit erfolgreich aus, kann er die vollständige Kontrolle über ein betroffenes System erlangen. Ein Angreifer kann dann Programme installieren, Daten anzeigen, ändern oder löschen oder neue Konten mit sämtlichen Benutzerrechten erstellen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Office</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=169404">MS09-072</a></td>
<td style="border:1px solid black;"><strong>Kumulatives Sicherheitsupdate für Internet Explorer (976325)</strong><br />
<br />
Dieses Sicherheitsupdate behebt vier vertraulich gemeldete Sicherheitsanfälligkeiten und eine öffentlich gemeldete Sicherheitsanfälligkeit in Internet Explorer. Wenn ein Benutzer eine speziell gestaltete Webseite mit Internet Explorer anzeigt, können diese Sicherheitsanfälligkeiten Remotecodeausführung ermöglichen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten. Ein mit ATL-Headern (Microsoft Active Template Library) erstelltes ActiveX-Steuerelement kann auch Remotecodeausführung ermöglichen. Diese Sicherheitsanfälligkeit ist in der Microsoft-Sicherheitsempfehlung 973882 und im Microsoft Security Bulletin MS09-035 beschrieben.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Kritisch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=177555">MS09-069</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit im Subsystemdienst für die lokale Sicherheitsautorität kann Denial-of-Service ermöglichen (974392)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft Windows. Die Sicherheitsanfälligkeit kann Denial-of-Service ermöglichen, wenn ein authentifizierter Remoteangreifer während der Kommunikation durch IPSec (Internet Protocol Security) eine speziell gestaltete ISAKMP-Nachricht an den LSASS-Dienst (Local Security Authority Subsystem Service) auf einem betroffenen System sendet.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Hoch</a><br />
DoS (Denial of Service)</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="odd">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163844">MS09-070</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeiten in den Active Directory-Verbunddiensten können Remotecodeausführung ermöglichen (971726)</strong><br />
<br />
Dieses Sicherheitsupdate behebt zwei vertraulich gemeldete Sicherheitsanfälligkeiten in Microsoft Windows. Die schwerere dieser Sicherheitsanfälligkeiten kann Remotecodeausführung ermöglichen, wenn ein Angreifer einem ADFS-fähigen Webserver eine speziell gestaltete HTTP-Anforderung sendet. Ein Angreifer muss ein authentifizierter Benutzer sein, um eine dieser Sicherheitsanfälligkeiten auszunutzen.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Hoch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert Neustart</td>
<td style="border:1px solid black;">Microsoft Windows</td>
</tr>
<tr class="even">
<td style="border:1px solid black;"><a href="http://go.microsoft.com/fwlink/?linkid=163833">MS09-073</a></td>
<td style="border:1px solid black;"><strong>Sicherheitsanfälligkeit in WordPad- und Office-Textkonvertern kann Remotecodeausführung ermöglichen (975539)</strong><br />
<br />
Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in Microsoft WordPad- und Microsoft Office-Textkonvertern. Die Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn eine speziell gestaltete Word 97-Datei in WordPad oder Microsoft Office Word geöffnet wird. Ein Angreifer, der diese Sicherheitsanfälligkeit erfolgreich ausnutzt, kann die gleichen Berechtigungen wie der betreffende Benutzer erlangen. Für Benutzer, deren Konten mit geringeren Systemrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit Administratorberechtigungen arbeiten.</td>
<td style="border:1px solid black;"><a href="http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx">Hoch</a><br />
Remotecodeausführung</td>
<td style="border:1px solid black;">Erfordert u. U. Neustart</td>
<td style="border:1px solid black;">Microsoft Windows, Microsoft Office</td>
</tr>
</tbody>
</table>
  
Ausnutzbarkeitsindex  
--------------------
  
In der folgenden Tabelle wird eine Bewertung der Ausnutzbarkeit aller Sicherheitsanfälligkeiten bereitgestellt, die diesen Monat behoben werden. Die Sicherheitsanfälligkeiten sind nach Kennung des Bulletins und CVE-ID geordnet.
  
**Wie verwende ich diese Tabelle?**  
  
Verwenden Sie diese Tabelle, um etwas über die Wahrscheinlichkeit zu erfahren, dass für die einzelnen Sicherheitsupdates, die Sie möglicherweise installieren müssen, funktionierender Angreifercode veröffentlicht wird. Sie sollten sich unter Berücksichtigung Ihrer konkreten Konfiguration jede der unten stehenden Bewertungen ansehen, um Prioritäten für Ihre Bereitstellung festzulegen. Weitere Informationen zur Bedeutung und Festlegung dieser Bewertungen finden Sie im [Microsoft-Ausnutzbarkeitsindex](http://technet.microsoft.com/de-de/security/cc998259.aspx).
  
| Kennung des Bulletins                                     | Titel der Sicherheitsanfälligkeit                                                                         | CVE-ID                                                                           | Ausnutzbarkeitsindex – Bewertung                                                                                     | Wichtige Hinweise                                                                                                                                                                                                                                                                                               |  
|-----------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|  
| [MS09-069](http://go.microsoft.com/fwlink/?linkid=177555) | Sicherheitsanfälligkeit im Subsystemdienst für die lokale Sicherheitsautorität bzgl. Ressourcenauslastung | [CVE-2009-3675](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3675) | [**3**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Funktionierender Angreifercode unwahrscheinlich | Die Sicherheitsanfälligkeit ermöglicht keine Remotecodeausführung, nur Denial-of-Service; dies kann von einem authentifizierten Remoteangreifer ausgenutzt werden.                                                                                                                                              |  
| [MS09-070](http://go.microsoft.com/fwlink/?linkid=163844) | Sicherheitsanfälligkeit in ADFS bzgl. Spoofing der einmaligen Anmeldung                                   | [CVE-2009-2508](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2508) | [**3**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Funktionierender Angreifercode unwahrscheinlich | Die Sicherheitsanfälligkeit ermöglicht keine Remotecodeausführung, nur Spoofing.                                                                                                                                                                                                                                |  
| [MS09-070](http://go.microsoft.com/fwlink/?linkid=163844) | Sicherheitsanfälligkeit in ADFS bzgl. Remotecodeausführung                                                | [CVE-2009-2509](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2509) | [**1**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | Die Sicherheitsanfälligkeit kann nur von einem authentifizierten Angreifer ausgenutzt werden.                                                                                                                                                                                                                   |  
| [MS09-071](http://go.microsoft.com/fwlink/?linkid=177727) | Sicherheitsanfälligkeit im Internetauthentifizierungsdienst bezüglich Speicherbeschädigung                | [CVE-2009-2505](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2505) | [**2**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | Eingeschränkte Möglichkeit für Remotecodeausführung. Das wahrscheinlichste Ergebnis ist Denial-of-Service.                                                                                                                                                                                                      |  
| [MS09-071](http://go.microsoft.com/fwlink/?linkid=177727) | Sicherheitsanfälligkeit durch Umgehung der MS-CHAP-Authentifizierung                                      | [CVE-2009-3677](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3677) | [**3**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Funktionierender Angreifercode unwahrscheinlich | Die Sicherheitsanfälligkeit ermöglicht keine Remotecodeausführung, nur eine Erhöhung von Berechtigungen aufgrund einer Umgehung der Netzwerkauthentifizierung.                                                                                                                                                  |  
| [MS09-072](http://go.microsoft.com/fwlink/?linkid=169404) | Sicherheitsanfälligkeit bezüglich der COM-Initialisierung in ATL                                          | [CVE-2009-2493](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2493) | Keine                                                                                                                | (Diese Sicherheitsanfälligkeit wurde bereits im Ausnutzbarkeitsindex im [Bulletin Summary von Juli](http://www.microsoft.com/germany/technet/sicherheit/bulletins/ms09-jul.mspx) bewertet. Diese Sicherheitsanfälligkeit wurde erstmalig in [MS09-035](http://go.microsoft.com/fwlink/?linkid=158131) behoben.) |  
| [MS09-072](http://go.microsoft.com/fwlink/?linkid=169404) | Sicherheitsanfälligkeit bezüglich Speicherbeschädigung aufgrund von Nichtinitialisierung                  | [CVE-2009-3671](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3671) | [**1**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                                                                                                                                                                         |  
| [MS09-072](http://go.microsoft.com/fwlink/?linkid=169404) | Sicherheitsanfälligkeit durch Speicherbeschädigung bei HTML-Objekten                                      | [CVE-2009-3672](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3672) | [**1**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                                                                                                                                                                         |  
| [MS09-072](http://go.microsoft.com/fwlink/?linkid=169404) | Sicherheitsanfälligkeit bezüglich Speicherbeschädigung aufgrund von Nichtinitialisierung                  | [CVE-2009-3673](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3673) | [**1**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                                                                                                                                                                         |  
| [MS09-072](http://go.microsoft.com/fwlink/?linkid=169404) | Sicherheitsanfälligkeit bezüglich Speicherbeschädigung aufgrund von Nichtinitialisierung                  | [CVE-2009-3674](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-3674) | [**1**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Konsistenter Angreifercode wahrscheinlich       | (Keine)                                                                                                                                                                                                                                                                                                         |  
| [MS09-073](http://go.microsoft.com/fwlink/?linkid=163833) | Sicherheitsanfälligkeit bezüglich Speicherbeschädigung in WordPad- und Office-Textkonvertern              | [CVE-2009-2506](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-2506) | [**2**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                                                                                                                                                                                                                                         |  
| [MS09-074](http://go.microsoft.com/fwlink/?linkid=141642) | Sicherheitsanfälligkeit in Project bezüglich Speicherüberprüfung                                          | [CVE-2009-0102](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2009-0102) | [**2**](http://technet.microsoft.com/de-de/security/cc998259.aspx) – Inkonsistenter Angreifercode wahrscheinlich     | (Keine)                                                                                                                                                                                                                                                                                                         |
  
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
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Microsoft Windows 2000  
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-071**](http://go.microsoft.com/fwlink/?linkid=177727)
</td>
<td style="border:1px solid black;">
[**MS09-072**](http://go.microsoft.com/fwlink/?linkid=169404)
</td>
<td style="border:1px solid black;">
[**MS09-069**](http://go.microsoft.com/fwlink/?linkid=177555)
</td>
<td style="border:1px solid black;">
[**MS09-070**](http://go.microsoft.com/fwlink/?linkid=163844)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://go.microsoft.com/fwlink/?linkid=163833)
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
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
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
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=5b02d10d-1abd-4d68-826b-71dad543657a)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Internet Explorer 5.01 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=0cf37247-505a-4dc2-aad7-c8cb1a63b57a)  
(Kritisch)  
[Internet Explorer 6 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=7fb6261c-6895-4f79-be2c-bb110874a19c)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?familyid=560e01db-5f59-4ef1-9406-f5d7e0fd4128)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=50936f51-b0a9-4e94-85bf-93f9ad74fdd1)  
(KB973904)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-071**](http://go.microsoft.com/fwlink/?linkid=177727)
</td>
<td style="border:1px solid black;">
[**MS09-072**](http://go.microsoft.com/fwlink/?linkid=169404)
</td>
<td style="border:1px solid black;">
[**MS09-069**](http://go.microsoft.com/fwlink/?linkid=177555)
</td>
<td style="border:1px solid black;">
[**MS09-070**](http://go.microsoft.com/fwlink/?linkid=163844)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://go.microsoft.com/fwlink/?linkid=163833)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Mittel**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
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
[Windows XP Service Pack 2 und Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=4d294be6-19d1-43b5-9c75-f9d30699a2e7)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=facab13f-ea31-4c71-be4c-24e44ded174f)  
(Kritisch)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=def2c038-3b03-4162-a563-a6ebec756f37)  
(Kritisch)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=6c003629-77bf-4735-bd4a-c37c4386f869)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 und Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=5448b168-6bf7-4bae-9627-b88d76c4d5c5)  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2 und Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=c090c4c2-c277-4d8c-91e1-28286bc5443e)  
(KB973904)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=17b5206d-61e9-4663-afc7-80e98bf4d618)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?familyid=a253c19a-c808-4115-8bd0-cf312d396abd)  
(Kritisch)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?familyid=98a56425-4f88-4f0f-963b-dada8dc0d8f8)  
(Kritisch)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?familyid=0c9af3b5-d015-4025-bbb4-1a5113e9113f)  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=c2bbf515-f81a-436b-947b-cbf2db85fdd9)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=4b9bf156-cd34-460f-b4ad-571e37f54659)  
(KB973904)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-071**](http://go.microsoft.com/fwlink/?linkid=177727)
</td>
<td style="border:1px solid black;">
[**MS09-072**](http://go.microsoft.com/fwlink/?linkid=169404)
</td>
<td style="border:1px solid black;">
[**MS09-069**](http://go.microsoft.com/fwlink/?linkid=177555)
</td>
<td style="border:1px solid black;">
[**MS09-070**](http://go.microsoft.com/fwlink/?linkid=163844)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://go.microsoft.com/fwlink/?linkid=163833)
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
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
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
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=3d49b386-133a-4d51-b6f0-cec0c70ef93e)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=6659fc40-71ee-44a9-9656-8d3ee02b5bc0)  
(Kritisch)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=7bdba030-e2c6-44ac-bb5f-24ae8ec372a2)  
(Mittel)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=0dd50357-64f2-4286-86ba-c512e65eed2a)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a779aae1-7724-4458-94fb-a2343356ecae)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=31351b9e-b5bb-4618-990b-1089ea5a3bc2)<sup>[1]</sup>
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=b9678229-2473-4aae-a814-eca9ea556d17)  
(KB973904)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=5a273b47-8a18-4778-9b60-8b560a1ce089)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=287e7921-8aab-42a6-b647-551d0a9adc15)  
(Kritisch)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=4de4bbcd-b1b8-4482-8ef7-0d9b4a730e0c)  
(Mittel)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=e62aba15-5eeb-46a2-a142-bfca94016c55)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=a8a9bf12-4ad6-49fd-b2b7-f379dc3309d2)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](https://technet.microsoft.com/de-DE/library///www.microsoft.com/downloads/details.aspx?displaylang=de%26familyid=b6eb9d9b-1a43-4b30-a033-19a1db786244(v=Security.10))<sup>[2]</sup>
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=257facf3-20a1-49e2-ab4c-c1ae67fe05a0)  
(KB973904)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 mit SP2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=498f5eeb-d03e-42ee-ad6a-9d6f98c66acb)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Internet Explorer 6](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=9ce1a721-0c6a-4775-9407-9633d817d716)  
(Kritisch)  
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=72d44de7-dfc5-4667-a59f-2ee73d0e3708)  
(Mittel)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?familyid=f5b003ad-af25-488a-91fb-98835a0bfeac)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=1a7784ef-5d25-4de1-a293-f742b5a3473d)  
(KB973904)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-071**](http://go.microsoft.com/fwlink/?linkid=177727)
</td>
<td style="border:1px solid black;">
[**MS09-072**](http://go.microsoft.com/fwlink/?linkid=169404)
</td>
<td style="border:1px solid black;">
[**MS09-069**](http://go.microsoft.com/fwlink/?linkid=177555)
</td>
<td style="border:1px solid black;">
[**MS09-070**](http://go.microsoft.com/fwlink/?linkid=163844)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://go.microsoft.com/fwlink/?linkid=163833)
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
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
Keine
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
[Windows Vista und Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=3e4ae4d0-1060-4867-82c5-7e20ea93c2c6)  
(Mittel)  
[Windows Vista Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=3e4ae4d0-1060-4867-82c5-7e20ea93c2c6)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=40d26d40-4203-4013-b3f9-912a5b209fbd)  
(Kritisch)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=47d5ada1-1d60-4233-bdd3-64918b5e1245)  
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition, Windows Vista x64 Edition Service Pack 1 und Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition und Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=2ca62ea8-67cb-40da-8a65-db6f3607bbab)  
(Mittel)  
[Windows Vista x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=2ca62ea8-67cb-40da-8a65-db6f3607bbab)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=3140527a-aa33-462b-b3a6-bfcd78b5aa0c)  
(Kritisch)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=1e466b48-422f-4c80-8fdf-ba61111942b1)  
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
<th colspan="6" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-071**](http://go.microsoft.com/fwlink/?linkid=177727)
</td>
<td style="border:1px solid black;">
[**MS09-072**](http://go.microsoft.com/fwlink/?linkid=169404)
</td>
<td style="border:1px solid black;">
[**MS09-069**](http://go.microsoft.com/fwlink/?linkid=177555)
</td>
<td style="border:1px solid black;">
[**MS09-070**](http://go.microsoft.com/fwlink/?linkid=163844)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://go.microsoft.com/fwlink/?linkid=163833)
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
[**Mittel**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
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
Windows Server 2008 für 32-Bit-Systeme und Windows Server 2008 für 32-Bit-Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=582a1b15-214e-4f5e-bb5b-95677f4d5968)\*  
(Hoch)  
[Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=582a1b15-214e-4f5e-bb5b-95677f4d5968)\*  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=d0570536-756e-4fda-883d-f2a3c4ac5bbd)\*  
(Mittel)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=43660133-43e1-41f3-8a82-98c4a739914f)\*  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme und Windows Server 2008 für 32-Bit-Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=f6715abb-fd93-44ba-9854-2ecc672622da)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für x64-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=77e774b4-ec0c-481c-9e93-eee9f44ec71b)\*  
(Hoch)  
[Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=77e774b4-ec0c-481c-9e93-eee9f44ec71b)\*  
(Kritisch)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=0e72d0f1-2ce7-4650-b72c-bb303351aafc)\*  
(Mittel)  
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=22972970-740f-4c50-93ec-f6d49dd1b360)\*  
(Mittel)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für x64-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=7d1f5e9e-a7de-4f96-89c8-510fd51f16e7)\*  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme und Windows Server 2008 für Itanium-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=89defe77-7e82-4bfa-9693-66c93b930da1)  
(Mittel)  
[Windows Server 2008 für Itanium-basierte Systeme Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=89defe77-7e82-4bfa-9693-66c93b930da1)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Internet Explorer 7](http://www.microsoft.com/downloads/details.aspx?displaylang=de&amp;familyid=2c7765a2-3117-4dd8-94b4-0060ca16871b)  
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
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-071**](http://go.microsoft.com/fwlink/?linkid=177727)
</td>
<td style="border:1px solid black;">
[**MS09-072**](http://go.microsoft.com/fwlink/?linkid=169404)
</td>
<td style="border:1px solid black;">
[**MS09-069**](http://go.microsoft.com/fwlink/?linkid=177555)
</td>
<td style="border:1px solid black;">
[**MS09-070**](http://go.microsoft.com/fwlink/?linkid=163844)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://go.microsoft.com/fwlink/?linkid=163833)
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
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
Keine
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=5af3be0b-2dd2-4039-90e1-2278e9c5aee5)  
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
Windows 7 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=9d9a04c8-a019-4943-8e93-c6bfd77c8960)  
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
<th colspan="6" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS09-071**](http://go.microsoft.com/fwlink/?linkid=177727)
</td>
<td style="border:1px solid black;">
[**MS09-072**](http://go.microsoft.com/fwlink/?linkid=169404)
</td>
<td style="border:1px solid black;">
[**MS09-069**](http://go.microsoft.com/fwlink/?linkid=177555)
</td>
<td style="border:1px solid black;">
[**MS09-070**](http://go.microsoft.com/fwlink/?linkid=163844)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://go.microsoft.com/fwlink/?linkid=163833)
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
[**Mittel**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
Keine
</td>
<td style="border:1px solid black;">
Keine
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=bcb38127-787f-49b0-b3fb-62f6a8628d89)\*  
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
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Internet Explorer 8](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=2c1b96f2-b3c3-4711-a9ad-b2133ea7bf81)  
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
</tr>
</table>
 
**Hinweis für Windows Server 2008 und Windows Server 2008 R2**

**\*Die Server Core-Installation ist nicht betroffen.** Die durch dieses Update behobenen Sicherheitsanfälligkeiten betreffen unterstützte Editionen von Windows Server 2008 oder Windows Server 2008 R2 wie angegeben nicht, wenn diese mit der Server Core-Installationsoption installiert wurden. Weitere Informationen zu dieser Installationsoption finden Sie in den MSDN-Artikeln [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) und [Server Core für Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx). Beachten Sie, dass die Server Core-Installationsoption für bestimmte Editionen von Windows Server 2008 und Windows Server 2008 R2 nicht gilt; siehe dazu [Vergleichen von Server Core-Installationsoptionen](http://www.microsoft.com/germany/windowsserver2008/editionen/r2-vergleich-server-core.mspx).

**Hinweise für MS09-070**

<sup>[1]</sup> Nur betroffen, wenn Aktualisierung mit Windows Server 2003 R2 durchgeführt wurde, in dem Active Directory-Verbunddienste bereitgestellt werden.

<sup>[2]</sup> Nur betroffen, wenn Aktualisierung mit Windows Server 2003 R2 x64 Edition durchgeführt wurde, in dem Active Directory-Verbunddienste bereitgestellt werden.

**Hinweis für MS09-073**

Weitere Updatedateien finden Sie außerdem unter anderen Softwarekategorien im Abschnitt **Betroffene Software und Downloadadressen** unter der gleichen Kennung des Bulletins. Dieses Bulletin umfasst mehr als eine Softwarekategorie.

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
[**MS09-074**](http://go.microsoft.com/fwlink/?linkid=141642)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://go.microsoft.com/fwlink/?linkid=163833)
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
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office XP
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Office XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=bc3ec3ba-2cec-43ab-b184-c222794231f2)  
(KB975008)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2003
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Office 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=b4a4126c-b0b3-4db2-b6f5-0e67519c2a5f)  
(KB975051)  
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
[**MS09-074**](http://go.microsoft.com/fwlink/?linkid=141642)
</td>
<td style="border:1px solid black;">
[**MS09-073**](http://go.microsoft.com/fwlink/?linkid=163833)
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
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Project 2000
</td>
<td style="border:1px solid black;">
[Microsoft Project 2000 Service Release 1](http://www.microsoft.com/downloads/details.aspx?familyid=135c010a-55f4-4385-b67d-96ea06ef881a)  
(KB961083)  
(Kritisch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Project 2002
</td>
<td style="border:1px solid black;">
[Microsoft Project 2002 Service Pack 1](http://www.microsoft.com/downloads/details.aspx?familyid=c55ef8fe-8f66-42fc-a298-de6f8886b3e4)  
(KB961079)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Project 2003
</td>
<td style="border:1px solid black;">
[Microsoft Office Project 2003 Service Pack 3](http://www.microsoft.com/downloads/details.aspx?familyid=2ea8ca39-f130-439a-92d5-77e9ef050105)  
(KB961082)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Works 8.5
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Works 8.5](http://www.microsoft.com/downloads/details.aspx?familyid=807426a1-8b78-4681-a606-dc39f4d7b64a)  
(KB977304)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office Converter Pack
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
<td style="border:1px solid black;">
[Microsoft Office Converter Pack](http://www.microsoft.com/downloads/details.aspx?familyid=f3ff8bb6-d047-42f1-9331-b6df85fff9fd)  
(KB974882)  
(Hoch)
</td>
</tr>
</table>
 
**Hinweis für MS09-073**

Weitere Updatedateien finden Sie außerdem unter anderen Softwarekategorien im Abschnitt **Betroffene Software und Downloadadressen** unter der gleichen Kennung des Bulletins. Dieses Bulletin umfasst mehr als eine Softwarekategorie.

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

Der Systems Management Server von Microsoft stellt eine wertvolle Hilfe beim Bereitstellen von Sicherheitsupdates in Ihrer IT-Umgebung dar. Durch die Verwendung von SMS können Administratoren auf Windows basierte Systeme identifizieren, für die Sicherheitsupdates erforderlich sind, und für eine kontrollierte Bereitstellung dieser Updates im gesamten Unternehmen bei minimalen Unterbrechungen für Endbenutzer sorgen. Die nächste Version von SMS, System Center Configuration Manager 2007, ist jetzt verfügbar (siehe auch [System Center Configuration Manager 2007](http://technet.microsoft.com/de-de/library/bb735860.aspx)). Weitere Informationen zur Verwendung von SMS 2003 durch Administratoren für die Bereitstellung von Sicherheitsupdates finden Sie unter [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). Benutzer von SMS 2.0 können auch das Sicherheitsupdate-Inventurprogramm (SUIT) verwenden, um Hilfe bei der Bereitstellung von Sicherheitsupdates zu erhalten. Weitere Informationen zu SMS finden Sie auf der Website [Microsoft Systems Management Server](http://www.microsoft.com/germany/systemcenter/sccm/default.mspx).

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

-   Ryan Smith von [VeriSign iDefense Labs](http://labs.idefense.com/) für den Hinweis auf ein in MS09-072 beschriebenes Problem.
-   Sam Thomas von eshu.co.uk, der mit [TippingPoint](http://www.tippingpoint.com/) und [Zero Day Initiative](http://www.zerodayinitiative.com/) zusammenarbeitet, für den Hinweis auf ein in MS09-072 beschriebenes Problem.
-   [team509](http://www.team509.com/) in Zusammenarbeit mit [VeriSign iDefense Labs](http://labs.idefense.com/) für den Hinweis auf ein in MS09-072 beschriebenes Problem.
-   Einer Person, die mit [TippingPoint](http://www.tippingpoint.com/) und [Zero Day Initiative](http://www.zerodayinitiative.com/) zusammenarbeitet, aber anonym bleiben möchte, für den Hinweis auf ein in MS09-072 beschriebenes Problem.
-   Einer Person, die mit [TippingPoint](http://www.tippingpoint.com/) und [Zero Day Initiative](http://www.zerodayinitiative.com/) zusammenarbeitet, aber anonym bleiben möchte, für den Hinweis auf ein in MS09-072 beschriebenes Problem.
-   Sean Larsson und Jun Mao von [VeriSign iDefense Labs](http://labs.idefense.com/) für den Hinweis auf ein in MS09-073 beschriebenes Problem.
-   Bing Liu von [Fortinet's FortiGuard Labs](http://www.fortiguard.com/) für den Hinweis auf ein in MS09-074 beschriebenes Problem.

#### Support

-   Die betroffene Software wurde getestet, um die betroffenen Versionen zu ermitteln. Andere Versionen haben das Ende ihrer Supportlebenszyklen erreicht. Besuchen Sie die Website [Microsoft Support Lifecycle](http://support.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle), um den Supportlebenszyklus für Ihre Softwareversion zu ermitteln.
-   Technischer Support ist über den [Security Support](http://go.microsoft.com/fwlink/?linkid=21131) erhältlich. Supportanrufe zu Sicherheitsupdates sind kostenlos. Weitere Informationen zu verfügbaren Supportoptionen finden Sie auf der [Microsoft-Website „Hilfe und Support“](http://support.microsoft.com/).
-   Kunden außerhalb der USA erhalten Support bei ihren regionalen Microsoft-Niederlassungen. Supportanfragen zu Sicherheitsupdates sind kostenlos. Weitere Informationen dazu, wie Sie Microsoft in Bezug auf Supportfragen kontaktieren können, finden Sie auf der Website [Internationale Hilfe und Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Haftungsausschluss

Die Informationen der Microsoft Knowledge Base werden wie besehen und ohne jede Gewährleistung bereitgestellt. Microsoft schließt alle anderen Garantien, gleich ob ausdrücklich oder konkludent, einschließlich der Garantien der Handelsüblichkeit oder Eignung für einen bestimmten Zweck aus. In keinem Fall kann Microsoft Corporation und/oder deren jeweilige Lieferanten haftbar gemacht werden für Schäden irgendeiner Art, einschließlich direkter, indirekter, zufällig entstandener Schäden, Folgeschäden, Folgen entgangenen Gewinns oder spezieller Schäden, selbst dann nicht, wenn Microsoft Corporation und/oder deren jeweilige Lieferanten auf die mögliche Entstehung dieser Schäden hingewiesen wurde. Weil in einigen Staaten/Rechtsordnungen der Ausschluss oder die Beschränkung einer Haftung für zufällig entstandene Schäden oder Folgeschäden nicht gestattet ist, gilt die obige Einschränkung eventuell nicht für sie.

#### Revisionen

-   V1.0 (8. Dezember 2009): Bulletin Summary veröffentlicht.
-   V1.1 (9. Dezember 2009): Aktualisierung der Beschreibung für MS09-071 in der Tabelle „Kurzzusammenfassungen“. Die Neustartanforderung für MS09-073 wurde korrigiert.
-   V2.0 (13. Januar 2010): Für MS09-073 wurden die Updatepakete, die bisher als **Microsoft Office Word 2002 Service Pack 3 (KB975008)** und **Microsoft Office Word 2003 Service Pack 3 (KB975051)** aufgeführt wurden, entsprechend in **Microsoft Office XP Service Pack 3 (KB975008)** und **Microsoft Office 2003 Service Pack 3 (KB975051)** umbenannt.

*Built at 2014-04-18T01:50:00Z-07:00*
