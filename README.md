# Discord-Bot-Project
This bot keeps your server safe, fun, and welcoming. It greets new members, deletes bad words, and manages the Developer role with ease. Enjoy commands like !hello, !poll, and !dm. Plus, Developers get a secret command! Simple, friendly, and reliable — the perfect server companion.

To use your Discord bot safely, you first need to get an API key (called a bot token) from the Discord Developer Portal
. After creating your application and adding a bot, you’ll find the token under the Bot section. Copy it carefully but never share it publicly. Instead of pasting it directly into your code, create a file named .env in your project folder and add your token there like: DISCORD_TOKEN="your_api_key_here". In your Python script, you can load this with dotenv and os.getenv("DISCORD_TOKEN"), which keeps your token private and prevents it from leaking when sharing or uploading your code.
