## Installation
In order to use Market-Alert you must have [Tampermonkey](https://www.tampermonkey.net/) installed.
Market-Alert has only been tested in Firefox, there might be issues with any other browser.

After Tampermonkey has been installed, use the button below to add Market-Alert to your TamperMonkey userscripts:

[![Install](https://img.shields.io/badge/Install-Tampermonkey-brightgreen.svg?style=for-the-badge)](https://raw.githubusercontent.com/Shikster/Market-Alert/main/Market%20Alert.user.js)

## Discord Notifications 🔔
Market-Alert can ping you on Discord when it finds matching items on the market. Here's how to set up notifications:

**1. Get Your Discord User ID**

- **Discord:** Right-click your own username anywhere in Discord (like a chat message).
- **Copy ID:** Click "Copy ID" and paste it into the "User ID" field in the Market-Alert settings window. 

**2. Set Up Your Webhook**

- **Permissions:** You'll need the "Manage Webhooks" permission in the Discord server and channel where you want notifications.
- **Go to Server:** Open your Discord server.
- **Channel Settings:**  Choose the channel for notifications, click the channel name at the top, and select "Channel Settings" (gear icon).
- **Integrations:** Select "Integrations" on the left sidebar.
- **Create Webhook:** Click "Webhooks", then click the "Create Webhook" button.
- **Copy the URL:** A unique Webhook URL will appear – copy it to your clipboard! 

**3. Connect Market-Alert**

- **Settings:** Open Market-Alert's settings window.
- **Paste Webhook URL:** Paste the copied Webhook URL into the "Discord Webhook URL" field. 
- **Paste User ID:**  Paste the User ID you copied earlier into the "User ID" field.
- **Search:** Start searching! Your ID and Webhook are saved so you do not have to type them again.

**IMPORTANT: After setting the webhook via setup. Restart your browser!**
