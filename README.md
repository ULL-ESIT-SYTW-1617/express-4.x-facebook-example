This example demonstrates how to use [Express](http://expressjs.com/) 4.x and
[Passport](http://passportjs.org/) to authenticate users using GitHub.  Use
this example as a starting point for your own web applications.

## Instructions

To install this example on your computer, clone the repository and install
dependencies.

```bash
$ git clone git@github.com:ULL-ESIT-SYTW-1617/express-4.x-github-example.git
$ cd express-4.x-github-example
$ npm install
```

* The example uses environment variables to configure the consumer key and
consumer secret needed to access GitHub's API.  Start the server with those
variables set to the appropriate credentials.
```bash
$ CLIENT_ID=__FACEBOOK_CLIENT_ID__ CLIENT_SECRET=__FACEBOOK_CLIENT_SECRET__ node server.js
```
* Navigate to [https://github.com/settings/developers](https://github.com/settings/developers) ans press **register new application** to get the values for the `ID` and `SECRET`
* Open a web browser and navigate to [http://localhost:3000/](http://localhost:3000/)
to see the example in action.
