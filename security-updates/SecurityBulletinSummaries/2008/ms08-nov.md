---
TOCTitle: 'MS08-NOV'
Title: Microsoft Security Bulletin Summary für November 2008
ms:assetid: 'ms08-nov'
ms:contentKeyID: 61225064
ms:mtpsurl: 'https://technet.microsoft.com/de-DE/library/ms08-nov(v=Security.10)'
---

Security Bulletin Summary

Microsoft Security Bulletin Summary für November 2008
=====================================================

Veröffentlicht: Dienstag, 11. November 2008 | Aktualisiert: Dienstag, 12. Juli 2011

**Version:** 4.0

In diesem Bulletin Summary sind die im November 2008 veröffentlichten Security Bulletins aufgeführt.

Mit der Veröffentlichung der Bulletins für November 2008 ersetzt dieses Bulletin Summary die Bulletin Advance Notification, die erstmalig am 6. November 2008 veröffentlicht wurde. Weitere Informationen zum Bulletin Advance Notification-Service finden Sie unter [Microsoft Security Bulletin Advance Notification.](http://www.microsoft.com/germany/technet/sicherheit/bulletins/bulletinadvance.mspx)

Weitere Informationen zum Erhalten automatischer Benachrichtigungen über die Veröffentlichung von Microsoft Security Bulletins finden Sie unter [Microsoft Technische Sicherheitsbenachrichtigungen](http://www.microsoft.com/germany/technet/sicherheit/bulletins/bulletinadvance.mspx).

Am Mittwoch, den 12. November 2008 um 11:00 Uhr pazifischer Zeit (USA & Kanada) stellt Microsoft einen Webcast bereit, um Kundenfragen zu diesen Bulletins zu beantworten. [Registrieren Sie sich jetzt für das Security Bulletin-Webcast im November.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032374642) Ab diesem Datum steht dieser Webcast auf Anfrage zur Verfügung. Weitere Informationen dazu finden Sie unter [Microsoft Security Bulletin Zusammenfassungen und Webcasts.](http://www.microsoft.com/germany/technet/sicherheit/bulletins/bulletinadvance.mspx)

Microsoft stellt auch Informationen bereit, anhand derer Benutzer die Prioritäten für monatliche Sicherheitsupdates und alle nicht sicherheitsrelevanten wichtigen Updates festlegen können, die an demselben Tag veröffentlicht werden wie die monatlichen Sicherheitsupdates. Bitte lesen Sie den Abschnitt **Weitere Informationen**.

### Bulletin-Informationen

#### Kurzzusammenfassungen

Die Security Bulletins für diesen Monat, nach Schweregrad geordnet:

Kritisch (1)
------------


| Kennung des Bulletins                       | Microsoft Security Bulletin MS08-069                                                                                                                                                                                                                                                                                                                                                                                                                      |
|---------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Sicherheitsanfälligkeiten in Microsoft XML Core Services können Remotecodeausführung ermöglichen (955218)**](http://go.microsoft.com/fwlink/?linkid=128803)                                                                                                                                                                                                                                                                                            |
| **Kurzzusammenfassung**                     | Dieses Sicherheitsupdate behebt mehrere Sicherheitsanfälligkeiten in Microsoft XML Core Services. Die schwerste Sicherheitsanfälligkeit kann Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Webseite mit Internet Explorer anzeigt. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten. |
| **Bewertung des maximalen Schweregrads:**   | [Kritisch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                       |
| **Auswirkung der Sicherheitsanfälligkeit:** | Remotecodeausführung                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Das Update kann einen Neustart erfordern.                                                                                                                                                                                                                                                                                                               |
| **Betroffene Software:**                    | **Microsoft Windows.** Weitere Informationen finden Sie im Abschnitt „Betroffene Software und Downloadadressen“.                                                                                                                                                                                                                                                                                                                                          |

Hoch (1)
--------


| Kennung des Bulletins                       | Microsoft Security Bulletin MS08-068                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|---------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Sicherheitsanfälligkeit in SMB kann Remotecodeausführung ermöglichen (957097)**](http://go.microsoft.com/fwlink/?linkid=133434)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Kurzzusammenfassung**                     | Dieses Sicherheitsupdate behebt eine öffentlich gemeldete Sicherheitsanfälligkeit im Microsoft SMB-Protokoll (Server Message Block). Die Sicherheitsanfälligkeit kann auf betroffenen Systemen Remotecodeausführung ermöglichen. Ein Angreifer, der diese Sicherheitsanfälligkeit erfolgreich ausnutzt, kann Programme installieren, Daten anzeigen, ändern oder löschen oder neue Konten mit sämtlichen Benutzerrechten erstellen. Für Endbenutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten. |
| **Bewertung des maximalen Schweregrads:**   | [Hoch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Auswirkung der Sicherheitsanfälligkeit:** | Remotecodeausführung                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Für dieses Update ist ein Neustart erforderlich.                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Betroffene Software:**                    | **Microsoft Windows.** Weitere Informationen finden Sie im Abschnitt „Betroffene Software und Downloadadressen“.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |

Ausnutzbarkeitsindex
--------------------

**Wie verwende ich diese Tabelle?**  

Verwenden Sie diese Tabelle, um etwas über die Wahrscheinlichkeit zu erfahren, dass für die einzelnen Sicherheitsupdates, die Sie möglicherweise installieren müssen, innerhalb von 30 Tagen funktionierender Angreifercode veröffentlicht wird. Sie sollten sich unter Berücksichtigung Ihrer konkreten Konfiguration jede der unten stehenden Bewertungen ansehen, um Prioritäten für Ihre Bereitstellung festzulegen. Weitere Informationen zur Bedeutung und Festlegung dieser Bewertungen finden Sie im [Microsoft-Ausnutzbarkeitsindex](http://technet.microsoft.com/de-de/security/cc998259).

| Kennung des Bulletins                                     | Titel des Bulletins                                                                                                                                        | CVE-ID                                                                           | Ausnutzbarkeitsindex - Bewertung                                                                        | Wichtige Hinweise                                                                                                                            |
|-----------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------|
| [MS08-068](http://go.microsoft.com/fwlink/?linkid=133434) | [Sicherheitsanfälligkeit in SMB kann Remotecodeausführung ermöglichen (957097)](http://go.microsoft.com/fwlink/?linkid=133434)                             | [CVE-2008-4037](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4037) | [1 - Konsistenter Angreifercode wahrscheinlich](http://technet.microsoft.com/de-de/security/cc998259)   | Derzeit ist für diese Sicherheitsanfälligkeit unter Windows XP Angreifercode öffentlich verfügbar.                                           |
| [MS08-069](http://go.microsoft.com/fwlink/?linkid=128803) | [Sicherheitsanfälligkeiten in Microsoft XML Core Services können Remotecodeausführung ermöglichen (955218)](http://go.microsoft.com/fwlink/?linkid=128803) | [CVE-2008-4029](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4029) | [1 - Konsistenter Angreifercode wahrscheinlich](http://technet.microsoft.com/de-de/security/cc998259)   | Angreifercode für die Offenlegung von Informationen ist wahrscheinlich, da dieser bei domänenübergreifenden Angriffen verwendet werden kann. |
| [MS08-069](http://go.microsoft.com/fwlink/?linkid=128803) | [Sicherheitsanfälligkeiten in Microsoft XML Core Services können Remotecodeausführung ermöglichen (955218)](http://go.microsoft.com/fwlink/?linkid=128803) | [CVE-2007-0099](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2007-0099) | [2 - Inkonsistenter Angreifercode wahrscheinlich](http://technet.microsoft.com/de-de/security/cc998259) | Diese Sicherheitsanfälligkeit umfasst eine Wettlaufsituation beim Laden von XML-Dateien. Daher ist eine konsistente Ausnutzung schwierig.    |
| [MS08-069](http://go.microsoft.com/fwlink/?linkid=128803) | [Sicherheitsanfälligkeiten in Microsoft XML Core Services können Remotecodeausführung ermöglichen (955218)](http://go.microsoft.com/fwlink/?linkid=128803) | [CVE-2008-4033](http://www.cve.mitre.org/cgi-bin/cvename.cgi?name=cve-2008-4033) | [2 - Inkonsistenter Angreifercode wahrscheinlich](http://technet.microsoft.com/de-de/security/cc998259) |                                                                                                                                              |

Betroffene Software und Downloadadressen
----------------------------------------

**Wie verwende ich diese Tabelle?**  

In dieser Tabelle finden Sie Informationen zu Sicherheitsupdates, die Sie möglicherweise installieren sollten. Sie sollten jedes aufgeführte Softwareprogramm und jede Komponente überprüfen, um zu sehen, ob Sicherheitsupdates erforderlich sind. Wenn ein Softwareprogramm oder eine Komponente aufgeführt sind, dann ist das verfügbare Softwareupdate über einen Hyperlink verknüpft, und die Bewertung des Schweregrads des Softwareupdates ist ebenfalls aufgeführt.

**Hinweis**: Für eine Sicherheitsanfälligkeit müssen Sie möglicherweise mehrere Sicherheitsupdates installieren. Durchsuchen Sie in der gesamten Spalte die einzelnen Kennungen der aufgeführten Bulletins, um basierend auf den auf Ihrem System installierten Programmen oder Komponenten zu überprüfen, welche Updates Sie installieren müssen.

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
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Microsoft Windows 2000
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://go.microsoft.com/fwlink/?linkid=133434)
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
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=559cd4b6-24b7-4e60-8749-37d9b833d3eb)  
(KB955069)  
(Kritisch)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Hoch)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Microsoft Windows 2000 Service Pack 4](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=44c971e6-96fc-4bba-8f4a-f9d46bda2b6c)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows XP
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://go.microsoft.com/fwlink/?linkid=133434)
</td>
</tr>
<tr>
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
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=6ed1a087-97e2-4283-9b53-b7b046654d08)  
(KB955069)  
(Kritisch)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Hoch)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=6f8ae0aa-fd68-4156-9016-bba00149793c)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=6ed1a087-97e2-4283-9b53-b7b046654d08)  
(KB955069)  
(Kritisch)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Hoch)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=7493fa37-2cbf-4d66-8690-d50d63da4096)  
(KB954459)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows XP Service Pack 3](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=6f8ae0aa-fd68-4156-9016-bba00149793c)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition und Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?familyid=1b79f220-ebfc-49c1-963b-58bbda21b6e7)  
(KB955069)  
(Kritisch)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Hoch)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows XP Professional x64 Edition und Windows XP Professional x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?familyid=9501b33b-d639-43e7-ad5a-9e76ed66effd)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows Server 2003
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://go.microsoft.com/fwlink/?linkid=133434)
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
Windows Server 2003 Service Pack 1 und Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=0a0f8385-e908-4b5f-b9bf-80b7dabfcafd)  
(KB955069)  
(Kritisch)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Niedrig)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(Niedrig)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 Service Pack 1 und Windows Server 2003 Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=57a0606d-ea7a-4e5b-8b8b-7b77a444ef75)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition und Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=347c8c83-4269-4a0e-af6f-4be2e824d22b)  
(KB955069)  
(Kritisch)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Niedrig)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(Niedrig)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 x64 Edition und Windows Server 2003 x64 Edition Service Pack 2](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=915e001f-9aa0-4fb0-9c2a-0f0c72b4f056)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 mit SP1 für Itanium-basierte Systeme und Windows Server 2003 mit SP2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=3a65e1cd-eb4e-44b6-8868-a5a84be2cb32)  
(KB955069)  
(Kritisch)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Niedrig)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=59914795-60c7-4ebe-828d-f28cb457e6e3)  
(KB954459)  
(Niedrig)
</td>
<td style="border:1px solid black;">
[Windows Server 2003 mit SP1 für Itanium-basierte Systeme und Windows Server 2003 mit SP2 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=6abf7ba9-825f-4ee2-a2fe-6b1cd9fab622)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows Vista
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://go.microsoft.com/fwlink/?linkid=133434)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Mittel**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista und Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=affbc957-1867-4bbe-924d-6f0696ae0895)  
(KB955069)  
(Kritisch)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Hoch)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=cb6c4315-8c6d-43af-978b-b190b1a1577a)  
(KB954459)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Vista und Windows Vista Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=5612815f-8685-45d2-af4a-164c298a0869)  
(Mittel)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition und Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=b01a5f31-8c57-4c5c-909e-b37caf0439b0)  
(KB955069)  
(Kritisch)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Hoch)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=39443046-2093-4c87-ac7b-679deab96414)  
(KB954459)  
(Hoch)
</td>
<td style="border:1px solid black;">
[Windows Vista x64 Edition und Windows Vista x64 Edition Service Pack 1](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=727ce9b6-827f-4350-b4ff-c08e8ac541a6)  
(Mittel)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows Server 2008
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://go.microsoft.com/fwlink/?linkid=133434)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Mittel**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=90a04164-4d02-4ce9-b3d8-bddb1ec27618)\*\*  
(KB955069)  
(Kritisch)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(Niedrig)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=dea9f227-967f-47c7-bb2a-ed68f13645d9)\*\*  
(KB954459)  
(Niedrig)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für 32-Bit-Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=b305e894-61ec-46b4-91ee-4c9ac59bc47e)\*  
(Mittel)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(Niedrig)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=b7bfe3f4-835f-402c-95b5-6d49b6935308)\*\*  
(KB955069)  
(Kritisch)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(Niedrig)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=f16e2a5f-37fd-4ee1-aef0-597214323dc4)\*\*  
(KB954459)  
(Niedrig)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für x64-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=e8d26dfd-b347-4f10-b5b6-27dfff5e4f47)\*  
(Mittel)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(Niedrig)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 3.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=4e0d1efe-70ac-459b-b330-c0149b74f520)  
(KB955069)  
(Kritisch)  
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Niedrig)  
[Microsoft XML Core Services 6.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=d4ae74e2-1b09-4a99-8cf5-8a8ca8ac6f7f)  
(KB954459)  
(Niedrig)
</td>
<td style="border:1px solid black;">
[Windows Server 2008 für Itanium-basierte Systeme](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=d565467d-e10f-4ddc-a278-3f81a3798686)  
(Mittel)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme Service Pack 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Niedrig)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows 7
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://go.microsoft.com/fwlink/?linkid=133434)
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
Keine
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows 7 für 32-Bit Systeme und Windows 7 für 32-Bit Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows 7 für x64-basierte Systeme und Windows 7 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Hoch)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<th colspan="3" style="border:1px solid black;">
Windows Server 2008 R2
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
<td style="border:1px solid black;">
[**MS08-068**](http://go.microsoft.com/fwlink/?linkid=133434)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Niedrig**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
Keine
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 R2 für x64-basierte Systeme und Windows Server 2008 R2 für x64-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96a4413c-5261-4f69-83d0-932c430abd14)\*\*  
(KB954430)  
(Niedrig)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 R2 für Itanium-basierte Systeme und Windows Server 2008 R2 für Itanium-basierte Systeme Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 4.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=96a4413c-5261-4f69-83d0-932c430abd14)  
(KB954430)  
(Niedrig)
</td>
<td style="border:1px solid black;">
Nicht anwendbar
</td>
</tr>
</table>
 
**\*Die Server Core-Installation ist betroffen.** Dieses Update gilt, mit der gleichen Bewertung des Schweregrads, wie angezeigt auch für unterstützte Editionen von Windows Server 2008 oder Windows Server 2008 R2, unabhängig davon, ob bei der Installation die Server Core-Installationsoption verwendet wurde oder nicht. Weitere Informationen zu dieser Installationsoption finden Sie in den MSDN-Artikeln [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) und [Server Core für Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx). Beachten Sie, dass die Server Core-Installationsoption für bestimmte Editionen von Windows Server 2008 und Windows Server 2008 R2 nicht gilt; siehe dazu [Vergleichen von Server Core-Installationsoptionen](http://www.microsoft.com/germany/windowsserver2008/editionen/r2-vergleich-server-core.mspx).

**\*\*Die Server Core-Installation ist nicht betroffen.** Die durch dieses Update behobenen Sicherheitsanfälligkeiten betreffen unterstützte Editionen von Windows Server 2008 oder Windows Server 2008 R2 wie angegeben nicht, wenn diese mit der Server Core-Installationsoption installiert wurden. Weitere Informationen zu dieser Installationsoption finden Sie in den MSDN-Artikeln [Server Core](http://msdn.microsoft.com/en-us/library/ms723891(vs.85).aspx) und [Server Core für Windows Server 2008 R2](http://msdn.microsoft.com/en-us/library/ee391631(vs.85).aspx). Beachten Sie, dass die Server Core-Installationsoption für bestimmte Editionen von Windows Server 2008 und Windows Server 2008 R2 nicht gilt; siehe dazu [Vergleichen von Server Core-Installationsoptionen](http://www.microsoft.com/germany/windowsserver2008/editionen/r2-vergleich-server-core.mspx).

#### Microsoft Office Suites und Software

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
Microsoft Office Suites, Systeme und Komponenten
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=7ad891a8-c3bb-4479-8282-13d629c410e3)  
(KB951535)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office System 2007 und Microsoft Office System 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=27b06ee8-570a-4dc2-a230-c70d4a706245)  
(KB951550)  
(Hoch)
</td>
</tr>
<tr>
<th colspan="2" style="border:1px solid black;">
Weitere Office-Software
</th>
</tr>
<tr>
<td style="border:1px solid black;">
**Kennung des Bulletins**
</td>
<td style="border:1px solid black;">
[**MS08-069**](http://go.microsoft.com/fwlink/?linkid=128803)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des Gesamtschweregrads**
</td>
<td style="border:1px solid black;">
[**Hoch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer 2003 Service Pack 3
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=7ad891a8-c3bb-4479-8282-13d629c410e3)  
(KB951535)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Compatibility Pack für die Dateiformate von Word, Excel und PowerPoint 2007 und Microsoft Office Compatibility Pack für die Dateiformate von Word, Excel und PowerPoint 2007 Service Pack 1
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=27b06ee8-570a-4dc2-a230-c70d4a706245)  
(KB951550)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Expression Web und Microsoft Expression Web 2
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=27b06ee8-570a-4dc2-a230-c70d4a706245)  
(KB951550)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 und Microsoft Office SharePoint Server 2007 Service Pack 1 (32-Bit-Editionen)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=a208f2b5-2b0d-43bb-8f8a-58d4a3fc64f5)  
(KB951597)  
(Hoch)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server 2007 und Microsoft Office SharePoint Server 2007 Service Pack 1 (64-Bit-Editionen)
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=0735f4af-e32b-4970-bed7-b2b9323cf54c)  
(KB951597)  
(Hoch)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Groove Server 2007
</td>
<td style="border:1px solid black;">
[Microsoft XML Core Services 5.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=0735f4af-e32b-4970-bed7-b2b9323cf54c)  
(KB951597)  
(Hoch)
</td>
</tr>
</table>
 

Tools und Anleitungen zur Erkennung und Bereitstellung
------------------------------------------------------

**Sicherheitsportal:**

Verwalten Sie die Software und die Sicherheitsupdates, die Sie den Servern, Desktops und mobilen Computer in Ihrer Organisation bereitstellen müssen. Weitere Informationen finden Sie im [TechNet Update Management Center](http://technet.microsoft.com/de-de/updatemanagement/default.aspx). Im [TechNet Sicherheits-Center](http://www.microsoft.com/germany/technet/sicherheit/default.mspx) werden zusätzliche Informationen zur Sicherheit in Microsoft-Produkten zur Verfügung gestellt. Verbraucher können die Seite [Sicherheit zu Hause](http://www.microsoft.com/germany/athome/security/default.mspx) besuchen, wo diese Informationen auch durch einen Klick auf „Die neuesten Sicherheitsupdates“ verfügbar sind.

Sicherheitsupdates sind auch über [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747&displaylang=de), [Windows Update](http://update.microsoft.com/windowsupdate/) und [Office Update](http://office.microsoft.com/de-de/downloads/default.aspx) verfügbar. Sicherheitsupdates sind auch im [Microsoft Download Center](http://www.microsoft.com/downloads/results.aspx?displaylang=de&freetext=sicherheitsupdate) verfügbar. Sie können am einfachsten durch eine Suche nach dem Begriff „security update“ ermittelt werden.

Außerdem können Sicherheitsupdates vom [Windows Update-Katalog](http://go.microsoft.com/fwlink/?linkid=96155) heruntergeladen werden. Der Microsoft Update-Katalog stellt einen durchsuchbaren Katalog der Inhalte bereit, die über Windows Update und Microsoft Update zur Verfügung gestellt werden, einschließlich Sicherheitsupdates, Treiber und Service Packs. Indem Sie mit der Nummer des Security Bulletins suchen (z. B. „MS07-036“), können Sie Ihrem Warenkorb alle anwendbaren Updates (einschließlich verschiedener Sprachen für ein Update) hinzufügen und in den Ordner Ihrer Wahl herunterladen. Weitere Informationen zum Microsoft Update-Katalog, finden Sie unter [Häufig gestellte Fragen zum Microsoft Update-Katalog](http://catalog.update.microsoft.com/v7/site/faq.aspx).

**Anleitungen zur Erkennung und Bereitstellung**

Zu den Sicherheitsupdates dieses Monats stellt Microsoft Anleitungen zur Erkennung und Bereitstellung zur Verfügung. Diese Anleitungen geben auch IT-Profis Informationen zum Einsatz der verschiedenen Tools und zur Bereitstellung des Sicherheitsupdates. Behandelt werden u. a. Windows Update, Microsoft Update, Office Update, Microsoft Baseline Security Analyzer (MBSA), Office Detection Tool, Microsoft Systems Management Server (SMS) und das Erweiterte Sicherheitsupdate-Inventurprogramm (ESUIT). Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 910723](http://support.microsoft.com/kb/910723/de).

**Microsoft Baseline Security Analyzer**

Der Microsoft Baseline Security Analyzer (MBSA) ermöglicht Administratoren die Überprüfung von lokalen und Remotesystemen im Hinblick auf fehlende Sicherheitsupdates sowie auf häufig falsch konfigurierte Sicherheitsparameter. Weitere Informationen zu MBSA finden Sie auf der Website [Microsoft Baseline Security Analyzer](http://www.microsoft.com/germany/technet/sicherheit/tools/mbsa/2_0.mspx).

**Windows Server Update Services**

Mithilfe der Windows Server Update Services (WSUS), können Administratoren die neuesten wichtigen Aktualisierungen und Sicherheitsupdates für Windows 2000 und höher, Office XP und höher, Exchange Server 2003 und SQL Server 2000 für Windows 2000 und neuere Betriebssysteme schnell und zuverlässig bereitstellen.

Weitere Informationen zum Bereitstellen dieses Sicherheitsupdates mithilfe der Windows Server Update Services finden Sie auf der [Windows Server Update Services Website](http://www.microsoft.com/germany/technet/prodtechnol/windowsserver/wsus/default.mspx).

**Systems Management Server**

Der Systems Management Server von Microsoft stellt eine wertvolle Hilfe beim Bereitstellen von Sicherheitsupdates in Ihrer IT-Umgebung dar. Durch die Verwendung von SMS können Administratoren auf Windows basierte Systeme identifizieren, für die Sicherheitsupdates erforderlich sind, und für eine kontrollierte Bereitstellung dieser Updates im gesamten Unternehmen bei minimalen Unterbrechungen für Endbenutzer sorgen. Die nächste Version von SMS, System Center Configuration Manager 2007, ist jetzt verfügbar (siehe auch [System Center Configuration Manager 2007](http://technet.microsoft.com/de-de/library/bb735860.aspx)). Weitere Informationen zur Verwendung von SMS 2003 durch Administratoren für die Bereitstellung von Sicherheitsupdates finden Sie unter [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). Benutzer von SMS 2.0 können auch die Website [Software Updates Service Feature Pack](http://www.microsoft.com/technet/prodtechnol/sms/sms2/downloads/featurepacks/suspack/default.mspx) besuchen, um Hilfe bei der Bereitstellung von Sicherheitsupdates zu erhalten. Weitere Informationen zu SMS finden Sie auf der Website [Microsoft Systems Management Server](http://www.microsoft.com/germany/systemcenter/sccm/default.mspx).

**Hinweis:** SMS nutzt Microsoft Baseline Security Analyzer und das Microsoft Office Detection-Tool für eine breite Unterstützung bei der Erkennung und der Bereitstellung von Security Bulletin-Updates. Einige Softwareupdates werden von diesen Tools möglicherweise nicht erkannt. Administratoren können in diesen Fällen die Inventurfunktionen von SMS nutzen, um Updates auf ausgewählten Systemen zu installieren. Weitere Informationen zu diesem Verfahren finden Sie auf der Website [Bereitstellen von Softwareupdates mit der Funktion zur Softwareverteilung von SMS](http://www.microsoft.com/technet/sms/2003/patchupdate.mspx). Bei einigen Sicherheitsupdates, die einen Neustart des Systems erfordern, sind unter Umständen administrative Rechte nötig. Administratoren können das im [SMS 2003 Administration Feature Pack](http://www.microsoft.com/downloads/details.aspx?familyid=7bd3a16e-1899-4e0b-bb99-1320e816167d&displaylang=de) und im [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161) enthaltene Elevated Rights Deployment Tool verwenden, um diese Updates zu installieren.

**Updatekompatibilitätsbewertung und Anwendungskompatibilitäts-Toolkit**

Updates bearbeiten oft dieselben Dateien und Registrierungseinstellungen, die zum Ausführen Ihrer Anwendungen benötigt werden. Dies kann eine Inkompatibilität auslösen und die Bereitstellung von Sicherheitsupdates verzögern. Mit den Komponenten zur [Updatekompatibilitätsbewertung](http://technet.microsoft.com/de-de/library/cc766043(ws.10).aspx), die im [Microsoft Application Compatibility Toolkit 5.0](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=24da89e9-b581-47b0-b45e-492dd6da2971&amp;displaylang=en) enthalten sind, können Sie die Vereinbarkeit von Windows-Updates mit installierten Anwendungen testen und überprüfen.

Das Microsoft Application Compatibility Toolkit (ACT) enthält alle notwendigen Tools und Dokumentationen, um die Anwendungskompatibilität zu prüfen und eventuelle Probleme zu beheben, bevor Microsoft Windows Vista, ein Windows-Update, ein Microsoft-Sicherheitsupdate oder eine neue Version von Windows Internet Explorer in Ihrer Umgebung bereitgestellt wird.

### Weitere Informationen:

#### Windows-Tool zum Entfernen schädlicher Software

Microsoft hat eine aktualisierte Version des Microsoft Windows-Tools zum Entfernen bösartiger Software in Windows Update, Microsoft Update, Windows Server Update Services und dem Download Center veröffentlicht.

#### Nicht sicherheitsrelevante, wichtige Updates unter MU, WU und WSUS:

Weitere Informationen zu nicht sicherheitsrelevanten Veröffentlichungen auf Windows-Update und Microsoft Update finden Sie unter:

-   [Microsoft Knowledge Base-Artikel 894199](http://support.microsoft.com/kb/894199/de): Beschreibung der Änderungen an den Inhalten von Software Update Services und Windows Server Update Services für 2008. Umfasst alle Windows-Inhalte.
-   [Neue, überarbeitete und veröffentlichte Updates für andere Microsoft-Produkte als Microsoft Windows](http://technet.microsoft.com/en-us/wsus/bb466214.aspx).

#### Sicherheitsstrategien und Community

**Strategien für die Verwaltung von Sicherheitspatches:**

Auf der Seite [Security Guidance für Updateverwaltung](http://www.microsoft.com/germany/technet/sicherheit/themen/patchmanagement.mspx) werden zusätzliche Informationen zu den empfohlenen Vorgehensweisen für die Anwendung von Sicherheitsupdates von Microsoft bereitgestellt.

**Weitere Sicherheitsupdates**

Updates für andere Sicherheitsrisiken sind unter den folgenden Adressen erhältlich:

-   Sicherheitsupdates sind im [Microsoft Download Center](http://www.microsoft.com/downloads/results.aspx?displaylang=de&freetext=sicherheitsupdate) verfügbar. Sie können am einfachsten durch eine Suche nach dem Begriff „security update“ ermittelt werden.
-   Updates für Benutzerplattformen sind auf [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747&displaylang=de) verfügbar.
-   Die Sicherheitsupdates, die in diesem Monat über Windows Update veröffentlicht wurden, können Sie auch im „Security and Critical Releases ISO CD Image“ über Microsoft Download Center erhalten. Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 913086](http://support.microsoft.com/kb/913086/de).

**IT Pro Security Community**

Erfahren Sie, wie Sie die Sicherheit Ihrer IT-Umgebung erhöhen und Ihren IT-Betrieb optimieren können. Diskutieren Sie auf der [IT Pro Security Zone](http://go.microsoft.com/fwlink/?linkid=21164) Website mit anderen IT-Profis über das Thema Sicherheit.

#### Danksagungen

Microsoft [dankt](http://www.microsoft.com/germany/technet/sicherheit/bulletins/policy.mspx) den folgenden Personen, dass sie zum Schutz unserer Kunden mit uns zusammengearbeitet haben:

-   Gregory Fleischer für den Hinweis auf ein in MS08-069 beschriebenes Problem.
-   Stefano Di Paola von [Minded Security](http://www.mindedsecurity.com/) für den Hinweis auf ein in MS08-069 beschriebenes Problem.

#### Support

-   Die betroffene Software wurde getestet, um die betroffenen Versionen zu ermitteln. Andere Versionen haben das Ende ihrer Supportlebenszyklen erreicht. Besuchen Sie die Website [Microsoft Support Lifecycle](http://support.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle&displaylang=de), um den Supportlebenszyklus für Ihre Softwareversion zu ermitteln.
-   Technischer Support ist über die [Microsoft Support Services](http://go.microsoft.com/fwlink/?linkid=21131) erhältlich. Supportanrufe zu Sicherheitsupdates sind kostenlos.
-   Kunden außerhalb der USA erhalten Support bei ihren regionalen Microsoft-Niederlassungen. Supportanfragen zu Sicherheitsupdates sind kostenlos. Weitere Informationen dazu, wie Sie Microsoft in Bezug auf Supportfragen kontaktieren können, finden Sie auf der Website [Internationale Hilfe und Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Haftungsausschluss

Die Informationen der Microsoft Knowledge Base werden wie besehen und ohne jede Gewährleistung bereitgestellt. Microsoft schließt alle anderen Garantien, gleich ob ausdrücklich oder konkludent, einschließlich der Garantien der Handelsüblichkeit oder Eignung für einen bestimmten Zweck aus. In keinem Fall kann Microsoft Corporation und/oder deren jeweilige Lieferanten haftbar gemacht werden für Schäden irgendeiner Art, einschließlich direkter, indirekter, zufällig entstandener Schäden, Folgeschäden, Folgen entgangenen Gewinns oder spezieller Schäden, selbst dann nicht, wenn Microsoft Corporation und/oder deren jeweilige Lieferanten auf die mögliche Entstehung dieser Schäden hingewiesen wurde. Weil in einigen Staaten/Rechtsordnungen der Ausschluss oder die Beschränkung einer Haftung für zufällig entstandene Schäden oder Folgeschäden nicht gestattet ist, gilt die obige Einschränkung eventuell nicht für Sie.

#### Revisionen

-   V1.0 (11. November 2008): Bulletin Summary veröffentlicht.
-   V2.0 (29. April 2009): Microsoft XML Core Services 4.0 (KB954430) unter 32-Bit- und x64-basierten Editionen von Windows Vista Service Pack 2 und unter 32-Bit-, x64-basierten und Itanium-basierten Editionen von Windows Server 2008 Service Pack 2 wurden als betroffene Software für MS08-069 hinzugefügt. Dies ist lediglich eine Erkennungsänderung. Die Binärdateien wurden nicht verändert. Benutzer, die KB954430 bereits erfolgreich installiert haben, müssen es nicht erneut installieren.
-   V3.0 (13. Oktober 2009): Microsoft XML Core Services 4.0 (KB954430) unter 32-Bit- und x64-basierten Editionen von Windows 7 und unter x64-basierten und Itanium-basierten Editionen von Windows Server 2008 R2 wurden als betroffene Software für MS08-069 hinzugefügt. Dies ist lediglich eine Erkennungsänderung. Die Binärdateien wurden nicht verändert. Benutzer, die KB954430 bereits erfolgreich installiert haben, müssen es nicht erneut installieren.
-   V4.0 (12. Juli 2011): Microsoft XML Core Services 4.0 (KB954430) unter 32-Bit- und x64-basierten Editionen von Windows 7 Service Pack 1 und unter x64-basierten und Itanium-basierten Editionen von Windows Server 2008 R2 Service Pack 1 wurden als betroffene Software für MS08-069 hinzugefügt. Dies ist lediglich eine Erkennungsänderung. Die Binärdateien wurden nicht verändert. Benutzer, die KB954430 bereits erfolgreich installiert haben, müssen es nicht erneut installieren.

*Built at 2014-04-18T01:50:00Z-07:00*
