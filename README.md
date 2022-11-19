# 19---Text-Editor

I built a text editor that runs in the browser.  The app is a single page application developed using service workers, manifests and other features that provides users with an experience similar to using a native app. The text editor is available while users are offline using service workers.

Data is stored in the IndexedDB, a lightweight wrapper around the IndexedDB API.  Users will be able to create notes or code snippets with or without an internet connection and be able to retrieve them at some other time, while either on or offline.  The application has both a client and server folder structure.  Users can use npm run start from the root directory to start up the backend and serve the client.

When the text editor is run from the terminal, JavaScript files have been bundled using webpack.  When plugins are ran, an HTML file, service worker and manifest file are generated. Clicking on the install button, will create a desktop icon.  When the application is loaded, a registered service worker using workbox is loaded with pre cached static assets.

The heroku deploy has proper build structured scripts for webpack application.

While working on this project, I learned the importance of improving the user experience by allowing usere to use applications both on and offline.

