# Hello360


Basic Setup Node configuration 
==
npm install 12.9.0

nvm install /*search NVM install on GitHub*/

nvm list /*Display the list of Node version installed and the one used!*/

nvm use 12.9.0 /*Facebook VR project require*/

npm create-360-cli /*Create APP*/

Native Modules
==
This package allowed me to call methods in run time!!! I need more research, In the Surface-repo I am calling 3d shapes with the help of nativeModule which is a method I created in client.js

Mobile Movement
==
Web-VR -Polyfill Github allows to use mobile motion to change the rendered orientation 


Audio Player
==
Use Audio-Module



IN APP  
==
Flexbox is very helpful for rendering components read on Bootstrap about flexbox implementation in VR, 
CSS allows to move the position of flexbox using X,Y and Z-axis


Trick 
==
test any 2D HTML page and place 
<iframe src = "https://your-VR-web-app.com" /> 
note: src could be source check!!!


Notes
==

//The Facebook APP created will have one default component and in the event of a setState the whole component is refereshed hence the output is lagging. We should use containers for each components so when a prop is setState only the target is refereshed not the whole enviornment. 
