---
layout: post
title: Approaching WebGoat as a Total Beginner
---

Started today with learning the basics of secure Web applications from [webGoat](https://github.com/WebGoat/WebGoat/wiki) and seems really interesting so far!
The easiest way to access webGoat is through the docker container is with the command `docker run -d -p 80:8888 -p 8080:8080 -p 9090:9090 -e TZ=Europe/Amsterdam webgoat/goatandwolf:latest`

It's nice to start with the basics but I already encountered some confusing wording regarding POST requests- a simple Google search sufficed for what I was looking for. I think that the tutorials themselves  should minimize confusion, and the previous explanation on GET requests and the relationship between clients and servers is fantastic.

I'll continue to delve through it later, but I'm curious why there's a disclaimer that you should run webGoat and webWolf with your internet disconnected. I assume it's something to do with "minimizing your exposure" but otherwise there's no explanation given. This is something to be seen through later.

Also, when initially running the docker container you have to provide your timezone, which I found on [wikipedia](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones) but I entered something that wasn't from there and the command ran without any problems.

I can't think of a reason why this would be something to be particularly important due to the project's nature of being disconnected from the internet. I haven't gone through the entirety of webgoat so we'll just have to see. 

Update(2021-01-04): [Someone else](https://mydeveloperplanet.com/2019/11/27/hack-the-owasp-goat/) has already gone through the entirety of webgoat with a fairly concise review, and mentions a few other issues when completing the lessons. A total beginner is most likely going to have a different opinion, though.