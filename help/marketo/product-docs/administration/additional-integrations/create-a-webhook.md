---
unique-page-id: 2360360
description: Create a Webhook - Marketo Docs - Product Documentation
title: Create a Webhook
exl-id: 3e753d2d-6f33-4987-884e-8e13167cf3df
---
# Create a Webhook {#create-a-webhook}

Use webhooks to take advantage of third-party web services to send text messages, expand person data, and more.

>[!AVAILABILITY]
>
>Not all customers have purchased this functionality. Contact your sales rep for details.

1. Go to the **Admin** area.

   ![](assets/create-a-webhook-1.png)

1. Click **Webhooks**.

   ![](assets/create-a-webhook-2.png)

1. Click **New Webhook**.

   ![](assets/create-a-webhook-3.png)

1. Name and configure your webhook.

   ![](assets/create-a-webhook-4.png)

   >[!NOTE]
   >
   >This often includes entering your third-party service credentials as a URL parameter, or in the POST template.

   * **URL**: Enter the URL you use in your request to the web service. To insert a token, such as the person's email address (**`{{lead.Email Address}}`**), in your request, click **Insert Token**.

   * **Template**: If you wish to transmit information in the body of the POST, enter the template. Use any data format that supports HTTP POST, including XML, JSON, or SOAP. To insert a token in your template, click **Insert Token**.

   * **Request Token Encoding**: If the token values include special characters (such as an ampersand, '&'), indicate the format of your request (**JSON** or **Form/Url**).

   * **Response type**: Select the format of the response you receive from the service (**JSON** or **XML**).

   * **Request Type**: Select the HTTP method to use (DELETE, GET, PATCH, POST, PUT).

1. Click **Create**.

   ![](assets/create-a-webhook-5.png)

>[!NOTE]
>
>Learn more in the [webhooks](https://developers.marketo.com/documentation/webhooks/) deep dive.
