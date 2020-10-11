## Setup
`git clone https://github.com/pratimakandel/EESCAlumniDatabaseCPSC_430.git`

`cd EESCAlumniDatabaseCPSC_430`

`echo "mongodb+srv://<username>:<password>@cluster0.na9dw.mongodb.net/<dbname>?retryWrites=true&w=majority" > .env`

`npm install`

`npm app.js`

## After Changes
`git add .`

`git commit -m`

`git push origin master`

`heroku push heroku master`
