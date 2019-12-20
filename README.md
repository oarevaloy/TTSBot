# TTSBot

Dockerized Telegram Text to Speech bot

It receives the string ```/tts <sentence>``` then it sends an audio to the user

Available as @ArevaloBot in Telegram

To replicate this bot, follow these instructions:

* Clone this repository
* [Create your own bot](https://core.telegram.org/bots#3-how-do-i-create-a-bot) talking with [@BotFather](https://telegram.me/BotFather)
* Edit config/auth.py file with the token provided by BotFather
* Run ```docker build -t ttsbot:local .```
* Then ```docker run -d ttsbot:local```

TODO: Support to choose language
