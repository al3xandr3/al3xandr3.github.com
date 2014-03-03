---
layout: post
title: Product and Application Design
category: other
tags:
  - product
  - application
  - startup
intro: "How to Create a new software product"
---

## Product

### #1 Give something back to users 

Computers are made to make people's live easier, do something that makes life easier/better for end user.

Dogfood: It should solve my problem, very important that me the inventor need it also and i must be an intensive user.

Reference:
- http://paulgraham.com/startupideas.html


## Application Design

### Always consider the end user point of view

How would my main target audience use it use it? Does the UI makes sense and is obvious, could things be simplified further.

### UI: Easy and simple to use

Must be easy and get out of the way, user does not need to know internal technology details.

Good example google search box, the most useful and simple (to use) application ever ?

- If app has many commands make them search-able (example: lightTable or sublime_text find command). Use  search box instead of endless nested menus, so that users only need to have a vague idea how it was named, don't make them learn endless nested menus or shortcuts.

UI is a key thing, needs constant constant curation and re-thinking, it should enable a good workflow, should be a multiplier of the program core abilities, UI is not just a way for user to reach its core abilities, think of Ableton live UI, that even breaks with the original paradigm of the music production and mixing, when needed, and takes advantage of computer abilities to make for a better workflow.

## Program Architecture

- Backend is an independent program exposed as a service (by an API endpoint), an application is then built by using several independent services (principle of composability). Follows Server <-> client model. (example: SuperCollider, end users can use whatever language they favor to communicate in a very simple protocol to the server)
- Do simple API's (REST like?)
- The services are built independently and their implementation details are hidden (each doing 1 thing well).
- This allows to replace backends while keeping same api interfaces.
- Allows to re-use the api services for different applications, on different UI interfaces for example, and to be re-used by others.

- Interface is in javascript so that can run both on cloud, desktop and mobile devices.


## API product tutorials

An API style of product is a product made to be re-used (as all should be), and that requires  proper references on information how to use it:

- Online documentation, maybe a getting started quick doc.
- Ready made examples
- Online video training, setup, examples, walkthroughs.

## Community
Keeping in touch with the product community and maintaining an active community is key.

- Forum, to communicate bidirectionally with users and solve common FAQ's.
- Maybe a dedicated FAQ section.
- Regular news means a lively, active (& trustworthy) product.
- Youtube videos, with demos, news, walkthroughs.
- Social Media, keep a page and feed on: FB, TW, etc...

## Branding
The visuals of how the product is exposed to end users, logo, brand design, colors, styles, approach that should be always consistent recognizable and associated to the product. 
Helps to make a stronger consistent product.

## References
- [Jeff Bezos (Amazon) 25 quotes](http://www.fool.com/investing/general/2013/09/09/the-25-smartest-things-jeff-bezos-has-ever-said.aspx)
