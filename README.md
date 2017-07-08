# videochat-peerjs-example

A videochat implementation using PeerJS with Node.js

# How to use

Open a terminal and switch to the `videochat-peerjs-example/server` directory and install dependencies executing:

```batch
npm install
```

Then switch to the `videochat-peerjs-example/public` directory and install dependencies executing:

```batch
npm install
```

Once the dependencies were installed, start with the terminal the website server by switching to the `videochat-peerjs-example/public` directory and executing:

```batch
node website-server.js
```

Let that terminal open and open a new one. Switch to the `videochat-peerjs-example/server` directory and start the PeerJS server executing:

```batch
node peer-server.js
```

Open your browser and access the addres: [title](https://localhost:8443) and have fun. For more information, please visit the article of this [example here in Our Code World](http://ourcodeworld.com/articles/read/496/how-to-create-a-videochat-with-webrtc-using-peerjs-and-node-js)

# Important

Don't forget to change the host address [at the line 16](https://github.com/ourcodeworld/videochat-peerjs-example/blob/master/public/source/js/script.js#L16) in `videochat-peerjs-example/public/source/js/scripts.js` according to yours.
