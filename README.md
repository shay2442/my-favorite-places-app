Favorite Places
### TO get this app running clone or fork this repository

git@github.com:shay2442/my-favorite-places-app-frontent.git

### VERY IMPORTANT - you must cd into frontend before running yarn start AND you must cd into backend before running the following commands 

### Then run the following commands in the terminal 
bundle install
rails db:create
npm install --global yarn

### Make sure to migrate and seed the data, bu running
rails db:migrate
rails db:seed

### Now you are able to start the servers 
The frontend is setup to run on PORT 3000 at localhost:3000
`yarn start`

The backend is setup to run on http://localhost:3001
`rails s`

How many times have you said the phrases, "What was the name of that place we stayed?" or "I forgot what I ordered here last time, but it was really good." Now there is an app to fix that! This app is designed to provide the client or the user a place where they can save all of their favorite places that they have visited. Once they create an account, or login to their account, they will be able to see all of the favorite spots they have gone to, the address of that location, the category of the type of place (i.e. restaurant, park, museum ) a picture of the location, how expensive it was,  and some notes about what they enjoyed about it.  They will also be able to search for a place they have recently added for when they might br going back to that place and want to read what they had liked or disliked about that place in the notes, etc.  
