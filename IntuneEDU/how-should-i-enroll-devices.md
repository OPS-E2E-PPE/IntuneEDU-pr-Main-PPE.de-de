---
title: Wie soll ich meine Geräte?
titleSuffix: Intune for Education
description: Erfahren Sie, nach Möglichkeiten zum Registrieren Ihrer Geräte in Intune for Education.
keywords: ''
author: lenewsad
ms.author: lanewsad
manager: dougeby
ms.date: 06/18/2019
ms.topic: article
ms.prod: ''
ms.service: microsoft-intune
ms.technology: ''
ms.assetid: 45160df9-126d-4c51-a0d3-0e9fad0fe929
searchScope:
- IntuneEDU
ms.openlocfilehash: 450f7c2d8debf0308ec50ab3b8e8a42ccc158ceb
ms.sourcegitcommit: 9c43411a2c210cf1d755c3120015c89611e33613
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 06/18/2019
ms.locfileid: "67213094"
---
# <a name="how-should-i-enroll-devices"></a><span data-ttu-id="a992d-103">Wie sollte die Geräte werden registriert?</span><span class="sxs-lookup"><span data-stu-id="a992d-103">How should I enroll devices?</span></span>

<span data-ttu-id="a992d-104">Erfahren Sie, wie Sie Geräte in Intune für Bildungseinrichtungen-Verwaltung zu registrieren.</span><span class="sxs-lookup"><span data-stu-id="a992d-104">Learn how to enroll devices under Intune for Education management.</span></span> <span data-ttu-id="a992d-105">Um die beste Methode für Ihrer Schule/Universität zu wählen, sollten Sie die:</span><span class="sxs-lookup"><span data-stu-id="a992d-105">To choose the best method for your school, consider the:</span></span>  
* <span data-ttu-id="a992d-106">Die Größe des Ihrer Region.</span><span class="sxs-lookup"><span data-stu-id="a992d-106">Size of your district.</span></span>    
* <span data-ttu-id="a992d-107">Der Typ des Geräts Empfänger.</span><span class="sxs-lookup"><span data-stu-id="a992d-107">Type of device recipients.</span></span>    
* <span data-ttu-id="a992d-108">Die Anzahl der Mitarbeiter können.</span><span class="sxs-lookup"><span data-stu-id="a992d-108">Number of staff available to help.</span></span>   
 
<span data-ttu-id="a992d-109">Lesen auf die beste Methode zum Registrieren von Geräten in Ihrer Schule/Universität bestimmen.</span><span class="sxs-lookup"><span data-stu-id="a992d-109">Read on to determine the best way to enroll devices in your school.</span></span>    

## <a name="run-the-set-up-school-pcs-app"></a><span data-ttu-id="a992d-110">Führen Sie den Satz von Schul-/ PCs-Apps</span><span class="sxs-lookup"><span data-stu-id="a992d-110">Run the Set up School PCs app</span></span> 
<span data-ttu-id="a992d-111">Laden Sie einen Satz von Schul-/ optimierten Einstellungen aller Ihrer Windows 10-PCs hoch.</span><span class="sxs-lookup"><span data-stu-id="a992d-111">Upload a single set of school-optimized settings to each of your Windows 10 PCs.</span></span> <span data-ttu-id="a992d-112">Die [festlegen, dass "School" PCs app](https://docs.microsoft.com/education/windows/use-set-up-school-pcs-app) führt Sie durch die Schritte zum Erstellen eines Installationspakets, das für Bildungseinrichtungen geeignet ist.</span><span class="sxs-lookup"><span data-stu-id="a992d-112">The [Set up School PCs app](https://docs.microsoft.com/education/windows/use-set-up-school-pcs-app) guides you through how to create an installation package that's appropriate for schools.</span></span> <span data-ttu-id="a992d-113">Nachdem Sie das Konfigurieren von Einstellungen für das Netzwerk und die Geräte fertig sind, speichert die app das Paket auf einem USB-Laufwerk an.</span><span class="sxs-lookup"><span data-stu-id="a992d-113">After you're done configuring settings for your network and devices, the app saves the package to a USB drive.</span></span> <span data-ttu-id="a992d-114">Fügen Sie das USB-Laufwerk direkt in zu jeder Schüler/Student-PC, um automatisch das Gerät für Ihre Schüler/Studenten einzurichten.</span><span class="sxs-lookup"><span data-stu-id="a992d-114">Insert the USB drive directly in to each student PC to automatically set up the device for your students.</span></span> <span data-ttu-id="a992d-115">Die app ist auf PCs mit der Windows 10, Version 1803 und frühere Versionen kompatibel.</span><span class="sxs-lookup"><span data-stu-id="a992d-115">The app is compatible on PCs running Windows 10 version 1803 and earlier.</span></span>

## <a name="give-school-faculty-enrollment-manager-permissions"></a><span data-ttu-id="a992d-116">Geben Sie "School" Lehrkräfte geräteregistrierungs-Manager-Berechtigungen</span><span class="sxs-lookup"><span data-stu-id="a992d-116">Give school faculty enrollment manager permissions</span></span>
<span data-ttu-id="a992d-117">Fügen Sie geräteregistrierungs-Manager oder ein geräteregistrierungs-Manager-Konto, damit Ihre Mitarbeiter können Sie Geräte registrieren können.</span><span class="sxs-lookup"><span data-stu-id="a992d-117">Add enrollment managers, or an enrollment manager account, to allow your staff to help you enroll devices.</span></span> <span data-ttu-id="a992d-118">[Geräteregistrierungs-Manager](add-enrollment-managers.md) bis zu 1.000 Geräte registrieren können.</span><span class="sxs-lookup"><span data-stu-id="a992d-118">[Enrollment managers](add-enrollment-managers.md) can enroll up to 1,000 devices.</span></span>  

## <a name="allow-users-to-enroll-their-own-devices"></a><span data-ttu-id="a992d-119">Ermöglichen Sie Benutzern, ihre eigenen Geräte anzumelden</span><span class="sxs-lookup"><span data-stu-id="a992d-119">Allow users to enroll their own devices</span></span>
<span data-ttu-id="a992d-120">Ermöglichen Sie die vertrauenswürdige Benutzer ihre eigenen Geräte registrieren.</span><span class="sxs-lookup"><span data-stu-id="a992d-120">Allow trusted users to enroll their own devices.</span></span> <span data-ttu-id="a992d-121">Diese Benutzer können ihre Geräte automatisch in Azure AD einbinden.</span><span class="sxs-lookup"><span data-stu-id="a992d-121">These users are able to automatically join their devices to Azure AD.</span></span>  

## <a name="next-steps"></a><span data-ttu-id="a992d-122">Nächste Schritte</span><span class="sxs-lookup"><span data-stu-id="a992d-122">Next steps</span></span>  

<span data-ttu-id="a992d-123">Möchten Sie Ihre Geräte registrieren?</span><span class="sxs-lookup"><span data-stu-id="a992d-123">Ready to enroll your devices?</span></span> <span data-ttu-id="a992d-124">Weitere Informationen zum [iOS](add-devices-ios-edu.md) und [Windows 10](add-devices-windows.md) unter Intune-Geräten für Bildungseinrichtungen-Verwaltung.</span><span class="sxs-lookup"><span data-stu-id="a992d-124">Learn how to add [iOS](add-devices-ios-edu.md) and [Windows 10](add-devices-windows.md) devices under Intune for Education management.</span></span>  

* <span data-ttu-id="a992d-125">Der Store Dokumentation [Herunterladen der **School-PCs** app](https://www.microsoft.com/store/p/set-up-school-pcs/9nblggh4ls40) aus dem Microsoft Store.</span><span class="sxs-lookup"><span data-stu-id="a992d-125">See the Store documentation to [download the **Set Up School PCs** app](https://www.microsoft.com/store/p/set-up-school-pcs/9nblggh4ls40) from the Microsoft Store.</span></span> 
* <span data-ttu-id="a992d-126">Erfahren Sie mehr [über das Einrichten von Windows-Geräten in Bildungseinrichtungen](https://docs.microsoft.com/education/windows/set-up-windows-10) aus dem Microsoft Education > Windows-Dokumentation.</span><span class="sxs-lookup"><span data-stu-id="a992d-126">Find out more [about setting up Windows devices in schools](https://docs.microsoft.com/education/windows/set-up-windows-10) from the Microsoft Education > Windows documentation.</span></span>

