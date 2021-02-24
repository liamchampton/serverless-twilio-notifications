# serverless-twillio-notifications
IBM Cloud Functions serverless code to send a text message using the Twillio API. Based upon a pull request action, code will be executed.

For worksop material and instructions please follow https://github.com/IBMDeveloperUK/Cloud-Functions-Twilio-Notifications

## Params
`action` = GitHub Webhook [pull requests actions](https://docs.github.com/en/developers/webhooks-and-events/webhook-events-and-payloads#pull_request)

`twilioNumber` = Your number associated with your Twilio Account

`recipientNumber` = The number you wish to send a text message too

`accountSid` = Your Twilio Account SID (Found on your dashboard)

`authToken` = Your Twilio Account Auth Token (Found on your dashboard)
