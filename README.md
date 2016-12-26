# GEL5 - Native HTML Runtime
HTML runtime for GEL5, the 5th generation version of GEL (Game Engine Library).

Also see https://github.com/povrazor/gel5-sdl2 for the native C/C++ runtime (using Chromium's V8 JavaScript interpreter).

# About GEL
GEL began XX years ago as a general purpose library of elements used for creating games. From rendering, to collision detection, to physics, to UI and audio playback. Much later, a spinoff library gelHTML was made for experimenting with HTML5 projects (https://github.com/povrazor/gelhtml-2011). GEL is also closely related to Quack, an engine and library that exposes 2D and 3D game making primitives via the Squirrel programming language (similar to JavaScript).

Prior GEL versions are tied to commercial games and contain code protected by NDA's, so it tends not to be readily available.

GEL5 is an attempt to unify some of the bold ideas of GEL and the GEL related projects over the years. GEL5 games are written in JavaScript, with an emphasis on modern Ecmascript language features. It's also open source now, because why not?

# Why JavaScript?
Thanks to the internet, the world effectively now has 2 distinct low level targets: Assembly and JavaScript. JavaScript isn't a perfect language, but does offer a lot of nice things. The ability to hardcode complex data structures like JSON natively in the language, as well as functions, gives the language a lot of power. Rather than having to break-up complex data across multiple files, they cane be unified in a single file. This is super-convenient for hacking things together.

# Why compile JavaScript?
Compiling is optional during development, but it does greatly improve compatibility. Raw native GEL5 code is designed to run in the Chrome Web Browser. But to support a wider variety of browsers (Firefox, Edge, Safari), and to create a tighter more compact binary, we compile

# Setting up a GEL5 project
TODO: this

It's like DairyBox (Vagrant, Scotchbox), but it also includes the full GEL5 library too.

Two URLs of interest, one for RAW, one for compiled.
