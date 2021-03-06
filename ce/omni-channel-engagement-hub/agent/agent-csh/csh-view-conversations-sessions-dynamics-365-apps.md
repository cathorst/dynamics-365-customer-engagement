---
title: "View omni-channel conversation and session form in Dynamics 365 for Customer Engagement apps | MicrosoftDocs"
description: "Learn about the omni-channel conversations and session forms that users (agents and supervisors) who are not part of can Omni-channel Engagement Hub can under the Acitivities in Dynamics 365 for Customer Engagement apps."
keywords: ""
author: kabala123
ms.author: kabala
manager: shujoshi
applies_to: 
ms.date: 2/8/2019
ms.service: dynamics-365-customerservice
ms.topic: article
ms.assetid: BAC4B607-59A4-4FD2-B121-9799081D5EB1
ms.custom: 
---

# View conversation and session form in Dynamics 365 for Customer Engagement apps

Applies to Dynamics 365 for Customer Engagement apps version 9.1.0

[!include[cc-beta-prerelease-disclaimer](../../../includes/cc-beta-prerelease-disclaimer.md)]

Your organization might have a classification where certain agents work in the contact center, which uses Omni-channel Engagement Hub on the web and certain agents work in another contact center, which uses Dynamics 365 for Customer Engagement apps. In this case, if you are an agent who works on Dynamics 365 for Customer Engagement apps and you need to analyze the conversation request from Omni-channel Engagement Hub on the web, you can find the information through **Activities** in Dynamics 365 for Customer Engagement apps.

You can find the following activity types in Dynamics 365 for Customer Engagement apps:

-   Conversation Form

-   Session Form

### Conversation Form

The Conversation Form displays information about an engagement request.

![Omni-channel conversation form](../../media/csh-oc-conversation-form.png "Omni-channel conversation form")  

| **Tab** | **Section**     | **Fields**        |
|---------|-----------------|-------------------|
| Details | Details         | Title             |
|         |                 | Customer          |
|         |                 | Work stream       |
|         |                 | Active agent      |
|         |                 | Activity status   |
|         |                 | Status reason     |
|         |                 | Status updated on |
|         |                 | Regarding         |
|         |                 | Queue             |
|         | History         | Create on         |
|         |                 | Closed on         |
|         |                 | Modified on       |
|         |                 | Transfer count    |
|         |                 | Escalation count  |
|         | Session Details | Subject           |
|         |                 | Date created      |
|         | Chat Transcript | Download          |

### Session form

The session form displays information about a conversation request.

![Omni-channel session form](../../media/csh-oc-session-form.png "Omni-channel session form")  

| **Tab** | **Section**          | **Field**          |
|---------|----------------------|--------------------|
| General | Header               | Activity Status    |
|         | General              | Subject            |
|         |                      | Owner              |
|         |                      | Conversation id    |
|         |                      | Session Created On |
|         |                      | Session Closed On  |
|         |                      | Agent Assigned On  |
|         |                      | Agent Accepted On  |
|         |                      | Regarding          |
|         |                      | Name               |
|         |                      | Created on         |
|         | Session Participants | Agents             |
|         |                      | Joined On          |
|         |                      | Left On            |
|         |                      | Mode               |

The Session Participants section lets you add a participant related to the session or add a session participant that already exists for the record you are working with.

> [!div class="nextstepaction"]
> [Next topic: View customer summary for an incoming conversation request](csh-view-customer-360-incoming-conversation-request.md)

## See also

- [Sign in to Dynamics 365 Customer Service hub](csh-sign-dynamics-365-customer-service-hub.md)
- [Introduction to the agent interface](csh-introduction-agent-interface-omni-channel-engagement-hub-customer-service-hub.md)
- [Know the sitemap navigation](csh-sitemap.md)
- [Navigate using the navigation bar](csh-navigation-bar.md)
- [Navigation bar buttons](csh-navigation-bar-buttons.md)
- [View agent dashboard and agent work items](csh-my-dashboard.md)
- [View communication panel](csh-conversation-control.md)
- [View notifications and screen pops](csh-notifications-screen-pops.md)
- [View customer summary](csh-customer-360-overview-of-the-existing-challenges.md)
- [Search for and share knowledge articles](csh-search-knowledge-articles.md)
- [Take notes specific to conversation](csh-take-notes.md)
- [Create a record](csh-create-record.md)
- [Search and link record to the conversation](csh-search-link-record.md)
