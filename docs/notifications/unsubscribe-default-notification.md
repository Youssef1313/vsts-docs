﻿---
title: View subscribed notifications
titleSuffix: Azure DevOps
description: View your notifications and unsubscribe from a default or built-in notification in Azure DevOps or Team Foundation Server
ms.prod: devops
ms.technology: devops-collab
ms.topic: conceptual
ms.manager: mijacobs
ms.author: chcomley
author: chcomley
ms.date: 12/30/2019
monikerRange: '>= tfs-2017'
---

# View your subscriptions, opt-out as needed

[!INCLUDE [version-vsts-tfs-2017-on](../_shared/version-tfs-2017-through-vsts.md)]

If you want to stop receiving select email notifications, you can do so by unsubscribing from them. For a description of each default subscription, see [Default notifications](oob-built-in-notifications.md)  

You start by opening your personal notification settings. If you don't have a project yet, create one in [Azure DevOps](../organizations/accounts/set-up-vs.md).

::: moniker range=">= azure-devops-2019"

1. From your home page, select the user settings icon ![user-settings-gear.png](../_img/icons/user-settings-gear.png), and then select **Profile**.

   ![Open Azure DevOps profile](../_shared/_img/open-user-settings-profile-preview.png)

   The notifications you're subscribed to are indicated with the the blue toggle under State. 

   ![Notifications turned On](_img/notifications-turned-on.png)

   The following image indicates a subscription is a default or out-of-the-box (OOB) subscription:

   ![OOB notification](_img/oob-notification.png)

   You can't modify an OOB subscription, but you can view its definition from its context menu.

2. To unsubscribe, slide the toggle to the *Off* position.

	In the following image the "Build completes" subscription is turned off.

	![Notification is turned off](_img/notification-turned-off.png)

::: moniker-end

::: moniker range="<= tfs-2018" 

1. From the web portal, select the icon with your initials or picture, and select **Notification settings** from the drop-down menu.

	<img src="_img/unsubscribe-open-notification-settings.png" alt="Open personal notification settings" style="border: 2px solid #C3C3C3;" />

	The notifications you're subscribed to are indicated with the State as **On**.  

	<img src="_img/unsubscribe-personal-notifications.png" alt="Personal notification subscriptions" style="border: 2px solid #C3C3C3;" />

	The following image indicates a subscription is a default or out-of-the-box (OOB) subscription:

   ![OOB notification](_img/oob-notification.png)

	You can't modify an OOB subscription, but you can view its definition from its context menu.

2. To unsubscribe, slide the state **On/Off** indicator to the *Off* position.

	In the following image the "Build completes" subscription is turned off.

	<img src="_img/unsubscribe-from-build-completes.png" alt="Unsubscribe from Build completes subscription" style="border: 2px solid #C3C3C3;" />

::: moniker-end

