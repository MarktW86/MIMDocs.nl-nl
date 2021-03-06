---
title: Stap 6 De PAM-vertrouwensrelatie installeren
description: Stap 6 van de procedure voor het configureren van PAM met behulp van scripts. Deze sectie bevat informatie over het instellen van de vereiste vertrouwensrelatie tussen het CORP- en het PRIV-domein
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
ms.openlocfilehash: 3b232dfa515b42fd42a5606d1beff9d3fe50389c
ms.sourcegitcommit: 02fb1274ae0dc11288f8bd9cd4799af144b8feae
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 07/13/2017
---
# Stap 6 De PAM-vertrouwensrelatie installeren
<a id="step-6-set-up-the-pam-trust" class="xliff"></a>

>[!div class="step-by-step"]
[« Stap 5](sp1-step5-configuring-pam.md)
[Stap 7 »](sp1-step7-setup-sidhistory-sidfiltering.md)

**Dit is niet vereist voor alleen een PRIV-omgeving** Meld u aan bij de PAM-server met het MIMAdmin-account.

1. Meld u aan bij de PAM-server met het MIMAdmin-account
2. Voer PowerShell uit als Administrator
3. cd $env:SYSTEMDRIVE\PAM
4. .\PAMDeployment.ps1
5. Selecteer menuoptie 6 (PAM trust setup)

  Als u erom wordt gevraagd, geeft u de referenties voor het CORP-beheeraccount in. Na het opgeven van referenties wordt de vertrouwensrelatie bevestigd en is de configuratie voltooid.

>[!div class="step-by-step"]
[« Stap 5](sp1-step5-configuring-pam.md)
[Stap 7 »](sp1-step7-setup-sidhistory-sidfiltering.md)
