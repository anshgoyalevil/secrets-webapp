# secrets-webapp

This is a very advanced web app made with Node.JS and Express.JS at the Backend, and HTML, CSS with Bootstrap & EJS at the frontend.
It uses the insane power of NoSQL based MongoDB to store data.

# Usage of the Application:
Its basically a web app where the user can share a secret anonymously with the rest of the world. But before doing that, the user needs to signup/signin using their email, or use google authentication. They can read the secrets shared by other users as well. But everyone is anonymous on the frontend of the platform, but the web application company (The developer handling the database) can see the secrets of the user linked to their email address.

In addition to the languages, the following libraries and modules are used:

# Modules Used:
- dotenv: For seperating the secrets and keys from the app.js file.
- express: For backend processing
- body-parser: For parsing the data recieved from the post requests in the forms.
- mongoose: For working with the MongoDB easily.
- express-session: For using the session handler, for express framework.
- passport: For working with the user authentication can encryption methods.
- passport-local-mongoose: For plugging the passport module to mongoose to handle the sending and recieving of data from the mongoDB.
- passport-google-oauth20: For using passport strategy of google authentication.
- mongoose-findorcreate: A helper module for a mongoose find and create methdod.

The app is made with perfect authentication system in mind. It includes Login/Signup pages and their behing the scene logic. It also contains the session and cookie handling logic with logout system, and the most awaited google authentication system.

Here's some screenshots of the web app.

![Homepage](https://github.com/anshgoyalevil/secrets-webapp/blob/master/Screenshots/homepage.PNG)
![Login Page](https://github.com/anshgoyalevil/secrets-webapp/blob/master/Screenshots/login_page.PNG)
![Register Page](https://github.com/anshgoyalevil/secrets-webapp/blob/master/Screenshots/register_page.PNG)
![Secrets Page](https://github.com/anshgoyalevil/secrets-webapp/blob/master/Screenshots/secrets_page.PNG)
![Submit a Secret Page](https://github.com/anshgoyalevil/secrets-webapp/blob/master/Screenshots/submit_a_secret_page.PNG)

Give it a try, fork it, play it, break it, keep learning..
