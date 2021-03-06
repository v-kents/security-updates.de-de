---
TOCTitle: 'MS07-AUG'
Title: Microsoft Security Bulletin Summary für August 2007
ms:assetid: 'ms07-aug'
ms:contentKeyID: 61225044
ms:mtpsurl: 'https://technet.microsoft.com/de-DE/library/ms07-aug(v=Security.10)'
---

Security Bulletin Summary

Microsoft Security Bulletin Summary für August 2007
===================================================

Veröffentlicht: Dienstag, 14. August 2007 | Aktualisiert: Dienstag, 24. Juni 2008

**Version:** 4,0

In diesem Bulletin Summary sind die im August 2007 veröffentlichten Security Bulletins aufgeführt.

Mit der Veröffentlichung der Bulletins für August 2007 ersetzt dieses Bulletin Summary die Bulletin Advance Notification, die erstmalig am 9. August 2007 veröffentlicht wurde. Weitere Informationen zum Bulletin Advance Notification-Service finden Sie unter [Microsoft Security Bulletin Advance Notification.](http://www.microsoft.com/germany/technet/sicherheit/bulletins/bulletinadvance.mspx)

Weitere Informationen zum Erhalten automatischer Benachrichtigungen über die Veröffentlichung von Microsoft Security Bulletins finden Sie unter [Microsoft Technische Sicherheitsbenachrichtigungen](http://www.microsoft.com/germany/technet/sicherheit/bulletins/notify.mspx).

Am Mittwoch, den 15. August 2007 um 20:00 Uhr (MEZ) führt Microsoft einen englischsprachigen Webcast durch, um Kundenfragen zu diesen Bulletins zu beantworten. [Registrieren Sie sich jetzt für das Security Bulletin-Webcast im August.](http://msevents.microsoft.com/cui/webcasteventdetails.aspx?eventid=1032344688&eventcategory=4&culture=en-us&countrycode=us)Ab diesem Datum steht dieser Webcast auf Anfrage zur Verfügung. Weitere Informationen dazu finden Sie unter [Microsoft Security Bulletin Zusammenfassungen und Webcasts.](http://technet.microsoft.com/security/bulletin/summary)

Microsoft stellt auch Informationen bereit, anhand derer Benutzer die Prioritäten für monatliche Sicherheitsupdates und alle nicht sicherheitsrelevanten wichtigen Updates festlegen können, die an demselben Tag veröffentlicht werden wie die monatlichen Sicherheitsupdates. Bitte lesen Sie den Abschnitt **Weitere Informationen**.

### Bulletin-Informationen

#### Kurzzusammenfassungen

Die Security Bulletins für diesen Monat, nach Schweregrad geordnet:

Kritisch (6)
------------

| Kennung des Bulletins                       | Microsoft Security Bulletin MS07-042                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|---------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Sicherheitsanfälligkeit in Microsoft XML Core Services kann Remotecodeausführung ermöglichen (936227)**](http://go.microsoft.com/fwlink/?linkid=88350)                                                                                                                                                                                                                                                                                                                                                                                     |
| **Kurzzusammenfassung**                     | Dieses kritische Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit. Wenn ein Benutzer eine speziell gestaltete Webseite mit Internet Explorer anzeigt, kann diese Sicherheitsanfälligkeit Remotecodeausführung ermöglichen. Die Sicherheitsanfälligkeit kann durch Angriffe auf Microsoft XML Core Services ausgenutzt werden. Für Benutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten. |
| **Bewertung des maximalen Schweregrads:**   | [Kritisch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **Auswirkung der Sicherheitsanfälligkeit:** | Remotecodeausführung                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Das Update erfordert einen Neustart.                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Betroffene Software**                     | **Windows, XML Core Services.**Weitere Informationen finden Sie im Abschnitt "Betroffene Software und Downloadadressen".                                                                                                                                                                                                                                                                                                                                                                                                                      |

| Kennung des Bulletins                       | Microsoft Security Bulletin MS07-043                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|---------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Sicherheitsanfälligkeit in OLE-Automatisierung kann Remotecodeausführung ermöglichen (921503)**](http://go.microsoft.com/fwlink/?linkid=70249)                                                                                                                                                                                                                                                                                                                                                                              |
| **Kurzzusammenfassung**                     | Dieses kritische Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit. Wenn ein Benutzer eine speziell gestaltete Webseite anzeigt, kann diese Sicherheitsanfälligkeit Remotecodeausführung ermöglichen. Die Sicherheitsanfälligkeit kann durch Angriffe auf OLE (Object Linking and Embedding) ausgenutzt werden. Für Benutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten. |
| **Bewertung des maximalen Schweregrads:**   | [Kritisch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Auswirkung der Sicherheitsanfälligkeit:** | Remotecodeausführung                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Das Update erfordert einen Neustart.                                                                                                                                                                                                                                                                                                                                                                                         |
| **Betroffene Software**                     | **Windows, Visual Basic, Office für Mac.**Weitere Informationen finden Sie im Abschnitt "Betroffene Software und Downloadadressen".                                                                                                                                                                                                                                                                                                                                                                                            |

| Kennung des Bulletins                       | Microsoft Security Bulletin MS07-044                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|---------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Sicherheitsanfälligkeit in Microsoft Excel kann Remotecodeausführung ermöglichen (940965)**](http://go.microsoft.com/fwlink/?linkid=96778)                                                                                                                                                                                                                                                                                                                                                                                         |
| **Kurzzusammenfassung**                     | Mit diesem Sicherheitsupdate wird eine Sicherheitsanfälligkeit, die vertraulich gemeldet wurde, zusammen mit anderen Sicherheitsproblemen behoben, die im Laufe der Untersuchungen identifiziert wurden. Diese Sicherheitsanfälligkeiten können Remotecodeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Excel-Datei öffnet. Für Benutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten. |
| **Bewertung des maximalen Schweregrads:**   | [Kritisch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Auswirkung der Sicherheitsanfälligkeit:** | Remotecodeausführung                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Für dieses Update ist kein Neustart des Computers erforderlich.                                                                                                                                                                                                                                                                                                                                                                     |
| **Betroffene Software**                     | **Office**. Weitere Informationen finden Sie im Abschnitt "Betroffene Software und Downloadadressen".                                                                                                                                                                                                                                                                                                                                                                                                                                 |

| Kennung des Bulletins                       | Microsoft Security Bulletin MS07-045                                                                                                                                                                                                                                                                                                                                                                                                            |
|---------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Kumulatives Sicherheitsupdate für Internet Explorer (937143)**](http://www.microsoft.com/germany/technet/sicherheit/bulletins/ms07-045.mspx)                                                                                                                                                                                                                                                                                                 |
| **Kurzzusammenfassung**                     | Dieses kritische Sicherheitsupdate behebt drei vertraulich gemeldete Sicherheitsanfälligkeiten. Wenn ein Benutzer eine speziell gestaltete Website mit Internet Explorer anzeigt, können diese Sicherheitsanfälligkeiten Remotecodeausführung ermöglichen. Für Benutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten. |
| **Bewertung des maximalen Schweregrads:**   | [Kritisch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                             |
| **Auswirkung der Sicherheitsanfälligkeit:** | Remotecodeausführung                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Das Update erfordert einen Neustart.                                                                                                                                                                                                                                                                                                          |
| **Betroffene Software**                     | **Windows, Internet Explorer**. Weitere Informationen finden Sie im Abschnitt "Betroffene Software und Downloadadressen".                                                                                                                                                                                                                                                                                                                       |

| Kennung des Bulletins                       | Microsoft Security Bulletin MS07-046                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|---------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Sicherheitsanfälligkeit in GDI kann Remotecodeausführung ermöglichen (938829)**](http://go.microsoft.com/fwlink/?linkid=94466)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Kurzzusammenfassung**                     | Dieses kritische Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit. Im Grafikwiedergabemodul liegt eine Sicherheitsanfälligkeit vor, die Remotecodeausführung ermöglichen kann und durch die Art und Weise verursacht wird, in der speziell gestaltete Bilder verarbeitet werden. Ein Angreifer kann diese Sicherheitsanfälligkeit ausnutzen, indem er ein speziell gestaltetes Bild erstellt, das u. U. eine Remotecodeausführung ermöglicht, wenn ein Benutzer einen speziell gestalteten Anhang in einer E-Mail öffnet. Nutzt ein Angreifer diese Sicherheitsanfälligkeit erfolgreich aus, kann er die vollständige Kontrolle über ein betroffenes System erlangen. |
| **Bewertung des maximalen Schweregrads:**   | [Kritisch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Auswirkung der Sicherheitsanfälligkeit:** | Remotecodeausführung                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Das Update erfordert einen Neustart.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **Betroffene Software**                     | **Windows.**Weitere Informationen finden Sie im Abschnitt "Betroffene Software und Downloadadressen".                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |

| Kennung des Bulletins                       | Microsoft Security Bulletin MS07-050                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|---------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Sicherheitsanfälligkeit in VML (Vector Markup Language) kann Remotecodeausführung ermöglichen (938127)**](http://go.microsoft.com/fwlink/?linkid=94737)                                                                                                                                                                                                                                                                                                                                      |
| **Kurzzusammenfassung**                     | Dieses Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit in der VML-Implementierung (Vector Markup Language) in Windows. Wenn ein Benutzer eine speziell gestaltete Webseite mit Internet Explorer anzeigt, kann diese Sicherheitsanfälligkeit Remotecodeausführung ermöglichen. Für Benutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten. |
| **Bewertung des maximalen Schweregrads:**   | [Kritisch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                                                             |
| **Auswirkung der Sicherheitsanfälligkeit:** | Remotecodeausführung                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Das Update erfordert einen Neustart.                                                                                                                                                                                                                                                                                                                                                          |
| **Betroffene Software**                     | **Windows, Internet Explorer**. Weitere Informationen finden Sie im Abschnitt "Betroffene Software und Downloadadressen".                                                                                                                                                                                                                                                                                                                                                                       |

Hoch (3)
--------

| Kennung des Bulletins                       | Microsoft Security Bulletin MS07-047                                                                                                                                                                                                                                                                                                                                                                                                     |
|---------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Sicherheitsanfälligkeit in Windows Media Player kann Remotecodeausführung ermöglichen (936782)**](http://go.microsoft.com/fwlink/?linkid=88628)                                                                                                                                                                                                                                                                                       |
| **Kurzzusammenfassung**                     | Dieses wichtige Sicherheitsupdate behebt zwei vertraulich gemeldete Sicherheitsanfälligkeiten. Diese Sicherheitsanfälligkeiten können Codeausführung ermöglichen, wenn ein Benutzer eine speziell gestaltete Datei in Windows Media Player anzeigt. Für Benutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten. |
| **Bewertung des maximalen Schweregrads:**   | [Hoch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                          |
| **Auswirkung der Sicherheitsanfälligkeit:** | Remotecodeausführung                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Für dieses Update ist kein Neustart des Computers erforderlich.                                                                                                                                                                                                                                                                        |
| **Betroffene Software**                     | **Windows.**Weitere Informationen finden Sie im Abschnitt "Betroffene Software und Downloadadressen".                                                                                                                                                                                                                                                                                                                                    |

| Kennung des Bulletins                       | Microsoft Security Bulletin MS07-048                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|---------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Sicherheitsanfälligkeiten in Windows-Minianwendung können Remotecodeausführung ermöglichen (938123)**](http://go.microsoft.com/fwlink/?linkid=94465)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Kurzzusammenfassung**                     | Mit diesem wichtigen Update werden zwei Sicherheitsanfälligkeiten behoben, die vertraulich gemeldet wurden, zusammen mit anderen Sicherheitsanfälligkeiten, die im Laufe der Untersuchungen identifiziert wurden. Diese Sicherheitsanfälligkeiten können einem anonymen Remoteangreifer ermöglichen, Code mit den Berechtigungen eines angemeldeten Benutzers auszuführen. Wenn ein Benutzer in der Minianwendung "Feedschlagzeilen" einen schädlichen RSS-Feed abonniert oder in der Minianwendung "Kontakte" eine schädliche Kontaktdatei hinzugefügt oder in der Minianwendung "Wetter" auf einen schädlichen Link geklickt hat, kann ein Angreifer Code auf dem System ausführen. Für Benutzer, deren Konten mit weniger Benutzerrechten konfiguriert sind, kann dies bei allen Angriffsmethoden geringere Auswirkungen haben als für Benutzer, die mit administrativen Benutzerrechten arbeiten. |
| **Bewertung des maximalen Schweregrads:**   | [Hoch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Auswirkung der Sicherheitsanfälligkeit:** | Remotecodeausführung                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Das Update erfordert einen Neustart.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Betroffene Software**                     | **WindowsVista.**Weitere Informationen finden Sie im Abschnitt "Betroffene Software und Downloadadressen".                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |

| Kennung des Bulletins                       | Microsoft Security Bulletin MS07-049                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|---------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Titel des Bulletins**                     | [**Sicherheitsanfälligkeit in Virtual PC und Virtual Server kann Erhöhung von Berechtigungen ermöglichen (937986)**](http://go.microsoft.com/fwlink/?linkid=92734)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Kurzzusammenfassung**                     | Dieses wichtige Sicherheitsupdate behebt eine vertraulich gemeldete Sicherheitsanfälligkeit. Diese Sicherheitsanfälligkeit kann für eine lokale Erhöhung von Berechtigungen ausgenutzt werden. Die Sicherheitsanfälligkeit in Microsoft Virtual PC und Microsoft Virtual Server kann einem Benutzer eines Gastbetriebssystems ermöglichen, Code auf dem Host oder einem weiteren Gastbetriebssystem auszuführen. Nur Benutzer von Gastbetriebssystemen, denen administrative Berechtigungen für das Gastbetriebssystem gewährt wurden, können diese Sicherheitsanfälligkeit ausnutzen. Benutzer von Gastbetriebssystemen, denen keine administrativen Berechtigungen für das Gastbetriebssystem gewährt wurden, können diese Sicherheitsanfälligkeit nicht ausnutzen. |
| **Bewertung des maximalen Schweregrads:**   | [Hoch](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Auswirkung der Sicherheitsanfälligkeit:** | Erhöhung von Berechtigungen                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| **Erkennung**                               | Microsoft Baseline Security Analyzer kann erkennen, ob Ihr Computersystem dieses Update benötigt. Für dieses Update ist kein Neustart des Computers erforderlich.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Betroffene Software**                     | **Virtual PC, Virtual Server.**Weitere Informationen finden Sie im Abschnitt "Betroffene Software und Downloadadressen".                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |

Betroffene Software und Downloadadressen
----------------------------------------

**Wie verwende ich diese Tabelle?**  

In dieser Tabelle finden Sie Informationen zu Sicherheitsupdates, die Sie möglicherweise installieren sollten. Sie sollten jedes aufgeführte Softwareprogramm und jede Komponente überprüfen, um zu sehen, ob Sicherheitsupdates erforderlich sind. Wenn ein Softwareprogramm oder eine Komponente aufgeführt ist, ist die Auswirkung der Sicherheitsanfälligkeit aufgelistet und mit einem Softwareupdate verlinkt.

**Hinweis:**Für eine Sicherheitsanfälligkeit müssen Sie möglicherweise mehrere Sicherheitsupdates installieren. Prüfen Sie für jede aufgeführte Kennung der Bulletins die gesamte Spalte, um basierend auf den in Ihrem System installierten Programmen und Komponenten alle Updates zu finden, die Sie installieren müssen.

#### Betroffene Software und Downloadadressen für MS07-042 bis MS07-046

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
<th style="border:1px solid black;" >
Details
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
[**MS07-042**](http://go.microsoft.com/fwlink/?linkid=88350)
</td>
<td style="border:1px solid black;">
[**MS07-043**](http://go.microsoft.com/fwlink/?linkid=70249)
</td>
<td style="border:1px solid black;">
[**MS07-044**](http://go.microsoft.com/fwlink/?linkid=96778)
</td>
<td style="border:1px solid black;">
[**MS07-045**](http://www.microsoft.com/germany/technet/sicherheit/bulletins/ms07-045.mspx)
</td>
<td style="border:1px solid black;">
[**MS07-046**](http://go.microsoft.com/fwlink/?linkid=94466)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des maximalen Schweregrads:**
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Betroffene Windows-Software:
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=5c35b6e8-732a-4451-b5d4-23ed63e6e792)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=8fc8340b-c2b3-4559-835c-caa00cf086b9)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=6e8de050-8589-4831-ae19-075c93509485)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=dc29475d-c0bb-4d35-8dd6-4ca1cac32315)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=b85bb583-dc61-4d37-b458-208f5bb07ece)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=3c81730a-981a-4649-b2d9-45144230d512)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=b85bb583-dc61-4d37-b458-208f5bb07ece)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?familyid=15d4d4fa-9bab-4da5-978e-f89c78c8086a)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=5374583d-de68-4d65-bca8-598d6b98b8b3)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?familyid=15d4d4fa-9bab-4da5-978e-f89c78c8086a)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?familyid=6608d722-3ef8-4085-b771-7b17bb0ba06e)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=c3359f27-e03e-4a4f-b896-3bda39f69f7e&displaylang=en)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?familyid=6608d722-3ef8-4085-b771-7b17bb0ba06e)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 mit SP1 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?familyid=fc04451a-0696-4a21-b2b6-f02d4e2c33bf)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=92822479-2060-4357-a340-ed096f180b2b)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 mit SP2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?familyid=fc04451a-0696-4a21-b2b6-f02d4e2c33bf)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2008 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2008 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Betroffene Systemkomponenten des Windows-Betriebssystems:
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 5.01 Service Pack 4 unter Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=fcf9440f-bb36-4ed1-9b6b-74a4f055650b&displaylang=de)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 6 Service Pack 1 unter Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=8db75461-4dca-43db-aa30-c7e67ce954ad&displaylang=de)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 6 für Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=5d31d916-867f-4dbf-b8a4-c75ea83f4f51&displaylang=de)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 6 für Windows XP Professional x64 Edition und Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=b15b2442-d6da-41dd-a424-11c9893be595&displaylang=de)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 6 für Windows Server 2003 Service Pack 1 und Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?familyid=f2f9fb69-0399-4df0-9f5b-8f42a130c581&displaylang=de)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 6 für Windows Server 2003 x64 Edition und Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?familyid=d0bd886d-2c80-4dd7-82b7-1bd1f8d398cc&displaylang=de)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 6 für Windows Server 2003 mit SP1 für Itanium-basierte Systeme und Windows Server 2003 mit SP2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?familyid=bf41033a-d6f0-451e-9b69-4cbe2bb3f804&displaylang=de)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 7 für Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?familyid=7a2b4395-eaba-45ec-8d0c-932ebcc3d344&displaylang=de)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 7 für Windows XP Professional x64 Edition und Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?familyid=cd7ed4d5-7790-41db-8b68-cfd59105ca36&displaylang=de)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 7 für Windows Server 2003 Service Pack 1 und Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Niedrig](http://www.microsoft.com/downloads/details.aspx?familyid=4f8daed8-9925-494d-b2f5-1e29f4040f6a&displaylang=de)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 7 für Windows Server 2003 x64 Edition und Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Niedrig](http://www.microsoft.com/downloads/details.aspx?familyid=34669ca2-46b0-4fbf-8fbd-ad7a13920103&displaylang=de)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 7 für Windows Server 2003 mit SP1 für Itanium-basierte Systeme und Windows Server 2003 mit SP2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Niedrig](http://www.microsoft.com/downloads/details.aspx?familyid=5bd7bcbd-528a-4a16-a39a-a5ff5f69a2e2&displaylang=de)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 7 in Windows Vista
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?familyid=9ae27b2f-aca4-4758-8ce4-a98f1ff6ba70&displaylang=de)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 7 in Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?familyid=53497e53-d10c-43af-ad56-9f07739a5284&displaylang=de)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 (KB936021) unter Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=245214ea-76f9-4755-8a14-a74232e20c1c)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 (KB936021) unter Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=dea6a48f-fb00-43f3-a374-3220f9759c2d)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 (KB936021) unter Windows XP Professional x64 Edition und Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=b8862ca9-1203-4056-a257-29271838ac0d)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 (KB936021) unter Windows Server 2003 Service Pack 1 und Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?familyid=12618ad0-aefd-4c9a-a769-4b14a7603d6e)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 (KB936021) unter Windows Server 2003 x64 Edition und Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?familyid=61bf00a9-aeea-431a-86d3-526a4a373bb7)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 (KB936021) unter Windows Server 2003 mit SP1 für Itanium-basierte Systeme und Microsoft Windows Server 2003 mit SP2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?familyid=b0285dd7-bf66-4226-9948-26e8aae99046)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 (KB936021) unter Windows Vista
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=c734d7de-5d87-4904-81c3-714db2cb8b0d)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 3.0 (KB936021) unter Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=0a465d77-a737-4d26-82a1-570f9c788a8a)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) bei Installation unter Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) unter Windows XP Service Pack 2 und Windows XP Service Pack 3
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) bei Installation unter Windows XP Professional x64 Edition und Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) unter Windows Server 2003 Service Pack 1 und Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) unter Windows Server 2003 x64 Edition und Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) unter Windows Server 2003 mit SP1 für Itanium-basierte Systeme und Microsoft Windows Server 2003 mit SP2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) bei Installation unter Windows Vista und Windows Vista Service Pack 1
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) bei Installation unter Windows Vista x64 Edition und Windows Vista x64 Edition Service Pack 1
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) bei Installation unter Windows Server 2008 für 32-Bit-Systeme
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) bei Installation unter Windows Server 2008 für x64-basierte Systeme
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 4.0 (KB936181) bei Installation unter Windows Server 2008 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?familyid=021e12f5-cb46-43df-a2b8-185639ba2807)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 6.0  
(KB933579) bei Installation unter Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=70c92e77-9e5a-41b1-a9d2-64443913c976)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 6.0 (KB933579) bei Installation unter Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=70c92e77-9e5a-41b1-a9d2-64443913c976)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 6.0 (KB933579) bei Installation unter Windows XP Professional x64 Edition und Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=70c92e77-9e5a-41b1-a9d2-64443913c976)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 6.0 (KB933579) unter Windows Server 2003 Service Pack 1 und Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?familyid=70c92e77-9e5a-41b1-a9d2-64443913c976)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 6.0 (KB933579) unter Windows Server 2003 x64 Edition und Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?familyid=70c92e77-9e5a-41b1-a9d2-64443913c976)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 6.0 (KB933579) unter Windows Server 2003 mit SP1 für Itanium-basierte Systeme und Microsoft Windows Server 2003 mit SP2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
[Mittel](http://www.microsoft.com/downloads/details.aspx?familyid=70c92e77-9e5a-41b1-a9d2-64443913c976)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft XML Core Services 6.0 (KB933579) unter Windows Vista
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=14270529-3ae5-43bf-a471-722ab010d81e)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft XML Core Services 6.0 (KB933579) unter Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=928da3d2-b0b9-447a-b37a-4350497fe563)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Betroffene Office-Software
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel 2000 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=082b98f7-9556-4f1f-823a-c41ddf5a7c9a&displaylang=de)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Excel 2002 Service Pack 3
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?familyid=91308769-2577-4f9f-8209-06f2c8c8a86f&displaylang=de)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?familyid=b0130e9e-8845-4d79-aaa1-a21cc9388abe&displaylang=de)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office 2003 Service Pack 2 mit Microsoft XML Core Services 5.0 (KB936048)
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=a339cb7b-e08a-47f8-ac0b-df449191424a&displaylang=de)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Excel Viewer 2003
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?familyid=c4a87572-3128-44f7-8069-95535a78500a&displaylang=de)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Word Viewer 2003 mit Microsoft XML Core Services 5.0 (KB936048)
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=a339cb7b-e08a-47f8-ac0b-df449191424a)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office 2004 für Mac
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/mac/downloads.aspx)
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/mac/downloads.aspx)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
2007 Office System mit Microsoft XML Core Services 5.0 (KB936960)
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=7a97478a-832c-4a6b-b074-0e18b1e4ed33)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Office Groove Server 2007 mit Microsoft XML Core Services 5.0 (KB936056)
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=e875613b-2f32-4f28-a635-664a25c95c18)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Office SharePoint Server mit Microsoft XML Core Services 5.0 (KB936056)
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=e875613b-2f32-4f28-a635-664a25c95c18)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="6" style="border:1px solid black;">
Weitere betroffene Software:
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Visual Basic 6.0 Service Pack 6 (KB924053)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=e1646fb0-29d5-4a6e-a8d2-304c4d7735b7)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
</table>
 
**Hinweise**

**<sup>[1]</sup>**Für dieses Betriebssystem steht ein Sicherheitsupdate zur Verfügung. In der Tabelle finden Sie weitere Informationen zum entsprechenden Security Bulletin für die betroffene Software oder Komponente. 

#### Betroffene Software und Downloadadressen für MS07-047 bis MS07-050

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
[**MS07-047**](http://go.microsoft.com/fwlink/?linkid=88628)
</td>
<td style="border:1px solid black;">
[**MS07-048**](http://go.microsoft.com/fwlink/?linkid=94465)
</td>
<td style="border:1px solid black;">
[**MS07-049**](http://go.microsoft.com/fwlink/?linkid=92734)
</td>
<td style="border:1px solid black;">
[**MS07-050**](http://go.microsoft.com/fwlink/?linkid=94737)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
**Bewertung des maximalen Schweregrads:**
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
<td style="border:1px solid black;">
[**Kritisch**](http://www.microsoft.com/germany/technet/datenbank/articles/527029.mspx)
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Betroffene Windows-Software:
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows XP Professional x64 Edition
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 1
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Server 2003 mit SP1 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Server 2003 mit SP2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Vista
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?familyid=49a5bd84-da71-4529-b4d3-ac57dab59e01)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?familyid=24443f59-b908-480b-9b72-7094d4b5e128)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
**<sup>[1]</sup>**
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Betroffene Systemkomponenten des Windows-Betriebssystems:
</th>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 5.01 Service Pack 4 unter Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=31e63d6f-b6b7-41d7-8ae6-dd7fcf89d477)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 6 Service Pack 1 unter Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=7099d33a-0ef6-423f-824e-757482517612)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 6 für Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=4447d74f-09ea-4be0-9dae-c243ce657fb7)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 6 für Windows XP Professional x64 Edition und Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=98ccd207-f4d0-4625-aeab-0ebf1643a5fd)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 6 für Windows Server 2003 Service Pack 1 und Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=463535aa-e04e-4a30-b3ab-8cd6d8cdd13c)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 6 für Windows Server 2003 x64 Edition und Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=9d4375d4-fb9b-4771-bd6f-e5d23eedbc6b)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 6 für Windows Server 2003 mit SP1 für Itanium-basierte Systeme und Windows Server 2003 mit SP2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=c7be313b-3405-42e1-9e4b-0cb6bf3d2cb1)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 7 für Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=9f5da816-194c-478e-8a96-9421a0c52c9f)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 7 für Windows XP Professional x64 Edition und Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=1c3168a9-d959-4137-868a-ec70da737c21)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 7 für Windows Server 2003 Service Pack 1 und Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=59884e97-4912-4a9a-8a31-8182ea2d24db)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 7 für Windows Server 2003 x64 Edition und Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=42060e27-de14-4d0c-92a0-138cb57fe2b5)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 7 für Windows Server 2003 mit SP1 für Itanium-basierte Systeme und Windows Server 2003 mit SP2 für Itanium-basierte Systeme
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=a536206e-9d1b-49a8-81a1-53d46f2de973)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Internet Explorer 7 in Windows Vista
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=2dd908a4-6152-4976-aaaa-01f5f37c9143)
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Internet Explorer 7 in Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Kritisch](http://www.microsoft.com/downloads/details.aspx?familyid=592435bc-1d43-4544-bd8a-4a2d829dc1a1)
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Media Player 7.1 unter Microsoft Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=9f46b1fc-ee7b-437f-9492-67d003711021)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Windows Media Player 9 bei Installation unter Windows 2000 Service Pack 4
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?familyid=bd4a6474-5fde-415e-840e-7d973cb71c95)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Media Player 9 unter Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?familyid=bd4a6474-5fde-415e-840e-7d973cb71c95)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Media Player 10 bei Installation unter Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=48f5a9d3-b859-4cb6-a68e-abde76a14782)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Media Player 10 unter Windows XP Professional x64 Edition und Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?familyid=949580be-cbb3-4271-8ca0-0ead7f2d8801&displaylang=en)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Media Player 10 für Windows Server 2003 Service Pack 1 und Windows Server 2003 Service Pack 2
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?familyid=8d9f1fdf-6d4c-44d4-9b5f-bdbe8ac28d7f)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Media Player 10 unter Windows Server 2003 x64 Edition und Windows Server 2003 x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?familyid=2c04c7f2-728e-43bd-8574-26e411fcd129)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Media Player 11 bei Installation unter Windows XP Service Pack 2
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=a690d042-1137-4aaf-bd0e-565ea04d1f2b)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Media Player 11 unter Windows XP Professional x64 Edition und Windows XP Professional x64 Edition Service Pack 2
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?familyid=bdc89f34-c1ff-46ab-b52d-c02d51c5c373&displaylang=en)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Windows Media Player 11 unter Windows Vista
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=80e5167c-4f75-4ce3-8b15-2f50958deec8)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Windows Media Player 11 unter Windows Vista x64 Edition
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=bf30b714-d6e7-47ea-b79e-84c18370a661)
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<th colspan="5" style="border:1px solid black;">
Weitere betroffene Software:
</th>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual PC 2004
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?familyid=cbdeaa50-7115-4673-97c4-10009f9c5c42)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual PC 2004 Service Pack 1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=17ffe5a2-3551-4858-93b6-5e25af87d808)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 Standard Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?familyid=bc02ea6d-2884-4637-9894-3413a71329ee)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 Enterprise Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/http://www.microsoft.com/downloads/details.aspx?familyid=da474b6f-9f0c-43f6-b432-050f7e76967d)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 R2 Standard Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=43fa1327-8e5e-4c92-901f-1ff2a0a087b4)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual Server 2005 R2 Enterprise Edition
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/downloads/details.aspx?displaylang=de&familyid=c2fc16c4-1fb0-4c09-b04a-684b40df8517)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr class="alternateRow">
<td style="border:1px solid black;">
Microsoft Virtual PC für Mac Version 6.1
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/germany/mac/downloads.mspx)
</td>
<td style="border:1px solid black;">
</td>
</tr>
<tr>
<td style="border:1px solid black;">
Microsoft Virtual PC für Mac Version 7
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
</td>
<td style="border:1px solid black;">
[Hoch](http://www.microsoft.com/germany/mac/downloads.mspx)
</td>
<td style="border:1px solid black;">
</td>
</tr>
</table>
 
**Hinweise**

**<sup>[1]</sup>**Für dieses Betriebssystem steht ein Sicherheitsupdate zur Verfügung. In der Tabelle finden Sie weitere Informationen zum entsprechenden Security Bulletin für die betroffene Software oder Komponente. 

Tools und Anleitungen zur Erkennung und Bereitstellung
------------------------------------------------------

**Sicherheitsportal:**

Verwalten Sie die Software und die Sicherheitsupdates, die Sie den Servern, Desktops und mobilen Computer in Ihrer Organisation bereitstellen müssen. Weitere Informationen finden Sie im [TechNet Update Management Center](http://technet.microsoft.com/de-de/updatemanagement/default.aspx). Im [TechNet Security Center](http://www.microsoft.com/germany/technet/sicherheit/default.mspx)werden zusätzliche Informationen zur Sicherheit in Microsoft-Produkten zur Verfügung gestellt. Verbraucher können die Seite [Sicherheit zu Hause](http://www.microsoft.com/germany/athome/security/default.mspx)besuchen, wo diese Informationen auch durch einen Klick auf "Die neuesten Sicherheitsupdates" verfügbar sind.

Sicherheitsupdates sind auch über [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747), [Windows Update](http://go.microsoft.com/fwlink/?linkid=21130)und [Office Update](http://office.microsoft.com/de-de/downloads/default.aspx)verfügbar. Sicherheitsupdates sind auch im [Microsoft Download Center](http://www.microsoft.com/downloads/results.aspx?displaylang=de&freetext=sicherheitsupdate)verfügbar. und können am einfachsten durch eine Suche nach dem Begriff "security\_patch" oder "security\_update" ermittelt werden. Außerdem können Sicherheitsupdates vom Windows Update-Katalog heruntergeladen werden. Weitere Informationen zum Windows Update-Katalog finden Sie im [Microsoft Knowledge Base-Artikel 323166](http://support.microsoft.com/kb/323166).

**Anleitungen zur Erkennung und Bereitstellung**

Zu den Sicherheitsupdates dieses Monats stellt Microsoft Anleitungen zur Erkennung und Bereitstellung zur Verfügung: Diese Anleitungen geben auch IT-Profis Informationen zum Einsatz der verschiedenen Tools und zur Bereitstellung des Sicherheitsupdates. Behandelt werden u. a. Windows Update, Microsoft Update, Office Update, Microsoft Baseline Security Analyzer (MBSA), Office Detection Tool, Microsoft Systems Management Server (SMS), Extended Security Update Inventory Tool und Enterprise Update Scan Tool (EST). Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 910723](http://support.microsoft.com/kb/910723).

**Microsoft Baseline Security Analyzer undEnterpriseUpdate Scan Tool**

Mit dem Microsoft Baseline Security Analyzer können Sie als Administrator Systeme sowohl lokal als auch remote auf fehlende Sicherheitspatches und fehlerhafte Konfigurationen überprüfen. Weitere Informationen zu MBSA finden Sie auf der Website [Microsoft Baseline Security Analyzer](http://www.microsoft.com/germany/technet/sicherheit/tools/mbsa/2_0.mspx).

Wenn MBSA 1.2.1 die Erkennung für ein bestimmtes Sicherheitsupdate nicht unterstützen kann, veröffentlicht Microsoft für dieses bestimmte Sicherheitsupdate eine Version des Enterprise Update Scan Tools (EST). Weitere Informationen zu EST finden Sie auf der Website [Enterprise Update Scan Tool](http://support.microsoft.com/default.aspx?id=894193).

**Hinweis:**Nach dem 9. Oktober 2007 wird die von MBSA 1.2.1 verwendete Datei MSSecure.XML nicht mehr aktualisiert. Nach diesem Datum werden keine neuen Sicherheitsupdates für die von MBSA 1.2.1 verwendete Datei MSSecure.XML erstellt und keine neuen Versionen des Enterprise Scan Tools veröffentlicht. Weitere Informationen dazu finden Sie auf der Website [Microsoft Baseline Security Analyzer](http://www.microsoft.com/germany/technet/sicherheit/tools/mbsa/2_0.mspx).

**Windows Server Update Services**

Mithilfe der Windows Server Update Services (WSUS), können Administratoren die neuesten wichtigen Aktualisierungen und Sicherheitsupdates für Windows 2000 und höher, Office XP und höher, Exchange Server 2003 und SQL Server 2000 schnell und zuverlässig bereitstellen.

Weitere Informationen zum Bereitstellen dieses Sicherheitsupdates mithilfe der Windows Server Update Services finden Sie auf der [Windows Server Update Services Website](http://www.microsoft.com/germany/technet/prodtechnol/windowsserver/wsus/default.mspx).

**Systems Management Server**

Der Systems Management Server von Microsoft stellt eine wertvolle Hilfe beim Bereitstellen von Sicherheitsupdates in Ihrer IT-Umgebung dar. Durch die Verwendung von SMS können Administratoren auf Windows basierte Systeme identifizieren, für die Sicherheitsupdates erforderlich sind, und für eine kontrollierte Bereitstellung dieser Updates im gesamten Unternehmen bei minimalen Unterbrechungen für Endbenutzer sorgen. Weitere Informationen zur Verwendung von SMS 2003 durch Administratoren für die Bereitstellung von Sicherheitsupdates finden Sie auf der Website [SMS 2003 Security Patch Management](http://go.microsoft.com/fwlink/?linkid=22939). Benutzer von SMS 2.0 können auch die Website [Software Updates Service Feature Pack](http://www.microsoft.com/technet/prodtechnol/sms/sms2/downloads/featurepacks/suspack/default.mspx)besuchen, um Hilfe bei der Bereitstellung von Sicherheitsupdates zu erhalten. Weitere Informationen zu SMS finden Sie auf der Website [Microsoft Systems Management Server](http://www.microsoft.com/germany/smserver/default.mspx).

**Hinweis:**SMS nutzt Microsoft Baseline Security Analyzer und das Microsoft Office Detection Tool, um eine breite Unterstützung bei der Erkennung und der Bereitstellung von Security Bulletin-Updates bereitzustellen. Einige Softwareupdates werden von diesen Tools möglicherweise nicht erkannt. Administratoren können in diesen Fällen die Inventurfunktionen von SMS nutzen, um Updates auf ausgewählten Systemen zu installieren. Weitere Informationen zu diesem Verfahren finden Sie auf der Website [Bereitstellen von Softwareupdates mit der Funktion zur Softwareverteilung von SMS](http://www.microsoft.com/technet/sms/2003/patchupdate.mspx). Bei einigen Sicherheitsupdates, die einen Neustart des Systems erfordern, sind unter Umständen administrative Rechte nötig. Administratoren können das im [SMS 2003 Administration Feature Pack](http://www.microsoft.com/technet/prodtechnol/sms/sms2003/downloads/featurepacks/adminpack.mspx)und im [SMS 2.0 Administration Feature Pack](http://go.microsoft.com/fwlink/?linkid=21161)enthaltene Elevated Rights Deployment Tool verwenden, um diese Updates zu installieren.

### Weitere Informationen:

#### Windows-Tool zum Entfernen bösartiger Software

Microsoft hat eine aktualisierte Version des Microsoft Windows-Tools zum Entfernen bösartiger Software in Windows Update, Microsoft Update, Windows Server Update Services und dem Download Center veröffentlicht.

#### Nicht sicherheitsrelevante, wichtige Updates unter MU, WU und WSUS:

Für diesen Monat:

-   Microsoft hat vier **nicht sicherheitsrelevante**Updates mit hoher Priorität auf Microsoft Update (MU) und Windows Server Update Services (WSUS) veröffentlicht.
-   Microsoft hat zwei **nicht sicherheitsrelevante**Updates mit hoher Priorität für Windows auf Windows-Update (WU) veröffentlicht.

Diese Informationen gelten **nur**für wichtige, **nicht sicherheitsrelevante**Updates auf Microsoft Update, Windows Update und Windows Server Update Services, die an demselben Tag wie das Security Bulletin Summary veröffentlicht wurden. Es werden **keine**Informationen zu **nicht sicherheitsrelevanten**Updates bereitgestellt, die an anderen Tagen veröffentlicht werden.

#### Sicherheitsstrategien und Community

**Strategien für die Verwaltung von Sicherheitspatches:**

Nutzen Sie den [Microsoft-Leitfaden zur Sicherheitspatch-Verwaltung](http://www.microsoft.com/germany/technet/sicherheit/themen/patchmanagement.mspx). Er enthält Best Practices und von Microsoft empfohlene Vorgehensweisen für die Bereitstellung, Verteilung und Installation von Sicherheitsupdates in Ihrer IT-Umgebung.

**Weitere Sicherheitsupdates**

Updates für andere Sicherheitsrisiken sind unter den folgenden Adressen erhältlich:

-   Sicherheitsupdates sind im [Microsoft Download Center](http://www.microsoft.com/downloads/results.aspx?displaylang=de&freetext=sicherheitsupdate)verfügbar und können am einfachsten durch eine Schlüsselwortsuche nach dem Begriff "security\_patch" ermittelt werden.
-   Updates für Benutzerplattformen sind auf [Microsoft Update](http://go.microsoft.com/fwlink/?linkid=40747)verfügbar.
-   Die Sicherheitsupdates, die in diesem Monat über Windows Update veröffentlicht wurden, können Sie auch im "Security and Critical Releases ISO CD Image" über Microsoft Download Center erhalten. Weitere Informationen finden Sie im [Microsoft Knowledge Base-Artikel 913086](http://support.microsoft.com/kb/913086).

**IT Pro Security Community:**

Erfahren Sie, wie Sie die Sicherheit Ihrer IT-Umgebung erhöhen und Ihren IT-Betrieb optimieren können. Diskutieren Sie auf der [IT Pro Security Zone](http://go.microsoft.com/fwlink/?linkid=21164)Website mit anderen IT-Profis über das Thema Sicherheit.

#### Danksagungen

Microsoft [dankt](http://www.microsoft.com/germany/technet/sicherheit/bulletins/policy.mspx)den folgenden Personen, dass sie zum Schutz unserer Kunden mit uns zusammengearbeitet haben:

-   Einer Person, die mit [VeriSign iDefense VCP](http://idefense.com/)zusammenarbeitet, aber anonym bleiben möchte, für den Hinweis auf ein in [MS07-042](http://go.microsoft.com/fwlink/?linkid=88350)beschriebenes Problem.
-   Einer Person, die mit der [Zero Day Initiative](http://www.zerodayinitiative.com/)zusammenarbeitet, aber anonym bleiben möchte, für den Hinweis auf ein in [MS07-042](http://go.microsoft.com/fwlink/?linkid=88350)beschriebenes Problem.
-   Einer Person, die mit [VeriSign iDefense VCP](http://idefense.com/)zusammenarbeitet, aber anonym bleiben möchte, für den Hinweis auf ein in [MS07-043](http://go.microsoft.com/fwlink/?linkid=70249)beschriebenes Problem.
-   Einer Person, die mit der [Zero Day Initiative](http://www.zerodayinitiative.com/)zusammenarbeitet, aber anonym bleiben möchte, für den Hinweis auf ein in [MS07-043](http://go.microsoft.com/fwlink/?linkid=70249)beschriebenes Problem.
-   Dyon Balding von [Secunia](http://secunia.com/)für den Hinweis auf ein in [MS07-044](http://go.microsoft.com/fwlink/?linkid=96778)beschriebenes Problem.
-   Das [NSFocus Security Team](http://www.nsfocus.com/)für den Hinweis auf ein in [MS06-045](http://www.microsoft.com/germany/technet/sicherheit/bulletins/ms07-045.mspx)beschriebenes Problem.
-   Brett Moore von [Security-Assessment.com](http://www.security-assessment.com/)für den Hinweis auf ein in [MS007-045](http://www.microsoft.com/germany/technet/sicherheit/bulletins/ms07-045.mspx)beschriebenes Problem.
-   [eEye Digital Security](http://www.eeye.com/)für den Hinweis auf ein in [MS05-046](http://go.microsoft.com/fwlink/?linkid=94466)beschriebenes Problem.
-   Pjotr Bania, der mit [TippingPoint](http://www.tippingpoint.com/)und der [Zero Day Initiative](http://www.zerodayintiative.com/)zusammenarbeitet, für den Hinweis auf ein in [MS07-047](http://go.microsoft.com/fwlink/?linkid=88628)beschriebenes Problem.
-   Aviv Raff von [Finjan](http://www.finjan.com/)für den Hinweis auf ein in [MS07-048](http://go.microsoft.com/fwlink/?linkid=94465)beschriebenes Problem.
-   Aviv Raff in Zusammenarbeit mit [iDefense Labs](http://labs.idefense.com/)für den Hinweis auf ein in [MS07-048](http://go.microsoft.com/fwlink/?linkid=94465)beschriebenes Problem.
-   Rafal Wojtczuk von [McAfee Avert Labs](http://www.avertlabs.com/)für die Zusammenarbeit mit Microsoft an einem in [MS07-049](http://go.microsoft.com/fwlink/?linkid=92734)beschriebenen Problem.
-   [eEye Digital Security](http://www.eeye.com/)für den Hinweis auf ein in [MS05-050](http://go.microsoft.com/fwlink/?linkid=94737)beschriebenes Problem.

#### Support

-   Die betroffene Software wurde getestet, um die betroffenen Versionen zu ermitteln. Andere Versionen haben das Ende ihrer Supportlebenszyklen erreicht. Besuchen Sie die Website [Microsoft Support Lifecycle](http://support.microsoft.com/default.aspx?scid=fh;%5Bln%5D;lifecycle), um den Supportlebenszyklus für Ihre Softwareversion zu ermitteln.
-   Technischer Support ist über die [Microsoft Support Services](http://go.microsoft.com/fwlink/?linkid=21131)erhältlich. Supportanrufe zu Sicherheitsupdates sind kostenlos.
-   Kunden außerhalb der USA erhalten Support bei ihren regionalen Microsoft-Niederlassungen. Supportanfragen zu Sicherheitsupdates sind kostenlos. Weitere Informationen dazu, wie Sie Microsoft in Bezug auf Supportfragen kontaktieren können, finden Sie auf der Website [Internationale Hilfe und Support](http://go.microsoft.com/fwlink/?linkid=21155).

#### Haftungsausschluss

Die Informationen der Microsoft Knowledge Base werden wie besehen und ohne jede Gewährleistung bereitgestellt. Microsoft schließt alle anderen Garantien, gleich ob ausdrücklich oder konkludent, einschließlich der Garantien der Handelsüblichkeit oder Eignung für einen bestimmten Zweck aus. In keinem Fall kann Microsoft Corporation und/oder deren jeweilige Lieferanten haftbar gemacht werden für Schäden irgendeiner Art, einschließlich direkter, indirekter, zufällig entstandener Schäden, Folgeschäden, Folgen entgangenen Gewinns oder spezieller Schäden, selbst dann nicht, wenn Microsoft Corporation und/oder deren jeweilige Lieferanten auf die mögliche Entstehung dieser Schäden hingewiesen wurde. Weil in einigen Staaten/Rechtsordnungen der Ausschluss oder die Beschränkung einer Haftung für zufällig entstandene Schäden oder Folgeschäden nicht gestattet ist, gilt die obige Einschränkung eventuell nicht für sie.

#### Revisionen

-   V1.0 (14. August 2007): Bulletin Summary veröffentlicht.
-   V1.1 (29. August 2007): Die Tabelle "Betroffene Software" wurde aktualisiert, um den Eintrag für "Betroffene Office-Software" für MS07-044 von "Office 2000", "Office XP" und "Office 2003" jeweils in "Excel 2000", "Excel 2002" und "Excel 2003" zu ändern.
-   V2.0 (13. November 2007): Die Tabelle "Betroffene Software" wurde mit Downloadlinks für MS07-049 aktualisiert. Jetzt steht ein überarbeitetes Sicherheitsupdate zur Installation für Microsoft Virtual PC 2004, Microsoft Virtual PC 2004 Service Pack 1, Microsoft Virtual Server 2005 Standard Edition, Microsoft Virtual Server 2005 Enterprise Edition, Microsoft Virtual Server 2005 R2 Standard Edition, Microsoft Virtual Server 2005 R2 Enterprise Edition zur Verfügung.
-   V3.0 (9. Januar 2008): Die Tabelle "Betroffene Software" wurde aktualisiert, um Microsoft Word Viewer 2003 unter MS07-042 hinzuzufügen. Das Update für Microsoft Office 2003 Service Pack 2 gilt auch für Microsoft Word Viewer 2003.
-   V4.0 (24. Juni 2008): Die Tabelle der betroffenen Software wurde aktualisiert, um Windows XP Service Pack 3, Windows Vista Service Pack 1, Windows Vista x64 Edition Service Pack 1, Windows Server 2008 für 32-Bit-Systeme, Windows Server 2008 für x64-basierte Systeme und Windows Server 2008 für Itanium-basierte Systeme unter MS07-042 für das KB936181-Update für Microsoft XML Core Services 4.0 hinzuzufügen. Dies ist lediglich eine Erkennungsänderung. Die Binärdateien wurden nicht verändert.

*Built at 2014-04-18T01:50:00Z-07:00*
