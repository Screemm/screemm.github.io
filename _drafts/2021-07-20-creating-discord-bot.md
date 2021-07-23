---
layout: post
title: Creating a Discord bot
tags: discord tutorials
---

When making a Discord bot, you'll need to create an application, a bot within the application and copy the bot's token to your bot's config file. Below, I'll walk you through how to create a bot user in your application.

## Creating your application

First, you'll want to head to Discord's [developer portal](https://discord.com/developers/applications) and login. If you don't have a Discord account, you'll need to register for one in this window.

Once you're logged in, you'll find yourself on the "Applocations" page. Create an application by clicking "New Application" in the top right corner, enter a name for your project and click "Create".

SCREENSHOTS HERE

TA-DA! You've now create your application and are taken to it's "General Information" page.

SCREENSHOT HERE

## Creating your bot

Now, we want to create your bot. On the left panel, click "Bot" and the "Add Bot" button. A popup will ask if you're sure you want to create a bot, as it's irreversible, so go ahead and click "Yes, do it!".

SCREENSHOTS HERE

HOORAY! You now have a bot that you can now join to Discord servers!

## Finding your bot's token

From here, your bot's token is very easy to find. On your bot page, next to the bot's avatar, you'll see "Token" with a "Copy" button and a "Regenerate" button. There will also be a "Click to Reveal Token" hyperlink, but we won't be needing to use that.

Click the "Copy" button and copy that straight into your bot's config file.

**NOTE:** If, at any time, you need to regenerate your bot's token (if it's accidentally leaked), you'll need to replace the token within your bot's config file after getting a new token.

SCREENSHOT HERE

## Joining your bot to a Discord server

So now we've done the bulk of the work and want to test our bot on a Discord server, but there's no official Discord documentation, at the time of writing this guide. Now what?

Head on over to [this guide](#) and we'll take you through that process.
