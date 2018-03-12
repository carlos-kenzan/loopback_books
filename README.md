# loopback books API

This guide will walk you through the process of creating a simple REST API using [Loopback](http://loopback.io/).

### What you'll Build

At the end of this guide you will be have a working REST API where you can perform CRUD operations on a `Book` and `Author` endpoints.

### What you'll Need
 * A text editor
    * [VSCode](https://code.visualstudio.com/download) - free
    * [Webstorm](https://www.jetbrains.com/webstorm/) - Paid / Free trial
    * [Komodo](https://www.activestate.com/komodo-ide) - Paid / Free trial
 * Basic knowledge
    * Javascript
      * [JS Tutorial](http://www.learn-js.org/)
      * Books to read
        * [Eloquent Javascript](http://eloquentjavascript.net/)
        * [You don't know JS](https://github.com/getify/You-Dont-Know-JS) Series
    * NodeJS
      * [NodeJS Training](https://nodeschool.io/#workshoppers)
      * [Node Event Loop](https://www.youtube.com/watch?v=8aGhZQkoFbQ)
      * Basics of [ExpressJS](https://expressjs.com/en/starter/installing.html)
 * [NodeJS & NPM](https://nodejs.org/en/download/) installed in your machine (Node v6.x or greater, npm v4.x or greater).

### How to complete this guide

This guide is a composed of a collection of git branches that will guide you though the steps
on how to gradually build a REST API using Loopback. Most branches will build on top of the previous one.

To start, check out the desired branch (example: `git checkout routing`). See [branches](#BranchingStructure) section
for available branches. In branches that require some kind of setup there will be a commit named `setup` that showcases the required
build up for that feature.
