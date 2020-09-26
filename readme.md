## My learnings from this project

### StoryBooks

This app uses Node.js/Express/MongoDB with Google OAuth for authentication

### Usage

Add your mongoDB URI and Google OAuth credentials to the config.env file

```
# Install dependencies
npm install

# Run in development
npm run dev

# Run in production
npm start
```
### Authentication
In modern web applications, authentication can take a variety of forms. 
Traditionally, users log in by providing a username and password. With 
the rise of social networking, single sign-on using an OAuth provider 
such as Facebook or Twitter has become a popular authentication method.


### way to create project in developer.google.console.Its a way to use 
### google as authentication system for your application.Steps involved
### are :

* create project
* select api that u want to work with
* enable that api
* select oauth and generate creds
* use keys that were generated in your project

### Authentication middleware for node
http://www.passportjs.org/docs/oauth/
Passport is authentication middleware for Node. It is designed to serve a singular purpose: authenticate requests.

### Express handlebars and its directory structure..supports convention over
### configuration
https://www.npmjs.com/package/express-handlebars

### learnt about structuring of this project