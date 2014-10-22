---
layout: default
title: Hammerspoon
---

# Hammerspoon

## What is Hammerspoon?

This is a tool for powerful automation of OS X. At its core, Hammerspoon is just a bridge between the operating system and a Lua scripting engine.
What gives Hammerspoon its power is a set of extensions that expose specific pieces of system functionality, to the user.

## How do I install it?

Grab the latest release from [here](https://github.com/Hammerspoon/hammerspoon/releases/latest) and then drag the application to `/Applications/`.

## How do I use it?

Hammerspoon is controlled by the config you write in `~/.hammerspoon/init.lua`. You can place any Lua script you like in there, using the APIs that Hammerspoon provides. A full API reference can be found [here](http://hammerspoon.org/docs).

If you need a reference for the Lua scripting language, see [lua.org](http://www.lua.org/docs.html).

## How can I contribute?

More extensions will always be a huge benefit to Hammerspoon. They can either be pure Lua scripts that offer useful helper functions, or you can write Objective-C extensions to expose new areas of system functionality to users. For more information, see [the contribution guidelines on GitHub](https://github.com/Hammerspoon/hammerspoon/blob/master/CONTRIBUTING.md).

## Where can I get help?

You can usually get a quick answer in #hammerspoon on Freenode.

You can also file an issue on the [issue tracker](https://github.com/Hammerspoon/hammerspoon/issues).