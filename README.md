# cypress.js boilerplate
Unit testing with cypress.js. This repo is a boilerplate to setup a javascript react application and use cypress to control the unit test.

* It will include a basic react app to submit and email form.
* Cypress will validate it, send the email and verify if that was success.

# Get started
* $ git clone https://github.com/minorsolis/cypress.git
* Install the Demo App:
* `cd ./app/`
* `npm install`
* Install the Cypress App
* `cd ./cypress/`
* `npm install`

# Usage
* Run the app first
* `cd ./app/`
* `npm start`
* `It will run in http://localhost:3000`
* Run the cypress app
* `cd ./cypress/`
* `npm run cypress:open`
* `It will run in http://localhost:3001`

# Result
* You will have both things running, the demo app and the cypress unit testing running. You can modify the demo_app.spec in `./cypress/cypress/integration/demo_app.spec.js`

# Finally
* It was tested with node `v16.14.0`

