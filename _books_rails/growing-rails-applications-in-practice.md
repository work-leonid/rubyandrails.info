---
title: Growing Rails Applications in Practice
subtitle: Structure large Ruby on Rails apps with the tools you already know and love
author: ['Henning Koch', 'Thomas Eisenbarth']
cover: rails/growing-rails-applications-in-practice.jpg
publisher: https://leanpub.com/growing-rails
publisher_title: www.leanpub.com
year: 2016
category: ['rails']
tags: ['ruby-on-rails']
---

> Discover a simpler way to scale Rails codebases. Instead of introducing new patterns or service-oriented architecture, we will show how to use discipline, consistency and code organization to make your application grow more gently.

## How we got here

When you started working with Rails some years ago, it all seemed so easy. You saw the blog-in-ten-minutes video. You reproduced the result. ActiveRecord felt great and everything had its place.

Fast forward two years. Your blog is now a full-blown CMS with a hundred models and controllers. Your team has grown to four developers. Every change to the application is a pain. Your code feels like a house of cards.

You turn to the internet for assistance, and find it filled with silver bullets. You should move away from fat controllers, it says. But do avoid fat models. And use DCI. Or CQRS. Or SOA. As you cycle through patterns, your application is becoming a patchwork of different coding techniques. New team members are having a hard time catching up. And you're beginning to question if all those new techniques actually help, or if you're just adding layers of indirection.

You start missing the early days, when everything had seemed so easy and every new piece of code had its place. You actually liked ActiveRecord before it drowned you in a sea of callbacks. If only there was a way to do things "the Rails way" without having it fall apart as your application grows.


## The myth of the infinitely scalable architecture

We'd like to show you one path to write Rails apps that are a joy to understand and change, even as your team and codebase grows. This book describes a complete toolbox that has served us well for all requirements that we have encountered.

But before we do that, we need to let you in on an inconvenient secret: Large applications are large. The optimal implementation of a large application will always be more complex than the optimal representation of a smaller app. We cannot make this go away. What we can do is to organize a codebase in a way that "scales logarithmically". Twice as many models should not mean twice as many problems.

To accomplish this, you don't necessarily need to change the entire way your application is built. You don't necessarily need to introduce revolutionary architectures to your code. You can probably make it with the tools built into Rails, if you use them in a smarter way.

Compare this to sorting algorithms. When a sorting function is too slow, our first thought is not "install a Hadoop cluster". Instead we simply look for an algorithm that scales better. In a similar fashion this book is not about revolutionary design patterns or magic gems that make all your problems go away. Instead we will show how to use discipline, consistency and organization to make your application grow more gently.