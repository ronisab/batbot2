# Telegram Bot with OpenAI Integration

This Telegram Bot is built with Python and the TeleBot and OpenAI libraries. It allows users to generate responses to messages sent in Telegram groups or private chats using OpenAI's text generation API.

## Demo
[@GPTReplyBot](https://t.me/GPTReplyBot)

## Tools Used
1. [Telebot](https://github.com/eternnoir/pyTelegramBotAPI) - A Python wrapper for the Telegram Bot API
2. [OpenAI API](https://beta.openai.com/docs/api-reference) - OpenAI's language generation API

## Deployment
1. Clone the repository to your local machine: 
$`git clone https://github.com/dhir4j/chatgpt-bot-telegram.git`

2. Install the required packages: 
$`pip install -r requirements.txt`

3. Replace the [OpenAI API key](https://beta.openai.com/account/api-keys) and [Telegram Bot Token](https://telegram.me/BotFather) in the code with your own.

4. Run the program: 
$`python main.py`

## Usage
1. gpt - chatGPT answer, give a query after the command
2. reply - use it as reply to a message, you can extend the query after the command
3. dan - chatGPT unleashed, give a query after the command
4. karen - AI character: I'm Karen; demanding, arrogant, and unapologetically myself
5. rdan - use dan to reply
6. rkaren - use karen to reply
7. bug - use it to find bugs in the code snippets
8. roasthim - same as reply but for roasting
9. gpta - chatGPT answer in mp3
10. tl - use it as reply or provide text to translate it into English
11. tts - use it as reply to convert text to speech
12. help - to view this command manual
## To-Do

- [x] Add /rdan (reply dan)
- [x] Add /rkaren (reply karen)
- [ ] Optimize reply (check for telegram commands in prompt, if found remove it from array)

## License

[MIT](https://choosealicense.com/licenses/mit/)
