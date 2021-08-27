# Welcome to John's Tall Tales
Here's how to get the project running like a real guy

###1. Install things
Install node.js and npm. (node is basically a server running JavaScript and npm is a package manager) https://nodejs.org/en/download/

Now, install `http-server` from npm.
```shell
npm install -g http-server
```
If your command line complains at you because permissions or something, you have to pull rank on it and remind it who's really in charge here
```shell
sudo npm install -g http-server
```

### 2. Hit the on button
```shell
http-server
```
This will start your web pages running at `localhost:8080`.
