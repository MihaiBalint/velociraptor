Velociraptor: node backend for the cycle-o-maniacs apps
=======================================================
[![GitHub version](https://badge.fury.io/gh/MihaiBalint%2Fvelociraptor.png)](http://badge.fury.io/gh/MihaiBalint%2Fvelociraptor) [![Dependency Status](https://david-dm.org/MihaiBalint/velociraptor.png)](https://david-dm.org/MihaiBalint/velociraptor) [![devDependency Status](https://david-dm.org/MihaiBalint/velociraptor/dev-status.png)](https://david-dm.org/MihaiBalint/velociraptor#info=devDependencies) [![Code Climate](https://codeclimate.com/github/MihaiBalint/velociraptor.png)](https://codeclimate.com/github/MihaiBalint/velociraptor) 
[![Build Status](https://secure.travis-ci.org/MihaiBalint/velociraptor.png?branch=master)](https://travis-ci.org/MihaiBalint/velociraptor) 
[![Coverage](https://codeclimate.com/github/MihaiBalint/velociraptor/coverage.png)](https://codeclimate.com/github/MihaiBalint/velociraptor) 
[![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/) 

<blockquote>
Implements persistence and stuff for the cycle-o-maniacs HackTM project. Based on the CleverStack Node backend Seed.
</blockquote>

## Some Highlights
* NodeJS Async Non-Blocking Core.
* Modular Coding Structure based on NPM.
* Grunt powered tasks, including Server with Live Restart using nodemon.
* Uses PostgreSQL..
* Official ORM (Object Relational Mapper) Module provides an enterprise SQL based solution out of the box.
* Clustered application with high Concurrency out of the box.
* NodeJS Background Tasks Module which allows CPU intensive (blocking) operations to take place in separate processes, allowing your HTTP Web Server Processes to continue serving HTTP Requests.
* Unit & E2E (Integration) Testing with Mocha and Request.

## Documentation

[Directory structure](http://cleverstack.io/documentation/backend/#directory-structure)

## Install

First install [node.js v7.10.0](http://nodejs.org), or even better: install [nvm](https://github.com/creationix/nvm) and then install node using nvm.

1. `$ npm install -g https://github.com/MihaiBalint/velociraptor`
2. `$ clever test`
3. `$ clever serve`
4. Go to: `http://localhost:8080`. Your express server runs on port `8080` by default.

## License

MIT
