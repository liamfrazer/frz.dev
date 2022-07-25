2022-07-24 22:42
# 01 - Introduction
---

## Course Outline
* Node.js Fundamentals
* Main applications
	* File.io
	* Web Servers
	* Express.js
* Master Project
	* NASA data combined with SpaceX to build Space Launch system
	* Focus on advanced topics and build in a proffesional manor
* Authentication
* Databases
* NoSQL vs SQL
* RESTful APIs
* Deployment and CI/CD
* Production & the Cloud
* GraphQL vs REST
* Sockets
* Deno & TypeScript

## How Node is Born
* Writing instructions that a machine can understand
* JS > JavaScript Engine > Do something with those instructions

## JavaScript Runtime
*  V8 Engine
* Automatic performance boosts with V8 engine upgrades
* libuv
	* Simply a way to give a JavaScript file > JavaScript runtime > Chrome V8 > libuv (if not javascript)
	* Combination of V8 + libuv - Whenever they encounter asynronous, the libuv is used
* *console.log* isn't part of JavaScript, but part of the runtime provided by the window object within the browser
* global is used instead of window in Node.JS

* Node is a set of tools allowing us to write applications, this is read by the V8 engine, but with async features via libuv

## Getting the Most out of the Course
* Code along
* Build projects, learning and practising along the way

---
## References
[[frz.dev/docs/Runtimes/Node.js/index]]