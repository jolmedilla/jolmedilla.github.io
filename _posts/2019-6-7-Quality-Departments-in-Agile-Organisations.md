---
layout: post
title: What could be the role of a Quality Department in an Agile Organisation?
---

Recently I had an interesting chat with my good friend and esteemed colleague Javier Garzás (if you can read Spanish don't miss his [Blog on Agile](http://www.javiergarzas.com)). He is renown Agile Coach and author in the Software Development area with an impressive CV. We were talking about a pervasive problem he encounters in a huge percentage of the companies he helps to transform in Agile organisations, that of having a Quality Department, understood as the department that makes sure that everyone is working the same way in their projects across the organisation. 

This is something very common in large organisations and has a long history dating back to the 80s. Many customers still ask for certifications such as ISO 9001 or even now Agile ones. As Javier was telling me, he gets contacted by companies thar are interested in getting an Agile certification rather than being Agile. And we both have experienced that shocking oxymoron of a company Quality Department standardising their Agile process. And let me be clear about what this mean: a group of people who is not involved in delivering anything to any client, who is not part of any software development team, writing a set of documents that describe ceremonies, templates of documents that must be produced as a result of the project by the so called Agile teams and a set of rules for when and how documents and actions must be written or performed. And this same group of people that has written the *ACME Standard Agile Process* will audit agile teams to make sure there is written trace of the process. In this respect I have been involved in kafkaeske situations in which and auditor has asked my team for the Product Plan document or what documentation where we generating for the tests.

The prevalent culture in companies that have this type of Quality Departments is based on two pillars, documentary evidence and auditting, both interrelated. But let's get clear about this: what is the rationale for a Quality Department? Well, this of course responds to a problem that is more than 40 years old, that of not being able to predict the outcome of software projects, the infamous *Software Crisis*. As a result of that famous NATO conference in 1969 some people in the industry came with the idea of applying the knowledge accrued in the car manufacturing industry to Software production to make it **repeatable** and thus **predictable** and **reliable**. How do you make something repeatable? By creating a set of easy to follow steps or procedures almost in the form of a recipe or an algorithm so that if two different persons or teams apply the same exact process to two different inputs (project in the Software industry case) we will obtain results that are comparable, in that way if I did a previous project with a similar input in the past and I apply the same process the duration and results can be predicted. Assuming all of this is true, well, then I must make sure that everyone in my company follows the same procedures and I will evolve those procedures with time to adapt them, make them more efficient and economical and obtain better results in all projects as I evolve. Ok, how do I make sure everyone does the same things? If I am a 1970s or 1980s office animal, my instinct tells me that, given that my fellow inmates, sorry, coworkers, are cheaters I will ask of documentary evidence, an evidence that must be in close relationship with the procedures to produce software that I want everyone to follow. And, at the time, that documentary evidence and the way in which the industry thought software had to be produced were clearly related if you think about it, it was the golden era of SSAD, Waterfall and the like, so you needed to have a design before coding and testing, what more natural than having a Design Document and before that a Requirements Document and what more natural than make sure we have not forgotten any of those requirements when we deliver by way of having a Traceability Matrix Document and so on. Thus we only need to add a few extra documents to leave some evidence that we were following project management company procedures such as periodical risk assessment, status reports, meetings with customers, internal meetings, etc., and voilà, auditing made easy! Now I am sure you follow the right steps by seeing that you produced a document for each meeting and each of the project phases (remember, each project phase in Waterfall produces an output that is an input for the next phase and many of those outputs are documents and only one is the final software). So now we as a team produce both documents and software, our mandate is to follow the procedures and trust that someone else has designed them efficiently, we are not paid to think nor to change them, at least during their day to day application, there is a department for that, a department that is freed of the contaminating contact with everyday projects. 

And now back to my conversation with Javier, here he is, as Carl Sagan's apple landing on a planet of two dimensional polygons trying to explain to them what the third dimension is, that is, how to become Agile teams. As in the Cosmos' metaphor the polygons adapt what they see, a three dimensional figure, the apple, to their vision and therefore they see the two dimensional print of the apple on the surface of their planet, so that Quality Deparments try to adapt Agile to their world. At the end of the end, it's yet another methodology so we must be able to write procedures to follow it and templates to generate documents that leave documentary evidence. They have not made the big leap forward, the paradigm shift. The centre of the Agile philosophy is the customer, and what the customer wants and what he pays for is, in our case, software, just plain, running, reliable software. It is the team what produces software and the team is made of people. Client, people and running software, forget about the rest. First of all there is no Agile Methodology, there is no magic formula, there is no single recipe for all teams, each team must find its own way of working. But they must show running software with new value for the client in every Sprint. That's the core, that's the way you see they are Agile.

My good friend Javier, being an optimist as he is, told me then:
> I still think those Quality Department people can be recycled to the new paradigm, but how? What can they do in an Agile organisation?

Well, I was thinking about this for several days and finally I came up with a sensible answer, an answer that came to me when someone else asked me the following question:
> How do I make sure that my teams in the organisation are being Agile and not just simply using it as an excuse? How do I make sure they are doing what they should?

Well, this is what this person asked me, I know the question is a bit old fashioned but it contained a grain of truth. I realized that the answer had been in front of me all the time. In fact, there are already many people doing what a Quality Department could do internally, that is, make sure they produce software and that they customise the Agile Framework to their needs along the way. These Quality Department ask for evidence that they do the Agile ceremonies, it does not have to be documentary evidence, you can do audits, of course, but why not go to the ceremonies as an audit in itself? What does an Agile Coach do? He goes to your daily standups, to your retrospectives, to your demos, to your grooming and planning sessions, etc. An Agile Quality Department should in fact be an internal Agile Coaching Team of sorts. Here is my list of things they should do:
* Go randomly to daily standups, demos, retrospectives from different teams
* Make sure that every team has some kind of CI a minimum, better if they also have CD. But not prescribe a given technology or any specifics
* Make sure every demo shows running software that increases value and that is automatically generated and possibly automatically installed from CI/CD
* Make sure there is no powerpoint or vaporware in demos
* Make sure there are tests, not by having any kind of documents, but by seing coverage percentages that the CI produces. But again, each team must be free to use whatever coverage measuring tool they like in their CI.
* Make sure there is a Backlog and a Sprint Backlog with User Stories that have a relation with what is been shown in demo

This is a basic list, add what you like and makes sense within the Agile Framework, but do not include documents.

Does this answer your question, Javier? And you reader, what do you think?