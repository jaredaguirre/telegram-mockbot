# telegram-mockbot
This is my first proyect to test the main functioning of a telegram api bot. This example just gets information from telegrm chat as input, and replies according the used command. I have two commands implemented right now, "/name" that simply replies with the name of user who called the command, and "/dice" which returns a random number from 1 to 6. The auth token form telegram was removed from this git for security purposes.

The pom.xml file contains the necessary dependencies to work on a maven environment.

## The Procfile

Procfile is just a necessary file for running the proyect on the Heroku Cloud. The file just describes the command that the Heroku container should run when starting the application.

## Error i'm getting:
```
agujared@38f9d3a7605b:~/Desktop/telegram-bot$ heroku local web
7:01:48 AM web.1 |  Error: Unable to initialize main class domain.Main
7:01:48 AM web.1 |  Caused by: java.lang.NoClassDefFoundError: org/telegram/telegrambots/meta/exceptions/TelegramApiException
[DONE] Killing all processes with signal  SIGINT
7:01:48 AM web.1 Exited with exit code null
```
