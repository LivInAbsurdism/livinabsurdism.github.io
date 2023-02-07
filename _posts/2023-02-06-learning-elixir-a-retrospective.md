---
layout: post
title:	"Brief but painful lessons"
date: 2023-02-06 12:34:27 +0100
categories:
    - learning_elixir
tags:
    - elixir
---

Today was one of those days that's like rough, but fun. I'm working in Phoenix LiveView trying to display information in a repo I'm just jumping into. 

From what I've learned of Phoenix LiveView so far, it's got a lot of moving parts. There's action that you can `broadcast` and sockets that you can have listen for these broadcasts. You can then assign the data to the from the sockets to `assigns`.

Then there's `Ecto` the database adapater for Elixir. I needed to make sure I cast my `changeset` to get my changes to the database. 

I don't necessarily have a ton of time to spend in this repo so I've been trying to pick up Phoenix as quickly as I can, but there's still a lot I don't know. 

Lesson of the day: double check your arguments and parameters, every single time. It doesn't feel good when something isn't working and you spend an hour spinnning on it only to realize it was literally one argument. Don't do that. 