# Run Daily Lighthouse report and post in Slack

Run a daily Lighthouse report and share scores.

Example:
Lighthouse Report for https://www.foo.com on 08/21/2024

- Performance: 100
- Accessibility: 100
- Best Practices: 100
- SEO: 100

## Getting Started

1. Create a Slack app and webhook URL ([docs](https://api.slack.com/messaging/webhooks)).
2. Create a `SLACK_WEBHOOK_URL` Github secret  and add the webhook URL.
3. Create a `LIGHTHOUSE_URL` Github secret and add the URL you want run Lighthouse on.