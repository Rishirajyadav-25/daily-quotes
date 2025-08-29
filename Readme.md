# n8n Daily Quote Bot

This workflow sends a random motivational quote to your email every morning at 9 AM.

## How it works
- **Schedule Trigger** runs daily at 9 AM
- **HTTP Request** fetches a quote from ZenQuotes API
- **Email node** sends the quote to your inbox

## Usage
1. Import `daily-quote-bot.json` into your n8n instance
2. Update the Email node with your SMTP or Gmail credentials
3. Activate the workflow
