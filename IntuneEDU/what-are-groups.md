---
title: Was sind Gruppen?
titleSuffix: Intune for Education
description: "Informationen Sie zum Verwalten von Gruppen von Geräten mit Intune Education."
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 4b570196-a640-4d13-8e01-8e8553ce1468
searchScope:
- IntuneEDU
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: 925fee7b2807a340d2b4d0e1e9aa4ca069875f84
ms.contentlocale: de-de
ms.lasthandoff: 07/05/2017


---

# <a name="what-are-groups"></a>Was sind Gruppen?

Verwenden Sie _Gruppen_ zum Verwalten von Benutzern, apps und Geräte in Intune Education. Sie können Benutzern oder Geräten zusammen, ohne dass jedes Gerät einzeln verwaltet gruppieren. Dadurch können Sie problemlos apps oder Einstellungen für eine große Anzahl von Benutzern und Geräten zuweisen.

Wenn Sie Gruppen erstellen, erwägen Sie, wie Sie die Einstellungen und apps für Benutzer und Geräte angewendet werden. Beispielsweise müssen Sie apps mithilfe von Standortdiensten für alle Geräte zu blockieren. Eine Alternative besteht, wie bestimmte Gruppen möglicherweise bestimmte Aspekte, z. B. Vergabe Studenten dauert [AP Informatik](https://www.tealsk12.org) apps auf ihren Code zu bearbeiten.

Einstellungen werden auf Gruppen angewendet. Da Gruppen als Hierarchien mit einer Gruppe über eine andere eingerichtet sind [werden alle Einstellungen für eine Gruppe von alle Untergruppen geerbt](settings-inheritance.md). Dies erleichtert die Einstellungen auf größere Gruppen von Benutzern, apps und Geräten anwenden.

Intune Education erstellt automatisch die __alle Geräte__ und __alle Benutzer__ gruppiert werden, wenn Ihr Mandant erstellt wird. Diese Standardgruppen darstellen, die allgemeinsten Kategorien von Benutzern und Geräten in Ihrem Geschäfts-, Schul- oder UNI-Region und [kann nicht verschoben werden](what-are-groups.md#why-cant-i-move-certain-groups).


## <a name="managing-groups-and-subgroups"></a>Verwalten von Gruppen und Untergruppen

Sie können Gruppen erstellen, navigieren Sie zur **Gruppen**, wählen Sie dann **Gruppenerstellungs** vom oberen Rand der Liste. Sie können weitere Gruppen organisieren, indem erstellen *Untergruppen* unter einer beliebigen Gruppe mit Ausnahme von __alle Geräte__ oder __alle Benutzer__.

  ![Seite Untergruppe erstellen mit den beiden Speicherorten für die Erstellung von Untergruppen – am oberen Rand der Gruppenname und der Randleiste – rot eingekreist](./media/groups-007-create-subgroup.png)

1. In der [Intune für die Bildung Konsole](https://intuneeducation.portal.azure.com)Option **Benutzer- und Gerätegruppen verwalten**.
2. Wählen Sie die Gruppe, die unter der Sie eine Untergruppe erstellen möchten.
3. Klicken Sie auf **Untergruppe erstellen**, geben Sie dann die **Gruppenname**.

## <a name="making-changes-to-groups"></a>Änderungen an Gruppen

Nachdem Sie eine Gruppe erstellt haben, es ist möglich, müssen Sie seine Mitgliedschaft bearbeiten – z. B. wenn ein Gerät muss übertragen werden können, an einem anderen Schule in Ihrer Region.

  ![Geräte in einer Gruppe bearbeiten](./media/groups-008-edit-group-membership.png)

1. Wählen Sie die Gruppe, deren Mitglieder, die Sie bearbeiten möchten.
2. Wählen Sie die **Geräte** Registerkarte.
3. Wählen Sie die **Geräte bearbeiten** Schaltfläche aus, und wählen Sie dann **Geräte hinzufügen** Weitere Geräte aus einer Liste hinzufügen oder die **X** neben einem Gerät zu löschen.

Wenn Sie eine Gruppe umbenennen möchten, wählen Sie die Gruppe, die umbenannt werden soll, muss die **umbenennen** Schaltfläche, um den Namen zu bearbeiten.

## <a name="move-a-group"></a>Verschieben einer Gruppe

Sie können eine Gruppe in der Gruppenstruktur verschieben oder **Hierarchie**.

  ![Verschieben Sie gruppieren in rot eingekreist](./media/groups-010-move-groups.png)

1.  In der [Intune für die Bildung Portal](https://intuneeducation.portal.azure.com), wählen Sie **Gruppen verwalten**.
2. Wählen Sie die Gruppe, die verschoben werden soll.
3.  Klicken Sie auf **Gruppe verschieben** in der Liste oder durch Auswählen der **Gruppe verschieben** Schaltfläche.
4.  Wählen Sie die Gruppe-Speicherort, zu dem Sie die Gruppe verschoben werden, indem Sie entweder einen Gruppennamen suchen oder indem Sie sie in der Hierarchie auswählen möchten.
5.  Wählen Sie **OK** zum Speichern der Änderungen.

## <a name="why-cant-i-move-certain-groups"></a>Warum verschieben kann nicht ich bestimmte Gruppen?

Intune Education bietet eine Reihe von Standardgruppen, die verschoben werden kann, **alle Benutzer** und **alle Geräte**, wenn Ihre [-Mandant wird erstellt](what-are-tenants.md). **Alle Lehrer** und **aller Studenten** werden Standardgruppen, die erstellt werden, nachdem School-Datensynchronisierung Student "und" Lehrer Daten in Intune für die Bildung importiert wurde.

Dies kann nur selten ein Problem führen, in dem Sie eine Untergruppe unter zwei Gruppen zum Schluss können.

  ![Untergruppe unter mehreren Gruppen Fehlermeldung wird angezeigt.](./media/groups-012-subgroup-is-under-two-groups-warning.png)

In diesem Fall müssen Sie eine einzelne Gruppe platzieren oberhalb dieser Untergruppe zu wählen.

## <a name="delete-a-group"></a>Löschen einer Gruppe

Wenn Sie eine Gruppe löschen, entfernt Intune Education die Auflistung von apps oder Einstellungen auf jedem Gerät, das ein Mitglied dieser Gruppe ist. Beim Löschen einer Gruppe werden nicht auf die Benutzer oder Geräte aus der Verwaltung entfernt.

  ![Löschen Sie die Schaltflächen, die rot eingekreist Gruppen](./media/groups-011-delete-groups.png)

1.  In der [Intune für die Bildung Portal](https://intuneeducation.portal.azure.com), wählen Sie **Gruppen verwalten**.
2. Wählen Sie die Gruppe, die Sie löschen möchten.
3.  Klicken Sie auf **Gruppe löschen** entweder in der Taskliste aus.

## <a name="find-out-more"></a>Weitere Informationen

- [Erfahren Sie mehr über die vollständige Gruppen Verwaltungsoberfläche in Intune](https://docs.microsoft.com/intune/deploy-use/use-groups-to-manage-users-and-devices-with-microsoft-intune)

