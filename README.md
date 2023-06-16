Progressive-Web-Applications-Web-Editor 

The task was to build a text editor that runs in the browser. The app is a single-page application that meets the PWA criteria. Additionally, it features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. This application will also function offline.

To build this text editor, I started with an existing application and implement methods for getting and storing data to an IndexedDB database. I used a package called `idb`, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.

This app also uses the Cache API to store static assets, and the Service Worker API to intercept network requests and serve cached assets instead. This allows the app to function offline.

It also uses the Web App Manifest API to provide metadata about the app, which allows it to be installed on a user's device.

In addition to the above, this app uses the File System Access API to allow users to save their work to their local file system.

This app uses the following technologies: HTML, CSS, JavaScript, Node.js, Express.js, IndexedDB, Cache API, Service Worker API, Web App Manifest API, and File System Access API. All of these technologies are used to build a Progressive Web Application (PWA). A PWA is a web application that uses modern web technologies to provide a native app-like experience to users. This includes the ability to install the app on a user's device, and the ability to function offline.

Webpack is used to bundle the JavaScript files, and Babel is used to transpile the JavaScript from ES6 to ES5. This allows the app to be compatible with older browsers. 

The app is deployed to Heroku. 

I copied this app from the main (finished) folder in the challenge for modiule 19.



