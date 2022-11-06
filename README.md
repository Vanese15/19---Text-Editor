# 19---Text-Editor

To build this text editor, you will start with an existing application and implement methods for getting and storing data to an IndexedDB database. You will use a package called `idb`, which is a lightweight wrapper around the IndexedDB API.

WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets


Needed:
`manifest.json` file
application's IndexedDB storage:


Uses IndexedDB to create an object store and includes both GET and PUT methods

  * The application works without an internet connection
  * Automatically saves content inside the text editor when the DOM window is unfocused
  * Bundled with webpack
  * Create a service worker with workbox that Caches static assets
  * The application should use babel in order to use async / await
  * Application must have a generated `manifest.json` using the `WebpackPwaManifest` plug-in
  * Can be installed as a Progressive Web Application