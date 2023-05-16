# Social Network Web Application API

This is an API for a social network web application where users can share their thoughts, react to their friends' thoughts, and create a friends list. The API uses Express.js for routing, a MongoDB database, Mongoose for data modeling, and the native JavaScript Date object to format timestamps. The seed data is created using Insomnia.

# Installation

Clone the repository.

```sh

git clone https://github.com/your_username/social-network-api.git


Install NPM packages.
npm install

Start the server.
npm start
```

# Thoughts

```sh
GET /api/thoughts - Get all thoughts
GET /api/thoughts/:thoughtId - Get a single thought by id
POST /api/thoughts - Create a new thought
PUT /api/thoughts/:thoughtId - Update a thought by id
DELETE /api/thoughts/:thoughtId - Delete a thought by id Reactions
POST /api/thoughts/:thoughtId/reactions - Create a reaction to a thought
DELETE /api/thoughts/:thoughtId/reactions/:reactionId - Delete a reaction to a thought Friends
GET /api/users - Get all users
GET /api/users/:userId - Get a single user by id
POST /api/users - Create a new user
PUT /api/users/:userId - Update a user by id
DELETE /api/users/:userId - Delete a user by id
POST /api/users/:userId/friends/:friendId - Add a friend to a user's friend list
DELETE /api/users/:userId/friends/:friendId - Remove a friend from a user's friend list
Timestamps
All timestamps are formatted using the native JavaScript Date object in ISO 8601 format.
```

# Contributing

Contributions are always welcome! Please open an issue or pull request for any changes.

# License

This project is licensed under the MIT License.
