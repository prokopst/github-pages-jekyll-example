---
title: Hello world in Node.js
layout: post
perex: Node.js and its Hello world!
---
This is pretty useless *"Hello world"* in Node.js:

```javascript
console.log("Hello World");
```

Hmm, who would actually use Node.js as a console application?
It's a *"Hello world"*, so let's talk with the world!

```javascript
var http = require('http');

var server = http.createServer(function (request, response) {
  response.writeHead(200, {"Content-Type": "text/plain"});
  response.end("Hello World\n");
});

server.listen(8000);
```
