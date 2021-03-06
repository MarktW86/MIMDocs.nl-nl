---
title: Stap 5 PAM installeren/configureren
description: Dit is stap 5 van de procedure voor het configureren van Privileged Identity Manager met behulp van scripts. In dit document worden de implementatiestappen op de PAM-server behandeld.
keywords: 
author: barclayn
ms.author: barclayn
manager: MBaldwin
ms.date: 01/10/2017
ms.topic: article
ms.service: microsoft-identity-manager
ms.technology: active-directory-domain-services
ms.assetid: 4b524ae7-6610-40a0-8127-de5a08988a8a
ms.reviewer: 
ms.suite: ems
ms.openlocfilehash: 862f62ab9bac87bcee31c35e249db34740e9fb14
ms.sourcegitcommit: 02fb1274ae0dc11288f8bd9cd4799af144b8feae
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 07/13/2017
---
# Stap 5 PAM installeren/configureren
<a id="step-5-installingconfiguring-pam" class="xliff"></a>

>[!div class="step-by-step"]
[« Stap 4](sp1-step4-configuring-sharepoint.md)
[Stap 6 »](sp1-step6-setup-pam-trust.md)

Voor een PAM-server die lid is van een domein meldt u zich aan als MIMAdmin. Anders meldt u zich aan als een lokale administrator.
1. Voer PowerShell uit als Administrator
2. cd $env:SYSTEMDRIVE\PAM
3. .\PAMDeploymnet.ps1
4. Selecteer menuoptie 5 (MIM PAM Setup)

>[!NOTE]
>Als de computer nog geen lid van een PRIV-domein is, wordt u gevraagd referenties in te voeren. Nadat u dit hebt gedaan, wordt de computer opnieuw opgestart.

Nadat de PAMServer opnieuw is opgestart, meldt u zich weer aan bij de computer met het MIMAdmin-account.

1. Voer PowerShell uit als Administrator
2. cd $env:SYSTEMDRIVE\PAM
3. .\PAMDeployment.ps1
4. Selecteer menuoptie 5 (MIM PAM Setup)

  Als u erom wordt gevraagd, voert u het wachtwoord van het MIM-controleaccount, MIM-onderdeelaccount, MIM MA-account, MIM-serviceaccount, MIM-beheeraccount en het SharePoint-account in.
  Nadat de installatie is voltooid, wordt de machine wordt opnieuw opgestart.

>[!div class="step-by-step"]
[« Stap 4](sp1-step4-configuring-sharepoint.md)
[Stap 6 »](sp1-step6-setup-pam-trust.md)
