---
title: "Surface & Interface"
description: "We tend to treat machine learning as a brain in a jar rather than one part in a whole system. The best examples of AI, from autosuggest to…"
date: "2019-08-05T02:25:51.475Z"
categories: []
published: false
---

![An early Drawing Machine used by Albrecht Dürer to reduce high-dimensional datasets.](./asset-1.gif)

_We tend to treat machine learning as a brain in a jar rather than one part in a whole system. The best examples of AI, from autosuggest to dancing robots, are part of integrated systems. A dualistic approach to software development seems easier at first but increases the likelihood of system failure._

---

If you’re used to making applications, machine learning can be quite a shift in thinking. 

  

  

So it turns out that applying machine learning to business problems is harder than we expected. I work in the enterprise and have seen firsthand how difficult it is to get get your hands on the data in the first (something Andrew Ng refers to here). Then there is the feature engineering, cleaning, finding the right classifier and building machine learning pipeline. If your business problem is less obvious and more deeply embedded in processes, you have another set of architectural hurdles to contend with, as well some method to make sure the prediction model doesn’t go off the rails at some point in the future.

Given that each step in process is pretty new territory for most engineers, it’s no surprise that a company would want to silo data science off from the rest of IT. 

But there is a flaw in this assumption that goes all the way down to how data scientists perceive problems. 

The above illustration shows an old technique that uses a drawing machine to more accurately depict the subject of a drawing. It may seem quaint to us today, but this method revolutionized painting and arguably triggered the Renaissance. For the first time, we were able to visualize the world in a way that was too unintuitive for our eyes before. Just compare this method to the medieval illustrations from a few decades prior.

We need tools to help us see the surface. 

There are many kinds of surfaces. The surfaces I’m talking about the ones that transform data into something we can more easily understand.

---

If you follow the step by step instructions, it seems that all one has to is 1) identify the problem you want to solve 2) Find the right data for it 3) Clean the data 4) Determine the right model, learning rate, etc 5) Create a pipeline (n¹, n², …, n^m )

---

The medieval illustration above by Durer depicts a perspective machine used by artists in the 16th century. One could make a strong argument that this optical augmentation launched the Enlightenment. Certainly, the unprecedented success mapping a scene to a surface would trigger the telescope, the camera, the microscope, and data science. 

In order to put machine learning in perspective, I have to talk about the history of our tools. Tools are shortcuts. Some help us see more clearly and some intervene in a system. It’s similar to mind-body dualism and it’s what is preventing a better application of machine learning.

---

We see what machine learning can do everyday in news reports and youtube videos. AlphaGo, created by DeepMind, beat the world’s best Go player and reset our wildest predictions about artificial intelligence. Atlas, by Boston Dynamics, built a robot that can do parkour and dance.

And on the other extreme, there are cases of Airbnb hosts who have been nearly murdered and may never feel safe again. (However, we might never know about that story if there wasn’t twitter to push news to the forefront.)

Half of us regard technology as a rainbow of potential, the other half see technology as a kaleidoscope of confusion.

I see the problem with machine learning as stemming from a dualist approach to surface and interface. Think of surfaces as graphs and charts. And interfaces as the things you interact with. If this doesn’t make sense, stick with me and I’ll explain. 

Data science is the ultimately the study of surfaces. Long before a prediction model becomes a product, data scientists scrutinize data to look for patterns. Data is just a record of past events. The theory is that if there is enough record of past events, it is possible to predict future events. 

Take the price of homes in Portland. Given enough records of home sales that includes details about the number of rooms, their location, and recent economic trends, one could predict how much a particular home in Portland would go for. This is reasonable.

Another example could be determining whether there was a cat in a photo. Seems simple enough, but up until a few years ago image recognition was only used in extreme cases where stakes were high. 

If you think of a photo in terms of data, its a very simple problem. Every pixel is a just a combination of red, green, and blue. Any pixel can boil down to a number that won’t exceed 15 million. So a photograph is just a spreadsheet of numbers. Find the patterns of these numbers that are close together and you can interpret any picture. 

But a photograph is still a surface. There is a wealth of data that isn’t recorded in a photograph. The temperature in the room, the thoughts and fears of people or cats, the tension felt just outside the photo.

Data science is successful because it doesn’t care about how the world works. If you train to become a data scientist, you learn three foundational beliefs. I’m taking this from “How to Measure Anything,” which is a fantastic primer on how to become Sherlock Holmes. In Hubbard’s chain, there are three simple truths: Anything that exists has an effect on the material world. Anything that has an effect on the material world can be measured. Therefore, anything that matters becomes data.

It’s hard to argue with his point, but I’ll give it a shot. 

I’m fully aware that calendars start on Sunday and I’m sure most people think that the week starts on Sunday. But I happen to think the week starts on Monday because that is when I start my work week. (This is such a minor observation that we barely consider when the concept of a week begins.) Would a person who thinks that Sunday is the first day of the week make different choices on a Saturday night than me?

A data scientist wouldn’t care, and for good reason. If I had to fit this belief to a mantra, it would be “Blood Will Tell.” In other words, if this Saturday/Sunday belief mattered so much, it would show up in other choices and other data. It could actually be rather trivial to predict whether a person believed that Saturday was the last day of the week or Sunday was based on their aggregate patterns. So their model of the world still works: if it matters at all, it will effect matter. A butterfly could flap its wings and create a tsunami somewhere in the world, but if it only happens once, it doesn’t matter. There were most likely other systems at play that triggered the even that happen more often. This is materialism at its most refined.

I’m not here to attack data scientists but to give a perspective of how they think and how it is misapplied to business problems.

  

  

  

  

Rather than feeling like technology has enabled our march toward progress, it seems like the landscape of human progress has turned into a kaleidoscope. 

  

  

  

  

When the USAF discovered that their planes were crashing because the cockpits weren’t shaped for pilots, they went back to the data. They found that the initial specs for pilot dimensions didn’t fit a single a pilot. The data wasn’t wrong, there just wasn’t an average pilot. So they told the plane manufacturers to fix it.   
The manufacturers came back with adjustable seats. They turned what was previously a surface into an interface.   
In order to apply ML, data science and UX need to overlap. This talk explores how to do that in the enterprise.
