---
title: Was sind Berichte?
titleSuffix: Intune for Education
description: "Erfahren Sie, wie Berichte Verständnis der Aktivität in Intune für die Bildung unterstützen können."
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: a5922c35-261c-43db-9c7b-c5c93af9cbec
searchScope: IntuneEDU
ms.reviewer: travisj
ms.openlocfilehash: b1a7a0a574982a48f46559ae0577e6663491b8b3
ms.sourcegitcommit: 293ad8c775aa37b5d3b6a9e547c80f31ba6a5bdd
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/15/2017
---
# <a name="what-are-reports-in-intune-for-education"></a>Was sind Berichte in Intune für die Bildung?

Intune Education bietet Berichte, mit die Sie bestimmte Aktivitäten von Geräten und apps mit Intune Education verwaltet anzeigen können. Sie können diese Berichte sind sie offline zu überprüfen.

Es gibt derzeit drei Arten von Berichten, die Sie in Intune für die Bildung anzeigen können: __Gerätebestand__, __Anwendungsinventur__, und __Einstellungsfehlern__.

1. In der [Intune Education](https://intuneeducation.portal.azure.com) -Konsole, und wählen Sie **Berichte** in der linken Navigationsleiste.

2. Wählen Sie den Bericht, den Sie anzeigen möchten. Die folgenden Berichte sind in Intune Education verfügbar:

  * **Gerätebestand** – eine Liste der Geräte von Intune Education verwaltet werden.

  ![Die Hardwareinventur Bericht Gerätebildschirm, zeigt eine Liste der Geräte in Intune für die Verwaltung der Education.](./media/reports-001-device-inventory.png)

  * **Anwendungsbestand** – eine Liste von apps auf Geräten unter Verwaltung von Intune installiert Education, einschließlich der Anzahl der Geräte mit dieser app installiert.

  ![Die Anwendung Berichts Bestandsliste, zeigt eine Liste von apps unter Intune für die Bildung-Verwaltung.](./media/reports-002-app-inventory.png)

  * **Einstellungsfehlern** – eine Liste der Einstellungen im [derzeit in Konflikt stehende](settings-inheritance.md) für alle Gruppen in Ihrer Hierarchie.

  ![Bildschirm mit einer Liste von Konflikten bei gruppenrichtlinieneinstellung melden die Settings-Fehler.](./media/reports-003-settings-error.png)

  Sie können auch den Typ der app (Web-app, Desktop-app, Microsoft Store-app), um nur Informationen anzeigen über diese bestimmte Art von app auswählen.

## <a name="download-reports"></a>Herunterladen von Berichten

Sie können Intune auch für Education-Berichten herunterladen. In der [Intune Education](https://intuneeducation.portal.azure.com) -Konsole, suchen Sie den Bericht interessieren Sie insbesondere herunterladen. Wählen Sie die **Bericht herunterladen** Schaltfläche zum Exportieren und das Herunterladen eines Berichts als Datei mit kommagetrennten Werten (CSV), die angezeigt und in einer Kalkulationstabelle app wie z. B. geändert werden kann [Excel](https://support.office.com/article/Import-or-export-text-txt-or-csv-files-5250ac4c-663c-47ce-937b-339e391393ba).

## <a name="find-out-more"></a>Weitere Informationen

- [Erfahren Sie mehr über das vollständige berichtsverhalten in Intune](https://docs.microsoft.com/intune/deploy-use/understand-microsoft-intune-operations-by-using-reports)
- [Erfahren Sie mehr über die berichterstellung mithilfe von Microsoft Graph](https://developer.microsoft.com/graph/docs/overview/overview)
