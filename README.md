gitcheater.com
==============

Summary
-------

[gitcheater.com](http://www.gitcheater.com) is meant to be a super-fast reference for those moments, where you just can't remember the syntax of that one command or whether you had to use three dots or two or brackets or the caret sign. Specify the branch first or the remote? What was the command again for stashing the current state? gitcheater.com is meant to answer that question at a single, quick glance.

Motivation
----------

Although I'm not one of those "command line is god"-people, when I decided to start to learn [Git](http://git-scm.com/) quite some time ago, I wanted to avoid using any GUI tools for the time being and rather try learn the commands and what they actually do, get a better gist of what's really going on in Git's internals. While Scott Chacon's [Pro Git](http://progit.org/), and even more so [Git Internals](http://peepcode.com/products/git-internals-pdf) for sure have been of great help here, I didn't exactly spend 24 hours a day, 7 days a week on learning Git. Rather I'd find a few hours every week looking at it, reading about it and using it each time a little more, slowly starting to rely on it more and more.

But especially in the beginning I found myself confronted with a single problem over and over again. I just couldn't remember all the commands and their exact syntax. Maybe I've just extremely bad memory but I'd rather think it's not just me who's had that problem. And while in theory it's not that hard to find the explanations, neither looking it up in Scott's books nor crawling through man pages was what I needed. I had already read and understood the commands, what they do, etc., I just couldn't remember which one was which, was it pull or fetch, remote show -v or -a?

What I needed was a single-page, categorized overview of the most useful Git commands with extremely short, one-line comments (if any) explaining them. That's how gitcheater.com came to be!

State
-----

gitcheater.com is a work in progress. My learning Git is a work in progress. So it's surely neither complete nor free of errors or the one perfect reference. I'd be happy to get your feedback, hear your comments, suggestions and criticism. Find a bug or miss a command or explanation? Feel free to [email me](mailto:mail@juergentreml.de?subject=gitcheater.com%20via%20Github), leave a comment here or on [my website](http://www.juergentreml.de/) or fork the project, make the changes yourself and send a pull request.

Tech Background
---------------

I'm always up for playing and experimenting with new things so I took gitcheater.com as a chance to try out a few things. Years of experience have taught me that for my own learning and orientation it's extremely important to have visual cues and separation, and that's why I've always had some kind of cards concept in mind find for the site. The code, comment and break-point style is just me having fun with CSS. Anyways, I hope you like it and find it as helpful as I do. In the end that's what I ended up using:

  - [Github Pages](http://pages.github.com/) to host the site
  - [jQuery](http://jquery.com/) of course, for all the small things
  - [jQuery Masonry](http://masonry.desandro.com/) for a dynamically adapting layout without having to care for the actual arrangement
  - [Reset CSS](http://meyerweb.com/eric/tools/css/reset/) to free myself of hours of work trying to make it look the same in all browsers
  - [CSS Auto-width Margins](http://bluerobot.com/web/css/center1.html) centering
  - [CSS box-shadow](http://www.w3schools.com/cssref/css3_pr_box-shadow.asp) for smooth & soft visuals
  - [CSS text-shadow](http://www.onlinecasinodemar.com/webdesign/xhtml-css/beeindruckende-effekte-mit-der-css-eigenschaft-text-shadow/) for text relief effects

Also, I assume and trust that most of those people interested in Git are programmers using any browser but Internet Explorer. The truth is, that I've made zero attempts to make the site look nice, or for that matter, even work in IE.

Final Note
----------

Git is a great tool. I couldn't live without it anymore. For those of you in the process of learning it, I hope to have made it a little easier. For those of you considering Git and who just haven't got around to try it yet: Do it now! I promise it's worth it and you won't regret it. It'll be time well spent.

And don't forget: Leave some [feedback](mailto:mail@juergentreml.de?subject=gitcheater.com%20via%20Github). I really wanna hear from you!