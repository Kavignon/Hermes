# Hermes

## Introduction

As the reader probably knows, [Twitter](https://twitter.com/) is a social media platform where people can engage with whomever they'd like to talk to, such as their friends, family, movie stars, and so on. You can create small messages, up to a limited amount of characters (280), and share them with people who _follow_ you on the platform. The level of engagement that you can get by following your friends and people you admire is quite incredible. You can have entire conversations with people you'd never thought you'd talk to due to geographical concerns, for instance.

The main goal is to somehow recreate the implementation of _Twitter_ as a training exercise to demonstrate how it can be possible to engineer a distributed system. 


## Motivation

Being quite fond of software design, I've decided to push the boundaries of my knowledge and deepen my expertise in the topics that have piqued my interest thus far. Another reason for this passion project is to provide a helpful guide with a blog series attached to this repository in the future. 

Software engineering is still young at heart and is evolving quite quickly. It can be challenging to find the exact pieces you were looking for when web articles only focus on a small topic instead of demonstrating the entire picture. As we all know, the final vision is bigger than the sum of the parts.

To that end, I decided to take it upon myself to showcase how, given an infinite amount of time, I would engineer a system such as a copy of Twitter. Being the only developer working on this project, I cannot hope to capture everything _Twitter_ is doing as a product, which is perfectly fine. The truth is that I want to go through the main pain points that are encountered as we're building a product from the ground up while making sure it matches the user requirements. 

I would like to make perfectly clear: there are several ways to approach re-building _Twitter_ from the ground up. The following repository shows my perspective on the matter as I'm trying to learn more about my craft while building this proof of concept. As you go through the repository's contents, if there is something that you think can list as an issue, do create a ticket with your comment. I appreciate feedback and will take the opportunity to learn from you, the set of individuals from the technical community who took some of their time to review my work! :)

## Features cloned

- [The home timeline](https://help.twitter.com/en/using-twitter/twitter-timeline):
 > Home serves Tweets from accounts and Topics you follow as well as recommended Tweets

 > _In the scope of the project, we will solely focus on the Tweets coming from accounts that we follow and tweets liked by accounts we follow._

- Registering on the platform with a _handle_.

- Posting tweets which have a character limit of 280 characters. (no hashtag or  video or image support for now.)

- Allowing end-users to _Like_ a tweet.

- Allowing end-users to _Retweet_ a tweet on their own home timeline.

- Allowing end-users to _Follow_ an account.

- Setting the profile of the account through a _Bio_ and an _Avatar_.

- Setting the month the account registered on the platform.

- Observing the amount of accounts followed by a end-user and the amount of followers it has.

 - Allowing end-users to _Search_ for tweets through search keywords.

 - Allowing end-users to see the tweets they've liked on the platform.

 - Allowing end-users to do single conversation responses to tweets.