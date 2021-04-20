# Youtube Sync App

A simple web application which syncs youtube video playback between two computers. 


Stack
-----

- Youtube Player API
- React.js
- Node.js
- Websockets


How to Run
------------

1. Start the node.js app, run: (Making sure you have npm installed)

'''
$ cd backend/ && npm start
'''

2. Start the react app
'''
$ cd frontend/ && npm start
'''

Overview
------------
`youtube-sync-app` consists of a client and a server application, which makes it possible to synchronize youtube video playback between two computers. This means that when a user pauses or plays a video, it will do the same for other viewers as well.
The frontend is built using React.  It uses WebSockets to communicate to the backend (Node.js). Websockets allow user actions to be easily broadcast to other users. 

Depoyment
------------

*Prerequisites: basic knowledge of [Heroku](https://www.heroku.com/).*

**Setup your Heroku account and Heroku CLI**

For installing the CLI tool, see [this article](https://devcenter.heroku.com/articles/heroku-command-line).

**1. Create the Heroku app**

```
heroku apps:create youtube-sync-app
```

**2. Push to Heroku**

```
git push heroku master
```

Heroku will give you a link at which to view your live app.
