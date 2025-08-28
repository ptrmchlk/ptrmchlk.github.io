---
layout: page
title: resources
text_title:
permalink: /resources/
---
[Introduction to Mathematics for Life Scientists]: https://link.springer.com/book/10.1007/978-3-642-61869-7
[Calculus Made Easy]: https://www.gutenberg.org/ebooks/33283
[Statistical Rethinking]: https://xcelab.net/rm/
[Mathematical Models of Social Evolution]: https://press.uchicago.edu/ucp/books/book/chicago/M/bo4343149.html
[Learn C++ website]: https://www.learncpp.com/
[The Linux Command Line]: https://www.linuxcommand.org/tlcl.php
[Art of R Programming]: https://nostarch.com/artofr.htm
[Writing Down the Bones]: https://nataliegoldberg.com/books/writing-down-the-bones/
[A Biologist's Guide to Mathematical Modeling in Ecology and Evolution]: https://www.zoology.ubc.ca/biomath/
[Automate the Boring Stuff with Python]: https://automatetheboringstuff.com/
[Modelling for Field Biologists and Other Interesting People]:https://doi.org/10.1017/CBO9780511811388

<span style="font-size:20px;"> also known as ***an unsolicited list of recommendations of stuff that might or might not be useful for people trying to be scientists, especially if they like theory and evolution***. Mostly books.</span>

#### **Modelling and theory**

###### ***[Statistical Rethinking]*** by Richard McElreath, 2020

Bayesian methods used to be all the rage, but although well explained here, it's not the point of the book. The point is, statistical tests are not black box tools to be applied using some decision tree. Science is complicated and our analysis should reflect as much of what we know as possible. If you want to understand what you are doing when you're analyzing your data, this is a great book to go to. Especially if you are an early graduate student who still feels like they don't understand statistics, this will give you background to engage with those models. And maybe tempt you to write your own. Oh, and there are [free videos](https://www.youtube.com/watch?v=FdnMWdICdRs&list=PLDcUM9US4XdPz-KxHM4XHt7uUVGWWVSus) connected to the course by the author.

###### ***[Mathematical Models of Social Evolution]*** by Richard McElreath and Robert Boyd, 2007

Modelling not just for social problems. But it helps if you're interested in the topic. A nice general introduction to modelling evolution using social evolution as base. A little population genetics, a little game theory, quite a bit of evolution and a nice derivation of the Price equation. It has some typos, sometimes answers to questions are missing or the answers do not match. Needs to be read vigilantly. But for me, it was a tremendous boost of modelling confidence. It just needs a second edition.

###### ***[A Biologist's Guide to Mathematical Modeling in Ecology and Evolution]*** by Sarah Otto and Troy Day, 2007 

One of those books I was always recommended - and for good reason. It tells you how to construct the model - how to graph it, trace its logic before getting bogged down by equations. And presents several classic models before jumping into methods of analyzing various modelling strategies. It's comprehensive and certainly useful. But, it's big. It might be better seen as a reference, rather than something to read cover to cover. Especially if you just want to dabble in models.

###### ***[Modelling for Field Biologists and Other Interesting People]*** by Hanna Kokko, 2007

Hanna Kokko is both a well known theoretical biologist and a writer with a sense of humour. Each chapter is a question, followed by an approach that can be used to solve it. It reads nicely and stresses the most important part - we are trying to solve a biological problem here. It's a great book not only for those theoretically skewed, but, as title suggests, also for those who spend some time in the sun. What you will get from this book is an important insight - "would a model help me clarify my problem". And then you can try yourself to see what emerges. I don't think it has been republished, but you can find second hand copies.

*Sidenote: 2007 seems to have been a good year for modelling textbooks*

#### **Mathematics**

###### ***[Calculus Made Easy]*** by Silvanus P. Thompson, 1914 - but consider Martin Gardner 1998 updated version

This one can be somewhat controversial. And mathematicians might sneer at it. That said... if you are terrified by a derivative, this book will fix it. You'll be hunting for infinitesimals and have fun with it. You might need a follow up, but whatever it is, it will not be scary anymore. 

###### ***[Introduction to Mathematics for Life Scientists]*** by Edward Batschelet, 1979

A little gem. Well, relatively little - it is still 600 pages. But it is a one stop book if you are a biologist unsure of their mathematics. It might not replace a specialized textbook, but will give you most of the tools needed to understand those "mathy" papers. From real numbers to differential equations, probability, and linear algebra. Just make sure to get the third edition - the earlier ones were published before SI units were a thing.

#### **Programming**

###### ***[Learn C++ website]*** 

Made by a self described "dude" named Alex, it's a great introduction to using C++ as a general programming language. It will not teach you how to do scientific programming with it, but if you're curious about going beyond R or Python, this is a great place to start.

###### ***[The Linux Command Line]*** by William Shotts

As a scientist working with computers, you might need to touch the command line and deal with Linux - either for your own convenience or because some server/cluster requires it. Then, you need to grasp some *bash* and command line tools. Here is a great book to get you up to speed with how this whole thing works - if you need vim, awk, grep or pipe your results to file. And the best thing is - the PDF is freely distributed by the author. 

###### ***[Art of R Programming]*** by Norman Matloff, 2011

I don't remember when I learned R. I had a statistics class during my bachelor from which I remember little, a quick R intro for the master. I think it was really only when I had to analyse my master experiments that I learned - on the "need to know" basis. But if I was to start again, I think I would start with this book. I have it near my desk for when I'm unsure about some technical detail. It even has chapters on debugging, enhancing R with C++, and parallel computation. So, if you can get the book somewhere, without ruining your wallet, I'd recommend. Author also has a free online tutorial, called [fasteR](https://github.com/matloff/fasteR). If you're just starting with R, it might be a good place to begin. *A small note*: it doesn't teach *ggplot2* or the fashionable *tidyverse*. While these days, whenever possible, I avoid those, its just a personal preference and you might need them. Or your supervisor uses them. Or co-authors. In any case, if so, you might want to check out Wickham *et al.* [R for Data Science](https://r4ds.hadley.nz/) and [ggplot2: Elegant Graphics for Data Analysis](https://ggplot2-book.org/). They are good if you've been strong-armed.

#### **General science**

###### ***The Elements of Graphing Data*** by William S. Cleveland, 1985

This is another a bit old, but an interesting one. It comes just from around the time of transit towards computer generated graphs. The book spells out the logic and principles behind what makes for a readable graph. Author clearly is focused on research data and, I think, for a scientist it is more useful than the famous Tufte's books. Also, R users might notice that the graphs look quite familiar. Cleveland was a part of the group working at Bell Labs designing graphics for the S language, R's predecessor. As such, the book gives a logic behind the design of the R plots - and just might make you appreciate some of the default settings. But, if you hate R graphs, maybe not the obvious choice.

#### **Writing**

###### ***[Writing Down the Bones]*** by Nathalie Goldberg, 1986

You probably know Strunk and White's [*Elements of Style*](https://gutenberg.org/ebooks/37134) and I don't think anybody disagrees that its one of the best. It's clear, witty, and makes sure you write in a way that's clear, understandable, and mostly correct. But it will not tell you what to write. And if, like me, you stare at a blank page and don't know where to start - this is the book. It might seem not directly relevant to a scientific writing, but it is aimed at writers of all sorts. It is the book that made me enjoy writing the papers again. It is scientific *communication* after all. The book came too late to help with my thesis, but it might come early enough for yours.


