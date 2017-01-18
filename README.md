![Logo](./resources/Text_Logo_Grey.png)

# Code Our Challenge

This challenge will test your knowledge of Javascript mainly as well as Git, Node, Express, React Native and MongoDB. If you are unfamiliar with any of these technologies, don't panic. There are lots of straight forward tutorials and videos out there to help you get on your way partner!

<br>
#### These are just some of the resources you may want to read

- http://brew.sh/ Recommended package install manager
- https://nodejs.org/en/ Official Node.js docs
- http://expressjs.com/ Official Express Library docs
- https://zellwk.com/blog/crud-express-mongodb/ code a node express server from scratch and demon it!
- https://www.tutorialspoint.com/nodejs/nodejs_express_framework.htm explaining the parts of a node express server
- https://expressjs.com/en/starter/generator.html create and configure a node express server in a few seconds!
- https://docs.mongodb.com/manual/tutorial/install-mongodb-on-os-x/
- https://github.com/Automattic/mongoose
- https://blog.xervo.io/getting-started-with-mongoose


#### Before beginning, make sure you have installed the following
```
- Homebrew
- Node v6.2.1 (NPM v3.9.3)
- MongoDB 3.4.0
- XCode 8.2.1

To manage Node versions: https://github.com/creationix/nvm
```
<br>
## Lets begin!

<br>

- First make a clone of this repo locally on your machine and create a seperate branched named your name.

<br>

- Next create an express application server using the generator. 
>See - https://expressjs.com/en/starter/generator.html

<br>

- Test your application, `cd express_folder` now run `npm install` to install all the dependiences then `npm start` to start the server on port 3000.
You should now be able to see the index page if you go to http://localhost:3000/

<br>

- Next create two additional GET routes in routes/index.js,
'/users' route
'/places' route
and one POST route
'/sent'

Restart the server when you make any changes

<br>

- Next `npm install mongoose --save` to use mongoose. 
>Follow the instructions for Mongoose to connect a database - https://blog.xervo.io/mongodb-tutorial

<br>

- Next create a sample set of data for both `/users` and `/places` so when you hit either one of those endpoints, data is returned from the MongoDB database.

A User model should include first name, last name, age, city
A Place model should include name, city, address, type, rating
- include atleast 15 data points for each User and Place collections

<br>

- Now with a solid backend structure containing some user and place data we should create a simple react-native iOS project. 
>See - https://facebook.github.io/react-native/docs/getting-started.html#content

Follow the steps setting up your environment, CLI tools and initialising a project `react-native init Project_Name`

Test your iOS app works through the iPhone simulator `react-native run-ios` cmd.

<br>

- Next create two buttons on the index screen of your iOS app, one for users and another for places. When you click a button it should take you to a new screen which listviews the data from our back-end. 

>See resources
- https://facebook.github.io/react-native/docs/touchableopacity.html
- https://facebook.github.io/react-native/docs/navigator.html 
- https://medium.com/react-native-training/react-native-navigator-navigating-like-a-pro-in-react-native-3cb1b6dc1e30#.71eyfswzj 
- https://facebook.github.io/react-native/docs/using-a-listview.html 
- https://facebook.github.io/react-native/docs/network.html 
- https://www.youtube.com/watch?v=r5OPRhelEIU

<br>

- And a button labeled Send which you guessed it, when pressed sends arbituary data to the /sent post route on our server.

<br>

- *** BONUS *** Create a folder named 'app' in your react-native project root directory, inside 'app' folder create another folder called 'Screens'. Create a UsersScreen.js and PlacesScreen.js inside 'Screens' and export your screen components there. Import them back in inside index.ios.js.  

<br>

#### When you have got this far, commit all changes and push your own branch up to GitHub.

![Penguin](./resources/penguin.jpg)

#### We look forward to your submission 
### & 
## Good Luck from the Kompas Family!

Email: team@kompasapp.com
Website: https://www.kompasapp.com

![Color_Strip](./resources/ColourStrip.jpg)