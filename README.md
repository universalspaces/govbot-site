# GovBot — Website

This repository hosts the public-facing website for **GovBot**, a mock-government Discord bot.

Served via **GitHub Pages** at your configured domain.

## Pages

- `index.html` — Homepage with feature overview and bot invite link
- `legal.html` — Terms of Service and Privacy Policy

## Setup

1. Push this folder to a GitHub repository
2. Go to **Settings → Pages** and set the source to the `main` branch, root folder `/`
3. Your site will be live at `https://<your-username>.github.io/<repo-name>/`

## Before publishing

Update the **Add to Discord** invite link in `index.html` — replace `YOUR_CLIENT_ID` with your actual Discord Application ID:

```
https://discord.com/oauth2/authorize?client_id=YOUR_CLIENT_ID&scope=bot+applications.commands&permissions=268445760
```
