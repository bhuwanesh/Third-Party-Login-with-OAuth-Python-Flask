# Third-Party-Login-with-OAuth

OAuth is really powerful, using Python Flask-Oauthlib and its various clients, changed our user model, so that a password is no longer required.
Sending the user to GitHub alongside some of user's details and which redirected back to the application with an access token.
The access token is used to retrieve a bunch of information about user such as, their repositories, contributions, organisations, etc.
After, once the user had logged in, application creates a user model for user
and save it in the database without a password, which saves the password details for future login.


