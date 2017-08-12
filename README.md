# Making an NES RPG in Love
An ongoing tutorial of how to make an NES-Era RPG in Love

This is an attempt to remedy a problem I saw for training game developers. New game developers are often tasked with creating some very basic game types to learn their craft and their engine. These include games like:

* Breakout
* Pong
* Tetris
* Pac-Man
* Super Mario Bros.

While these games do teach programming concepts used in RPGs, they're not RPGs. So this tutorial will describe how to make a certain kind of RPG, namely, a game like the first Dragon Quest/Dragon Warrior (henceforth DQ) game for the Nintendo Entertainment System.

# Why this kind of game?

RPGs cover a broad spectrum of game types. Depending on who you ask, the boundaries of what an RPG are will vary. My reasons for choosing DQ are that it's the simplest kind of RPG you can create from this era while keeping all the classical elements. DQ is a classic RPG without action elements (unlike Zelda) or deep tactical elements (unlike Fire Emblem). These and other elements can be added later, but like the programming examples above I believe DQ boils console RPGs down to their essence.

# Why the NES?

Simplicity. RPGs have gotten more and more complex over time, just like all the other game types above have. Thus, we need to look back in time to find a good example. Note, however, that this is not an attempt to faithfully replicate the look-and-feel of an NES RPG. I will be using some of the restrictions but only as an aim to keep the RPG from getting too crazy.

# Why Love?

Love2D is a 2D engine for the Lua language. Lua is used in many scripting languages found in modern games and it is quite easy to pick up. I use Linux, so some Lua-based SDKs are out for me and, frankly, I like writing in Love2D. That said, you can take the principles out of this guide and likely apply them to other engines. You'll just have to transfer them out of Love's way of doing things.

# What will you need?

Right now you'll need an installation of Love and some form of editor. Love can be found at http://www.love2d.org. Ideally, you should be able to complete the Hello, World example for Love and be able to try a few of the other tutorials. Lua itself can be learned at http://www.lua.org/start.html or from many other tutorials online.
