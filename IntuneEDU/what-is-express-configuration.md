---
title: Was ist eine Express-Konfiguration?
titleSuffix: Intune for Education
description: "Verwenden Sie Express-Konfiguration, die Gruppen in Intune für die Bildung schnell einzurichten."
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: af5d35ee-84f5-4245-a441-671600bcc376
searchScope: IntuneEDU
ms.openlocfilehash: 796782e6c0cf9fa975bd9c8f3a94314bb00d8d89
ms.sourcegitcommit: 293ad8c775aa37b5d3b6a9e547c80f31ba6a5bdd
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/15/2017
---
# <a name="what-is-express-configuration"></a>Was ist eine Express-Konfiguration?

Express-Konfiguration ist eine der Kacheln, die Sie sehen, wenn Sie zuerst Education Intune anmelden.

  ![Die Express-Konfiguration-Kachel, die Express Konfiguration starten - besagt, dass die klicken Sie hier, um apps und Einstellungen für eine Gruppe auszuwählen.](./media/express-config-001-launch-tile.png)

Express-Konfiguration können Sie schnell bereitstellen, Benutzer und Geräte mit apps und Einstellungen, die sie benötigen. Es ist nicht etwas, das Sie auf die Verwendung von lediglich einmal beschränkt sind. Sie können jedes Mal, wenn Sie Änderungen an einer beliebigen Gruppe vornehmen, die Sie verwalten möchten. Wir haben einige apps ausgewählt und die Standardeinstellungen, dass Sie vielleicht hilfreich finden. Sie können diese Auswahl Ihren Anforderungen anpassen ändern.

## <a name="choose-a-group"></a>Wählen Sie eine Gruppe

Beginnen Sie dazu eine Gruppe zu konfigurieren.

  ![Im auswählen-Bildschirm, der Benutzern das Auswählen einer Gruppenstatus aufgefordert.](./media/express-config-004-choose-group.png)

Ein _Gruppe_ in Intune für Education eine Sammlung von Geräten oder Benutzern, die organisiert sind ist, zu verstehen, wer oder was Sie in der Konsole konfigurieren, zu vereinfachen. Kann dies Geräte (z. B. _sechste Grade Computer Einkaufswagen_) oder Benutzer (wie _vierten Grade Studenten_ oder _Biologie Lehrer_). Intune Education im Lieferumfang von vordefinierten Gruppen basierend auf den School-Informationen, den Sie bereitgestellt haben. Wir haben die Weitere Informationen zu Gruppen verfügbar, in unserem [Gruppen von Artikeln](what-are-groups.md).

Es wird empfohlen, zunächst ein Zuweisen von Einstellungen, die Sie kennen **alle Benutzer** benötigen, z. B. für das Domänenkennwort oder Blockieren von Popups in Microsoft Edge.

Wählen Sie eine Gruppe einrichten, wählen Sie dann **Weiter** um den Vorgang fortzusetzen.

## <a name="choose-apps"></a>Apps auswählen

Nun legen Sie apps zu dieser Gruppe zugewiesen werden sollen.

  ![Der Bildschirm des app-Zuordnung. Apps werden für die Zuweisung von anderen Typen, einschließlich Web-apps und Microsoft Store für Education apps organisiert.](./media/express-config-005-choose-apps.png)

Es gibt einige Typen von apps, die Sie auf Geräten installieren können:

* [Web-Apps](how-to-add-apps.md#add-web-apps)
* [Desktop-apps](how-to-add-apps.md#add-desktop-apps)
* [Microsoft Store für Education-apps](acquire-store-apps.md)

Intune Education angezeigt, auch [beliebten apps aus dem Microsoft-Store Education](how-to-add-apps.md#add-popular-apps) aus über alle Intune für die Bildung Benutzer.

Wählen Sie die apps, weisen Sie dieser Gruppe aus, und wählen Sie dann **Weiter** um den Vorgang fortzusetzen.

## <a name="choose-settings"></a>Wählen Sie die Einstellungen

Als nächstes wählen Sie die Einstellungen aus, auf die Geräte oder Benutzer in der Verwaltungsgruppe angewendet werden sollen.

  ![Der Bildschirm "Wählen Sie Einstellungen". Einstellungen werden in einer reduzierten Liste, einschließlich Abteilungen, z. B. Geräte freigeben, grundlegende für Geräte, app-Einstellungen, Einstellungen für den Browser und mehr organisiert.](./media/express-config-006-choose-settings.png)

Express-Konfiguration wird gezeigt, Einstellungen, die möglicherweise jetzt kann es losgehen Gruppen abgerufen werden soll. Wir haben diese Einstellungen für Ihre Benutzer schnell erste Schritte mit ihren Geräten erleichtern ausgewählt. Sie müssen keine Änderungen vornehmen, wenn Sie unsere Empfehlung verwenden möchten oder Sie können diese Einstellungen, um die speziellen Anforderungen anpassen.

Sie können Express Konfigurationsauswahl jederzeit an Änderungen anpassen müssen, ändern und Anpassen Ihrer Einstellungen noch weiter unter Verwendung der vollständigen [Liste der verfügbaren Einstellungen im Rahmen des Intune Education](available-settings.md).

## <a name="finish-up"></a>Fertig stellen

Nachdem Sie Ihre Auswahl getroffen haben, müssen Sie die Möglichkeit, überprüfen die apps und Einstellungen, die Sie ausgewählt haben. Sie können die **Fertig stellen** klicken, oder wechseln Sie zurück zur alle Schritte zum Ändern dieser Einstellungen.

  ![Die Überprüfung Ihrer Auswahl Bildschirm. Es zeigt die apps oder Einstellungen, die während der Express-Konfiguration aktiviert.](./media/express-config-007-save-changes.png)

Nachdem Sie ausgewählt haben **Fertig stellen**, können Sie **konfigurieren Sie weitere Gruppen** oder **Fertig**.

  ![Der letzten Seite. Es zeigt die konfigurieren, weitere Gruppen und abgeschlossenen Optionen. "Fertig" ändert Option ' All ' bietet eine kurze Erklärung, was als Nächstes den Prozess, einschließlich Hinzufügen von Geräten in Intune Education belauschen, indem diese mit Azure Active Directory ist.](./media/express-config-008-all-done.png)

Wenn Sie fertig sind, werden Sie weitergeleitet im Intune-Education Dashboards, in denen können Sie weiterhin auf Ihre Geräte, Benutzer und apps verwalten. Sie können zurückkehren, um Express-Konfiguration jederzeit über das Dashboard oder im Navigationsmenü hinzufügen, entfernen oder Ändern von apps und Einstellungen für eine beliebige Gruppe.

## <a name="next-steps"></a>Nächste Schritte

Nachdem Sie, die Gruppen mit apps und Einstellungen, die sie benötigen eingerichtet haben, können Sie mit der Verwendung von Geräten mit Intune Education beginnen.

## <a name="find-out-more"></a>Weitere Informationen
- [Erfahren Sie mehr zu den Einstellungen in der zur vollständigen Verwaltung in Intune](https://docs.microsoft.com/intune/deploy-use/manage-settings-and-features-on-your-devices-with-microsoft-intune-policies)
