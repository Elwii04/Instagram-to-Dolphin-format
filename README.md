# Instagram-to-Dolphin-format
A python script that takes exported instagram chats in .json format, merges them and converts them into the cognitivecomputation dolphin training format for llm finetuning.

# Telegram-chat-to-Dolphin-finetuning-format-converter
A python script that takes exported telegram chats in .json format, merges them and converts them into the cognitivecomputation dolphin training format for llm finetuning.

How to use:

1. Download your Instagram data from your account using the official Instagram site
2. Run the code and choose the your inbox folder at ...zip\your_instagram_activity\messages\inbox
3. Enter a system prompt to use e.g. "You are a helpful robot"


Currently not working: The script currently also checks for "Hat mit ❤️ auf deine Nachricht  reagiert" and skips that. If you also want to use this feature, change the string according to your language.
It also filters out chats where there are 3 or less messages sent.
