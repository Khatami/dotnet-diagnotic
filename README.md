# dotnet-diagnotic

Every software developer at some time or other has stumbled with an application that doesn’t perform well, and when it happens I find a lot of unfamiliarity about what steps to take. And that’s the reason I decided to write this post.  This post is aimed at people with no knowledge of how to profile an application using the .NET CLI tools and what should they look for when a possible performance issue arises. If you’re a performance veteran you can skip it.  I have built a containerized .NET6 application beforehand, this app has a few performance issues and we’re going to try to spot them.  The performance issues on this demo app are oversimplified and I’m sure that if you take a quick glance on its source code you’ll be able to spot them pretty quickly, but we are not going to do that, instead of that we’re going to use the .NET CLI diagnostic tools to profile the app and try to understand what is happening.  On a real scenario the performance issues will not be so easy to spot on, but the objective of this post is to serve as stepping stone for beginners, so when faced with a real performance issue you know the basic steps to follow.

https://www.mytechramblings.com/posts/profiling-a-net-app-with-dotnet-cli-diagnostic-tools/
