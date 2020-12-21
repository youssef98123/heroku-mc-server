# heroku-mc-server

I'll be going over what each file and folder does lol

.ngrok2: contains the token to run ngrok
logs: minecraft server file
node_modules: modules for node.js
world: mc world file
banned-ips.json: mc server file
banned-players.json: mc server file
composer.json: required for heroku to run php
eula.txt: mc server file
fetchworld.js: a js script I wrote to fetch world.zip from postgreSQL 
home.html: a website to bind to $PORT so the processes won't crash
index.php: required for the html to work
main.py: the script that runs all the processes
ops.json: mc server file
package.json: required to run node.js
package-lock.json: required to run node.js
pom.xml: required for heroku to run java 
Procfile: runs the main.py
requirements.txt: required for heroku to run python
savetodb.js: saves the current world.zip file to postgreSQL as bytea
server.jar: mc server.jar
server.properties: mc server file
setup.js: run this when setting up the server (creates a table and uploads world.zip)
usercache.json: mc server file
whitelist.js: mc server file
world.zip: world folder zipped (to be uploaded to postgreSQL)
