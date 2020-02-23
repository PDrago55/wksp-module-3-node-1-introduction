# 3.1.2 - Module Spotlight: Express

<img src='./assets/express.png' style="min-width: 50%;" />

---

## One of the most important node modules

It removes _a lot_ of the complexity around creating and maintaining a server.

---

### Example

This will give us a barebones server that we can _GET_ content.

```js
const express = require("express");

const app = express();
const handleHello = (req, res) => {
  res.send("hello");
};
// the "/" argument says that this is the beginning of the path on a page//
// req = request, res = response

app.get("/", handleHello);
app.get ("/bacon", (req, res)) => {
  res.send("yum");
});

app.listen(4000);
```

---

_Let's create a server right now!_
// to run, in terminal, type, node index.js (whatever your js file is called);
// in browser, go to localhost.4000 ( it will print "hello")

---

Let's explore the workshop repository together.

---
