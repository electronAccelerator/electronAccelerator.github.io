---
layout: post
title: Docker and current steps towards Cyber Security
---

Currently working with <a href="https://docker-curriculum.com/">docker curriculumn</a> in order to make a website that'll host some lore for the 5th edition Dungeons and Dragons campaign that I'm running. 

Got a bit stuck at sending a cURL request to the container. It displays the following:

```
curl : Unable to connect to the remote server
At line:1 char:1
+ curl 0.0.0.0:9200
+ ~~~~~~~~~~~~~~~~~
    + CategoryInfo          : InvalidOperation: (System.Net.HttpWebRequest:HttpWebRequest) [Invoke-WebRequest], WebException
    + FullyQualifiedErrorId : WebCmdletWebResponseException,Microsoft.PowerShell.Commands.InvokeWebRequestCommand
```

But when I visit localhost:9200 I get the correct output
![Image of correct output](/images/screenshot_localhost9200.png "Screenshot of correct output")
So I'm unsure whether it is an error on my misunderstanding of cURL or something else. 

Moving on, I highly appreciate that Mr.Prakhar took the time to write out some code to demonstrate the flask app being unable to connect to Elasticsearch.

![Image of code made to output the failure to connect in the Foodtrucks application](/images\screenshot_pycodeOutput.png)

After commenting this out just to see what would happen, I also discovered that I had to comment out the `check_and_load()` function.

![Image of output when commenting out the check_and_load function](/images\commentingout_prakhar.png)

Wow! I have no idea what this means. I'll come back to it later.

