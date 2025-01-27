# Overview

The Pipedream Slack app enables you to build event-driven workflows that interact with the Slack API. When you authorize the Pipedream app's access to your workspace, you can use [Pipedream workflows](/workflows/) to perform common Slack [actions](#workflow-actions), or [write your own code](/code/) against the Slack API.

The Pipedream Slack app is not a typical app. You don't interact with it directly as a bot, and it doesn't add custom functionality to your workspace out of the box. It makes it easier to automate anything you'd typically use the Slack API for, using Pipedream workflows. 

- Automate posting updates to your team channels
- Create a bot to answer common questions
- Integrate with your existing tools and services
- And much more!

# Getting Started

## Should I use the Slack or Slack Bot app on Pipedream?

The Slack app is the easiest and most convienent option to get started. It installs the official Pipedream bot into your Slack workspace with just a few clicks.

However, if you'd like to use your own bot registered with the [Slack API](https://api.slack.com), you can use the [Slack Bot app](https://pipedream.com/apps/slack-bot) instead.

The Slack Bot requires a bot token to allow your Pipedream workflows to authenticate as your bot. The extra set up steps allow you to list your custom bot on the Slack Marketplace, or install the bot on other workspaces as your bot's name instead of as Pipedream.

## Accounts

1. Visit [https://pipedream.com/accounts](https://pipedream.com/accounts).
2. Click on the **Click Here To Connect An App** button in the top-right.
3. Search for "Slack" among the list of apps, and select it.
4. This will open a new window asking you to allow Pipedream access to your Slack workspace. Choose the right workspace where you'd like to install the app, then click **Allow**.
5. That's it! You can now use this Slack account in any [actions](#workflow-actions), or [link it to any code step](/connected-accounts/#connecting-accounts).

## Within a workflow

1. [Create a new workflow](https://pipedream.com/new).
2. Select your trigger (HTTP, Cron, etc.).
3. Click on the **+** button below the trigger step, and search for "Slack".
4. Select the **Send a Message** action.
5. Click the **Connect Account** button near the top of the step. This will prompt you to select any existing Slack accounts you've previously authenticated with Pipedream, or you can select a **New** account. Clicking **New** opens a new window asking you to allow Pipedream access to your Slack workspace. Choose the right workspace where you'd like to install the app, then click **Allow**.
6. That's it! You can now connect to the Slack API using any of the Slack actions within a Pipedream workflow.

# Example Use Cases

- **Automated Standup Reports**: Trigger a workflow on Pipedream to collect standup updates from team members within a Slack channel at a scheduled time. The workflow can compile the updates into a formatted report and post it to a designated channel or send it via email using an app like SendGrid.

- **Customer Support Ticketing**: Use Pipedream to monitor a Slack support channel for new messages. On detecting a message, the workflow can create a ticket in a customer support platform like Zendesk or Jira. It can also format and forward critical information back to the Slack channel to keep the team updated.

- **Real-time CRM Updates**: Configure a Pipedream workflow to listen for specific trigger words in sales-related Slack channels. When mentioned, the workflow fetches corresponding data from a CRM tool like Salesforce and posts the latest deal status or customer information in the Slack conversation for quick reference.


# Troubleshooting

Please [reach out](https://pipedream.com/support/) to the Pipedream team with any technical issues or questions about the Slack integration. We're happy to help!
