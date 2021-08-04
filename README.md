# simple-chatapp-socket

As the name, this project is a simple chat app with socket. 
**Features can be added:**
- Authentication
- Right now, chat data is stored in array, which is fine for small application. But for bigger data size, binary search should be implemented. [Behind FB messages](https://www.youtube.com/watch?v=cSNGGAKJqwk&ab_channel=FOSDEM)

## App structure:
```
├── README.md
├── client
│   ├── .netlify
│   ├── build
│   ├── public
|   ├── src 
|   ├── package-lock.json 
|   └── package.json
└── server
    ├── .gitignore
    ├── index.js
    ├── package.js
    ├── pack-lock-json
    ├── Procfile
    ├── router.js
    └── user.js
```

### Try it out at: [Simple-chat-app](https://610ac01ab7d0b1009fb2aec5--dreamy-kowalevski-3f52e5.netlify.app/chat?name=fdfd&room=fdf)

Setup:

<ul>run npm i && npm start for both client and server side to start the development server</ul>
