# [11-Friend-Finder - *Deployed to Heroku*](https://potatofinder.herokuapp.com/)

## A VERY rudimentary 'dating' app.

'Friend Finder' is a demo app utilizing Node.js, Express and deployed to Heroku.

## How To Use:

1. Click **Start Survey**

2. Enter your ***Name*** and an *image URL*, then:

3. Answer all **10** questions and hit submit

4. A modal will appear with the *'person'* that your answers matched best with.

## How Does it Work?

- Through Node.js, Express creates a web server via server.js and listens to incoming HTTP requests, routing them according to rules in our router file.

- Then via the survey page, user submitted answers are compared to our friends object, via friends.js and apiRoutes.html.

- The result with the least overall score variance from our friends object is returned as the greatest likely match for the user's input.

## Video Demo

![How To Use GIF](https://github.com/CapraRoyale/11-Friend-Finder/blob/master/app/public/assets/vid/howToUse.gif)


