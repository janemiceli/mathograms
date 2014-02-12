Math-o-grams by Desmos
======================

This is a little project by the folks at desmos.com to:
* show the world how easy it is to use the Desmos API
* let the math nerds and math nerd lovers send adorable valentine's day cards

Try it out live at http://mathogram.desmos.com

Quick Start Guide
-------

1. Install node (visit www.nodejs.org)
2. Clone this repo and navigate to the root of it
3. Install dependencies by typing: `npm install`
4. Run the app by typing: `node app.js`
5. Visit http://localhost:5000 from your browser

Using Mandrill Locally
--------------

To get the full experience, including the ability to e-mail math-o-grams, you'll need to:

1. get a key from the fine folks at Mandrill (www.mandrill.com).
2. rename config.example.js to config.js, and enter the key in there

Deploying
---------

To deploy, you'll need to get an account set up with heroku and follow their instructions here: https://devcenter.heroku.com/articles/getting-started-with-nodejs

In order to enable Mandrill, use the key from above, and set it as an environment variable by typing:
```
heroku config:set MANDRILL_KEY=[your key]
```

Making Your own Desmos Apps
---------
Head over to https://www.desmos.com/api to see our API docs. If you'd like your own key (required for any public-facing app), send us an e-mail at partnerships@desmos.com. 

We can't wait to see what you build with the Desmos API!
