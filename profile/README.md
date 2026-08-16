# Holder - Your knowledge belongs to you. Now you got to organise it.

Looking for Holder itself rather than the source code?

**Visit the Holder website for downloads, installation and getting started.**

## What is this?

Holder is a free, open-source, community-built personal knowledge system.

## When will this be finished?

London is two thousand years old, look up, the skyline is full of cranes, look down they are digging new tube lines.

With Holder, it is very new. There are rough edges. Things will change. Some platforms and features are further along than others. No point to pretend otherwise.

But that's also why this is an interesting time to get involved.

Holder is being built in the open, and I'd like other people to help shape what it becomes, whether that's through code, testing, packaging, documentation, design, ideas, bug reports, or simply trying it and figuring out what doesn't work.

## Who is making this?

The project has been started by Zeth, a software engineer from England, but he is hoping others will join.

## Why are you making this

I have never been naturally an organised person. 

When I was young, anything important that I needed to remember, I would write on the back of my hand.
If that wasn't enough space then I would write it on the back of an old envelope and use it as a bookmark for the current book that I carried with me.
That was enough, it worked.

But now a few decades later. I am underwater in an swirling chaotic ocean of information. I have emails, documents, forms, bills, ideas, research, bookmarks, AI conversations, notes, things I need to remember, things I need to write, and an endless stream of crap coming at me.

How do I get on top of it? I found existing programs did not suit my needs, my ways of working. They were too closed, too commercial, too annoying. They were often worse than just a directory of text files.

So I am building a tool for myself. It seems to be ever growing in scope. 

The problem may be beyond me as an individual to solve. But as a community, we can work together. And this tool is useful for other people, so I am trying to make it an open source project. Then other people can contribute and we can collectively bring order to the chaos.

## How can I help?

The most useful way to start is to simply to get it working on your computer, use it seriously to try to organise yourself, and then think: what works, what doesn't, what's confusing, and what's missing.

Contributions of all kinds are welcome. Development, testing, art, web design, writing.

You don't need to be an expert on the whole project to contribute. If something interests you, pick a repository, have a look around, open an issue, join a discussion, or try building it.

## Where is it?

Holder is made up of several repositories:

* **Holder Website** — the public website at https://holder.team

Holder is an open ecosystem that hopefully can fit into your workflow. It is a framework that comes with a GUI, but also an HTTP API and a Command Line interface.

It is made up in parts, each one does one thing well.

The biggest two parts are the frontend and backend. If you have ever made a web application, you can get the idea.  

The backend has the core logic and the server, which in classic Unix terminology is called a daemon.  

The frontend has the UI desktop interface.

In packaged managed setups like Ubuntu Linux, that is all we need. The service manager (Systemd or OpenRC) starts the daemon and the GUI frontend, the API and command line tool can just expect it to be there.

But on Mac and Windows we need to handle this process ourselves. So a third program called the launcher checks the backend is up, starts it if needed, then hands over to the frontend.

We also have a couple of more dev-ops repos that handle the workflows of getting the source code from repo to release.


