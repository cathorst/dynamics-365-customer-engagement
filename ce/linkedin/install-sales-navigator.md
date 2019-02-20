---
title: "Enable Default LinkedIn Sales Navigator for Dynamics 365 | Microsoft Docs"
description: "Enable the LinkedIn Sales Navigator for Dynamics 365 capabilities from AppSource"
keywords: "installation, setup, sales navigator"
ms.date: 2/20/2019
ms.service: crm-online
ms.topic: article
applies_to: 
  - "Dynamics 365 Version 9.x"
  - "Dynamics 365 (online)"
ms.assetid: 4b15aff2-3a7b-3488-260c-21611dee658a
author: m-hartmann
ms.author: mhart
manager: shellyha
search.audienceType: 
  - admin
  - customizer
  - enduser
search.app: 
  - D365CE
  - D365LinkedIn
---

# Enable Default Sales Navigator Controls for Dynamics 365 Unified Interface

## Prerequisites
- You have a System Administrator security role in [!INCLUDE[pn-dynamics-365](../includes/pn-dynamics-365.md)]. 
- [LinkedIn Sales Navigator for Dynamics CRM](https://appsource.microsoft.com/product/dynamics-365/linkedin.0cb76fe0-d453-4edb-a68c-65fb9119493a?tab=Overview) is installed. [Review the installation steps](https://www.linkedin.com/help/sales-navigator/topics/2052/2071/80081).
- You have a [Microsoft Relationship Sales subscription](https://dynamics.microsoft.com/sales/relationship-sales/) for Dynamics 365   
--OR--   
You will need to sign your team up for [LinkedIn Sales Navigator Team](https://business.linkedin.com/sales-solutions) or [LinkedIn Sales Navigator Enterprise](https://business.linkedin.com/sales-solutions).    
  We recommend having a Sales Navigator Administrator + Team Member seat to complete the installation. However, you may use a Sales Navigator Administrator seat.
- You will need to enable JavaScript in your browser.
- You will need to disable your pop-up blocker for the [!INCLUDE[pn-dynamics-365](../includes/pn-dynamics-365.md)] domain.


## Enable the default forms

1. Navigate to the business management settings
2. Select LinkedIn Sales Navigator
3. Click the toggle to enable "Enable Sales Navigator Itegration"
4. Select OK on dialogue

By following this process the LinkedIn Sales Navigator UCI controls will be enabled for the contact, opportunity, lead, and account forms. The Sales Navigator controls will now load on these forms when visited by users. For further control and customization take a look at [Customize forms to show Sales Navigator controls](add-sales-navigator-controls-forms.md).


## Disable the default forms

Disabling the forms follows the same process as enabling them.

1. Navigate to the business management settings
2. Select LinkedIn Sales Navigator
3. Click the toggle to disable "Enable Sales Navigator Itegration"
4. Select OK on the dialogue


### See also

[Overview for LinkedIn Sales Navigator solutions](integrate-sales-navigator.md)     
[Customize forms to show Sales Navigator controls](add-sales-navigator-controls-forms.md)    
[Work with Sales Navigator controls on forms](view-sales-navigator-forms.md)
