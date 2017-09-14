---
title: Was ist School-Datensynchronisierung?
titleSuffix: Intune for Education
description: Verwendung School-Datensynchronisierung School-Gruppen und Benutzer in Azure AD zu importieren.
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 08/11/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: f9cb6daf-a789-427b-bbfd-fa0a3d36e01f
searchScope: IntuneEDU
ms.openlocfilehash: be48cf06dc4ddc037a04398141bfcc197512ddaf
ms.sourcegitcommit: f4fb37302cb3c927196958c33e7215f7827bfcb3
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/14/2017
---
# <a name="what-is-school-data-sync"></a>Was ist School-Datensynchronisierung?

Microsofts School Daten Synchronisierungsgruppe (SDS) können Sie die School-Datensätze aus einer vorhandenen Student Informationssystems (SIS) Daten mit Intune Education importieren.

SDS dupliziert die Informationen aus der SIS und speichert ihn in Azure Active Directory (AD). Azure AD ist ein Microsoft-Verwaltungssystem, das Ihnen das Organisieren von Studenten und Geräten hilft. Anschließend können Sie diese Daten mit Intune Education zum Bereitstellen von apps und Verwalten von Einstellungen. [Weitere Informationen zur Bereitstellung von SDS](https://support.office.com/article/Overview-of-School-Data-Sync-and-Classroom-f3d1147b-4ade-4905-8518-508e729f2e91).

Beim Importieren von Informationen aus der SIS in Intune für die Bildung mit School-Datensynchronisierung stellen Sie sicher, dass Sie enthalten __Grade__ und __sich auf die Einteilung Jahr__ Wenn Sie beabsichtigen, stellen [dynamische Gruppen](what-are-groups.md#managing-groups-and-subgroups) mit diesen Eigenschaften. Dies ist unter __Student Optionen__ > __Student-Eigenschaften auswählen__. Sie können diese Informationen verwenden, um ein Profil zu erstellen.  

## <a name="find-out-more"></a>Weitere Informationen

- [Erfahren Sie mehr über die Synchronisierung von Schul-/Unidaten von Microsoft](https://sds.microsoft.com)
