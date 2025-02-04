---
title: Automatic MDM enrollment in the Intune admin center
description: Automatic MDM enrollment in the Intune admin center
ms.topic: article
ms.date: 08/10/2023
---

# Automatic MDM enrollment in the Intune admin center

Windows devices can be enrolled in to Intune automatically when they join or register with Azure Active Directory. Automatic enrollment can be configured in Azure portal.

1. Go to your Azure AD portal.
1. Select **Mobility (MDM and MAM)**, and find the Microsoft Intune app.
1. Select **Microsoft Intune** and configure the enrollment options. You can specify settings to allow **All** users to enroll a device, or choose to allow **Some** users (and specify a group).

   ![Configure the Blade.](images/azure-intune-configure-scope.png)

1. Select **Save** to configure MDM autoenrollment for Azure AD joined devices and bring-your-own-device scenarios.
