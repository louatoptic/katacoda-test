# Installing the Optic CLI

Start by installing the Optic CLI, a sample API ([`json-server` by typicode](https://github.com/typicode/json-server)) and grabbing a cup of coffee:

`npm install -g @useoptic/cli json-server`{{execute "HOST1"}}

Then, give the json-server a quick check. Run the server and try to view the `/posts` route:

`json-server --watch db.json --port 34444 --host 0.0.0.0`{{execute "HOST1"}}

You should see the a landing page for JSON Server on the Dashboard tab. You may have to ask Katacoda nicely to show it on port 34444 by clicking a button.
