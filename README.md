# Documentation

## What is Express?

Express is a fast minimalist web framework for Node.js.

## Why use Express?

Used for both server rendered apps as well as API/ Microservices
Extremely light, fast and free
The most popular Node.js framework
Great to use with client side frameworks as it is all Javascript

## Basic Server Syntax

```
const express = require('express');

// Init server
const app = express();

// Create endpoints/routes
app.get('/', (req, res) => {
    res.send('Hello World!');
});

const PORT = process.env.PORT || 5000;

// Listen the server
app.listen(PORT, () => {console.log(`Server is running on PORT: ${PORT}`)});
```

### Credits

All notes were taken from Traversy Media's youtube channel. https://www.youtube.com/channel/UC29ju8bIPH5as8OGnQzwJyA
