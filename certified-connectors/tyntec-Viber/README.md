## Tyntec Conversation API - Send Viber

Tyntec Conversation API allows you to send customized Viber messages.

### User Cases of this connector
- Use this connector in PowerApps Workflows (great for Marketing, CRM or Sales)
- Send SMS messages using Azure Logic Apps
- Build SMS support in your Microsoft Power Automate automatizations

And many more!


## Pre-requisites
You will need the following to proceed:
- A Microsoft Power Apps or Power Automate plan with custom connector feature
- [tyntec API Key](http://my.tyntec.com/api-settings)
- [Viber Service ID](https://www.tyntec.com/viber-business-messages#contact)

## Supported requests
- **Send_Viber** using tyntec Conversation API [reference](https://api.tyntec.com/reference/#conversations-send-messages-send-a-message)
 - To make a successful request, please, populate the followings fields:
 - **apikey** - your tyntec API key
 - **to** - receiver's phone number in _international_ form without leading 00 (_E.g. 4989202451100_)
 - **from** - your Viber Service ID
 - **contentType** - content type of your message, use **text**
 - **channels key item** - used tyntec Conversation API channel, use **viber**
 - **text** - text of your Viber message
- **Status_Check**
 - To make a successful status check, please, provide the connector with the following values
 - **apikey** - your tyntec API key
 - **id** - messageID of your message (_returned after each request_)


## How to get API key 
Please [sign up for a free account](https://www.tyntec.com/create-account). In your account, select the [API settings](http://my.tyntec.com/api-settings) and copy your API key.

## How to get Viber Service ID
Please, fill our [form](https://www.tyntec.com/viber-business-messages#contact). Tyntec will guide you through the whole process.

## Deployment instructions
Please use [these instructions](https://docs.microsoft.com/en-us/connectors/custom-connectors/paconn-cli) to deploy this connector as a custom connector in Microsoft Power Automate and Power Apps.

