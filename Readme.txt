----Deliverables of LiveTweet Stream--------

Backend - node.js
Frontend - react.js

Facts:
->This setup uses concurrently for process management. 
Executing npm start instructs concurrently to boot both the Webpack dev server and the API server.

->Inside Client.js, I used Fetch function to make a request to the Twitter API - return fetch(`/api/tweets?q=${query}`,

-> As This Application comprises of Live Stream Twitter API, I haven't used any kind of datastore.

->Used Reflux Library which follows MVC like pattern and adopts a single data flow.

-> Action-based Scripting files:
fetchTrends
fetchTweets
fetchMoreTweets

-> To Store Temp Data
TweetsStore

--------Future Enhancements----------

-After successful implementation at localhost, 
I'm planning to deploy it on Docker Container or Heroku.

