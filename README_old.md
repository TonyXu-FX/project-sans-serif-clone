# CSCC09 Project Proposal
## Project Title
InstaChat

## Team Members
Chuan Peng Xu - 1005305714

Wentao Ge - 1005186781

Su Tong Kong - 1004304790

## The Web Application
A messaging application similar to something like Discord or Facebook Messenger

## Key Features
- Users can signup, signin, and log out

  - Users have a profile which can be customized (e.g. profile pic)

- Users can direct message each other

  - Files and images can be sent too

- Users can create group chats (GCs) and invite others

  - Users who join the GC can send and view messages/images/files in the gc

  - Users can leave GCs
  
  - GC owner can change the name/picture of the GC and delete it

- Users can delete their messages

- Users can join a GC via a link

## Additional Features

- Video/Voice calls and sending video/voice messages

- Password reset

- Third-party authentication (things like Google, Facebook, Twitter sign in)

## Technology Stack

- MERNG (MongoDB, Express.js, React.js, Node.js, GraphQL)

- Frontend:

  - React

    - Useful frameworks/libraries
    
      - e.g. React Bootstrap (for UI), React Router (for routing)

- Backend:
  
  - Node.js

    - ExpressJS, GraphQL for the server

    - MongoDB as the database

    - Firebase for OAuth

    - Other useful frameworks/libraries
    
      - e.g. mongoose (for MongoDB), express-validator (for security), multer (for files and images) etc.

- Typescript

- Deployment: Undecided

  - Will wait until the lecture on deployment

## 5 Technical Challenges

- How to manage real-time messaging between people

  - The method shown in labs is, presumably, not the ideal method

- How to manage real-time video/voice calls

  - Not sure if this will be similar to real-time messaging since it is a continuous stream of data

- If video/voice messages implemented, how to store and transmit them

- Ensuring proper security (e.g. not allowing people outside a group chat to access it)

- Learning new technologies such as Typescript, GraphQL, and Firebase

  - As well as refamiliarizing ourselves with ones like React
