# Webhook Request Blocker

A simple webhook request blocker that protects against loggers using `dcwh.my`, `stealer.to`, and other webhook protectors

## Features
- Blocks webhook requests to `dcwh.my`, `stealer.to`, and standard Discord webhooks (`api/webhooks/`).
- Logs blocked requests (URL, body, headers) to the console.
- Copies blocked request details to clipboard (toggleable).
- Compatible with Roblox exploit environments.

## Global Variables
- Set `getgenv().G_PrankWebhook = true` to enable pranks (default).
- Set `getgenv().G_PrankWebhook = false` to disable pranks and only block requests.
- Set `getgenv().G_CopyToClipboard = true` to copy blocked request details to your clipboard (default is false).
