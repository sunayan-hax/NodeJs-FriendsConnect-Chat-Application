FriendsConnect Chat Application ( NodeJS Based Chat Application )
=================================================================

This is a node.js chat application powered by SocketJS and Express that provides the main functions you'd expect from a chat, such as emojis, private messages, an admin system, etc.


- Type `/help` to get a list of the available chat commands

---
## ScreenShot Preview
![ScreenShot Preview](https://www.dl.dropboxusercontent.com/s/poz9pavk34p8v1r/chat-1.png?dl=0)

![ScreenShot Preview](https://www.dl.dropboxusercontent.com/s/d0q7n7wlzge3qo5/chat-2.png?dl=0)

![ScreenShot Preview](https://www.dl.dropboxusercontent.com/s/d0q7n7wlzge3qo5/chat-2.png?dl=0)

![ScreenShot Preview](https://www.dl.dropboxusercontent.com/s/e1df6xeownkw6li/chat-4.png?dl=0)

## Features
- Material Design
- Emoji support
- User @mentioning
- Private messaging
- Message deleting (for admins)
- Ability to kick/ban users (for admins)
- See other user's IPs (for admins)
- Other awesome features yet to be implemented

## Video Demo
-Link: https://www.youtube.com/watch?v=VnIZ3DGdjiM

####There are 3 admin levels:
- **Helper:** Can delete chat messages
- **Moderator:** The above plus the ability to kick and ban users
- **Administrator:** All the above plus send global alerts and promote/demote users

---

## Setup
Clone this repo to your desktop and run `npm install` to install all the dependencies.

You might want to look into `config.json` to make change the port you want to use and set up a SSL certificate.

---

## Usage
After you clone this repo to your desktop, go to its root directory and run `npm install` to install its dependencies.

Once the dependencies are installed, you can run  `npm start` to start the application. You will then be able to access it at localhost:3000

To give yourself administrator permissions on the chat, you will have to type `/role [your-name]` in the app console.
