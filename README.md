**Simple login with mongoDB and express js**

Languages:
- HTML
- CSS
- JAVASCRIPT

Tools:
- EXPRESS JS
- MONGODB


Site link: https://thendoshane.github.io/project-root/frontend/

NB:
The login will not function as we cannot directly connect to MongoDB from the client-side (browser) due to security risks and CORS restrictions. 
I am working on a backend server that the frontend can communicate with but i havent decided which to with between (Heroku or Render) after that i will make the frontend hosted with github pages make API calls to the backend.

The connection string is disconnected for you to use the code:

1. Set up mongodb
2. Create a cluster
3. Database ad collection
4. document with (_id, fname, lname, email, password)

You can edit the .env to include your connection string (found under your mongo)
edit the server.js to connect to the correct database and collection
