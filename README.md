# secrets-webapp

This is a very advanced web app made with Node.JS and Express.JS at the Backend, and HTML, CSS with Bootstrap & EJS at the frontend.
It uses the insane power of NoSQL based MongoDB to store data.

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

<img scr="https://github.com/anshgoyalevil/secrets-webapp/blob/master/Screenshots/homepage.PNG"></img>

Give it a try, fork it, play it, break it, keep learning..!
