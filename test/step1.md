# Installing the Optic CLI

Start by installing the Optic CLI, a sample API ([`json-server` by typicode](https://github.com/typicode/json-server)) and grabbing a cup of coffee:

`npm install -g @useoptic/cli json-server`{{execute "HOST1"}}

Then, give the json-server a quick check. Run the server and try to view the `/posts` route:

`json-server --watch /app/db.json --listen http://localhost:3001`{{execute "HOST1"}}
