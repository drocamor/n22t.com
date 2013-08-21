---
layout: default
title: On Text Editors
---

It's not like my life is defined by the computer programs I use, but I was just thinking about how the way I use my computer has changed over time. Some of the changes of tools were caused by the work I needed to do and others have influenced the kinds of things that I do. Tools shape the way we work. 

Text editing is a big part of what you do on a UNIX like system so my text editor is probably the program I deal with the most. I am starting to work with a new text editor and that made me think about my history with text editing. Here's a brief summary:

* ~1996 - My family gets a shell account with our ISP in Wisconsin (ExecPC!). I telnet into a Sun machine (though I have no idea what that is) and run emacs because I heard it was a UNIX program. I have no idea what to do, hit a bunch of keys, and close the window.
* 1999-2002 - I use pico when I start using Linux. I don't do much with it other than edit configuration files. I don't think I even learn any of the commands for it (are there commands for it?).
* 2002-2010 - While I'm working on a script to deploy a Mac OS X image to a bunch of workstations, pico wraps a very long line of the script. I reluctantly switch to vi. I got really into it, learning a lot from the other UNIX administrator when I worked at R/GA. I starting using gvim pretty heavily in the last year or two. 
* 2010-2013 - I feel a bit of editor wanderlust and try to make a switch to emacs in early 2010. It doesn't really work out, but I got married that year and when I returned from my honeymoon (refreshed and having not used a computer for a few weeks) switching was easier. I used emacs full time starting in mid 2010. For a while I used it for pretty much everything including mail, twitter, and music. 
* 2013-?? - I'm on vacation as I write this, but since my daughter was born in June I've been spending a lot of time thinking about how I compute. This is probably more because of a lack of sleep than because of any sort of epiphany. In any case, 2013 is the summer of my Computing Crisis and I've decided to change editors. I've started using [acme](http://plan9.bell-labs.com/sys/doc/acme.html). We'll see how long this lasts.

Acme is sort of the opposite of emacs. It edits text and that is it. It doesn't do syntax highlighting or magic indenting or what not. You can't really change the colors. The font options are pretty limited.

This is not to say it sucks or it is not flexible. It positions windows very intelligently. The mouse is quite integrated into the environment, and super useful. I can customize it by mixing in any UNIX command in the tag and clicking on it with the middle button. My favorite part so far is the ability to right click on an address of some lines in a file and have it open the file and jump to it. I'm modifying some programs I use for editing [CloudFormation](http://aws.amazon.com/cloudformation/) templates to take advantage of this (Should be super helpful when editing a 1600 line JSON file).

Like I said, I'm not sure how long this will last. Acme may not be practical for me, but who knows-- maybe it will have a run as long as vi and emacs did!
