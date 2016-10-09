git clone --recursive ... # to clone all the submodules as well.

# Server (install node, mongodb and gulp globally)
cd server  
npm install   

# Client (install ember-cli globally)
cd client  
npm install  
bower install  

# Start Server (localhost:3000)
cd server  
gulp  

# Start Client
## On another terminal
cd client    
ember s  

visit http://localhost:4200

# Build From Scratch
(ember part reference) https://ivanheral.github.io/tutorial/2016/06/10/app-ember-mongo.html  
(server part reference) http://thejackalofjavascript.com/mean-stack-hands-on-tutorial/  

## Under server/ install server
npm init  
npm i --save-dev express morgan body-parser cookie-parser cors debug mongojs gulp gulp-nodemon gulp-watch jshint gulp-jshint gulp-livereload  
vim gulpfile.js  
gulp  

## Under project root
ember new client    
cd client  
ember s  

## Initial Ember Config
pods, bootstrap-4, sass, JSONSerializer

