# Webhook Authorization

This repo provides of an example of preforming webhook authorization for the messages API. For a full explainer see the concepts page on our [documentation website](https://developer.nexmo.com/messages/concepts/signed-webhooks).

## Setup

1. Clone this repo
2. Copy env.example to .env
3. Set the value of NEXMO_API_SIGNATURE_SECRET to your signing secret from your [dashboard](https://dashboard.nexmo.com/settings)
4. Install the required node packages `npm install dotenv jsonwebtoken js-sha256 express body-parser`
5. Start your server with `node server.js`
6. Reconfigure your app's webhooks to point at your server
7. Send your app a message
