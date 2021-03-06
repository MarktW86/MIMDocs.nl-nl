---
title: Stap 7 SID-geschiedenis/filtering instellen
description: Dit is de stap 7 van de procedure voor het configureren van Privileged Identity Manager met behulp van scripts. Deze stap omvat het instellen van de SID-geschiedenis/SID-filtering.
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
ms.openlocfilehash: e608593f40759e3bc995daa56c4575510a71e987
ms.sourcegitcommit: 02fb1274ae0dc11288f8bd9cd4799af144b8feae
ms.translationtype: MT
ms.contentlocale: nl-NL
ms.lasthandoff: 07/13/2017
---
# Stap 7 SID-geschiedenis/filtering instellen
<a id="step-7-set-up-sid-historysid-filtering" class="xliff"></a>

>[!div class="step-by-step"]
[« Stap 6](sp1-step6-setup-pam-trust.md)
[Stap 8 »](sp1-step8-pam-deployment-verification.md)

**Dit is niet vereist voor alleen een PRIV-omgeving** Meld u aan bij de PAM-server met het MIMAdmin-account.

1. Meld u aan bij de CORP DC als administrator
2. Voer PowerShell uit als Administrator
3. cd $env:SYSTEMDRIVE\PAM
4. .\PAMDeployment.ps1
5. Selecteer menuoptie 8 (Setup SID history/SID filtering)

Als de uitvoering is geslaagd, verschijnen de volgende berichten:<br/></br>
Voor SID-filtering: <br/></br>
Instellen dat de vertrouwensrelatie geen SIDs filtert of SID-filtering is niet ingeschakeld voor deze vertrouwensrelatie. </br></br>
Voor SID-geschiedenis: </br></br>
SID-geschiedenis wordt ingeschakeld voor deze vertrouwensrelatie of SID-geschiedenis is al ingeschakeld voor deze vertrouwensrelatie.

>[!div class="step-by-step"]
[« Stap 6](sp1-step6-setup-pam-trust.md)
[Stap 8 »](sp1-step8-pam-deployment-verification.md)
