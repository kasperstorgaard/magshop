# MAGSHOP

### Setup

##### Prerequisites

Install global utilities:

    npm install -g bower polymer-cli@next


##### Install

Install packages

    npm install

(this will install bower packages too in a postinstall hook)

### Start the development server

    npm run serve

This will serve the app on localhost:8081

### Test the build

    npm run serve-prod

This will build the app and serve it on localhost:8081

### Deploy the shop

    npm run deploy

This will build the app and deploy it using `zeit.now`