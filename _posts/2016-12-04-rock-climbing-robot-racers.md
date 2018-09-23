---
layout: default
modal-id: rock-climbing-robot-racers
title: Rock-climbing Robot Racers
link: https://rockclimbing-robot-racers.herokuapp.com
featured: splash.jpg
screenshots:
- screenshot.jpg
description: Race yourself or a friend up a wall of scattered letters with the keyboard.  It's "Twister" for your fingers!
order: 100

---

I wrote this entire game from scratch in vanilla javascript (except for the audio and web sockets libraries), including the inverse kinematics.  The backend is a simple node.js app with socket.io.  This is the first networked game I've made.  All of the code is open source at [https://github.com/jschomay/climbing-game](https://github.com/jschomay/climbing-game).

The idea came from thinking about how you would capture the physical experience of holding a grip while rock-climbing in a computer game, and I thought of the idea of "Twister" for your fingers, and not having to let go.  The motivation came from wondering if it would actually be fun.  Doing the IK turned out to be very challenging and a bit buggy, but I'm quite proud of how well it works.  I think the end result has proved to be very fun, and even rather addictive.
