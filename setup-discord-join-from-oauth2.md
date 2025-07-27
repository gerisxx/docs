---
icon: coffin
---

# Setup Discord Join from OAuth2

#### Step 1: Create a New Discord Application

1. Visit the [Discord Developer Portal](https://discord.com/developers/applications).
2. Click on New Application.
3. Provide a name for your bot and click Create.

<figure><img src=".gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

#### Step 2: Configure OAuth2

1. Navigate to the **OAuth2** section of your application.
2. Copy the **Client ID** and **Client Secret**.
3.  Create a Redirect URI with the following link:

    **https://api.authguard.org/session/discord/callback**

#### Step 3: Obtain the Bot Token

1. Go to the Bot section of your application.
2. Copy the Bot Token.

#### Step 4: Configure API Settings on AuthGuard

1. Discord URL: Paste the Discord invite URL for your server. You can find this in your Discord Developer Portal under your application settings (in the OAuth2 section).
2. Discord Client ID: Enter the Client ID you copied from the OAuth2 section of your Discord Developer Portal.
3. Discord Client Secret: Paste the Client Secret from the OAuth2 section.
4. Discord Bot Token: Enter the Bot Token you obtained earlier from the Bot section of your Discord Developer Portal.

<figure><img src=".gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

***

This will guide users through the necessary steps to configure their Discord application for integration with AuthGuard.

