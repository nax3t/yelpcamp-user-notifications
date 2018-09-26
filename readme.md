# Download and run instructions

`git clone https://github.com/nax3t/yelpcamp-user-notifications.git`

`cd yelpcamp-user-notifications`

`npm install`

Start mongodb (in its own terminal tab)

`cd ./mongod`

Run the app (in its own terminal tab)

`node app.js`

Test it out:

- Create two users.
- Log in with the first user and create a campground.
- Log in with the second user and go to that campground
- Click the author's name to go to his/her profile
- Click Follow <author name> button
- Logout and log back in with original user
- Create another campground
- Log back in with second user and see the notification
