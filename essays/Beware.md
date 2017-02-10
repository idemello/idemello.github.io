---
layout: essay
type: essay
title: Beware the IDEs of Javascript
date: 2017-09-02
labels:
  - Software Engineering
  - Programming
  - Coding Standards
  - Javascript
---

On the surface coding standars do seem a bit trivial. What difference does it make that there are 4 spaces as opposed to two?
# Experience is the Teacher of All Things

On the surface coding standars do seem a bit trivial. What difference does it make that there are 4 spaces as opposed to two?
Is it necessary to use single quotes as opposed to double quotes? At first I was slightly annoyed by the prospect that I would be unable 
to submit my code without following some arbitrary standard. However after noticing the difference in the style of my code I have taken a different
outlook on what coding standards really do. 
                                                                                                                                                                                                                                                                              
From a linguistic perspective, every language and culture has certain ideas or customs that they put a great emphasis on. For example in Thailand there are
a dozen words to say smile, each with a very different meaning.  Bringing this back to the realm of programming, in the same way that cultures emphasize
different aspects of their daily lives or the world around them; coding standards show what different languages emphasize. While I have not used strict coding standards
in any other language (simply suggested guidelines), even my sojourn within javascript coding statndards has taught me where to emphasize and de-emphasize certain aspects of the 
language. For example one of the erros I came across today within our ESLint standards was that string concatenation was disallowed. I found this to be very interesting as it is 
such a common practice within Java. 

## Et Tu, IntelliJ?

Previously, our class has been coding in a cloud base programming environment known as JSFiddle. Within JSFiddle I had a lot of complaints about the environment,
primarily about the way the error messages were displayed. Having an error message that lets you know there is a missing delimeter somewhere in your code, but not
the exact location is an absolute nightmare. Having to look through everyline without a general idea of where to look is time consuming, especially during one of
our graded, timed assignments. This being said when we were told do download a Javascript IDE I jumped at the opportunity, I then downloaded a program
known as IntelliJ. After watching a short tutorial on how to configure everything I was feeling great. When I missed a parenthesis the IDE was quick to inform me
of my mistake. I installed the coding style package of ESLint which corrected my stylistic errors, which were annoying at first, but after sometime I started to get used to.

Then why the pessimistic title of this subsection and the overall essay? During my timed programming assignment this Thursday I was stabbed in the back by ESLint and IntelliJ.
The code we were required to do was simple enough. Given an array of strings, return a new array with the length of the element added onto the end of the element. Took me a bit
longer than I wanted to because ESLint does not approve of string concatenation, so I had to play around with using the template format of Javascript, not a big deal. Almost done
with one error left before I commit to GitHub. I scroll over the error to find "_ is not defined", seemed harmless enough with 8 minutes remaining I could easily trouble shoot this.
Running through all the possibilities I checked my .html file to be sure I included the underscore library, included. Strange, next step is my ESLint working? Yes. 7 minutes left.
Maybe someone else has had this error? 
~                                        
