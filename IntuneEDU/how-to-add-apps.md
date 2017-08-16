---
title: "Hinzufügen von Apps"
titleSuffix: Intune for Education
description: "Informationen Sie zum Hinzufügen von apps zu Intune Education."
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: 24ab6547-aa65-428a-b184-06b806e95bd1
searchScope: IntuneEDU
ms.openlocfilehash: 7a2298d4a1b55d8a1355ca9e828d92c0a561eac8
ms.sourcegitcommit: 293ad8c775aa37b5d3b6a9e547c80f31ba6a5bdd
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/15/2017
---
# <a name="how-do-i-add-apps-to-intune-for-education"></a>Wie füge ich Intune Education apps hinzu?

Vor der Installation von apps auf Ihre Schule-Geräten mit Intune Education müssen diese apps in Ihrem Intune für Education Konto hinzugefügt werden.

Intune Education unterstützt die folgenden Arten von apps:
- Web-apps, wie z. B. [Online Microsoft Word](https://office.live.com/start/Word.aspx)
- Microsoft Store für Education-apps sind [Universal-apps, verteilt über den Store](https://technet.microsoft.com/itpro/windows/manage/apps-in-windows-store-for-business)
- Desktop-apps wie z. B. [eigenständigen Microsoft Office](https://products.office.com/products)

Nachdem Sie apps hinzugefügt haben, können Sie [installieren Sie die apps](install-apps.md) auf Gruppen von Geräten.

Einstellungen werden auf Gruppen, einschließlich Gruppen, die Apps angewendet. Da Gruppen als Hierarchien mit einer Gruppe über eine andere eingerichtet sind [keine apps zu einer Gruppe zugewiesen werden von allen Untergruppen geerbt](settings-inheritance.md).

## <a name="add-web-apps"></a>Hinzufügen von webapps

Ein _Web-app_ ist eine app, die von Benutzern, die ausschließlich in einem Browser zugegriffen wird. Sie sind einfach zu zugewiesen werden, da beim Senden an Benutzer haben Links zu Websites, anstatt alle Dateien auf ihren Geräten senden sind.

Sie können die Web-apps als Links im Startmenü von Windows 10-Geräte mit Intune Education zuweisen. Um eine app zuordnen möchten, müssen Sie zuerst hinzufügen sie Intune für die Bildung in der **Verwalten von apps** Abschnitt.

  ![Das Hinzufügen einer Seite neue Web-app, die Benutzer die Informationen in das folgende Verfahren beschriebenen aufgefordert werden.](./media/apps-001-add-webapp.png)

1. In der [Intune Education](https://intuneeducation.portal.azure.com) -Konsole, und wählen Sie **Apps**.

2. Klicken Sie unter **Web apps**Option **+ neue app**, geben Sie dann die folgenden Details:
 * **URL** – die URL der app, die Sie zuweisen möchten.
 * **App-Name** – der Name der app angezeigt wird, im Startmenü auf Geräten
 * **Symbol "** – hochladen PNG- oder JPG von Ihrem Computer als Symbol für die app verwenden

3. Wählen Sie **Speichern** aus. Ihre Web-app ist jetzt bereit.

4. Sie können jetzt [installieren Sie die app auf Geräten](install-apps.md).

Sie können die app jederzeit bearbeiten, indem auswählen **bearbeiten**, die erneut öffnet die Seite "Details".

## <a name="add-desktop-apps"></a>Hinzufügen von desktop-apps

Sie können über die gleiche Schnittstelle-desktop-apps installieren, auf die **Apps** Seite. Dieser Prozess ähnelt dem eine Web-app installieren, jedoch umfasst die Installationsdatei, die keine Web-apps erfordern.

![Der Bildschirm für neue desktop-app.](./media/apps-003-add-desktop-app.png)

1. In der [Intune Education](https://intuneeducation.portal.azure.com) -Konsole, und wählen Sie **Apps**.

2. Klicken Sie unter **Desktop-apps**Option **+ neue app**. Dies öffnet die **neue desktop-app** Bildschirm, und geben Sie die folgenden Details:
 * **App-Datei** – eine MSI-Installationsprogramm für die app hochladen
 * **App-Name** – der Name der app auf Geräten angezeigt werden.
 * **Beschreibung** – ist eine Beschreibung der app, die Ihnen helfen, schnell identifizieren der app
 * **Publisher** – der Name der Herausgeber der app können Sie schnell identifizieren, die die app entwickelt
 * **Symbol "** – hochladen PNG- oder JPG von Ihrem Computer als Symbol für die app verwenden

3. Wählen Sie **speichern und Hochladen der Datei**.

  ![Das Hinzufügen neuer desktop-app-Bildschirm, mit allen Feldern für die Beispiel-app, Evernote ausgefüllt.](./media/apps-004-filled-out-desktop-app.png)

4. Die app wird dann in Intune Education hochladen. Nachdem das Hochladen abgeschlossen ist, können Sie [installieren Sie die app auf Geräten](install-apps.md).

> [!NOTE]
> In einigen Fällen kann ein Fehler auftreten, die besagt, dass "die app verfügt nicht über eine Installationsdatei" oder "Es wurde keine app-Installationsdatei hinzugefügt". Dies bedeutet, dass die Datei ordnungsgemäß hochgeladen haben nicht. Versuchen Sie es speichern und Laden Sie die Datei erneut aus, um diesen Fehler zu beheben.

## <a name="add-popular-apps"></a>Hinzufügen von beliebten apps

Sie können auch schnell beliebten Bildungseinrichtung apps aus dem Microsoft Store Education installieren. Unser Ziel ist es zu suchen und installieren Sie Ihre bevorzugten apps für Ihre Benutzer vereinfachen. Diese apps wird empfohlen, da es häufig sinnvoll, Erzieher sind. Sie können diese apps finden Sie in der Express-Konfiguration oder unter der **Verwalten von apps** Kachel.

  ![Eine Auswahl von beliebten apps während der Prozess zum Hinzufügen von apps in Express-Konfiguration.](./media/apps-005-popular-apps.png)

Die Intune für die Bildung Portal zeigt die obersten zwölf Bildungseinrichtung web-apps und die ersten zwölf Bildungseinrichtung Microsoft Store für Education-apps, die noch nicht unter hinzugefügt **Apps** Management.

> [!TIP]
> Wenn Sie Ihre Microsoft Store für Education Konto zum Hinzufügen von apps zu Intune Education eingerichtet haben, können Sie erfahren Sie, wie dies [hier](acquire-store-apps.md).

1. In der [Intune Education](https://intuneeducation.portal.azure.com) -Konsole, und wählen Sie **Apps verwalten** > **Hinzufügen von apps** > **schnellen Hinzufügen beliebten apps**. Eine Liste der **Web apps** und **Microsoft Store-apps** wird angezeigt.

  ![Der schnellen Hinzufügen Bildschirm "beliebten apps".](./media/apps-006-add-popular-apps.png)

2. Wählen Sie die apps, die Sie verwenden möchten, hinzufügen, und wählen Sie dann **Hinzufügen von apps**.

  ![Bei der Auswahl mehrere gängige apps das Portal hinzu.](./media/apps-007-select-multiple-popular-apps.png)

3. Ihre apps fügen im Hintergrund und angezeigt werden, auf der linken Randleiste, sobald er bereit ist.

  ![Ihre apps werden Bildschirm hinzugefügt.](./media/apps-008-your-popular-apps-are-being-added.png)

## <a name="find-out-more"></a>Weitere Informationen

- [Erfahren Sie mehr über die vollständige Erfahrung mit dem Verwalten von apps mit Intune](https://docs.microsoft.com/intune/deploy-use/add-apps)
