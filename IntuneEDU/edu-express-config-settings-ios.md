---
title: Standard-Einstellungen für iOS in Express-Konfiguration
titleSuffix: Intune for Education
description: Listet die Standardnamen für die Einstellung und Verhaltensweisen, die bei der Verwendung von Express-Konfiguration festgelegt.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 04/19/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 2221009e-68cf-4171-8118-0d750b0f35f1
searchScope:
- IntuneEDU
ms.openlocfilehash: af6eca94a4098885ef7c932f39e9c787e2a4450b
ms.sourcegitcommit: 52d0b7bf230bba5182057e4875ee507843a906d6
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2019
ms.locfileid: "62147490"
---
# <a name="default-ios-settings-in-express-configuration"></a>Standard-Einstellungen für iOS in Express-Konfiguration
Express-Konfiguration ist mit iOS festlegen Vorschläge zum schnellen Einrichten einer Gruppe von Geräten oder Benutzern voreingestellt. Intune for Education wählt die Einstellungen, die von Microsoft empfohlenen und für "School"-Umgebungen am besten geeignet sind. Nehmen Sie Änderungen an passen, Regeln und Richtlinien Ihrer Schule oder klicken direkt über die Seite "Einstellungen", um unsere Empfehlungen anzuwenden. 

Die vollständige Liste der Einstellungen und Beschreibungen, finden Sie unter [alle iOS-Einstellungen in Intune for Education](all-edu-settings-ios.md). 

> [!IMPORTANT]
> Überprüfen Sie Wenn iOS-Konfigurationen deaktiviert sind, wenn Sie die Express-Konfiguration starten, um sicherzustellen, dass Sie Ihre Apple-MDM-Push-Zertifikat und die DEP-Token eingerichtet haben. Wenn Sie beides haben, stellen Sie sicher, dass es sich bei keiner abgelaufen ist. Weitere Informationen zum Einrichten der Verwaltung von iOS-Geräte finden Sie unter [Verwaltung von iOS-Gerät einrichten](setup-ios-device-management.md)


## <a name="app-store-itunes-store-and-book-store"></a>Buch-Store, App Store und iTunes-Store  
Einstellung|Empfohlener Wert|  
|---|---|
|Die App Store blockieren|Blockieren|
|Block-in-app-Käufe|Blockieren|
|Explizite Inhalte im App Store und iTunes Store blockieren|Blockieren|
|Herunterladen von Inhalten mit Apple Bücher Block bei "erotik".|Blockieren|  

## <a name="built-in-apps"></a>Integrierte Apps  
Einstellung|Empfohlener Wert|  
|---|---|
|Kamera blockieren|Blockieren|
|Hiermit blockieren Sie FaceTime|Blockieren|
|Game Center blockieren|Blockieren|  
|Blockiert den Musikdienst Apple|Blockieren|
|Block-Nachrichten-app|Blockieren|
|Blockieren von Apple-Bücher|Blockieren|  

## <a name="device-restrictions"></a>Geräteeinschränkungen  
Name der Einstellung|Empfohlener Wert|
|---|---|
|Änderung von Gerätenamen blockieren|Blockieren|
|Ändern des Hintergrunds blockieren|Blockieren|
|Änderung von Benachrichtigungseinstellungen blockieren|Blockieren|
|Blockiert Änderungen an Inhalten und der Datenschutz-Einschränkungen|Blockieren|
|Block-Schaltfläche, die alle Inhalte und Einstellungen werden gelöscht|Blockieren|  

## <a name="icloud"></a>iCloud
|Einstellung|Empfohlener Wert|
|---|---|
|ICloud-Sicherung blockieren|Blockieren|
|Synchronisierung von Dokumenten in iCloud blockieren|Blockieren|
|ICloud-Fotomediathek blockieren|Blockieren|  

## <a name="lock-screen-and-wallpaper"></a>Sperrbildschirm und Hintergrund
Einstellung|Empfohlener Wert|
|---|---|
|Benachrichtigungen auf Sperrbildschirm blockieren|Blockieren|
|Wird der Zugriff auf Wallet über Sperrbildschirm blockieren|Blockieren|
|Set-Gerät Hintergrundbild für Sperrbildschirm|Eine JPG- oder PNG-Datei; Maximale Dateigröße 960 KB|
|Set-home-Bildschirm gerätebilds|Eine JPG- oder PNG-Datei; Maximale Dateigröße 960 KB|  

## <a name="passcode-touch-id-and-face-id"></a>Kennung, Touch ID und Face ID  
Einstellung|Empfohlener Wert|
|---|---|  
|Kennung erforderlich|Nicht konfiguriert|
|Ändern der Kennung blockieren|Blockieren|
|Anzahl fehlerhafter Versuche für kennungseingabe bis zum Gerät|Nicht konfiguriert|
|Block Touch ID und Face ID|Blockieren|

## <a name="siri-and-search"></a>Siri und Suche 
Einstellung|Empfohlener Wert|
|---|---|   
|Hiermit blockieren Sie Siri|Blockieren|  

## <a name="reset-default-settings"></a>Standardeinstellungen zurücksetzen
Klicken Sie zum Wiederherstellen aller Einstellungen auf ihre Standardwerte **auf vorgeschlagene Standardwerte zurücksetzen**. 

## <a name="next-steps"></a>Nächste Schritte  
Erfahren Sie alles über Gruppen, Einstellungen und Überwachung Konflikte in Intune for Education. 
* Erfahren Sie, den Unterschied zwischen [zugewiesenen und dynamische](create-groups.md) Gruppen
* Weisen Sie [Gruppe Administratoren](group-admin-delegate.md) helfen Ihnen beim Verwalten von Classroom-Einstellungen innerhalb Ihrer Schule/Universität oder in der Region
* Erfahren Sie, wie [einstellungsvererbung](settings-inheritance.md) wirkt sich auf Gruppe Zuweisungen
* Überprüfen Sie [Berichte](what-are-reports.md) zu ermitteln, identifizieren und beheben Konflikte bei der Einrichtung
