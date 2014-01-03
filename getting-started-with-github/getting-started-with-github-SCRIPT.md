# Getting Started with GitHub (SCRIPT)

_[slide X: description]_

_[slide 1: talk title: "Getting Started with GitHub and Version Control"]_

_[slide 2: name and twitter handle]_

I'm Joel Glovier - "jglovier" on GitHub and Twitter, so if you have any questions or thoughts about the workshop after it's over, I'll be around for a little while to answer questions but feel free to ping me on Twitter and we can continue the discussion.

I work at GitHub where I'm a front-end designer. I build products that support the mission of our training team. At GitHub we make tools to help developers work better together. 

[Question] Just out of curiosity how many people here use GitHub? How many people aren’t using it but are familiar with it? Is there anybody whose never heard of GitHub?

Awesome. Well for anyone who’s never heard of GitHub, we make tools that help people work better together. Collaboration is what we're all about, and the way we focus on that is with GitHub.com, which is a git hosting solution. If you're not familiar with git, git is a type of version control system, and we'll talk more about that in just a minute.

_[slide 3: the roadmap ]_

Here's the roadmap for our time together. We're going to take a look at Version Control, what it is and why it's important; we'll talk about Git, and what makes it's so special; I'll explain how to get setup on GitHub and show you how it makes building software better together; and finally we'll dig right into the details of getting started with how git works, how to make commits by thinking in logical chunks, how to use a feature branch, and we'll if we have enough time we'll look at merging, conflicts, and pull requests.

_[slide 4: Breaking things]_

So first let's talk about Version Control

[QUESTION] I'd like see who all here codes? Put your hand in the air if you code in: HTML? CSS? JavaScript? PHP? .Net? Ruby? Java? How about Python? Pearl? Anything I missed? (go ahead shout it out..)

[QUESTION] So who's has ever had to write a paper for school? Has anyone ever had the experience of losing your work only to have to retype the whole paper again? That moment when you realize all the work you spent so much time on is gone, you get that sinking feeling in your stomach, probably want to throw something. It sucks, right?

[QUESTION] Now who has ever had that similar experience happen to them when you're working on a code project? That sucks even more, doesn't it? It's not just words you lost that you could probably type our and ramble on about again like your school paper, but it feels like you've lost so much more. Logic and engineering. Problems you solved that you'll have to resolve again. That really sucks, doesn't it.

[QUESTION] Or, have you ever felt nervous about making a change to your code because your concerned that the change you make might break the whole thing? Have you ever wanted to experiment with changing a feature, but your afraid if it doesn't work, you're going to have to spend a bunch to time trying to get everything back to where it was before your started playing around with that idea?

[POINT] The very best designers and programmers are experimenters. The best developers out there don't just get it right on the first try, they iterate. Great code, great software, great products they don't just happen, they are the product of trying things and trying things, over and over and over again until you discover the best way to accomplish something.

_[slide 5: worry/fear emoji]_

But how do you get around that fear of breaking your code or having to waste time getting back to where you were before when you realize what you're attempting to do just isn't working out?

_[slide 6: Version Control]_

Version Control Systems.

Version Control is a way to freely experiment in your project without the risk of losing anything, or breaking something, or having to rebuild what you already had built before you started experimenting with a new feature.

It's like having a map of where you are and where you have been. And it gives you the ability to explore a new route to somewhere without getting lost and to retrace your steps if you have to go back to where you were.

_[slide 7: VC benefits]_

And there's lots of other benefits to using version control software, like having a way to track issues, having built in backups of your work, and making collaboration with others much easier.

- allows you to experiment freely
- gives you backups of your code so you can roll back to a previous state at any time
- issue and bug tracking
- makes collaboration with others easier

[QUESTION] So who here has used a version control system before? Which version control are you using? Who has used CVS? How about Subversion (any SVN users?)? Who has used Git? How about Mercurial? Who has used Trac? Bazaar or LibreSource?

_[slide 8: Git]_

Well next we're going to talk about what makes Git awesome and why you should be using it as your version control system.

Git is a distributed version control system. What that means is everyone gets a copy of the codebase on their local machine and you don't have to have a centralized hosted repository anywhere if you don't want to. It's optimized for multiple people working asynchronously on separate copies of the codebase, and then combining their work later.

A little history...

Git was created by Linus Torvalds and born out of the open source development of Linux...

_[slide 9: Git benefits]_

So some of the most important features of Git are that it is: (see slide...)

Most importantly, though, git is optimized for working on open source projects. Let's imaging you maintain an open source project and you want to get other people involved in working on the project. With Git you can get others involved while still maintaining control over your project because users can branch your code (what we call "forking"), make changes to the code (adding features, fixing bugs) and then you can merge their work back into the primary codebase ("master" branch)

_[slide 10: GitHub]_

So let's talk a little about GitHub and how it makes working with Git awesome.

GitHub is quite simply the easiest way to use Git. We provide a platform where you can host your code for free if you're working on open source projects, and all the awesomeness of git is built right in.

That means you get bug and issue tracking built into GitHub. Branching, forking repositories you find, merging and pull requests, and social features like following people's projects so you can get notified of activity that happens on them.

Also, we have desktop clients that integrate directly with your local code repositories.

So the first thing we are going to do is get started with using GitHub!