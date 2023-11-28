# Frank's note on DEA-C01 Exam

*27 Novembre 2023*

Phew! Just finished up taking the AWS Certified Data Engineer Associate exam here, as it is now available in its beta form. Because it's a beta, it's 85 questions instead of the usual 65, and you'll need quite a bit of mental stamina going into it! After a half-hour-long process getting checked in (due to some glitch with Pearson VUE and my microphone, and the inability of their app to take a focused picture of my ID), I spent a full 2 1/2 hours on the exam itself. I can't tell you anything about the actual questions of course, but I will share my higher-level impressions - and what I've learned in terms of gaps I need to close in the content of this prep course.

First of all, this is no ordinary associate-level exam. If you took AWS's practice exam online and said "wow, that's not associate-level," well, the real exam is even more challenging than that. Expect lots of very complex scenarios involving many different services, where you need to solve a problem while optimizing for some specific thing. There were only two or three questions in the whole exam I would describe as easy. Don't coast into this thinking "oh, it's only an associate level exam - it won't be hard." It is every bit as hard as the data analytics specialty exam it is replacing; maybe more so, as it covers a wider range of services and technologies.

I was also surprised that the exam really did cover most of what was in the exam guide, as expansive as the guide is. It's no idle threat that you are expected to know SQL and be able to debug subtle problems in complex queries, and even services I didn't really expect to see on the exam (such as API Gateway and some legacy Hadoop stuff) really did turn up. If it's in the exam guide, it's fair game (and then some.)

Devtools, however, did not play a prominent role in the questions I received. Although the exam guide tells you to know all of AWS's developer tools and the intricacies of git, I would focus on that the least.

The questions themselves however seemed pretty well written, complex as they are. There were only a couple where I felt they were worded in an ambiguous manner that led to more than one potentially correct answer; but I suppose it's the purpose of a beta exam to uncover those things.

Anyhow, here's my list of things I'll be adding to this prep course in the very near future:

- Glue Workflows - you need to know about this in a fair amount of detail. This is the main gap I need to fill in this course.
- Even more depth on SQL
- Even more depth on Redshift, including its system tables and views
- Even more depth on Glue DataBrew, including some specific transformations
- Even more depth on Step Functions and its state types
- EBS elastic volumes
- More on EC2 instance types, including Graviton
- Using "Create Table As Select" 

Those are topics you may want to read up on yourself if you're taking the exam within the next week or two, before I have a chance to add new content on them. The good news, however, is that the vast majority of the questions involved things we explicitly cover in this course already.

While the exam does not expect you to remember specific numbers or prices for anything, the level of depth it expects of you is very surprising for an associate-level exam. Don't make this the first AWS certification exam you take; it's one you want to work up to.

Best of luck on the exam! And as always, thank you for having me along on your learning journey.

Frank Kane