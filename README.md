- for linux/mac
  "watch": "nodemon db --ignore frontend-js --ignore public/ & webpack --watch"
- for windows
  "watch": "start nodemon db --ignore frontend-js --ignore public/ && start webpack --watch"
  "For start Mongodb connection: create your mongouri url from mongodb and paste it in .env file"
And then run command - npm run watch
