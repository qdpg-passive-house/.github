## QDPG
This project uses Strapi for the backend database + api (`qdpg-api`) and a Next.js app for the frontend (`qdpg-fe`)

The backend is deployed with Heroku at this url: https://qdpg-api.herokuapp.com/

Important notes about Strapi: you can't access the content-type builder in production. Instead you have to run the app locally, add your types, and then push up your changes. So if I wanted to make a "Post" type, I would do that locally and push that up. However, if a user with the necessary role wants to write a post, that can be done in production since it's just data that will be stored in the db. So a QDPG employee won't have to worry about running anything locally. 

### Local Setup
1. run `qdpg-api` on port 1337
2. run `qdpg-fe` on port 3000

More detailed instructions for how to do this should be in the README's for the respective repos.
