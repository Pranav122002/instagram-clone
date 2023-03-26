# Instagram Clone with Messenger

A Instagram Clone with Messenger implemented using React, Nodejs, Express and MongoDB.

## See live demo at :
https://mern-instagram.vercel.app/

## Functionalities this Instagram clone has :

- Signin, Signup, Forgot password and Logout
- User can reset password if he forgets his password
- Reset password link is sent in email
- Users can't access pages without logging in
- Messaging with other users
- Like, unlike, and comment on posts
- View the users who liked the post
- Delete the comment
- Create and delete the post
- View your profile and number of followers and following and your posts
- View other users profile
- Follow and unfollow users
- View posts shared by all users in home feed
- View posts shared by users which you follow, in my following feed
- Edit and upload the profile photo
- Delete your account
- Search users by their email or name
- Responsive website

## Installation & Running

Clone the project:

```
git clone https://github.com/Pranav122002/Instagram-Clone-with-Messenger.git
```

Install dependencies for backend:

```
cd .\Instagram-Clone-with-Messenger\
npm install
```

Install dependencies for frontend:

```
cd .\Instagram-Clone-with-Messenger\frontend\
npm install
```

Create dev.js in config folder and add your MONGOURI and JWT_SECRET in the format:

```
module.exports = {
    MONGOURI: "mongodb://localhost:27017/instagram-clone-with-messenger",
    JWT_SECRET: <your jwt secret>
};

```

Start the project:

```
npm start
```

Go to:

```
http://localhost:5000/
```

### Note:

If you do any changes in frontend code, then run this command:

```
cd .\Instagram-Clone-with-Messenger\frontend\
npm run build
```

## Tech Stack :

- HTML
- CSS
- Javascript
- React
- Socket.IO
- Nodejs
- Express
- MongoDB

## Demo images

To view more demo images go to images folder of this repo
