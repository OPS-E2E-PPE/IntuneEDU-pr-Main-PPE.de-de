---
title: Wie verwalte ich Einstellungen?
titleSuffix: Intune for Education
description: "Führen Sie diese Schritte aus, um die Einstellungen, die über Intune für Education-Richtlinien zu verwalten."
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 20c0f6c9-f1de-4048-aa96-5b0a068c1b75
searchScope: IntuneEDU
.md#ms.tgt_pltfrm: 
ms.openlocfilehash: a8a9619476315459d49dc128e14c3bc0f2f7794e
ms.sourcegitcommit: 293ad8c775aa37b5d3b6a9e547c80f31ba6a5bdd
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/15/2017
---
# <a name="how-do-i-manage-settings"></a>Wie verwalte ich Einstellungen?

Sie können eine Vielzahl von Einstellungen für Ihre Benutzer, apps und Geräte mit Intune verwalten. Es ist, wie Sie ändern, wie Geräte auf Benutzeraktionen reagieren können.

Wenn Einstellungen für eine Gruppe von Geräten angewendet werden, werden die betroffenen Benutzer beim Zugriff auf ein Gerät aus dieser Gruppe. Wenn eine Einstellung für eine Gruppe von Benutzern angewendet wird,

Einstellungen für Geräte gelten für alle Geräte in ihrer Gruppe. Einstellungen im **nicht konfiguriert** ermöglicht dem Benutzer ihre Einstellungen für ihre Geräte selbst definieren.

## <a name="manage-settings-for-groups"></a>Verwalten von Einstellungen für Gruppen

Verwenden Sie die folgenden Schritte aus, um die vollständige Liste der Einstellungen in Intune Education verwalten:
1. In der [Intune Education](https://intuneeducation.portal.azure.com) -Konsole im linken Navigationsmenü, wählen Sie **Gruppen**.
2. Wählen Sie die Gruppe, deren Einstellungen, die Sie verwalten möchten. Eine vollständige Liste finden Sie unter [verfügbaren Einstellungen](what-are-settings.md).
3. Klicken Sie auf **Einstellungen** am oberen Rand der Seite, um die vollständige Liste der verfügbaren Einstellungen anzuzeigen.
4. Erweitern Sie Kategorien, und ändern Sie die einzelne Einstellungen für die ausgewählte Gruppe.
5. Klicken Sie auf **speichern** zum Speichern der Änderungen für diese Gruppe. Einstellungen werden automatisch auf Geräten in dieser Gruppe gesendet.

## <a name="manage-settings-with-express-configuration"></a>Verwalten von Einstellungen mit den Express-Konfiguration

Express-Konfiguration Sie zum schnellen Einstieg erleichtert, jedoch kann Ihnen außerdem schnelle Änderungen auf Ihren Geräten vornehmen.

  ![Express-Konfiguration Einstellungen Korrektur](./media/express-config-006-choose-settings.png)

1. In der [Intune Education](https://intuneeducation.portal.azure.com) -Konsole, und wählen Sie **Express-Konfiguration starten**. Überprüfen Sie die **Willkommen** Seite, und wählen Sie **Einstieg in die**.
2. Überprüfen Sie die **School Informationen abrufen** Seite. Wenn Sie bereits School Informationen hinzugefügt haben, wählen Sie **Weiter**.
3. Wählen Sie die Gruppe, deren Einstellungen, die Sie verwalten, und wählen Sie dann möchten **Weiter**.
4. Überprüfen Sie die Liste der apps, und wählen Sie dann **Weiter**.
5. Auf der **Einstellungen** Seite, erweitern Sie die Kategorien der verfügbaren Einstellungen:
  * [Grundlegende für Geräte](available-settings.md#basic-device-settings)
  * [Einstellungen für den Microsoft Edge](available-settings.md#microsoft-edge-settings)
  * [Update-Einstellungen für Geräte](available-settings.md#device-update-settings)
  * [Drahtlose Netzwerke](available-settings.md#wireless-settings)
  * [App-Einstellungen](available-settings.md#app-settings)
  * [Anmeldeeinstellungen](available-settings.md#sign-in-settings)

  Erweitern Sie eine Kategorie aus, und schalten Sie das Steuerelement, um Einstellungen zu ändern, und wählen Sie dann **Weiter**.

6. Überprüfen Sie Ihre Auswahl, und wählen Sie dann **Fertig stellen** zum Speichern die Änderungen auf Aktualisieren Geräte in der ausgewählten Gruppe.

## <a name="can-i-ever-have-settings-that-dont-work-together"></a>Kann ich Einstellungen verfügen, die zusammenarbeiten, nicht?

Es ist möglich, dass nicht kompatiblen Einstellungen auf der gleichen Gruppe angewendet werden soll. Diese Inkonsistenzen führen zu Fehlern, wenn ein Benutzer oder Gerät mit unterschiedlichen Einstellungen an mehreren Stellen eingerichtet wird. Dies geschieht aufgrund der Benutzer bzw. das Gerät seiner Zugehörigkeit zu mehreren Gruppen.

Esperanza ist z. B. ein Mitglied der *6. Grade* gruppieren und ist auch Mitglied der Gruppe mit dem Namen *Erde Science*. Wenn Sie eine Einstellung für die Startseite konfigurieren und Zuweisen *6. Grade*, und Sie eine andere Homepage Einstellung konfigurieren, und weisen Sie ihn *Erde Science*, sie verfügt jetzt über zwei in Konflikt stehenden Homepage-Einstellungen, die ihre Benutzer zugewiesen. Das ergibt eine inkonsistente einstellungszuweisung zu einem Fehler führen. Finden Sie, welche Geräte und Benutzer mit einstellungsfehlern haben die [Fehler Bericht](what-are-reports.md).

## <a name="find-out-more"></a>Weitere Informationen

- [Erfahren Sie mehr über die Verwaltungsoberfläche vollständigen Richtlinie in Intune](https://docs.microsoft.com/intune/deploy-use/manage-settings-and-features-on-your-devices-with-microsoft-intune-policies)
