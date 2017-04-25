# WebSockets

## What are WebSockets? Why use them?

WebSockets provide a persistent connection between a client and server that both parties can use to start sending data at any time.

After making an intial HTTP request, the client makes a WS request, which remains open so that data can be pushed in either direction.

The advantage here is that you can send data in either direction without having to include an entire HTTP request every time. No head and cookies because those can start adding up if you're sending a lot of requests back and forth. 

WebSockets are a great tool for any app that needs realtime data, such as a chat or a stock ticker.

## Code Demo with DevTools

Open `index.html` in this repo, then open Chrome DevTools and navigate to the Network tab. 

![screenshot of demo with devtools](https://github.com/njarin/websockets/blob/master/ws_screenshot1.png)
![screenshot of demo with devtools](https://github.com/njarin/websockets/blob/master/ws_screenshot2.png)

## WebSockets and Rails

* [Chatty](https://action-cable-example.herokuapp.com/)

## Resources
* [A Introduction to WebSockets](http://blog.teamtreehouse.com/an-introduction-to-websockets)
* [Real-Time Rails](https://blog.heroku.com/real_time_rails_implementing_websockets_in_rails_5_with_action_cable)
* [Socket.IO](https://github.com/socketio/socket.io)
* [Can I Use WebSockets?](http://caniuse.com/#feat=websockets)
