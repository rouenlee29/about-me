---
title: "Functions are not ugly"
date: 2020-12-23T00:00:00+00:00
categories:
  - Thoughts
tags:
  - Mathematics
---

### How interesting can a function be?

In school you might have encountered the dreaded `f(x)` symbol in algebra, for example:

```
f(x) = x + 2
```

The equation above is enough to intimidate and bore many people, and the purpose of this article is to show that there is a beautiful and ridiculously simple concept behind it. We often encounter this concept in our daily lives, but because it is so straightforward and obscure, we fail to notice it. 

The concept is *mapping*. So, what is a mapping? When you think of _maps_, you think of diagram that brings you from one place to another, say, from Berlin to Amsterdam. That's what mapping does - it brings you from one thing to another. 

> TODO elaborate with visual example

Similarly, a mathematical function like `f(x) = x + 2` uses addition (`+`) to bring you from one number to another. For example, when you feed the function with `3`, it adds `2` to it and brings you to `5`. In other words, we have mapped `3` to `5`. 


 Mapping is the invisible processes that happen everywhere and anywhere. The respiration process can be thought of as a mapping of gases to different forms : oxygen in; carbon dioxide and water vapour out. Likewise, when your partner says "Honey, we need to talk", you mentally map it to "Something has gone wrong".

### Functions are all about giving and receiving.

A function like `f(x) = x + 2` can also be interpreted as a process of giving and receiving — if the function is given `3`, you will receive `5` in return. The process of giving and receiving, to me, is by itself rather fascinating, because it happens everywhere in the internet. It happens when you casually click the "like" button on Facebook, follow someone on Instagram, or execute a sneak attack in a video game. Underneath the fancy interfaces lie many function-like objects that receive your keystrokes, execute some commands, and returns something that results in a visual change on your screen (and probably in some remote database). 


### Mapping in AI algorithms

When you see a picture like this:

![Cat](./images/cat.JPG)


Your brain automatically maps it to the word "cat". See? another mapping process. But wait — functions perform mappings, so can we try to express the act of seeing as a function? We'd have something like:

```
f(image of cat) = cat 
```

We can also have:

```
f("this movie sucks!")  = negative review 
```

Many (but not all) challenges in AI involve mapping tangible objects (like images and words) to a label (like "dog" or "cat"), without the guidance of humans. More specifically, many AI algorithms are nothing more than complex mathematical functions that perform these mappings. 

Hang in there - if AI algorithm are mathematical functions, then how do we perform mathematical operations on images and words? On images - the problem is straighforward to solve, as images are nothing more than a collection of pixels. On words - this is slightly trickier, and there is an entire research field dedicated to finding the correct numercial representations for words. 

> TODO elaborate with visual example
> https://stackoverflow.com/questions/16994797/convert-image-in-to-numbers

Also, the raw outputs of AI algorithms are not word labels like "dog" or "cat". Rather, they are numbers (unsuprising, since they are mathematical functions anyway). The humans have to arbitrarily decide on the numbers that correspond to each label. 


For example, an AI algorithm that is able to detect cat pictures will behave like the following function:

```
f(numbers representing the pixels of a cat image) = 1
```
Where we have decided `1` = cat. 

The billion dollar question is, how do we find `f`? Surely it is not going to be as simple as `f(x) = x + 2`. Also, surely it will take _a lot_ of mathematical computations to transform a collection of numbers to the number `1`! 

In a promising AI technique called _Deep Learning_, we'd start by mapping the inputs to another set of numbers. Then we take this new set of numbers are map it to another set of numbers. We'd then repeat this mapping process until we can get a number that represents the desired label. This method has the word _deep_ because there are many "layers" of functions working consecutively to process the inputs. 


### In a relay race

This brings us to our next point — functions can be in a relay race, where an output of a function serves as an input to another functions

Piecing all the functions together 

Helpful to think functions as transformers... perform transformation

```python
knife(one loaf of bread) = bread slices
toaster(bread slice) = toasted bread

butterKnife(toasted bread + peanut butter) = breakfast
```

### Functions within functions

Functions can be made up of other functions, for example:

```
f(x) = a(x) + g(x)
```

A more concrete example is as below:

```python

f(hears "I love you") = a(hears "I love you") + b(hears "I love you") = crazy in love
where  a(hears "I love you") = face blushes and 
b(hears "I love you") = heart rate increases 
```

### Before we say goodbye...

To me, software programs can be thought of as a synchrony of many different components giving and receiving things between each other. The same can be said about many biological processes that occur in living organisms. To me, it is refreshing to think how mathematical functions elegantly demonstrate the process of giving and receiving in mathematical notations. I hope you do too.