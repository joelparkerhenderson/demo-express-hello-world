# Demo Express hello world

This demo shows how to create a simple app using [Express](http://expressjs.com/), which is a web framework for Node.js


## Start

Use the Express starter instructions: http://expressjs.com/en/starter/installing.html

Make an app:

```sh
$ mkdir myapp
$ cd myapp
```

Initialize:

```sh
$ npm init
This utility will walk you through creating a package.json file.
It only covers the most common items, and tries to guess sensible defaults.

See `npm help json` for definitive documentation on these fields
and exactly what they do.

Use `npm install <pkg>` afterwards to install a package and
save it as a dependency in the package.json file.

Press ^C at any time to quit.
package name: (myapp)
version: (1.0.0)
description: demo description
entry point: (index.js) app.js
test command:
git repository:
keywords: demo keywords
author: Joel Parker Henderson (joel@joelparkerhenderson.com)
license: (ISC)
About to write to /Users/joel/git/joelparkerhenderson/demo_express_hello_world/myapp/package.json:

{
  "name": "myapp",
  "version": "1.0.0",
  "description": "demo description",
  "main": "app.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [
    "demo",
    "keywords"
  ],
  "author": "Joel Parker Henderson (joel@joelparkerhenderson.com)",
  "license": "ISC"
}


Is this OK? (yes)
```

Install Express:

```sh
npm install express
```


## Run

Run the app file:

```sh
$ node app.js
Example app listening on port 3000!
```

Browse http://localhost:3000/

You see "Hello World!"


## Git

```sh
git init
echo "/node_modules" > .gitignore
git add --all
git commit "Start"
```
