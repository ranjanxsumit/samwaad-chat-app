# Samwaad-chat-app

Samwaad-chat-app is a real-time chat application based on socket.io for communication between multiple clients.

Technology
Frontend: JavaScript, React, HTML
CSS: React's styled-components


Backend: Node.js, Express.js, Axios


Database: NoSQL (MongoDB)



![Samwaad](https://github.com/user-attachments/assets/4fae32cb-f372-49d4-8b95-e678ecc7a216)



Installation Guide
Requirements
Nodejs
Mongodb
Both should be installed and make sure mongodb is running.

Installation
First Method
git clone https://github.com/ranjanxsumit/samwaad-chat-app/tree/main
cd samwaad-chat-app
Now rename env files from .env.example to .env

cd public
mv .env.example .env
cd ..
cd server
mv .env.example .env
cd ..
Now install the dependencies

cd server
yarn
cd ..
cd public
yarn
We are almost done, Now just start the development server.

For Frontend.

cd public
yarn start
For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.

cd server
yarn start
Done! Now open localhost:3000 in your browser.

Second Method
This method requires docker and docker-compose to be installed in your system.
Make sure you are in the root of your project and run the following command.
docker compose build --no-cache
after the build is complete run the containers using the following command

docker compose up
now open localhost:3000 in your browser.
