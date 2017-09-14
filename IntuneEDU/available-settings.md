---
title: "Verfügbare Einstellungen"
titleSuffix: Intune for Education
description: "Weitere Informationen zu den Einstellungen, die für Intune Education zur Verfügung stehen."
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 08/16/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 2221009e-68cf-4171-8118-0d750b0f35f1
searchScope: IntuneEDU
ms.openlocfilehash: 2e9d06366142f7adce5eff9454c85cab62165c46
ms.sourcegitcommit: f4fb37302cb3c927196958c33e7215f7827bfcb3
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/14/2017
---
# <a name="available-settings-for-intune-for-education"></a>Verfügbare Einstellungen für Intune Education

Konfigurieren der Einstellungen ist eine der wichtigsten Methoden, die können Sie Ihre Windows 10-Geräte zu sichern und erstellen die richtigen Arten des Zugriffs auf das Learning zu verbessern. Intune Education bietet viele weitere Einstellungen, mit die Sie diese Oberflächen, sowohl für einzelne Gruppen und ihrer Untergruppen anpassen können.

Die meisten Einstellungen eingerichtet sind, entweder **Block** oder **zulassen** Zugriff auf eine bestimmte Gerätefunktion, in denen **nicht konfiguriert** Standardeinstellung für das Gerät oder eine Einstellung für Benutzer ausgewählt wird.

> [!NOTE]
> Diese Benutzer, Anwendung und Ihre Einstellungen unterscheiden sich von [mandanteneinstellungen](what-are-tenants.md).

Sie finden diese Einstellungen, indem Sie zuerst eine **Gruppe**, drücken Sie dann die **Einstellungen**.

  ![Die Seite "Einstellungen" für eine Gruppe](./media/settings-001-list-of-settings.png)

Viele der Informationen in den **wozu** Spalte kann auch in der Intune für Education-Konsole gefunden werden; diese ist so konzipiert, dass Sie die Einstellungen für bestimmte Elemente durchsuchen erleichtern.

## <a name="basic-device-settings"></a>Grundlegende für Geräte

|Einstellung|Funktion|
|---|---|
|Kamera|Benutzerzugriff auf die Kamera des Geräts zu blockieren.|
|Wechselmedien|Blockieren Sie für Benutzer von der Verwendung von Wechselmedien wie z. B. USB-Laufwerken und externen Festplatten.|
|Datum und Uhrzeit|Benutzer sperren, ändern das Gerät von Datums- und Uhrzeiteinstellungen.|
|Gerätename|Blockieren Sie ändern Sie den Gerätenamen für Benutzer.|
|Spracheinstellungen|Blockieren Sie ändern Sie die Sprache des Geräts für Benutzer.|
|Aufheben der Registrierung Geräte|Blockieren Sie Benutzer von Geräten in der Verwaltung manuell aufgehoben.|
|Senden von Diagnosedaten|Definieren Sie, ob zum Erfassen und senden anonyme Nutzungsdaten an Microsoft zur Verbesserung von Windows.|
|Hinzufügen von Bereitstellung von Paketen|Blockieren Benutzer hinzufügen hinzufügen, neue Bereitstellung Pakete, die Einstellungen für Geräte enthält.|
|Entfernen Sie die Bereitstellung Pakete|Blockieren Sie entfernen Sie die Bereitstellung Pakete, die Einstellungen für Geräte, für Benutzer.|
|Ortsbezogene Dienste|Verhindern Sie apps mithilfe von Standortdiensten auf den Standort eines Geräts zugreifen.|
|Internetfreigabe|Blockieren Sie für Benutzer von Freigeben der Internetverbindung des Geräts mit Internetfreigabe.|
|Cortana|Blockieren Sie Cortana, die digitale Assistant, Assistent für Windows 10, die um Fragen zu beantworten und Aufgaben können integriert.|
|Region-Einstellungen für Geräte|Blockieren Sie Benutzer regionale Einstellungen, z. B. Land und die Sprache ändern.|
|Dateien in der lokalen Festplatte speichern|Blockieren Sie Benutzer Dateien lokal speichern.|
|Einstellungen für Stromversorgung und dem Standbymodus|Blockieren Sie Benutzer am Ändern von Power und Standbymodus Einstellungen.|
|Menü Startgröße|Definieren Sie, ob das Startmenü Vollbildmodus angezeigt werden erzwungen.|
|Windows-Blickpunkt|Alle Windows-Spotlight-Features auf diesen Geräten zu blockieren.|
|OneDrive-Synchronisierung|OneDrive-Synchronisierung für diese Geräte und Benutzer blockieren.|

## <a name="microsoft-edge-settings"></a>Einstellungen für den Microsoft Edge

|Einstellung|Funktion|
|---|---|
|Popups|Blockieren von Websites neue Fenster zu öffnen.|
|-Nicht-Track-Header|Erfordern Sie Microsoft Edge, bitten Sie ihn, Websites Benutzerdaten nicht nachverfolgt.|
|Cookies|Cookies können websiteeinstellungen speichern, oder Nachverfolgen Benutzer des Verhalten suchen.|
|Füllen Sie automatisch Formulareinträge aus|Speichern von online in ein Formular eingegebenen Daten blockieren.|
|Kennwort-manager|Blockieren Sie Benutzer mit dem Kennwortmanager, Kennwörter zu speichern.|
|Entwicklertools|Blockieren Sie Zugriff auf die Entwicklertools für Benutzer.|
|Browsererweiterungen|Blockieren Sie Verwendung von Erweiterungen Rand mit zusätzliche Funktionalität von Microsoft und anderen Quellen anpassen, für Benutzer.|
|InPrivate-Browsen|Blockieren Sie Kante der verhindert wird, Speichern von Daten, wie z. B. Browsen Verlauf und Cookies für Benutzer von der Verwendung von InPrivate-Browsen.|
|Der Zugriff auf Informationen zu: Seite "Flags"|Blockieren des Zugriffs auf die über: Flags-Seite, die experimentelle Einstellungen und Features enthält.|
|SmartScreen Außerkraftsetzung|Blockieren Benutzer ignorieren von Warnungen für die Websites, die durch den SmartScreen-Filter blockiert.|
|Der SmartScreen-Außerkraftsetzung für Dateien|Blockieren Sie für Benutzer von ignorieren von SmartScreen-Filter-Warnungen zum Herunterladen der nicht überprüften Dateien.|
|Block nicht jugendfreie Inhalte mit Filtern strict SafeSearch|Einstellung auf "Blockieren" wird einen Mittel, anstatt strict SafeSearch Filter verwenden, um nicht jugendfreie Inhalte zu blockieren.|
|Search-Vorschläge|Block Rand von möglichen Websites vorgeschlagen, während der Eingabe von eines Begriffs suchen oder die URL.|
|Intranetdatenverkehr in Internet Explorer|Wenn auf "Blockieren" festgelegt ist, wird interner Datenverkehr Rand anstelle von Internet Explorer gesendet.|
|JavaScript|Verhindern Sie, dass JavaScript im Edge ausgeführt.|
|Standard-Suchmodul|Wählen Sie Bing, Yahoo oder Google als Standard-Suchmaschine für Microsoft Edge. Wenn eine benutzerdefinierte Suchmodul bereitgestellt, in der vollständigen Intune zur Sie oder ein anderer Administrator eingerichtet hat, können Sie diese benutzerdefinierte Suchmodul bereitgestellt als Standard Hier definieren.|
|Konfigurieren von Microsoft Edge-homepages|Wählen Sie, was auf Startseiten öffnen Sie jedes Mal, wenn jemand eine neue Sitzung, die mit Microsoft Edge durchsuchen beginnt.|
|Konfigurieren von Microsoft Edge-Favoriten|Wählen Sie die Websites im Microsoft Edge-Favoritenliste angezeigt werden.|
|Block Favoriten bearbeiten|Blockieren Sie Bearbeiten von Edge-Browser-Favoriten für Benutzer.|

## <a name="user-access-to-device-settings"></a>Benutzerzugriff auf Einstellungen für Geräte

|Einstellung|Funktion|
|---|---|
|Systemsteuerung|Blockieren Sie Benutzerzugriff auf die Systemsteuerung.|
|Für die app|Blockieren Sie Benutzerzugriff auf die für die app an. Wenn Sie diese Einstellung nicht blockieren, können Sie stattdessen auswählen, die einzelnen Teile der Einstellungs-app in den Rest der Tabelle aufgeführten sperren.|
|Systemeinstellungen|Anzeige, Benachrichtigungen, apps, Einstellungen für die energieverwaltung zu blockieren.|
|Geräte|Blockieren Sie Bluetooth, Drucker und mehr.|
|Netzwerk und Internet|Block WLAN, flugzeugmodus und VPN.|
|Personalization|Blockieren Sie Hintergrund, Sperrbildschirm und Farbe bearbeiten.|
|Konten|Blockieren Sie Benutzerkonten, e-Mail, Synchronisierung, Arbeit und andere Personen.|
|Zeit und Sprache|Blockgröße, Region und Datum.|
|Erleichterte Bedienung|Sprachausgabe, Bildschirmlupe und hoher Kontrast zu blockieren.|
|Datenschutz|Block-Speicherort und der Kamera.|
|Update und Sicherheit|Blockieren Sie Windows Update, Wiederherstellung und Sicherung.|
|Apps|Blockieren Sie deinstallieren, Standardwerte und optionalen Features.|
|Spiele|Spiel Leiste, DVR, senden und Spielmodus zu blockieren.|


## <a name="device-update-settings"></a>Update-Einstellungen für Geräte

|Einstellung|Funktion|
|---|---|
|Verzweigung Bereitschaft Ebene|Definieren Sie, ob die Geräte auf dem aktuellen Branch oder des Current Branch für Unternehmen für Windows-Updates sind.|
|Updates und Wartung|Definieren Sie die Updates und Wartung für die Installation von Updates.|
|Installationstag für geplante|Definieren Sie den Tag der Woche, die Geräte aktualisiert und neu gestartet werden.|
|Geplante Installationszeit|Definieren Sie die Zeit, die Geräte aktualisiert und neu gestartet werden.|
|Ein Update außerhalb des geplanten Zeiten|Aktivieren Sie die Geräte, die (z. B. in einem Einkaufswagen) angeschlossen sind, die außerhalb der geplanten Aktualisierungszeiten aktualisiert werden.|
|Verzögern der Feature-updates|Definieren Sie die Anzahl der Tage zu warten, bis die Feature-Updates auf Geräte angewendet, nachdem sie verfügbar sind.|
|Qualität Updates aufschieben|Definieren Sie die Anzahl der Tage zu warten, bis die Updates Qualität auf Geräte angewendet, nachdem sie verfügbar sind.|
|Ermöglicht es Benutzern, einen Abruf Insider Preview-builds|Definieren Sie, ob Benutzer ihre Geräte für den Download und Installation von Preview-Software verfügbar machen können.|
|Features der Vorabversion|Definieren von Weather sehen Benutzer die Features der Vorabversion für Einstellungen, Einstellungen und Experimente oder keine Features der Vorabversion.|
|Optimierung der Übermittlung|Definieren Sie, wie Updates an Geräte übermittelt werden.|

## <a name="windows-defender-settings"></a>Windows Defender-Einstellungen

> [!NOTE]
> Bestimmte Windows Defender-Einstellungen finden Sie unter der [Mandanten](what-are-tenants.md) Ebene.

|Einstellung|Funktion|
|---|---|
|Block-Benutzerzugriff auf Windows Defender-Einstellungen|Blockieren Sie Benutzer von Windows Defender-Einstellungen auf dem Gerät ändern.|
|Echtzeit-Überwachung|Aktivieren Sie AlwaysOn-Scans für Malware, Spyware und andere Bedrohungen.|
|Verhaltensüberwachung|Aktivieren Sie Defender bestimmte bekannte Muster verdächtiger Aktivitäten überprüft.|
|Netzwerkinspektionsdienst|Geräten vor netzwerkbasierten Sicherheitslücken durch die Signaturen bekannter Sicherheitsrisiken aus dem Microsoft Endpoint Protection-Center verwenden, um zu erkennen und Blockieren von schädlichen Datenverkehr zu schützen.|
|Alle heruntergeladene Dateien überprüfen|Automatisch alle heruntergeladene Dateien auf Schadsoftware zu überprüfen.|
|Scannen von Skripts in Microsoft Webbrowsern ausführen|Überprüfen Sie alle Skripts, die versucht, dass eine Website in Edge und Internet Explorer auszuführen.|
|Aktualisierungshäufigkeit|Wie häufig Defender überprüft und Anti-Malware werden dann heruntergeladen, definieren.|
|Überprüfen Sie die Datei-und Programmaktivität|Suchen Sie nach Malware, wenn Dateien oder Programme geöffnet sind und Benachrichtigung von Benutzern für verdächtige Aktivitäten.|
|Tage vor Schadsoftware unter Quarantäne gestellten entfernt wird|Definieren Sie die Anzahl der Tage, die vor dem Entfernen eine Datei gespeichert ist (0 = sofort gelöscht wird).|
|Cloud-basierten Schutz|Abgerufen Sie Echtzeitschutz Defender sendet Informationen an Microsoft zu Sicherheitsrisiken werden soll. Dieses Feature funktioniert am besten mit "Fordert beim Benutzer nachfragen Beispiel" Set Beispiele automatisch senden.|
|Beim Benutzer nachfragen Beispiel|Definieren Sie, ob Dateien, die weitere Analyse benötigen möglicherweise automatisch an Microsoft gesendet werden.|
|Erkennen und blockieren potenziell unerwünschte Anwendungen|Benutzer- und blockieren, die potenziell unerwünschter Software, die versucht, sich selbst auf Geräten installieren, werden Defender benachrichtigt.|
|Ausschließen von Dateien mit diesen Erweiterungen von Überprüfungen und Echtzeitschutz|Definieren Sie die Typen von Dateien, die Benutzern ohne Überprüfung von Sicherheitsrisiken zugreifen können sollen.|

## <a name="wireless-settings"></a>Drahtlose Netzwerke

|Einstellung|Funktion|
|---|---|
|Servergespeicherte mobilfunkdaten|Die Geräte blockieren mithilfe Mobilfunk Datentarife beim roaming.|
|Bluetooth|Die Geräte blockieren über Bluetooth.|
|Bluetooth-Erkennung|Block-Geräte als erkennbar über Bluetooth festgelegt wird.|
|Bluetooth-Werbung|Blockieren Sie Geräte aus der Empfang von Werbung über Bluetooth.|
|WLAN|Blockieren Sie Geräte mit Wi-Fi.|
|Verbinden Sie automatisch, um WLAN-Hotspots zu öffnen.|Wenn Sie aktiviert haben **Wi-Fi**, können Sie auswählen, ob Geräte automatisch eine Verbindung mit WLAN-Hotspots herstellen zu blockieren.|
|Proxyeinstellungen automatisch erkennen|Wenn Sie Proxys Gerät Netzwerkverkehr verarbeitet eingerichtet haben, können Sie auswählen, ob die Geräte bei Verbindung mit den Proxyeinstellungen automatisch erkennen.|
|Verwenden Sie die Proxy-Skript|Die Verwendung eines Skripts Proxy für Ihre Geräte zu aktivieren. Wenn Sie **zulassen** dieser Einstellung müssen Sie bieten eine **Setup-Skript Adresse**.|
|Manuelle Proxyserverkonfiguration verwendet|Wenn Sie einen manuellen Proxy eingerichtet haben, können Sie hier Einstellungen dafür definieren. Wenn Sie **zulassen** dieser Einstellung müssen Sie bieten die **Proxyserveradresse**, **Port**, **Proxy-Ausnahmen**, und ob **Proxyserver für lokale Verbindungen verwenden**.|


## <a name="device-sharing-settings"></a>Freigabeeinstellungen Gerät

|Einstellung|Funktion|
|---|---|
|Geräte für die gemeinsame Nutzung optimieren|Konfiguriert die empfohlene Einstellungen für gemeinsam genutzte Geräte, z. B. Power und aktualisierungsverwaltung, und dadurch können mehrere Benutzer auf einem Gerät anmelden.|
|Gastbenutzer Sperren|Wenn Sie aktiviert haben **Geräte für die gemeinsame Nutzung optimieren**, Sie können auch, ob der Gastbenutzer an Geräten anmelden blockiert auswählen. Blockiert, können nur Domänenbenutzer anmelden.|
|Schnelle benutzerumschaltung|Gestatten Sie Benutzern, wechseln Sie schnell zwischen Benutzerkonten über das Startmenü zugreifen.|

## <a name="app-settings"></a>App-Einstellungen

|Einstellung|Funktion|
|---|---|
|< a Name = "removew10apps"</a>Entfernen der integrierten Windows-10-apps|Deinstallieren Sie bestimmte integrierte Windows-apps. Erfahren Sie, was diese apps sind [unten](available-settings.md#additional-information-about-removing-built-in-apps).|
|Microsoft Store für Education-apps|Blockieren Sie Benutzer am Installieren von apps von Microsoft Store Education.|
|Erfordert Microsoft Store für Education-apps aus dem privaten Informationsspeicher|Nur gestatten Sie Benutzern, apps aus dem Microsoft Store Education installieren, die Ihre Organisation eingerichtet wurde.|
|Vertrauenswürdige apps|Definieren Sie, ob der Benutzer vertrauenswürdigen apps von Microsoft signiert installieren können.|
|Nicht vertrauenswürdige apps|Definieren Sie, ob die Benutzer installieren können, nicht signierte apps oder apps, die von externen Quellen, die nicht von Microsoft als vertrauenswürdig eingestuft werden signiert.|
|Automatische app-updates|Blockieren von Microsoft Store für Education-apps automatisch aktualisiert.|
|Freigegebenes app-Daten zwischen den Benutzern|Können Sie mehrere Benutzer gemeinsam genutzte Geräte app-Daten gemeinsam nutzen.|

## <a name="additional-information-about-removing-built-in-apps"></a>Weitere Informationen zum Entfernen von integrierten apps

Diese Einstellung wird automatisch aktiviert, wenn die "Optimieren Geräte für die gemeinsame Verwendung" Einstellung aktiviert ist. Die folgenden apps werden vollständig von den Computern der Benutzer entfernt, wenn diese Einstellung aktiviert ist:

* 3DBuilder
* Bing-Weather
* Desktop-App-Installer
* Erste Schritte
* Microsoft Office-Hub
* Solitär-Auflistung
* Eine Verbindung herstellen.
* Windows-Feedback-Hub
* Xbox
* Groove Musik
<!--* Zune Video-->
* Mail
* Kalender

## <a name="sign-in-settings"></a>Anmelden settings

|Einstellung|Funktion|
|---|---|
|Melden Sie sich mit Microsoft-Konto|Blockieren Sie Benutzer aus ihrem Microsoft-Konto anzumelden.|
|Melden Sie sich mit nicht-Microsoft-Kontos|Blockieren Sie Benutzer aus einem anderen Konto als ihrem Microsoft-Konto anzumelden. Verwenden Sie diese Einstellung, wenn Sie mit dem Sie von anderen Microsoft-Konten, ihre Office 365-Konto Anmeldung der Benutzer erzwingen möchten.|

## <a name="windows-interface-customizations"></a>Windows-Benutzeroberflächenanpassungen

|Einstellung|Funktion|
|---|---|
|Die meisten verwendet apps im Startmenü|Verhindern Sie, die am häufigsten verwendeten apps im Startmenü angezeigt.|
|Kürzlich hinzugefügte apps im Startmenü|Zuletzt hinzugefügten Block apps im Startmenü verhindern.|
|Zuletzt geöffnete Elemente in Start Sprung menülisten|Zuletzt geöffneten Block Elemente in Sprunglisten in der Taskleiste und im Startmenü angezeigt.|
|Liste der Apps im Startmenü|Die Liste aller Apps auf dem Gerät aus angezeigt, im Startmenü zu blockieren.|
|Power-Menü im Startmenü|Blockieren der Power-Menü (z. B. neu starten, Herunterfahren nach unten) im Startmenü verhindern.|
|Benutzerkachel im Startmenü|Blockieren des aktuellen Benutzers Informationen verhindern, dass im Startmenü angezeigt.|
|Benutzerdefinierte Sperre Bildschirm Hintergrundbild|Konfigurieren Sie ein benutzerdefiniertes Hintergrundbild auf den Anmeldebildschirm. Sie können eine JPG oder PNG kleiner als 20 MB Größe auswählen.|
|Benutzerdefinierte desktop-Hintergrundbild|Konfigurieren Sie ein benutzerdefiniertes Hintergrundbild auf dem Desktop. Sie können eine JPG oder PNG kleiner als 20 MB Größe auswählen.|
|Wählen Sie im Startmenü in der angezeigten Ordner|Sie könne **Datei-Explorer**, **Einstellungen**, **Dokumente**, **Downloads**, **Musik**, **Bilder**, **Videos**, **Heimnetzgruppe**, **Netzwerk**, und **persönlichen Ordner**.|
|Wählen Sie aus, welche Einstellungen auf der Benutzerkachel "im Startmenü angezeigt werden.|Sie könne **kontoeinstellungen ändern**, **Sperre**, und **Abmelden**.|
|Wenden Sie benutzerdefinierte Start Menü layout|Anwenden eines benutzerdefinierten Start Menü Layouts, die mithilfe einer XML-Datei an. Sie können eine XML-Datei ein, der kleiner als 2 MB Größe hochladen.|
|PIN-Websites als Kacheln im Startmenü|PIN Websites als Kacheln im Startmenü mithilfe einer XML-Datei. Sie können eine XML-Datei ein, der kleiner als 2 MB Größe hochladen.|

## <a name="email-settings"></a>E-Mail-Einstellungen

|Einstellung|Funktion|
|---|---|
|Konfigurieren von E-Mail-Einstellungen|Wählen Sie, ob Sie e-Mail-Einstellungen für diese Gruppe konfigurieren möchten. Diese Einstellungen werden auf der Windows-10-Mail-app angewendet. Wenn Sie nicht **konfigurieren** diese Einstellung keine der anderen e-Mail-Einstellungen in dieser Tabelle wird für Sie verfügbar werden.|
|Account name|SSL wird dies auf ihren Geräten sehen können.|
|E-Mail-server|Geben Sie den Namen des Servers, auf dem Ihre e-Mail-Adresse gehostet werden soll.|
|Benutzername|Wählen Sie das Attribut, mit dem Intune wird aus Azure Active Directory, beim Anwenden der Einstellungen für Benutzer um e-Mail-Profilen.|
|E-Mail-Adresse|Wählen Sie das Attribut, mit dem Intune wird aus Azure Active Directory, beim Anwenden der Einstellungen für e-Mail-Adresse um die e-Mail-Profilen.|
|Zeitdauer zum Speichern von e-Mail auf Geräten|Wählen Sie zum Speichern von e-Mail auf Geräten wie viel Zeit.|
|Intervall für die e-Mail-Synchronisierung|Wählen Sie, wie viel Zeit zwischen Synchronisierungen e-Mail übergibt.|
|Kontakte synchronisieren|Sync-Kontaktinformationen.|
|Sync-Kalender|Kalenderinformationen zu synchronisieren.|
|Synchronisierungsaufgaben|Informationen zum Vorgang zu synchronisieren.|
|SSL|Verwenden Sie Secure Sockets Layer (SSL) beim Senden von e-Mails zur Erhöhung der Sicherheit.|

## <a name="wi-fi"></a>WLAN

Wi-Fi-Einstellungen werden aus den Wi-Fi-Einstellungen finden separaten **Drahtloseinstellungen**.

|Einstellung|Funktion|
|---|---|
|Netzwerkname|Geben Sie den Namen des Netzwerks.|
|Sicherheitstyp|Wählen Sie das Sicherheitsprotokoll von WLAN-Netzwerk verwendet werden soll.|
|Kennwort|Geben Sie Ihr Netzwerk Wi-Fi-Kennwort.|
|Kennwort bestätigen|Überprüfen Sie Ihr Netzwerk Wi-Fi-Kennwort ein.|

## <a name="edition-upgrade"></a>Upgrade der Edition

Verwenden Sie diese Einstellungen so aktualisieren Sie die Geräte in dieser Gruppe auf eine andere Edition von Windows durch Auswahl der **Edition aktualisieren auf** und Bereitstellen Ihrer **Product Key**.

## <a name="find-out-more"></a>Weitere Informationen

- [Erfahren Sie mehr über die vollständige Windows 10-Einstellungen Verwaltungsoberfläche in Intune verfügbaren](https://docs.microsoft.com/intune/deploy-use/windows-10-policy-settings-in-microsoft-intune)
