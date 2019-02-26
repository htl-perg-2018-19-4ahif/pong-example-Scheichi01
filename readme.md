# Pong

![Pong](Pong.png)

## Introduction

Your job is to implement a [Pong](https://de.wikipedia.org/wiki/Pong) mobile browser game in which two distributed players can play against each other using WebSockets.

Everybody has to deliver her or his best try. You can earn up to two extra points if you deploy your working app to the web and send a link to it using a GitHub issue.

It is ok to work on this exercises in groups of up to two people. In case of teamwork, both team members must have GitHub checkins to prove their contribution to the project.

## Technical Requirements

* Use TypeScript, Node.js and [socket.io](https://socket.io/)

* Nice to have: The game should use the entire available screen and should work on mobile phones, too. Define your own rules for situations where players have different screen sizes (e.g. one uses smartphone, the other uses a desktop computer).

## Technical Tips

* [Get browser window size](https://developer.mozilla.org/en-US/docs/Web/API/Window/innerHeight)

* [Detecting window size changes](https://developer.mozilla.org/en-US/docs/Web/Events/resize)

* [Add guestures to web apps with *hammer.js*](https://hammerjs.github.io/)

* Work through the [lab about ball movement](lab-10-ball), in particular [lab-10-ball/index.ts](lab-10-ball/index.ts)

* Work through the [lab about paddle movement](lab-20-paddle), in particular [lab-20-paddle/src/client/index.ts](lab-20-paddle/src/client/index.ts)

* Work through the [lab about sending key strokes via socket.io](lab-30-socketio), in particular [lab-30-socketio/src/app.ts](lab-30-socketio/src/app.ts) and [lab-30-socketio/src/client/index.ts](lab-30-socketio/src/client/index.ts)
