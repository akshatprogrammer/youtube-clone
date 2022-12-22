# youtube-clone

This is a clone of youtube made using React.js, Node.js, Express.JS, MongoDB and Firebase.
The client/frontend is hosted on Netlify and server/backend is hosted on Heroku.

# Features
1. Authentication.
2. Like/Dislike.
3. Subscribe/unsubscribe.
4. Comment.
5. upload video.
6. Similar video recommendation on the side panel, etc.

# Frontend 
1. Made uing React.js.
2. Styling is done using React Components.
3. JWT and Firebase authentication are used for authentication.
4. Redux is used for state management.

# Backend
1. Made using Node.js and Express.js.
2. Connection is established with mongoDB to store all the data.
3. Firebase storage is used to store the videos and images. Then the link of images and videos is stored in the mongoDB.

# Screenshots
![Screenshot from 2022-09-09 20-51-32](https://user-images.githubusercontent.com/62903302/189466369-0f9d3644-0f1e-404a-b44b-907ab8be079b.png)

![Screenshot from 2022-09-09 20-51-27](https://user-images.githubusercontent.com/62903302/189466356-9e161eec-efe8-4efe-aebe-f5f2fc913580.png)

![Screenshot from 2022-09-09 20-52-17](https://user-images.githubusercontent.com/62903302/189466378-701ea3f3-9b92-43cd-bede-7841aef22026.png)

![Screenshot from 2022-09-09 20-52-54](https://user-images.githubusercontent.com/62903302/189466382-da7af44c-f8b3-4f66-a338-8b06257a936d.png)

![Screenshot from 2022-09-09 20-55-05](https://user-images.githubusercontent.com/62903302/189466384-ffda46b6-dc6f-4550-bc5a-af7f65ea2dd3.png)

# Run project Locally
1. Git clone the project. (git clone)
2. cd into the client folder. (cd client)
3. install all the dependencies of the frontend. (npm install)
4. create .env file in client folder and put all your firebase keys, ids etc there.
5. now cd into the server folder. (cd server)
6. install all the dependencies of the backend. (npm install)
7. create .env file in the server folder and put mongoDB key and JWt key in it.
8. finally run server using npm start and then run client using npm start. (npm start)

