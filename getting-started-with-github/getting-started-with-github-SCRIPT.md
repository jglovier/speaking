# Getting Started with GitHub (SCRIPT)

_[slide X: description]_

_[slide 1: talk title: "Getting Started with GitHub and Version Control"]_

_[slide 2: name and twitter handle]_

I'm Joel Glovier - "jglovier" on GitHub and Twitter, so if you have any questions or thoughts about the workshop after it's over, I'll be around for a little while to answer questions but feel free to ping me on Twitter and we can continue the discussion.

I work at GitHub where I'm a front-end designer. At GitHub we make tools to help developers work better together. 

[Question] Just out of curiosity how many people here use GitHub? How many people aren’t using it but are familiar with it? Is there anybody whose never heard of GitHub?

Awesome. Well for anyone who’s never heard of GitHub, we make tools that help people work better together. Collaboration is what we're all about, and the way we focus on that is with GitHub.com, which is a git hosting solution. If you're not familiar with git, git is a type of version control system, and we'll talk more about that in just a minute.

_[slide 3: the roadmap ]_

Here's the roadmap for our time together. We're going to take a look at Version Control, what it is and why it's important; we'll talk about Git, and what makes it's so special; I'll explain how to get setup on GitHub and show you how it makes building software better together; and finally we'll dig right into the details of getting started with how git works, how to make commits by thinking in logical chunks, how to use a feature branch, and we'll if we have enough time we'll look at merging, conflicts, and pull requests.

_[slide 4: Breaking things]_

So first let's talk about Version Control

[QUESTION] I'd like see who all here codes? Put your hand in the air if you code in: HTML? CSS? JavaScript? PHP? .Net? Ruby? Java? How about Python? Pearl? Anything I missed? (go ahead shout it out..)

[QUESTION] So who's has ever had to write a paper for school? Has anyone ever had the experience of losing your work only to have to retype the whole paper again? That moment when you realize all the work you spent so much time on is gone, you get that sinking feeling in your stomach, probably want to throw something. It sucks, right?

[QUESTION] Now who has ever had that similar experience happen to them when you're working on a code project? That sucks even more, doesn't it? It's not just words you lost that you could probably type our and ramble on about again like your school paper, but it's logic and engineering. Problems you solved that you'll have to resolve again. That really sucks, doesn't it.

[QUESTION] Or, have you ever felt nervous about making a change to your code because your concerned that the change you make might break the whole thing? Have you ever wanted to experiment with changing a feature, but your afraid if it doesn't work, you're going to have to spend a bunch to time trying to get everything back to where it was before your started playing around with that idea?

[POINT] The very best designers and programmers are experimenters. The best developers out there don't just get it right on the first try, they iterate. Great code, great software, great products they don't just happen, they are the product of trying things and trying things, over and over and over again until you discover the best way to accomplish something.

_[slide 5: worry/fear emoji]_

But how do you get around that fear of breaking your code or having to waste time getting back to where you were before your latest iteration it's just not working out?

_[slide 6: Version Control]_

Version Control Systems.

Version Control is a way to freely experiment in an environment without the risk of losing anything, or breaking anything, or having to redo what you had before you changed something.

It's like having a map of where you are going and where you have been. It gives you the ability to explore a new route to somewhere without getting lost.

_[slide 7: VC benefits]_

And there's lots of other benefits to using version control software, like having built in backups of your work, and making collaboration with others much easier.

- allows you to experiment freely
- gives you backups of your code so you can roll back to a previous state at any time
- makes collaboration with others easier

[QUESTION] So who here has used version control systems before? Which version control are you using? Who has used CVS? How about Subversion (any SVN users?)? Who has used Git? How about Mercurial? Who has used Trac? Bazaar or LibreSource?

_[slide 8: Git]_

Well next we're going to talk about what makes Git awesome.

Git is a distributed version control system. What that means is you don't have to have a hosted code repository anywhere for it to work (although you can if you want to, and that's what GitHub is for), and it's optimized specifically for that use case.

A little history...

Git was created by Linus Torvalds and born out of the open source development of Linux. 

----
NOTES:

- write the 3 or 4 big points on a markerboard if possible

- try getting them to fork a sample project from me
- avoid the command line and stick with GUIs

- Outline
- Why is version control important
- Reasons to use Git: Distributed, cheap branches, merging is easy, GitHub
- GitHub Desktop Clients
- 3 stage thinking (working directory, staging, and history)
- Commit in logical chunks
- Use branches for features / bugfixes
- Merging & resolving conflicts
- Pull Requests