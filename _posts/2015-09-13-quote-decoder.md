---
layout: default
modal-id: quote-decoder
title: Quote Decoder
link: https://quote-owl-fb.herokuapp.com/
featured: splash.jpg
screenshots:
- screenshot1.jpg
- screenshot2.jpg
- screenshot3.jpg
- screenshot4.jpg
- mobile1.jpg
- mobile2.jpg
- mobile3.jpg
- mobile4.jpg
description: A challenging word puzzle game somewhere between Hangman and Sudoku.
order: 300

---

I had the idea for this game after thinking about how players discover secret key combos to do special moves, like in old-school fighting games.  I realized that process could be turned into a puzzle game, but I had no idea if it would be fun or not. 

I had to finish 90% of the game (and cut and paste random quotes with my eyes closed for testing) to see if it was any fun at all.  Happily, it turned out to be very fun, despite being quite challenging.  Some players don't "get" it, but the ones who do find it extremely addicting, which makes me proud!

I wrote the entire game from scratch in coffeescript using a functional programming style with [ramda.js](http://ramdajs.com/), and designed a pure, reactive state machine as the central engine.

This is one of the first games where I added music (by Jamison Rivera).  I think the music pulls the whole game together and I thoroughly enjoyed working with the composer.

This is also one of the first games where I integrated with the Facebook api to socialize parts of the game.  I launched the game both on [Facebook](https://www.facebook.com/games/quote-decoder/) and [Kongregate](http://www.kongregate.com/games/juggle_monkey/quote-owl-a-hidden-message-game), though it hasn't performed particularly well on either platform.  Nevertheless, this is still one of my favorite games that I have made.
