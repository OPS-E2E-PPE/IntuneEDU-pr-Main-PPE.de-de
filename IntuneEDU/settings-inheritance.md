---
title: Was ist die Vererbung der Einstellungen?
titleSuffix: Intune for Education
description: "Informationen Sie zum Verwalten von Einstellungen für Gruppen von Geräten mit Intune Education."
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 4b69b884-bed9-43f4-8507-c802228a8804
searchScope: IntuneEDU
ms.openlocfilehash: 388e4f4468c3184d4dd941c74f8524a6302694f3
ms.sourcegitcommit: 293ad8c775aa37b5d3b6a9e547c80f31ba6a5bdd
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/15/2017
---
# <a name="what-is-settings-inheritance"></a>Was ist die Vererbung der Einstellungen?

Einstellungen werden auf Gruppen angewendet. Da Gruppen als eingerichtet sind, werden Hierarchien mit einer Gruppe über ein anderes, alle Einstellungen für eine Gruppe von alle Untergruppen geerbt. Dies erleichtert die Einstellungen auf größere Gruppen von Benutzern, apps und Geräten anwenden.

  ![Eine Struktur von Gruppen und Untergruppen.](./media/groups-002-inheritance.png)

Dies bedeutet, dass für eine beliebige Gruppe mit einer Untergruppe darunter, die Untergruppe automatisch alle Änderungen, die erben Sie die Gruppe über ihm vornehmen. Hierbei spricht _Vererbung_.

## <a name="can-i-configure-subgroups-differently-after-inheriting-settings-from-another-group"></a>Kann ich Untergruppen unterschiedlich konfigurieren nach der Übernahme der Einstellungen aus einer anderen Gruppe?

Untergruppen können einzeln konfiguriert werden, auch wenn sie Einstellungen von der Gruppe darüber liegenden erben. Sie können geerbte Standardeinstellungen überschreiben, indem einfach Konfigurieren der Einstellungen, die Sie benötigen, und klicken Sie dann speichern möchten.

## <a name="can-i-ever-end-up-with-settings-that-do-not-work-together"></a>Kann ich jemals mit Einstellungen annehmen, die nicht zusammenpassen?

Wenn mehrere Einstellungen auf der gleichen Gruppe angewendet wurden, wird jede Einstellung einzeln von Intune Education analysiert. Bestimmte Einstellungen, die Benutzer zu ergreifen, um ihre Geräte mit den Einstellungen entsprechen stellen gezwungen werden immer andere Einstellungen Vorrang.

Betrachten Sie eine Untergruppe *zwölften Grade AP Informatik*, zur Gruppe *zwölften Grade*. Sie wissen, dass die AP-Computerklasse Science müssen einige JavaScript-Dateien herunter, die Security-Überprüfung nicht benötigen, aber Sie möchten sicherstellen, dass die gesamte Grade nicht versucht wird, um diesen Vorgang auszuführen. Wenn Sie Vererbung von Einstellungen, die restriktiver ist nicht außer Kraft setzen *zwölften Grade* Einstellung gelten für die Benutzer in *zwölften Grade AP Informatik*.

## <a name="find-out-more"></a>Weitere Informationen

  - [Finden Sie heraus, die mehr über die vollständige Gruppen auftreten, in Intune](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)
