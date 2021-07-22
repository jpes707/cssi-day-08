# cssi-day-08

JavaScript + Firebase secret messages website

## Configuration

* `npm install -g firebase-tools`
* `firebase login`
* `firebase init`
    * Which Firebase CLI features do you want to set up for this folder? `Database, Hosting, Emulators`
    * Project Setup: `Use an existing project (to-do-list)`
    * Initialize RTDB? `Yes`
    * What file should be used for Realtime Database Security Rules? `Default`
    * What do you want to use as your public directory? `Default`
    * Configure as a single-page app (rewrite all urls to /index.html)? `No`
    * Set up automatic builds and deploys with GitHub? `No`
    * Which Firebase emulators do you want to set up? `Hosting`
    * Use default ports for emulators? `Yes`
* `firebase emulators:start --only hosting`
