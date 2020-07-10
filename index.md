## About Me
My name is Josh Malek, and I am a Computer Science major at Rensselaer Polytechnic Institute. I will be graduating in the Spring of 2021 with a concentration in AI & Data, and a minor in Psychology.  I am a member of the Society of Hispanic Professional Engineers, and passionate in spreading the love of technology in younger generations.  I am currently looking to start my career after I graduate, with a Masters planned in the future.  I love learning, and I want to continue after I complete my studies at RPI.  In my free time, I love gaming (personal favorites include Overwatch and CS:GO), and I am a member of RPI's competing collegiate Overwatch team.  

For my professional career, I love working with new and exciting technologies, and developing for the future.  I am currently looking for employment to start after I graduate, so feel free to contact me!  I am excited for what the future holds, and hope I can play a part in creating it.

[My Resume](/pdf/MalekJoshResume.pdf)

## Projects

### [Donatio](https://github.com/joshmalek/donatio)
A suite of products all created under the Donatio moniker, this project was built as part of the AWS Buildathon 2020 in partnership with [Abdul-Muiz Yusuff](https://github.com/sacrael). Donatio is a gamefied platform designed to piggyback on top of current online shopping pages. A user can choose to donate a percentage of their online purchase (e.g. Amazon) to the Nonprofit of the Day. Our solution uses Amazon Pay for the donation, and the user recieves experience and medals for their donation. They can share their donations on Twitter, and compete with their friends on the Leaderboard. The project consists of four subprojects, consisting the backend, a Chrome extension, a Mobile app built in Flutter & Dart, and a full website.  I have broken down the details of each subproject below.

#### [Backend](https://github.com/joshmalek/donatio)
The main core of our platform, providing API query access through GraphQL, and a database built in MongoDB Atlas.

#### [Mobile App](https://github.com/joshmalek/donatio-app)
The mobile side of our platform is built with Flutter, allowing for easy exports to both iOS and Android from one codebase. 

#### [Chrome Extension](https://github.com/joshmalek/donatio-extension)
The Chrome extension allows our users to directly hook into their Amazon checkout page, and use the Amazon Pay credentials they already have to donate easily.

#### [Website](https://github.com/joshmalek/donatio-site)
The website routes all the external traffic from our Chrome extension, as well as providing a place for new users to check out our product, and see how it works.

----

### [cookbook.js](https://github.com/joshmalek/cookbook)

The idea for this project was to make a platform where a user could easily save recipes to a graphic board, and add their own recipes to the board.  The site is currently using the Edamam API, allowing for recipe search by keyword.  The platform is built with React.js, with a backend and user authentication being currently developed.

----

### [Discord Server Relay](https://github.com/joshmalek/discord-relay)

This project was designed as a template for a basic server relay.  A server relay operates by having a normal Discord account in private server, which has a script running to scrape all channel activity.  One bot account is created for each channel one would want to relay, and easily be extended to however many bot accounts are required.  The unique feature of this program is that it needs only one account in the private server, and is undetectable.  The program was built with node.js, and uses the discord.js package.

----

### [Steam Trade Bot](https://github.com/joshmalek/Steam-Trade-Bot)

This bot was built for the Steam network to trade virtual currency (CS:GO skins) autonomously and generate real-dollar profit.  Bot will automatically accept all trade requests made from admin account.  If the amount offered by customer is greater than the amount to trade away, trade is accepted.  If a donation is made to bot account, trade is accepted.  Bot will deny all other trade requests.  This guarantees (ignoring market shift) a stable profit over time.  The system was built with node.js and uses a suite of Steam packages in npm.
