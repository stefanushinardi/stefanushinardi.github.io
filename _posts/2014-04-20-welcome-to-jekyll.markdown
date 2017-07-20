---
layout: post
title:  "Yahoo!"
role: "Software Engineering Intern"
date:   2014-04-20 09:11:03
cover: "assets/yahoo.png"
link : "https://github.com/apache/incubator-pulsar"
categories: projects
---
In the summer of 2016, I interned at Yahoo! (now Oath:) in cloud service team. I specifically worked on a distributed pub-sub service, Pulsar. The project is now open-sourced and was recently accepted to apache-incubator.

![Yahoo Picture]({{ site.url }}/assets/yahoo.png)

I did not quite have a specific summer project as I was treated as a full-time employee, but one of the significant was to build distributed Websocket proxy for Pulsar.

The objective of the Websocket proxy is to remove barrier of entry to use Pulsar service. Using the proxy, applications would not need to use the client SDK to consume/produce messages. Moreover, since it is language agnostic, it would allow more applications to use this service (At the time, Pulsar only provided Java and C++ client).
