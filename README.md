# rock-paper-scissors-server

## Deploy to Heroku Issue
Q: I get the error "Babel not found" while deploying to heroku.

A: It's because heroku doesn't automatically install dev-dependencies for npm, you need to set config variable NPM_CONFIG_PRODUCTION in heroku to false and it will work :)
ref: https://github.com/developit/express-es6-rest-api/issues/36
