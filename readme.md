# Browser push notifications in Node.js

This repo contains the example code from a blog post on the Knock blog about [sending browser push notifications in Node.js](https://knock.app/blog/how-to-send-browser-push-notifications-from-nodejs). You can find additonal details in that post.

This demo app uses Express and [Node Push Notifications](https://www.npmjs.com/package/node-pushnotifications) to send browser push notifications without an external service.

You will need to generate your own set of [VAPID key](https://vapidkeys.com/) to send push notifications.

## Getting started

You can clone this repository with the following command:

```bash
git clone https://github.com/JEverhart383/knock-browser-push-demo.git
```

and then install the dependencies with `npm install`. From there, update your VAPID keys in `server.js` and `main.js` with value you created from the website above. Finally, you can start your server with `server.js` and navigate to `http://locahost:3000`.
