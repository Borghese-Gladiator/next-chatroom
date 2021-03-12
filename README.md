# Next-Chatroom
Created a Next.js/Node.js SocketIO Chatroom

- Initialized chatroom projec with tutorial here: [https://dev.to/kamo/simple-react-based-chat-application-1p0](https://dev.to/kamo/simple-react-based-chat-application-1p0)
- Fixed WebSocket CORS here: [https://socket.io/docs/v3/handling-cors/](https://socket.io/docs/v3/handling-cors/)


## Deploying App
- Deployed Next.js client to Netlify
  - base directory: `/client/`
  - build command: `npm run export && npm run build`
  - publish directory: `/client/build`
  - Environment Variables:
    - set `API_URL: heroku_url`
    - set `NODE_ENV: production`
- Deployed Node.js server to Heroku