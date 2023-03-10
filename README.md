# Caching in a Node.js application using Redis
Implemented caching in a Node.js application using Redis as the caching mechanism. Redis is an in-memory data store that can be used to cache frequently accessed data and improve application performance. In Node.js, we can use the Redis client library to connect to a Redis instance and store and retrieve data from the cache. By caching data in Redis, I can reduce the number of requests made to your database, resulting in faster response times and better scalability. My project will involve writing code to connect to a Redis instance, perform CRUD operations on the cache, and integrate caching into your Node.js application.

---

## Requirements

For development, you will only need Node.js, redis and a node global package, installed in your environment.

### Node
- #### Node installation on Windows

  Just go on [official Node.js website](https://nodejs.org/) and download the installer.
Also, be sure to have `git` available in your PATH, `npm` might need it (You can find git [here](https://git-scm.com/)).

- #### Node installation on Ubuntu
  You can install nodejs and npm easily with apt install, just run the following commands.

      $ sudo apt install nodejs
      $ sudo apt install npm
      
If the installation was successful, you should be able to run the following command.

    $ node --version
    v16.17.1
    
    $ npm --version
    8.15.0

---

## Install

    $ git clone https://github.com/ritulsingh/cache-using-redis.git
    $ cd cache-using-redis
    $ npm install

## Run the project

    $ npm run dev
    Go to "http://localhost:3000"


