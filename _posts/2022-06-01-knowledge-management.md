---
title: "Digital garden: Knowledge Management"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - infosec
  - knowledge management
  - data visualisation
---
# Introduction
I would like to give you the immediate problem and solution statement as to why knowledge management is a good thing, but I can't.

We will start off with a small personal story and a scenario where we identify the underlying issues.

This in order to understand why I'm talking about the concept of knowledge management in the first place.
Along the way you and I will discover the problems many organizations face, and we will spot the usecases.

# Story Time

During my very first job in a small company I learned tons of stuff, but that shouldn't surprise anyone as it was the first time I was working in IT.

A lot of the problems I faced were brand new to me, but not to my colleague, they ranged from simple to complex.
When trying to solve these problems, my colleague who had experienced these before was able to provide me with resources.

These resources proved to be valuable as they contained the answer to the problems, but there was something odd with them.

It took me some time to actually figure out where the answers were, as I had not experienced the problems themselves and I was just provided with the answer.

There were other times that my colleague knew about a solution, but could not remember it as they had noted it down somewhere and consequently lost it. 

When asked to provide his documentation, I was given a bookmark structure that led to 100s of webpages!
Hardly a way to actually document something but in it there was logic and reason.
They were effective to their purpose, for the person who created the structure, as they knew where to look for links where to find answers.

I didn't realise it at the time, but this was effectively a knowledge management solution, not a good one , but it was one.

# Organisation size makes a difference?
Now imagine that this took place in a bigger organization, and you are working on a bunch of different projects.
Most of these projects are dependent on the work or the support of people spread across different teams each with their own tasks & responsibilities.

These people have to work together to solve problems that impact all of them, a datacenter outage for instance.
Given the nature of big organizations and people within them, there is good chance that communication doesn't always go 100%..

So in all likelyhood you end up with people partially collaborating with each other. Resulting in people trying to resolve an issue from different points of view and discovering the same solution multiple times over a period of time.

![com_broken](../../assets/images/com_broken.png){:style="display:block; margin-left:auto; margin-right:auto"}

A more common way of phrasing this is silo's, they are almost everywhere and they can exist between teams and within teams.

It might be beneficial that people share knowledge on the things that involve their operational work to prevent such further issues.
But surely there is documentation to address these issues?

Documentation is an entirely different story, it shouldn't surprise you that when you request documentation you encounter any of these:
- "Enter name of old colleague here" knew, but they left some time ago and there was no proper handover
- Yes we have some network designs lying around, I think they are on sharepoint, but don't ask me which one.
- Here is a bookmark to the sharepoint, if you want to update it, send it to me as I am the only one with rights to modify and I don't know how to change it.
- I think it's somewhere on our confluence page, you have to use the old confluence, not the new one, as we haven't migrated everything yet, so the documentation is spread here and there. Now that you mention it some of it might be in that project folder from 2 years ago, we should look into moving it.
- Our team exclusively stores documentation on our gitlab and no you are not allowed to access it.

In short the problems with documentation can be summarized to:
- Documentation exists everywhere and nowhere
- Not centralized
- Either no structure or too much structure
- Out of date
- Team is not supportive of it

Knowledge management within an organization is very cumbersome, and in the case of operational knowledge it is a daunting task.
I myself have failed at this numerous times but I did learn the following:
- Put efforts on technical knowledge
- Find people that are willing to participate
- Organization needs to be aware
- Note down the things that people can directly profit from

So how is knowledge management going to solve this?
Considering the above, we are going to put our focus on technical knowledge, aka learning about technical topics.

This also entails that we move away from the concept of documenting to taking notes.

As far as learning goes, acquiring knowledge in certain topics can be difficult, especially when you don't have someone to guide you.

## Problem whilst learning you say?
How many times can you recount the following situation:​

- Find something interesting and you want to pursue it​
- Gather learning material(s)​
  - Did you get the right ones?​ Are there any others?
- Stumble upon a concept which is familiar
  - You get a feeling this could be connected to something​
- Maybe someone else knows it? ​
  - Who do you contact?
- Get side tracked from the original interest in an attempt to contextualize/categorize it​
- Get overwhelmed as you reassess your learning material and the scope of it all​

If you have pursued any interest in any field or any area of expertise, you have encountered one or multiple of these statements.

This is where knowledge management comes in.
​
## How do we address the problem
We are in need of a application that holds  knowledge/notes, and it has to follow certain rules.

### Centralized
As we described earlier, it only causes discomfort if knowledge is spread across different solutions.
This goes both ways if it is for you personally or for a organisation.

### Flexible structure
Generally a flexible structure is more preferable, it needs to give you the tools to design it in the way you want.
It allows for groups and individuals to still use their own structure when they want to.

### Visual overview
Which sounds more appealing to you? 
- Textual description of a technical process.
- A video or pictorial representation of that technical process.

Visuals hold more appeal than plain text does, they help learners grasp concepts more easily.

This also goes for an overview of the things you have learned, it showcases the compounded knowledge that is written down.
It helps to build links between different concepts, which are related to each other.
![connections](../../assets/images/connections.png){:style="display:block; margin-left:auto; margin-right:auto"}

### No overhead
Generally speaking, overhead is the extra work required to set up and perform in order to do the work you actually want to do.
The solution we need should negate this, if someone wants to start, they can just start.

### Turning Known unknowns into Known knowns
Not knowing of the page's existence should have no impact on finding it.
You are not supposed to go through an entire directory structure to find a certain page.


# Obsidian
Obsidian is a note-taking and personal knowledge management solution(PKM).
The most powerful feature of this solution is it lets you transform a collection of  text files into a rich network of linked thoughts.

![obsidian](../../assets/images/obsidian-logo.png){:style="display:block; margin-left:auto; margin-right:auto"}

Obsidian’s data is stored in a local folder of Markdown files. 

The app’s powerful linking and backlinking features turn these separate files into a knowledge base that operates as your second brain.

## Why create a PKM?
PKM is a set of processes, individually constructed, to help each of us make sense of our world, learn more effectively, and contribute back.

A tool like obsidian facilitates you to create such knowledge management system, keeps track of everything you have acquired, stored and processed.​

### Why obsidian and not a different notes app?​

Obsidian’s most powerful feature is contained in linking notes and creating connections between different notes​.
Giving you an overview of every link that exists between different notes, potentially giving you new insights.

Below is a short summary of the [landscape](https://nesslabs.com/the-state-of-personal-knowledge-management) that exists in this knowledge management space.
![pkm_landscape](../../assets/images/landscape_pkm.jpg){:style="display:block; margin-left:auto; margin-right:auto"}
<!--more-->

# Usecases
## Unknown documentation
Documentation can exist in a flat structure or a hierarchy with multiple levels.
Obsidian allows you to view all of the existing pages through the visual overview.

There exists a arrangement of different types of links and tags at your disposal, allowing you to quickly search through all of the pages.

## Breaking silos
The word 'Silo' usually has a negative connotation but this is not what is meant.
People can be excluded from certain topics or fields because of a number of reasons.

- Barrier of entry is too high
- Starting with wrong information
- Going into the wrong direction
- ...

PKM has the potential to eliminate these things and allow for more people to connect & learn.

## Who you gonna call?
Ghostbusters!

No but really, it is often hard to identify people who are more knowledgeable on a subject.
Depending on the size of the organisation it can be hard to reach out to others.
People who contribute to a PKM will be easily recognized by others and it's an incentive to work on it.
![pkm_compound](../../assets/images/pkm_compound.gif){:style="display:block; margin-left:auto; margin-right:auto"}
Those that contribute will learn more & their network will grow along with it as people come to them with questions. 

## Connect people
Thanks to covid people are no longer located in one singular place, they are everywhere which comes with a challenge.
![pkm_team](../../assets/images/pkm_team.gif){:style="display:block; margin-left:auto; margin-right:auto"}
Learning brings people together, so contributing to a PKM is an ideal way to do that.
Remote working and remote teams are no longer a thing of the past.

## Knowledge visualization
The unique thing about pkm and obsidian in particular, it allows us to see what we have learned.

![pkm_overview](../../assets/images/pkm_full2.gif){:style="display:block; margin-left:auto; margin-right:auto"}

Reflecting on the things that you have learned and to see where things are headed towards is a great indicator for knowledge development.
It displays the strengths and weaknesses, the knowledge that was gained over time and where we are going.

## Promoting collaboration
Reaching out to others will be more straightforward as you know who to reach out to.

You will automatically reach out to someone if they have experience on the topic you are interested in.
This goes for personal development or project based tasks.
![pkm_link](../../assets/images/pkm_link.gif){:style="display:block; margin-left:auto; margin-right:auto"}

## Learning paths
  builds training trajectory
  links to training resources
![pkm_learn](../../assets/images/pkm_learn.gif){:style="display:block; margin-left:auto; margin-right:auto"}



## Spot double work 
More often than not, teams will work on similar tech and they will have an overlap in work.

They will repeat the research and hence experience the same struggle when dealing with unknown problems.
It is more profitable for both the teams and the organisation that this kind of work is avoided.
