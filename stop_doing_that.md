---
layout: article
title: Stop Doing that!
date: 2012-11-29
author: 
- Maksim Lin
tags:
- programming
- languages
- ui
---

So what do these languages have in common:
C:

    #include<stdio.h>
    main()
    {
        printf("Hello World");
    }

Lisp:

    (DEFUN HELLO ()
      "HELLO WORLD"
    ) 


Basic:

    10 PRINT "Hello World!"


They were all originally written in the 1950s,60s,70s by english-speakers 
using machines like these: 

![Ken and Dennis by PDP-11](http://cm.bell-labs.com/cm/cs/who/dmr/kd14.jpg)

[source](http://cm.bell-labs.com/cm/cs/who/dmr/picture.html)

And what do are languages look like today?
Javascript:

    function hw() {
        alert('hello world');
    }

Clojure:
    
    (def hello (fn [] "Hello world"))
    
C++:

    #include <iostream>
    using namespace std;

    int main ()
    {
      cout << "Hello World!";
      return 0;
    }

and this is what many people use to write in these languages:

![tmux screenshot](http://tmux.sourceforge.net/tmux3.png)

There are even some who take **pride** in making their modern, superfast GPU driven machines look like
glass-terminals from the 1970s - WTF?!?!

Brett Victor has some great (http://worrydream.com/#!/LadderOfAbstraction) 
ideas (http://worrydream.com/#!/LearnableProgramming) and demonstrates (http://vimeo.com/36579366)
really well. I suggest you read and watch all of those.

But as exciting as those are and there as some such as the iOS Codea app that have started incorporating
those ideas.
But I think we can take his ideas much further and I had started thinking about this even before watching 
"Inventing on Priciple" presentation. And its in that presentation (about 27min in) that Brett picks up on
what is for me a key idea - we need to use representations that best suit the medium we are working in.
He points out that the electrical circuit notation used universally in electrical engineering took the
form it did because it was easy to draw on paper, which was the medium being used at the time.
And coming back to where I started with, the early computer programming languages took the form they
did because of the medium and circumstances of the times, they were being invented and used by english
speakers using first punch-cards and then tele-types to input them into the early computers of the day.
Of course Brett makes exactly these points in that section of the presentation.

His following demo then uses an iPad to create an animation on the fly. And this is where I want to pick
things up and take them further. 

So lets do a thought experiment:

...You are living in a world where computing devices as small portable devices with touch screens, along
with fast gpus and decent cpus with plenty of both RAM and permenent storage.
These do not have physical keyboards, because most of them are capacitive touchscreens, you are forced
to interact with them using only your fingers and not any kind of stylus or other pointing device.
And finally to make things a bit more interesting, place yourself in the shoes of a speaker of Chinese,
Japanese or Hindi and not an anglo-germanic or romano-latin derived language.

Given those factors as your starting point, will your programming language look like this?

    foo(name) { 
        console.log('hi '+name); 
    }
    foo('maks');

I seriously don't think so.

Infact would it even be text based at all given that you have the limitation of only very awkward means for
entering text *and* have to potentially deal with a language encompassing tens of thousands of individual
characters instead of a few dozen?

So what would it then look like? Well stay tuned for part 2...


