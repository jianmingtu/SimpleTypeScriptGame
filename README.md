# Snake Food 
by Jianming Tu
## Description
This is a web app for a snake to find and eat food. Press any keys to start; use left, right, up, or down key to move the snake to eat food.

## Tech Stack
    TypeScript, Webpack, Less CSS

## Github
   https://github.com/jianmingtu/SimpleTypeScriptGame


## Run local
```
created - tsconfig.json
created - webpack.config.js
updated - package.json 
         ("dev": "webpack serve --open chrome.exe",)
> npm run dev
```
http://localhost:8080/
    

## Run on Heroku
```
created - tsconfig.json
created - webpack.prod.js
updated - package.json
updated - package.json 
         ( "start": "node server.js",
           "heroku-postbuild": "webpack --config webpack.prod.js")
1) manually deploy
heroku login
heroku create
git add .
git commit -am "make it better"
git push heroku master
heroku logs --app=agile-fjord-98845 --tail
2) continuous integrate with github
git remote add origin https://github.com/jianmingtu/SimpleTypeScriptGame.git
git branch -M main
git push -u origin main
on heroku, connect the heroku agile-fjord-98845 instance to the github 

```
    
https://simpletypescriptgame.herokuapp.com/

[Deploy A Web App To Heroku](https://dev.to/ellehallal/how-to-deploy-a-web-app-to-heroku-2f4l)
    



