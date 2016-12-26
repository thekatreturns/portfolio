---
layout: default
modal-id: haskellmind
title: Haskellmind
link: http://haskellmind.herokuapp.com/
featured: splash.jpg
description: See if the computer can guess your secret code

---

My friend wrote a Mastermind scorer and solver in Haskell, and I worked with him to create a frontend for the game in Elm with some fancy CSS.

The backend uses a "hill-climbing" algorithm, and can guess any code in 7 or less guesses, and detect discrepancies in the player's scoring.  The code is on [github](https://github.com/maorleger/mastermind).
