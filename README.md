# Chat App
Just a simple local chat app written in React and Golang

## Showcase
![Preview](https://raw.githubusercontent.com/sethpoly/chat-app/main/imgs/chat-app.PNG) 

## Quick Start
1. Clone the repository locally `https://github.com/sethpoly/chat-app.git`
2. Spin up the backend server via Dockerfile
   1. `cd \backend\`
   2. `docker build -t backend .`
   3. `docker run -it -p 8080:8080 backend`
3. Serve the frontend files
   1. `cd ..\frontend\`
   2. `npm start`
4. Navigate to **http://localhost:3000/** and starting chatting!

## Technologies
- React
- Golang
- Websocket integration (gorilla/websocket)
- Docker

