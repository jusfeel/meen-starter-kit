git clone --recursive ... # to clone all the submodules as well.

# SERVER(install node, mongodb and gulp globally)
mkdir server;cd server;npm install 

# CLIENT(install ember-cli globally)
cd..;cd client
npm install;bower install

# START SERVER
cd server;gulp

# START CLIENT
## on another terminal
cd client
ember s

# Build From Scratch

## under server/ install server
npm init
npm i --save-dev express morgan body-parser cookie-parser cors debug mongojs gulp gulp-nodemon gulp-watch jshint gulp-jshint gulp-livereload
vim gulpfile.js
gulp


## project root
ember new client
cd client;ember s



