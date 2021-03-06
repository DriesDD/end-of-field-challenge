end-of-field-challenge
=====================================

**Becode evaluation challenge**

Exercises:
----------

 - [complex.08](https://driesdd.github.io/end-of-field-challenge/#complex08) - [page link](https://driesdd.github.io/end-of-field-challenge/complex08.html)

 - [simple.01](https://driesdd.github.io/end-of-field-challenge/#simple01) - [page link](https://driesdd.github.io/end-of-field-challenge/simple01.html)

 - simple.04 

I chose the complex.08 exercise and the simple.01 exercise and used [these tools](https://driesdd.github.io/end-of-field-challenge/#tools-used).

Complex.08
----------

I did this exercise first.

The final result had to look like this:

![Complex exercise example](img/complex.08.png)

My result looks like this (at a certain viewport size):

![Complex exercise example](img/8showoff.png)

I first made a version that looks like that at a certain resolution, then made it responsive, and then fintetuned it. i did not use the image overlay pixel perfect technique because the page would scale anyway. I was a bit confused measuring the dimensions because the high resolution picture had huge fonts. I realized it was upscaled. I also didn't find the correct font right away so I went to the original article which showed the true font and font size for reference. I did not look at any non-font related CSS from that page because I wanted to build the rest of the CSS myself.

I used a flexbox because it had been a while since I used that and this seemed like a good case to use it. I think my solution for responsiveness is not the most elegant - I would personally prefer less lines of code in @media rules so that the code is more easily updateable - but it was fast to implement and the result looks good.

See it here: [https://driesdd.github.io/end-of-field-challenge/complex08.html](https://driesdd.github.io/end-of-field-challenge/complex08.html)

Simple.01
----------

The final result had to look like this:

![Simple exercise example](img/interface.01.png)

My result looks like this:

![Complex exercise example](img/1showoff.png)

This exercise was quite easy to do with the pixel perfect overlay technique. I found a closely matching font so I included it but with a fallback to a webfont as well. I used a grid but since it looks like a card with a fixed width, there were also other options to get the position of the elements right. I am just most comfortable with grids at this point.
I had a lot of time left in the afternoon so I tried different fonts and weights etc, in the end I never found the right font but the result is quite close.

See it here: [https://driesdd.github.io/end-of-field-challenge/simple01.html](https://driesdd.github.io/end-of-field-challenge/simple01.html)

Tools used
----------

**Offline**

 - VSCode with the beautify plugin

 - Pinta, a linux tool for image editing

 - The built-in linux Nautilus terminal with Git

 - GRIP app to preview this readme file before committing

 **Online**

 - Github

 - Font squirrel font generator and Font Matcherator

 - DuckDuckGo search engine

 - Google reverse image search

 - Google Fonts