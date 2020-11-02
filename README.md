# node_web_api

Project setup
```
npm init
npm install express
npm install nodemon
```

Nodemon config
```
"nodemonConfig": {
  "restartable": "rs",
  "ignore": [
    "node_modules/**/node_modules"
  ],
  "delay": "2500",
  "env": {
    "NODE_ENV": "development",
    "PORT": 4000
  }
}
```
