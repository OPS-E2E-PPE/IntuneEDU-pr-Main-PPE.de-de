---
title: "Hinzufügen von Geräten"
titleSuffix: Intune for Education
description: "Informationen Sie zum Einrichten von Windows 10-Geräte für Intune Education."
keywords: 
author: barlanmsft
ms.author: barlan
manager: angrobe
ms.date: 05/10/2017
ms.topic: article
ms.prod: 
ms.service: microsoft-intune
ms.technology: 
ms.assetid: c884df47-61a9-4799-a407-8cd311d376d1
searchScope:
- IntuneEDU
ms.translationtype: Machine Translation
ms.sourcegitcommit: f76a24da64ea7688f385c5ea15a368c76e982951
ms.openlocfilehash: 7b5343d996868ceaf18a58812a4db14d626d2969
ms.contentlocale: de-de
ms.lasthandoff: 07/05/2017


---

# <a name="how-do-i-add-devices-to-intune-for-education"></a>Wie füge ich Intune Education Geräte hinzu?

Nach dem Einrichten von Intune Education mit Ihren Informationen haben – z. B. Studentendatensätze, apps und Einstellungen für Geräte – müssen Sie die Geräte mit Intune Education verbinden. Diese Datenbank als Teil des Setupvorgangs für neue Windows 10-Geräte möglich.


> [!NOTE]
> Ihrer Geräte benötigen Zugriff auf das Internet und Ihrem Konto muss genügend Intune für die Bildung Gerätelizenzen verfügbar, um das Setup abzuschließen. Sie erhalten weitere Informationen finden Sie in unserem [Lizenzen Docs](https://docs.microsoft.com/intune/get-started/start-with-a-paid-subscription-to-microsoft-intune-step-4).

## <a name="add-devices-to-intune-for-education"></a>Hinzufügen von Geräten zu Intune Education

Sie müssen zu bringen führen Sie Folgendes ein, um Windows 10-Geräte in die Verwaltung von Intune Education schalten:

1. Aktivieren Sie das neue Windows 10-Gerät und starten Sie das standardmäßige Windows-Setup zu. Sie beim Erreichen der **Eigentümer dieser PC?** wählen **Meine Organisation oder Schule, besitzt er**.

  ![Screenshot von der "Wer diesen PC besitzt?" Bildschirm im Windows-setup](./media/devices-001-who-owns-this-pc.png)

2. Auf der **auswählen, wie Sie eine Verbindung herstellen müssen** wählen **Azure AD Join**.

  ![Screenshot des Bildschirms "Auswählen, wie Sie eine Verbindung herstellen" im Windows-setup](./media/devices-002-how-you-connect-pc.png)

3. Geben Sie die Details für die Intune-Administrator die Education oder **anderer Benutzer Berechtigung Registrierung** , und wählen Sie **Weiter**.

Ihr Gerät wird [bei Azure AD authentifiziert](https://docs.microsoft.com/azure/active-directory/active-directory-conditional-access) und erhalten die zugewiesenen apps und Einstellungen nach Abschluss des Setups.

Eine weitere Möglichkeit zum Registrieren von Geräten erfolgt über die [freien __School-PCs einrichten__ app](how-should-i-enroll-devices.md) , PCs, die mit einem USB-Schlüssel schnell einzurichten. 

## <a name="find-out-more"></a>Weitere Informationen
- [Erfahren Sie mehr über die **School-PCs einrichten** app](https://docs.microsoft.com/education/windows/use-set-up-school-pcs-app)
- [Erfahren Sie mehr über die vollständige Erfahrung, die zum Hinzufügen von Geräten in Intune](https://docs.microsoft.com/intune/deploy-use/enroll-devices-in-microsoft-intune)

