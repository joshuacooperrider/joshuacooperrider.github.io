---
layout: essay
type: essay
title: "Asking the Right Questions"
# All dates must be YYYY-MM-DD format!
date: 2025-01-30
published: true
labels:
  - Questions
  - Answers
  - StackOverflow
---
<img width="700px" height="200px" src="../img/question.png">

## Introduction

Have you ever wondered why your question on a forum goes unanswered or your responses are not so helpful? It might be because the question proposed wasn't written for your audience. Most people answering questions on forums are doing so out of the goodness of their hearts. A question that makes it sound like you havent done your research or sounds like your trolling will probably go ignored. It's important to understand how asking a question the right way can vastly improve the answers you get.

## What does a good question look like?

Stack Overflow, a question and answer site for programmers, has plenty of examples of how to write a smart question that will recieve good responses. Take the following example:

```
Question: C# var vs. interface vs. concrete class in object instantiation

As we know, there are (at least) four ways to instantiate a class object in C#. But I've never quite understood why some ways are better than others.

First of all, you can explicitly declare the variable as the concrete class and instantiate it as follows (this appears to be the practice of many general developers):

Customer cust = new Customer();

The redundancy of this appproach has always bothered me. (Why do we need to be told twice that the the object we're creating is a Customer?)

Secondly, there is the newer shorthand version of this approach, which I find much easier on my eyes:

Customer cust = new();

Thirdly, there is var.

var cust = new Customer();

And finally, one can code to the interface rather than the concrete class (assuming we have an interface ICustomer that Customer implements):

ICustomer cust = new Customer();

This pattern is frequently used by Java programmers.

The vast majority of the time I use var. But I am beginning to rethink this. It seems that there is a lot of wisdom in the fourth (Java-style) approach of coding to an interface, as it would be more dependency-injection friendly and allow one to more easily substitute out different implementations of the object.

Can you think of any reason why a developer would use the explicit first approach, as opposed to the shorthand version, or var, or an interface? Or is this all just a matter of style and opinion?
```

Can you tell why this is a good question? It shows that the user asking the question has a background in the subjest. It also shows that the user is able to understand the benefits of using different styles of code. Asking a question showing that you have experience with the subject matter will yield much better results when asking that question to the right community. It is also important to do your own research before hand. Imagine being asked the question "What is the capital of the USA?" on a forum dedicated to the bio-diversity of North America. A) The question clearly doesn't belong on that forum and B) its a question that could easily be answered with a quick google search.

## What does a bad question look like?

If your question is not well defined, looks like you don't have a concept of the subject, or looks like your trying to be lazy then you almost certainly won't be getting help anytime soon. As an example see the following question:

```
Title:
"Why is my code not working??? HELP ASAP!!!"

Body:
"Hey guys, I'm trying to write a program in Python, but it's not working. I keep getting some kind of error, but I don’t understand it. Here’s my code:

python
def doSomething(x):
    for i in x
        print(i)

doSomething(5)
I need this fixed fast for my school project. Please respond quickly. Thanks!!!"
```

Can you tell why this is a bad question? It shows that the user clearly doesn't have a baseline understanding of the information they're requesting assistance with. It is clear that the user did not even attempt to research the answer themselves prior to asking on the forum. Asking a question like this shows that the user doesn't value the time or effort of those on the forum. They're looking for a quick response to something that could easily be researched. The question is also just too vague. There is no explaination of what the intended result was or solutions tried by the user.

## Conclusion

While working in a professional environment it is important to be able to communicate efficiently with peers. It is important to take initiative and try to find an answer to the problem for yourself. Only after you have exhausted all you're own means in answering the question should you then try to seek the answer on a public forum. This shows that you are willing to learn, dedicated, and truly encounterng something that other experts might have also encountered. This will yield much better results and can help the entire community grow as a whole.

## References
https://softwareengineering.stackexchange.com/questions/456416/c-var-vs-interface-vs-concrete-class-in-object-instantiation

https://chatgpt.com/share/679c58cb-aa6c-8012-af32-fb2e0d7bd677

http://www.catb.org/esr/faqs/smart-questions.html
