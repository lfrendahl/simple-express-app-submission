#Disc Golf Score Keeper

heroku git:remote -a name-of-app

git add .
git commit -m "ready for heroku"
git push heroku master

//Create a Procfile to give Heroku instructions on how to run your app
touch Procfile
    web: node index.js

index.js  
    var PORT = process.env.PORT || 5000;

git push heroku master
