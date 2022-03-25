# Practice Task 1 Louis Durand

This is my submission of Practice task 1

I created an application that has a authentification, login, upload, notebook and chatbot options. You can create your identifiers through the `/signup` route, then login with the `/auth` route. All users are saved in the MongoDB database named *practice* and the collection named *users*.
You can then upload your images in the `/upload` route and then get auto redirected to `uploaded` route where you can see your image. If this one gets deleted and you refresh the page, you'll get redirected to `/upload` route.
I also developped a notebook at `/notebook` where a user can create notebooks that are saved in the *notebooks* collection in MongoDb, the user can delete them also. The only thing I didn't implement was the display by number of chosen notebooks.
There is also a chatbot at the `/chatbot` route, which responds basicaly to messages sent by the user. It will greet you back if you say Hello, Good morning, Hiya, etc... And will respond to your questions


- [x] Create a flask app which connects to MongoDB and runs at ‘http://localhost:8080’
- [x] Authentication
- [x] Implement image upload feature
- [x] Implement notebook at ‘/notebook’
- [x] Implement chat bot at ‘/chatbot’

## Prerequisites

Running MongoDB on localhost:8080 with created database `practice` and collections `users`, `notebooks`, `chats`

## Run

`python app.py`
or 
`flask run`
