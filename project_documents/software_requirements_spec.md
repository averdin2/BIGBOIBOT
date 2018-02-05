# SOFTWARE REQUIREMENTS SPECIFICATION
## 5.1 INTRODUCTION
This Software Requirements Specification (SRS) documents the requirements for the BIGBOIBOT Discord bot. BIGBOIBOT is a multipurpose bot for the social media platform known as Discord. Our focus will be to enhance the Discord user experience with extra functionality that is not natively available with Discord. Some of the functionality that BIGBOIBOT will provide will include interaction with outward facing APIs, word translations, channel management, music players, and more, providing users countless new ways to interact with other users in an online chatroom environment. BIGBOIBOT will be written mostly if not purely in JavaScript and thus will require our knowledge of the language (and node.js) to do so. We are looking forward to hosting it on a third-party server to ensure it runs 24/7.
## 5.2 FUNCTIONAL REQUIREMENTS
## 5.3 PERFORMANCE REQUIREMENTS
  - 5.4.1 Once the user has the website hosting our bot open, adding the bot either through our own website or Discord's website should take no longer than 5 seconds.
  - 5.4.2 Once the user has added the bot, the bot should show up in the selected channel in less than 1 second (pretty much immediately).
  - 5.4.3 Once the user has added the bot, a (direct) welcome message will be sent to the user who added the bot with the website link and a short tutorial on how to use the bot.
  - 5.4.4 Executing commands should take around 1 to 10 seconds, depending on the complexity of the command
     - 5.4.4.1 Muting/unmuting, deafening/undeafening, kicking, and banning a user in the server should take less than 1 second to execute.
     - 5.4.4.2 Inviting a user to the server should take less than 1 second to execute
     - 5.4.4.3 Changing one or another user's nickname should take less than 1 second to execute
     - 5.4.4.4 Changing one or another user's role should take less than 1 second to execute
     - 5.4.4.5 Calling on any API and getting the result back should take up most up to 1 second.
     - 5.4.4.6 Kicking the bot should take less than 1 second to execute.
       - 5.4.4.3.1 Verification of kicking the bot should take less than 1 second to execute.

## 5.4 ENVIRONMENT REQUIREMENTS

### 5.5.1	Development Environment Requirements
Hardware Requirements

| Category | Requirement |
|---|---|
| CPU | 2 x 1,6 GHz  |
| Graphics Card | Intel(R) HD Graphics 4600 |
| Ram | 8 GB |

Software Requirements

| Category | Requirement |
|---|---|
| Front End | Node.js |
| Server | Discord/Heroku |


## 5.4.2 EXECUTION ENVIRONMENT REQUIREMENTS

| Category | Requirement |
|---|---|
| Operating System | Windows 10 / Mac OSX / Linux / iOS / Android |
