# Learning New Technologies as a DevOps Engineer: Embrace Progress without Overwhelm 👏

 Here I want to about the challenge of learning multiple technologies and staying up to date with new ones in the DevOps field and how I personally manage not to be overwhelmed by it and make the learning process much easier. 💯

I hope sharing my experience and tips on this topic will be useful for some of you 😊


## Why it's overwhelming 🙉

Aspiring DevOps engineers often find themselves faced with a maze of technologies, all essential for embarking on their journey as Junior DevOps professionals. The entry bar is set high, and rightly so, as **DevOps revolves around crafting end-to-end processes** for software development and deployment, entailing a myriad of tools.

To thrive in this domain, it's not merely about grasping 5 to 10 technologies in isolation; it's about understanding how to seamlessly blend and integrate them to **build robust processes.** The synergy of multiple tools demands a holistic approach to learning.

Yet, this is just the beginning. The DevOps landscape is a constantly evolving realm, where novel technologies and concepts sprout incessantly, pressuring engineers to continually expand their skill sets. The velocity of change can be dizzying, making it challenging to keep an overview.

So, how do you strike the right balance? How do you avoid feeling overwhelmed while staying up-to-date with emerging technologies that can streamline your work, boost efficiency, and elevate your software development and deployment endeavors?

In this article, we will unlock strategies to navigate this dynamic landscape gracefully. From prioritizing essential technologies to cultivating a growth mindset, we'll delve into actionable tips to embrace the evolving nature of DevOps while managing the waves of innovation with confidence and ease. 🚀💡


# Separate Concepts & Tools

First of all, when we're talking about developments in the DevOps space, there are two main categories:

- the concepts 💡 
- the tools 🛠

And it's important to separate them. Concepts are the foundational basis of DevOps processes, they are guidelines to how things should be done. Therefore **understanding the concepts before learning the tools is super important.**

## Tools are just means to an end

It's also important to understand that tools are just means to an end. **Every tool is there to solve a problem or to serve some purpose.** Understanding the concepts helps you know what processes you have, what problems and challenges are in those processes. And when you have that as a basis, then you can start learning the tools that can actually solve those challenges or implement those concepts.

## CI/CD Example:
To give you some examples, before learning any DevOps tool you should actually learn the CI/CD concept first:
👉 What does a CI/CD process look like?
👉 What challenges does it have?
👉 What is its purpose? which is to release application
   improvements fast and in an automated way to the end users
👉 What does it include? What steps does it have? Like
   building the application, testing, deploying to development, to staging and so on:

**ADD Image-my-exp-1.jpg**

And then you learn the tools that implement this concept and help you achieve its goals.

So if you're just getting started in the DevOps field this will be the first step or the first concept to learn.

## Infrastructure as Code Example:
Another example would be, before learning any Infrastructure as Code tool, you should learn the Infrastructure as Code concept first. Again asking yourself:

- Why is it needed?
- What is its purpose? Like doing manual work versus automated code for infrastructure provisioning, because manual work is more effort. It has more mistakes, it is less transparent and so on.

And also understand what are the challenges of the Infrastructure as Code concept and then again you learn the tools that implement these concepts and you also understand how these different tools address those challenges.

So now when you're learning DevOps tools or you know a bunch of them already and the new tool comes up, your first question to challenge that technology, is to understand what problem does it actually solve and is that problem relevant for you? So you have a big picture of the concepts and the DevOps processes, because you learned the concepts first, so now you can easily fit each tool into that big picture by just understanding the main purpose of the tool on a high level. 🙌

**ADD Image-my**


## Use Cases - What problems does it solve?
🤔
So when I start learning a new tool, the first thing I want to find out is, not the cool features that it has or the cool UI that it provides or that it can integrate with 100 other technologies in the ecosystem or that it's super cloud native, Kubernetes native with automated workflow or other fancy stuff 🙄, but instead **my first question is what problem or problems does it solve and where does it fit on the big picture of DevOps.** 💯 The simpler the answer, the better.

And there are tools that solve one main problem, but there are also tools that solve multiple problems. In which case I want to find out, which one of those problems are the most important, the main ones, because a **tool is usually good at 1 or 2 things** and the rest of the use cases are additional bonus features. So in this step I investigate the use cases of the tool.

Once the problem is clear, then you can evaluate and measure how important or relevant that problem is to decide, whether you want to dig into that tool deeper and basically learn more about it.

## Also for established tools 
And for already established tools, like Kubernetes, Docker, Terraform and so on, which you anyways have to learn, it's still the first step. Because you may know that everyone is using Kubernetes and Docker, but you may not know why 🤷🏻‍♂️ and that's the first thing you should understand and find out when approaching any new technology.


## How does the tool work? 🧐
After that you can dive in the 'how the tool solves that problem'. There are many tools that address the same issue but in different ways.

So if you are learning an Infrastructure as Code tool like Terraform, you should find out how it does its job, like:
Terraform uses state management

- It has modules and providers
- It uses declarative approach
- It has a command line interface with its own commands
- How it connects to the cloud platforms that you want to provision infrastructure on
- And also how does it compare to alternative tools that you may already know about
So you learn about the core concept of the tool itself on a high level overview.


# Hands-On Practice with realistic use cases 👩‍💻
Once
✅ I understand the problem and the use cases of the tool,
✅ now I know why I'm even learning it,
✅ I also understand how it works theoretically
✅ so i know more or less how I could integrate it into my existing workflow processes.

Now it's time to get started and **actually use the tool, because the confidence comes from practice.**

## Learning with real use cases 🚀
And here is a super important thing to understand about practicing a tool hands-on. You should **always practice with an actual example use case**, something you can actually apply in real life projects.

So the way I do it is, I first define the actual simple, but realistic use case with the tool, because starting with hands-on practice without an example use case can be demotivating and confusing.

Let me give you some examples:

# Docker Example 🐳
If you want to learn how to use Docker, just take a simple application and dockerize it with Dockerfile to learn how this process works. Then think about how you can build and run this dockerized application. By implementing these simple steps you will actually learn much more than just randomly learning some concepts about the tool through the official documentation or some blog articles.

**So you create a use case like, I have a basic Node.js application:**
👉 I dockerize it
👉 I build an image
👉 Push it to the repository
👉 Then I run it and test that the application is accessible

And for each step you can learn how to do it and what are the Docker concepts related to implementing those steps 🚀

Later you can expand that use case. Like you want to add a database connection to your dockerized Node.js application and you want to run multiple Docker containers. So you learn about Docker Compose and how to use it 👍

# Kubernetes Example
Another example would be, if you're learning Kubernetes. Again think of a simple use case, like you already have a dockerized application with 2 other services. So you want to deploy all of them in Kubernetes with multiple replicas.

By doing just that one simple use case, you will already learn so much about how Kubernetes works and how to deploy applications in it and again you can expand on that use case and add more steps. 🙌

## Embrace lifelong learning 😎
As an IT professional, learning never stops, because the tech world is rapidly changing:

- new versions of the existing tools are being released
- as well as new tools are being developed all the time
So with the above techniques that I mentioned you will have a good foundation for quickly evaluating new tools, whether they are relevant for you and worth learning but also if you have a good understanding of a specific tool, you can easily learn the new features of that tool as well.

So it's also a mindset of lifelong continuous learning. ♾

## How to stay up to date? 🎯
Finally you of course need to be aware when a new version of a popular tool gets released or a new technology is becoming more mainstream and popular so you have to adopt that.

For that you also have many ways to stay up to date with industry developments, like:

- 🌐 you can follow some industry peers on social media accounts or blog platforms that basically post about these kind  of new developments
- 👥 you can join DevOps communities either online or offline communities, where people exchange this kind of information
- 🎬 or you can also subscribe to Youtube channels, many channels that make really great videos on DevOps trends as well
and much more ways like podcasts 🎤, newsletters 📩 and so on.
If you're interested, you will find a way to stay up to date that suits you.

