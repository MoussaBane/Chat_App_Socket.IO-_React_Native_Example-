# A chat app with Socket.io and React Native

We will create a sign in screen where you can enter your name, create groups where people can join and show real-time messages between the people in the group.

# Some necessary terms to know

* Socket.io: is a popular JavaScript library that allows us to create real-time, bi-directional communication between software applications and a Node.js server.

* Expo: is an open-source framework that enables us to create native apps for IOS and Android by writing React and JavaScript code. Expo saves us from the complex 
  configurations required to create a native application with React Native CLI, making it the easiest and fastest way to build and publish React Native apps.

* Express.js: is a fast, minimalist framework that provides several features for building web applications in Node.js.

* CORS: is a Node.js package that allows communication between different domains.

* Nodemon: is a Node.js tool that automatically restarts the server after detecting file changes, and Socket.io allows us to configure a real-time connection on the     server.

* Async Storage: is a React Native package used to store string data in native applications. It is similar to the local storage on the web and can be used to store       tokens and 
  various data in string format.

* React Navigation: allows us to navigate from one screen to another within a React Native application.
  
  # Install Socket.io Client API to the React Native app

   cd app
   
   expo install socket.io-client

  # Install React Navigation and its dependencies

   npm install @react-navigation/native
   
   npx expo install react-native-screens react-native-safe-area-context
   
  # Setting up the Socket.io Node.js server

   * Navigate into the server folder and create a package.json file: 
   
     cd server & npm init -y

  # Install Express.js, CORS, Nodemon, and Socket.io Server API

    npm install express cors nodemon socket.io

  # Install Async Storage

    expo install @react-native-async-storage/async-storage
  
  
  
# Steps for installation

1. Clone the project
2. Navigate into the app folder: cd app
3. Run: yarn install
4. Navigate into the server folder: cd server
5. Run: npm install
6. Then start the server using: npm start
6. Within the app "to start the app via an IOS Emulator." run: expo start --ios 










