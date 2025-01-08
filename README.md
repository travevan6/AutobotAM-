
# Automated Affiliate Marketing Bot

This bot automates content creation and affiliate marketing workflows. You can deploy it easily using Render.

## Features
- Generate AI-powered content using OpenAI.
- Health-check endpoint for monitoring.

## Deployment

1. Click the **Deploy to Render** button below.
2. Add your OpenAI API key as an environment variable.
3. Start using the bot!

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)

## Environment Variables

- `OPENAI_API_KEY`: Your OpenAI API key.

## Usage

### Generate Content
Send a POST request to `/generate` with a JSON payload:
```json
{
  "prompt": "Write an engaging blog post about affiliate marketing."
}
```
