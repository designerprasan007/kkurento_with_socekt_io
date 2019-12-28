install kurento setup from https://www.kurento.org/.





1. run npm install

//after installation of npm packages move to static

cd static/  

// in static directory run command



bower install --allow-root



//after bower install come back to the main source by where you previously installed npm packages


../

node server.js 



// kurento will start to serv



// now to add the socket.io follow this steps


cd /socket-io


npm install.


node index.js

your web is ready to serve.

open the port served by the socket io so u will get both call and chat in single page.

for any clarifiction feel free to ask. :-)
