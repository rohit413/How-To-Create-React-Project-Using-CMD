# How To Install And Setup A React App On Windows 10
1. Install Nodejs
Node.js actually provides a runtime environment to execute JavaScript code from outside a browser. NPM, the default package manager for Nodejs is used for managing and sharing the packages for any JavaScript projects. Node.js and NPM are used by Polymer.js for the management of dependencies and runtime.

In this tutorial, we are going to install React using the Node Package Manager(NPM). So first, it needs to install Nodejs on our system. NPM will be installed with Nodejs itself.

So, the latest version of Node.js can be downloaded and installed from the official website. The URL is given below. Currently, 12.8.0 is the latest version of Nodejs.

https://nodejs.org

2. Install Create-React-App Tool
Now we need to install a tool named create-react-app using NPM as global. This tool is used to create react applications easily from our system.

npm install -g create-react-app
3. Creating a New React Project
After successful installation of create-react-app, we can create our first react application using it.

create-react-app awesome-project
Here awesome-project is the name I have chosen for my react project.

Note:-
We can also combine the steps 3 and 4 with a single command using NPX( package runner tool that comes with NPM 5.2+).

npx create-react-app awesome-project
Here NPX will temporarily install create-react-app and create a new react project named awesome-project.
4. Running the Application
The app we created can be run locally on our system.

cd awesome-project
npm start
This will opens up the react application in a new tab of our browser with the below URL.

http://localhost:3000
TechoTip: We recommend using Visual Studio code as the source-code editor for working with React projects.
