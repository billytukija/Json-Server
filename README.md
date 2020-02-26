# Json-Server

1. Install JSON Server

npm install -g json-server

2. Create a db.json file

i.e :

{
  "posts": [
    { "id": 1, "title": "Come and See", "author": "Billy Tukija" }
  ],
  "comments": [
    { "id": 1, "body": "Follow some nutrition advice", "postId": 1 }
  ],
  "profile": { "name": "typicode" }
}

3. Start JSON Server

json-server --watch db.json and go to http://localhost:3000/posts/1

