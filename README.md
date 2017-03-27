![Logo](./resources/Text_Logo_Grey.png)

# Code Our Challenge - Create a server and react native ios app

This challenge will test your knowledge of Javascript mainly as well as Git, Node, Express, React Native and MongoDB. If you are unfamiliar with any of these technologies, don't panic. There are lots of straight forward tutorials and videos out there to help you out.

<br>

## These are just some of the resources you may want to read

- http://brew.sh/ Recommended package install manager
- https://nodejs.org/en/ Official Node.js docs
- http://expressjs.com/ Official Express Library docs
- https://zellwk.com/blog/crud-express-mongodb/ code a node express server from scratch and demon it!
- https://www.tutorialspoint.com/nodejs/nodejs_express_framework.htm explaining the parts of a node express server
- https://expressjs.com/en/starter/generator.html create and configure a node express server in a few seconds!
- https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/
- https://github.com/Automattic/mongoose
- https://blog.xervo.io/getting-started-with-mongoose
- https://www.npmjs.com/package/node-mongo-seeds

<br>

## Before beginning, make sure you have installed the following
```
- Homebrew
- Node v6.2.1 (NPM v3.9.3)
- MongoDB 3.4.0
- XCode 8.2.1

To manage Node versions: https://github.com/creationix/nvm
```

<br>

## You will be assessed on: 
- Well writting and organised code with commenting
- DRY code
- Visuals and Designs
- Completion of the challenge

<br>

# Lets begin!

## Back-End

- First make a clone of this repo, cd into it.

- Next create an express application server using the generator. 
```
https://expressjs.com/en/starter/generator.html
```

- Test your application, `cd express_folder` now run `npm install` to install all the dependiences then `npm start` to start the server on port 3000.
You should now be able to see the index page if you go to `http://localhost:3000/`

- Next create four endpoints in `routes/index.js`
```
GET '/users' route
GET '/places' route

POST '/users' route
POST '/places' route
```

note: Restart the server when you make any changes

<br>

- Next install and follow the instructions for Mongoose to connect a database to the server
```
https://blog.xervo.io/mongodb-tutorial
```

- Now seed our mongo database with some data, install globally `https://www.npmjs.com/package/node-mongo-seeds`

```
Seed some data into two collections (use Models below)

User: {
  first_name: String,
  last_name: String,
  dob: Date,
  email: String,
  username: String,
  password: String,
  gender: String
}

Place: {
  name: String,
  address: String,
  city: String,
  category: String,
  rating: Number,
  opening_times: String,
  latitude: Number,
  longitude: Number,
  image: String
}

```

## Front-End
Recommend watching [this tutorial](https://www.youtube.com/watch?v=r5OPRhelEIU) for the next part.

- Now create a simple react-native iOS project.
```
https://facebook.github.io/react-native/docs/getting-started.html#content

Make sure you can see the Welcome Message in the iOS Simulator
```

- Next create two buttons on the index screen of your iOS app, one for `users` and another for `places`.
```
https://facebook.github.io/react-native/docs/touchableopacity.html
```

- Add navigation to the app, Create two modules one for `users` and another `places`.

```
https://facebook.github.io/react-native/docs/navigator.html 
https://medium.com/react-native-training/react-native-navigator-navigating-like-a-pro-in-react-native-3cb1b6dc1e30#.71eyfswzj 
```

- Add a listview component for the two newly created screens, so now when you click users from index.ios.js it takes you to a new screen which displays in a listview all users in our mongoDB.
```
https://facebook.github.io/react-native/docs/using-a-listview.html 
https://facebook.github.io/react-native/docs/network.html
```

- Now Back to the home screen where you created two buttons, create another button which take you to a new screen with a form.

- The form page should include all information required to add a user.

- Create a submit button which saves a new user to the database we connected earlier.

- Test this works and that you can view the newly added user in the `user` Listview screen.

- Add commits, push to branch, create pull request to merge branch to master, send us the github repo link.

- *** BONUS *** Secure API Endpoints and add User Authentication using Passport.js
http://passportjs.org/

# Done!

![Penguin](./resources/penguin.jpg)

#### We look forward to your submission 
### & 
## Good Luck from the Kompas Family!

Email: team@kompasapp.com
Website: https://www.kompasapp.com

![Color_Strip](./resources/ColourStrip.jpg)