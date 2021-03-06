---
title: "Configure email | Microsoft Docs"
description: "Learn how to configure email."
ms.date: 08/03/2020
ms.service:
  - "dynamics-365-customerservice"
ms.topic: article
author: lerobbin
ms.author: lerobbin
manager: shujoshi
---

# Configure email 

[!include[cc-early-access](../includes/cc-early-access.md)]

> [!Note] 
> The existing enhanced email form will be deactivated with the general availability of the 2020 release wave 2 features. In the latest version of the Sales app (build 9.0.2006.5005), you'll notice that the name of the existing enhanced email form is changed to Enhanced Email (deprecated). A new form named Enhanced Email has been introduced with the new enhanced capabilities like quick preview or multiple email attachments. If you don't opt in for early access of the 2020 release wave 2 features, this form will be presented in a Read-only mode.

Email is a critical communication tool that allows users to interact with customers in a timely and effect manner. The email experience in customer engagement apps provides an easy and immersive rich text email experience for users that helps them deliver a more professional and consistent personalized service in an efficient and effective manner using templates and enhanced features and functionality.  

This experience gives system administrators the ability to configure email templates and enable quick access to email to help users create emails quickly directly from the timeline so they can deliver a more personalized service.

How to navigate email configurations
- [How to configure the email form order](customer-service-hub-user-guide-email-admin.md#how-to-configure-the-email-form-order)
- [How to enable the enhanced email experience](customer-service-hub-user-guide-email-admin.md#how-to-enable-the-enhanced-email-experience)
- [How to configure email attachments size limitations](customer-service-hub-user-guide-email-admin.md#how-to-configure-email-attachment-size-limitations)


## How to configure the email form order
Email must be enabled for users so they can view and access it. Unless email is enabled, it won't be available as an option on the command bar.

To enable email:

1.	Go to **Settings** > **Advanced Settings**.
2.	Select **Settings** > **Customizations** > **Customize the System**.
3.	Expand **Entities**, select and expand **Email**, and then select **Forms**.
4.	On the command bar, select **Form Order**. A drop-down list appears.
5.	Select **Main Form Set**.
    The **Form Order** display window appears, which shows all email forms that are enabled to be available. Both the 'Navigate-to' to and 'Contextual' (pop-up) email experience work off of the same form order. 
6.	If **Enhanced email** doesn't display at the top of the list, use the arrows to move it up so that it displays first on the list.
7.	Select **OK**
8.	You must **Publish All Customizations** for changes to appear; otherwise they will not display.

![How to enable email](media\email-how-to-enable-email-1.png "How to enable email")
![How to enable email](media\email-how-to-enable-email-2.png "How to enable email")
![How to enable email](media\email-how-to-enable-email-3.png "How to enable email")
![How to enable email](media\email-how-to-enable-email-4.png "How to enable email")
![How to enable email](media\email-how-to-enable-email-5.png "How to enable email")

## How to enable the enhanced email experience
Enhanced email is the default setting, but you must enable email for users to access and use the feature. 

Sign in to https://<YourOrgURL>.dynamics.com/apps and open a customer engagement app. In the app:
1.	Go to **Settings**.
2.	Select **Advanced Settings** > **Settings**.
3.	Select **Administration** > **System Settings**.
4.	Select the **Email** tab.
5.	To enable pop-up email windows, click the box in the **Enhanced email for Timeline** section. 
6.	Select **OK** to save your global organizational setting and close.

![How to enable the enhanced email experience](media\email-how-to-enable-email-1.png "How to enable the enhanced email experience")

![How to enable the enhanced email experience](media\email-how-to-enable-the-enhanced-email-experience-1.png "How to enable the enhanced email experience")

![How to enable the enhanced email experience](media\email-how-to-enable-the-enhanced-email-experience-2.png "How to enable the enhanced email experience")

![How to enable the enhanced email experience](media\email-how-to-enable-the-enhanced-email-experience-3.png "How to enable the enhanced email experience")

## How to configure email attachment size limitations
You can manage file size limits for emails file attachments. 

To manage email attachment size limitations, use the following steps: 
1.	Under **System Settings**, go to **Email**.
2.	Under the **Set file size limit for attachments** section, set file size on attachments. 

> [!Note] 
> The default file size limit for attachments is 5 MB. The size limit for attachments can be increased to a maximum of 132 MB per file. 

![How to configure email attachment size limitations](media\email-how-to-configure-email-attachment-size-limitations-1.png "How to configure email attachment size limitations")


### See Also

[Email FAQs](email-faqs.md)
