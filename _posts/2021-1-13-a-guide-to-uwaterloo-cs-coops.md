---
layout: post
title:  "A Guide to UWaterloo CS/Software Engineering Co-ops"
---


### Introduction

This article aims to serve as a comprehensive guide for navigating software co-ops/internships at the University of Waterloo. You may also find the advice here useful if you’re looking for software engineering internships and you study somewhere else. While many of these sections are entirely focused on software development, there’s also a lot of overlapping advice if you’re interested in data science or machine learning. 

At the end, I also include general thoughts about balancing your responsibilities at university because the entire process can be overwhelming, and it’s very easy to feel burned out.

Most of the content here is drawn from my own experience applying to and working at various tech companies in Canada and the Bay Area as part of UWaterloo’s Computer Science co-op program. There’s a lot to cover, so don’t feel the need to read all of it at once. I suggest skipping to whichever sections are most relevant to you right now, and bookmarking this page whenever you need to return to it in the future.


#### Contents:



1. [Crafting your resume](#crafting-your-resume)
2. [Acing the interview](#acing-the-interview)
3. [Looking for your first internship](#looking-for-your-first-internship)
4. [Finding your niche and deciding what you want to work on full-time](#finding-your-niche-and-deciding-what-you-want-to-work-on-full-time)
5. [Final thoughts about balance and enjoying the university experience](#final-thoughts-about-balance-and-enjoying-the-university-experience)
6. [Useful resources](#resources)


### Crafting your resume

<img src="/assets/coop-guide/resume-header.png" alt="drawing" class="center"/>

The first step to finding a good internship is getting an interview. For better or worse, with software co-ops at Waterloo, this mostly comes down to your resume. Referrals from friends who have worked at companies you are interested in can also be very helpful. Cover letters aren’t going to matter most of the time and you should generally avoid writing them unless the job specifically asks for it. There will be hundreds of applicants for most competitive jobs and recruiters generally won’t have the time to read a cover letter. It may be worth including for smaller companies if the job has few applicants and you have something very specific about you to convey.

Getting the resume right is much more important in the early stages of your co-op degree. Once you have a few internships at big-name companies under your belt, the brand names carry you and it becomes harder to really mess this up.

My advice on resume construction is to keep it simple. With larger companies especially, your resume may be filtered by non-technical HR employees who will spend less than 30 seconds on it. This means you need to be mindful of your bullet points and descriptions. keeping them short and to the point. Broadly, there are two things that matter for the content of your resume:



1. Describing what you did
2. Describing the product/business value of what you did

Consequently, it’s unlikely that the bullet point “Created a new gRPC-based microservice for Braintree payments processing” is any more useful than simply “Created a new microservice for processing payments”. If you can describe metrics around the throughput and scale of this microservice (e.g., if you mention that it handled 5000 requests/sec), then the latter bullet point is better still. Even if an engineer is reading your resume, you’re hardly going to be hired simply for your knowledge of gRPC or the Braintree API. The important thing to take away from that description is the fact that you created and owned a significant piece of the company’s technology. Try to avoid the fallacy of overemphasizing small libraries, frameworks, and APIs in your resume.

> Put yourself in the reader's shoes and constantly ask yourself whether or not a certain buzzword, technology, or statistic really adds meaningful new information

A good rule of thumb is to put yourself in the reader’s shoes and constantly ask yourself whether or not a certain buzzword, technology, or statistic really adds meaningful new information that might impact their decision to interview you. Knowledge of a broad and widely used technology such as AWS or C++ could indeed affect such a decision, depending on the job requirements, but it’s unlikely that something like knowledge of the Braintree API will. 

Statistics, in particular, should be used sparingly and only when you can really justify where they came from. If you’re mentioning that performance in some metric increased by 70% due to your new feature, make sure you can explain why that is the case. Did you run an A/B test or monitor CPU usage? A resume rife with statistics is likely to include some BS and recruiters are aware of this.

Another thing you should pay close attention to is design and formatting. Even with stellar content, is your resume easy to skim and read? (Remember, you should assume that your resume is going to be looked at for no more than 20-30 seconds before a decision). Avoid tiny fonts, tight spacing, and unnecessary blocks of color that distract from the content. Take out side projects and delete bullet points if you have to, but keep it legible. [This excellent article](https://medium.com/free-code-camp/how-to-write-a-good-resume-in-2017-b8ea9dfdd3b9) goes into more depth about formatting.

One final piece of Waterloo-specific advice: the education section of the resume should be at the bottom, unless you’re graduating soon and want to signal to the recruiter that you’ll soon be available for full-time opportunities. Since you’re applying through WaterlooWorks and your resume is included as part of a larger application package, recruiters already know where you go to school, what your program is, and what your grades are.

If you’re worried about the related problem of not having enough experience to add to your resume, refer to the “Looking for your first internship” section.

For reference, below are some resume examples:



*   [My resume](/assets/coop-guide/jashan-resume.pdf)
*   [A friend's resume](/assets/coop-guide/anonymized-resume.pdf) (anonymized for privacy)


### Acing the interview

Once you’ve created an amazing resume, it all comes down to the infamous technical interview. The style of the interview can vary significantly from company to company. In descending order of importance to the interview, there are 3 areas you need to think about:



1. Algorithms and Problem Solving
2. Systems Design
3. Miscellaneous Trivia and Software Knowledge


#### Algorithms and Problem Solving

Most of the time in technical interviews, especially with developer jobs, you will be asked to do some on-the-spot problem solving on a whiteboard. With remote interviews, you will probably be asked to write code or pseudocode inside a text editor to solve an algorithmic problem. Getting good at this part of the interview should be your primary focus. 

Fortunately, there is a plethora of resources dedicated to helping you prepare for this. The standard advice is to head over to [leetcode.com](https://leetcode.com/) and practice the hundreds of interview-style problems available over there. In my personal opinion, you should balance this problem-solving with a little more structure.

Mastering algorithms problems requires experienced knowledge of a vast array of data structures and programming techniques: from linked lists and recursion to trees and dynamic programming. To that end, it makes sense to focus on learning data structures and problem-solving techniques one-by-one rather than attempting problems related to completely different concepts while you are just starting out. 

<img src="/assets/coop-guide/ctci.jpg" class="center" style="width:30%;">

A book like _[Cracking the Coding Interview](https://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/0984782850)_ (which also helps with preparing for other parts of the interview), or video lectures from an online course like MIT’s _[Introduction to Algorithms](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/)_ (highly recommended) will help you structure your learning better. Pick whichever medium works best for you. Balance the theory with practicing related problems, and don’t try to rush it. Taking the time to understand each concept will help you retain the fruits of your practice long-term and ensures that you’re not scrambling to relearn everything over and over again when interview season rounds the corner. 

It’s important to not burn yourself out here, because the amount of content you need to learn while starting out can feel overwhelming. Recognize that it takes a long time to build this knowledge, and you should go as slow as you need to while balancing your other commitments. Even if you only learn 1 new concept every week, you’ll be poised to ace this part of the interview in a few months. Given that you have 5 whole years of co-op, this timeline is totally fine and well-worth the initial investment. 


#### Systems Design

While problem solving is often the main focus, many companies will also have a systems design round, usually on a whiteboard. If you’re applying for a backend position, you may be asked to design database schemas for a certain problem, or talk about caching and architecture. For front-end positions, you may be asked about how you would structure your UI and model for a hypothetical chat application. 

Naturally, it’s difficult to discuss these trade-offs and make these decisions without some firsthand experience. That’s why the best way to prepare for this stage of the interview, at least when you’re starting out in your co-op journey, is via side projects and exploring existing tools. It doesn’t matter if your project is something generic like a to-do list app, though you should definitely strive to do something _you _find interesting. Building something from scratch will teach you important concepts about software development and make you feel much more confident about both your own skills and this portion of the interview. If you’re applying for your first or second co-op, this will also give you something to add to your resume and talk about during your interview.

Once you develop a baseline understanding, you can also learn a lot about systems design through [blog posts](https://hackernoon.com/) and [articles](https://medium.com/) online. 


#### Miscellaneous Trivia and Software Knowledge

In addition to algorithms and systems design, you may be quizzed about general computer science and software knowledge. Can you describe, at a high level, [what happens when you type “google.com” in your web browser and hit enter](https://github.com/alex/what-happens-when)? What are the differences between a SQL and NoSQL database and what are the trade-offs? If you’re interested in data engineering, can you explain the differences and trade-offs between an ETL and ELT data pipeline?

The best way to learn about all of this is online articles and blogs, and I’d suggest making a consistent habit out of it. You’ll also come across many of these concepts in upper year CS courses (e.g. networks, security, distributed systems) but it isn’t worth waiting until then to learn about them. Basic CS knowledge is more than enough to get started. Undergraduate courses at Waterloo are designed to give you a basic understanding of databases or distributed systems, but won’t dive into more practical or niche areas that could be relevant to your career and important for your growth as a software engineer. This reading is hugely valuable to you outside the interview setting as well, and you should keep it up even if you’re not looking for jobs. 

Further reading:



1. [How the Web Works: A Primer for Newcomers to Web Development (or anyone, really)](https://www.freecodecamp.org/news/how-the-web-works-a-primer-for-newcomers-to-web-development-or-anyone-really-b4584e63585c/)
2. [Intro to Databases (for people who don’t know a whole lot about them)](https://medium.com/@rwilliams_bv/intro-to-databases-for-people-who-dont-know-a-whole-lot-about-them-a64ae9af712)
3. [A beginner-friendly introduction to containers, VMs, and Docker](https://www.preethikasireddy.com/post/a-beginner-friendly-introduction-to-containers-vms-and-docker)
4. [A Beginner’s Guide to Data Engineering, Part I](https://medium.com/@rchang/a-beginners-guide-to-data-engineering-the-series-finale-2cc92ff14b0)
5. [Hacker News](https://news.ycombinator.com/)


#### Communication and Presentation

While strong technical skills are a prerequisite to doing well in any interview, success also comes down to how you communicate and present yourself. All the technical knowledge in the world is useless if you have no way of conveying what you know to the interviewer and your peers in the workplace. The interviewer is also trying to use this time to assess whether or not you would be a good colleague to work with. 

<img src="/assets/coop-guide/presentation.jpg" class="center" style="width:80%">

With algorithmic problems especially, interviewers are just as interested (if not more so) in your ability to articulate your thought process as they are in your ability to produce a correct solution. You need to clarify all your assumptions before you start solving the problem, and talk through your solution as you’re coming up with it. This can seem difficult at first -- especially when all you want to do is remain quiet and think through the question for 5 minutes -- but you’ll get better at it with time. It’s a good idea to practice this with a friend, do mock interviews, and watch some examples of the [live interview process online](https://www.youtube.com/watch?v=XKu_SEDAykw). There are also upper year students who volunteer as practice interviewers every term. This information can usually be found on Facebook groups dedicated to mentoring (e.g. Tech+). 

Most interviews will also dedicate time for you to ask questions at the beginning or end, and you should use this to convey your interest in the job. Don’t forget to do your background research on the company beforehand. Asking about their product, technology stack, work culture, and what their top problems are is just one way to show that you know more about a company than their name. There’s often much more nuance to the quality of an internship than hearing anecdotal reviews from peers or Reddit, so make sure you collect your own data about the company. You want to gain as much information as possible so that you’ll be able to make an informed decision when you have to choose from multiple offers.

Finally, make sure you’re always honest about yourself and your knowledge during the interview. This applies to both talking about your past experience as well as answering technical and questions. If you don’t know something, communicate that or ask for a hint instead of trying to fake it. If you’ve seen a particular interview question before and know how to solve it already, tell the interviewer and ask if you should still proceed instead of pretending to solve it for the first time. Your sincerity will reflect positively.


### Looking for your first internship

In these early stages of your co-op journey, you (most likely) haven’t worked a software development job in the past, and are still familiarizing yourself with new software concepts for the first time. It may be difficult to populate your resume with relevant experience and skills, and learning algorithms may feel like a huge leap given your maturity with programming.

On the bright side, interviewers for more junior software engineering positions are mindful of this, and generally won’t ask you hard questions that require a deep proficiency with algorithms. You should instead focus more on developing your resume and learning practical skills that will be relevant to the job. To a great extent, this involves side projects and self-learning. Side projects boost otherwise sparse and empty resumes, give you something to talk about during the interview, and show the employer that you are capable of working on real-world problems -- which often differ considerably from assignments at university.

For your first co-op, you should aim to learn the basics of one or more areas of software engineering. Whether that involves front-end web development, data science, databases or something else entirely is up to you. Find something that interests you and get started with one of the many tutorials online. While you’re at it, learn how to use Git and create a [GitHub](https://github.com/) account if you haven’t already. 

Once you’ve completed a few tutorials and picked up the basics, it’s a good idea to design a more complex project of your own where you have to build things from scratch. This will solidify your understanding significantly. It’s one thing to copy/paste code from a tutorial but another entirely to write something from scratch. Your project doesn’t have to be new or groundbreaking, though it definitely helps if you’re particularly interested and excited by it. Even something simple like a Messenger bot that reminds you to drink water or a visualization tool that fetches and integrates data from different sources is worth pursuing. A good project will not only give you something to add to your resume and help you answer interview questions, but also teach you valuable skills that you will apply on the job and throughout your career.

If this still seems daunting, remember that learning and developing skills takes time. You have 5 years of university and 6 co-op terms, so don’t worry if you don’t find yourself incredibly knowledgeable overnight. Be patient, and manage your expectations. Unless you somehow have a lot of past experience, it’s unlikely that you will be chosen for the most highly coveted jobs that more senior students already have a difficult time securing. Make your applications accordingly. 

It’s also perfectly normal to fall back to the continuous round -- I personally know many people who were in continuous for their first several co-ops and ended up at amazing companies later on. The first co-op search is the hardest, so take comfort in knowing that things only get better from here.


### Finding your niche and deciding what you want to work on full-time

As you progress through your internships, you’ll soon come to realize that there are a lot of different roles and companies you could be working at, and the kind of experience that each of them provides varies widely. You may also, consciously or unconsciously, begin to specialize for particular roles (e.g., if you have done 4 internships writing mostly Python backend code). How do you make sure that you’re specializing in what’s right for you, that you’re working at a company that’s right for you, and most importantly, that you make the best decision when you have to commit to a full-time job somewhere?

Broadly, you can break this decision down into thinking about two things: the kind of work you want to do, and the type of company you work for.

The kind of work you do refers to your day-to-day tasks and the technologies you use on the job. Some different roles/specializations, including relevant links in case you want to learn more, are provided below:



*   [Front-end web development](https://medium.com/devtrailsio/beginners-web-development-guide-part-1-frontend-ca59f1877ec5)
*   [Back-end web development](https://medium.com/devtrailsio/beginners-web-development-guide-part-2-backend-fd466212dbfc)
*   [Full-stack development](https://medium.com/@crampeteb/beginners-guide-to-full-stack-web-development-347528b696e0)
*   Mobile development
*   [Dev ops](https://medium.com/taptuit/what-is-devops-fb3d044ef659#:~:text=DevOps%20%E2%80%94%20Put%20Simply,and%20at%20a%20faster%20rate.&text=It%20provides%20agility%20for%20developers,the%20appetite%20of%20the%20organisation.)
*   [Infrastructure](https://medium.com/timecampus/infrastructure-engineering-the-first-principles-9d7748e3b3fb)
*   [Data science/Machine learning](https://towardsdatascience.com/data-science-101-99e34bea86c)
*   [Data engineering](https://medium.com/@rchang/a-beginners-guide-to-data-engineering-part-i-4227c5c457d7)

When it comes to the type of company you work for, there are many different categories, and it is very important to get this right. Your experience is largely going to be shaped by the people you work with, how well you collaborate together, and how much you believe in the product. One way to think about a company is to ask yourself the following questions:



*   Is it a startup, a mid-market company, or a large corporation?
*   Is it building consumer software or enterprise software (or simply doing research)?
*   Am I impressed by the people who interviewed me, and do I feel like I will get a lot of high quality mentorship by working with them?
*   Do I feel like the work I will be doing is important?

Within enterprise software in particular, there are so many different domains and subdomains to think about (data logging/monitoring, internal tools, security tools, developer tools, API platforms etc.). Although I wouldn’t recommend focusing on one particular niche of enterprise technology unless you’re very convinced, I think it’s really helpful to build a mental picture of the landscape of things you could be working on. That way, whenever you get an offer from one of these companies, you have an idea of the problems they’re tackling and you can use this knowledge to weigh it against other options. 

There’s no best type of role or company for everyone and no one-size-fits-all approach that will help you decide what’s best for you. The beauty of co-op, however, is that you have 6 internships to try different things and figure out what’s important to you. If one of your long-term goals with co-op is to explore different kinds of positions and determine what you want to do full-time, then there are a few general principles that may be useful:



1. **Try to avoid repeating internships at the same role**, especially in the earlier stages of your degree. Even if you had a fantastic experience with your second or third co-op, chances are that there’s a certain type of role or company that you might still be interested in trying out. You’re also more likely to learn something new by working with different people and working on different problems than you are by returning to the same team that you’re already familiar with. In the worst case, you don’t have a great experience at your new job and you decide to return anyway for your later co-ops or full-time. There’s practically nothing to lose and a whole lot to gain.
2. **Bias yourself towards roles that are unlike anything you’ve done before.** If you’ve already done one or two co-ops in mobile development, for example, accepting another mobile position at a different company is less ideal than accepting a position where you’re doing something else entirely. You have 6 co-ops, so you should strive to learn as much as possible from each of them rather than treating them like full-time roles where you’re locked into a particular kind of work. The type of work you do day-to-day is also not the only factor you should consider when determining how much you will learn from another position. In general, some things you should think about are: \
    1. Your day-to-day role (mobile vs. front-end vs. back-end vs. infra vs. ...)
    2. The size and stage of the company (early stage startup vs. mid-market vs. enterprise)
    3. The domain of the company (consumer vs. enterprise software)
    4. The location of the job (it’s always great to explore new cities and places to live)

     \
By trying new things, you might be surprised by what you end up enjoying and learning. One of the most fruitful internships I ever did was by dropping engineering work altogether and working with the investment team at [8VC](https://8vc.com), a venture capital firm. Not only did it teach me more about software as an industry more than any other co-op, but it also deeply affected how I prioritize and evaluate different full-time opportunities.

3. **Seek out learning opportunities in new areas of software.** To find jobs in different roles and at different companies, you need to jump out of your comfort zone and learn about new technologies and how they fit together with what you know. If you’re mostly familiar with web development, it can feel unnatural to think about finding a co-op in infrastructure or data engineering, and you’re unlikely to learn anything meaningful about these new areas unless you intentionally try to do it. In the long run, doing this will help you appreciate the different challenges that engineering teams face, understand how engineering teams work together on various aspects of a product, and, most importantly, increase the pool of companies and positions that you consider. \
 \
You don’t necessarily have to spend hours doing tutorials or side projects. If you’re on a co-op term, you can ask other full-time employees what they work on and how it fits into the company. Reading technical blog posts and case studies will also give you plenty of context on the technical challenges and business value of these different areas of engineering. I especially enjoy engineering blogs from tech companies (e.g. [Netflix](https://netflixtechblog.com/), [Facebook](https://engineering.fb.com/), [Slack](https://slack.engineering/)). See the resources section at the end of this article if you’re interested in further readings.

At the end of every co-op, it’s also helpful to write down and articulate what you learned from the experience and how it impacts the kind of positions you will apply for later. For example, at the end of one of my internships, I determined that I might prefer working on enterprise software more than consumer software because I found the problems more valuable and technically interesting. During the following job search, it helped me filter my job applications better. Being explicit and consciously articulating these interests ensures that you’re able to take concrete actions based on your experiences.

Finally, remember to enjoy the process! The opportunity to do 6 different co-ops working in so many different roles (and cities!) is truly a gift, and -- in my opinion -- the single best part of studying at the University of Waterloo. You owe it to yourself to use this time to learn as much as you can and explore as much as possible rather than getting locked into a particular kind of work early on. This will help you make a better-informed decision when you eventually have to apply for and accept a full-time offer somewhere.


### Final thoughts about balance and enjoying the university experience

<img src="/assets/coop-guide/balance.jpg" class="center" style="width:70%;">

If there’s one thing I encourage you to take away from this entire article, it is to recognize that the 5 year co-op program is a long but deeply rewarding journey. Looking for jobs isn’t easy (especially now, during a pandemic). Learning algorithms and doing side projects isn’t easy. Having 6 technical interviews lined up in a week with 2 midterms and assignments isn’t easy.

With that said, you have 5 years to figure things out and no one expects you to have all the answers overnight. Especially in the early stages of the program, it’s natural to feel overwhelmed by everything you need to learn, and consequently overload your schedule and responsibilities to make sure you’re staying ahead. One of my biggest regrets early on was sweating too much by signing up for hackathons (which are terrible for your sleep/health, by the way!), enrolling in too many hard courses, while trying to do side projects and learn about new technologies in my free time.

We tend to overestimate what we can do in a day, and underestimate what we can do in a year. As long as you’re relatively consistent with your efforts, you shouldn’t need to be working all the time. Try to set hard boundaries around your work schedule to make sure that you’re setting aside enough time to rejuvenate. I, for example, refuse to work after dinner unless I have a deadline the very next morning. It’s also perfectly ok to lighten your course load early on in the term if you feel like you have too much on your plate (especially if the course isn’t a prerequisite for anything important downstream).

> We tend to overestimate what we can do in a day, and underestimate what we can do in a year.

Finally, don’t forget to enjoy the journey. Getting to travel to different cities and countries for co-op, and making new friends along the way, is amazing. Even with the pandemic right now, I hope you’re able to find some means of enjoyment, whether it be cooking a nourishing meal, learning a new instrument, or just sitting back and watching TV. If you’re early on in your program, keep in mind that the pandemic will pass and there will still be plenty of university for you to enjoy.

The past 5 years of co-op have been the most productive and enjoyable years of my life yet, and I hope you enjoy the journey as much as I did. If you made it all the way down here, thank you for reading and I wish you the best of luck with your program!


### Acknowledgements

Thanks to Richard Liu, Anubhav Srivastava, and Raphael Koh for reading early drafts of this article and providing their valuable feedback.


### Resources

Résumé Prep:



*   _[An Opinionated Guide to Writing Developer resumes](https://medium.com/free-code-camp/how-to-write-a-good-resume-in-2017-b8ea9dfdd3b9)_

Interview Prep:



*   _[Cracking the Coding Interview](https://www.amazon.ca/Cracking-Coding-Interview-Programming-Questions/dp/0984782850)_
*   _[MIT’s Intro to Algorithms](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-006-introduction-to-algorithms-fall-2011/)_
*   _[Leetcode](https://leetcode.com/)_
*   _[HackerRank](https://www.hackerrank.com/)_

Short blogs and articles to learn about new technology:



*   [How the Web Works: A Primer for Newcomers to Web Development (or anyone, really)](https://www.freecodecamp.org/news/how-the-web-works-a-primer-for-newcomers-to-web-development-or-anyone-really-b4584e63585c/)
*   [Intro to Databases (for people who don’t know a whole lot about them)](https://medium.com/@rwilliams_bv/intro-to-databases-for-people-who-dont-know-a-whole-lot-about-them-a64ae9af712)
*   [A beginner-friendly introduction to containers, VMs, and Docker](https://www.preethikasireddy.com/post/a-beginner-friendly-introduction-to-containers-vms-and-docker)
*   [A Beginner’s Guide to Data Engineering, Part I](https://medium.com/@rchang/a-beginners-guide-to-data-engineering-the-series-finale-2cc92ff14b0)

General reading:



*   [Hacker News](https://news.ycombinator.com/)
*   [Netflix Engineering Blog](https://netflixtechblog.com/), [Slack Engineering Blog](https://slack.engineering/), and the blogs of other tech companies
*   [Andreessen Horowitz](https://a16z.com/), for learning about the business of new technology

Some readings that I’ve recently really enjoyed:



*   [How Netflix Scales its API with GraphQL federation](https://netflixtechblog.com/how-netflix-scales-its-api-with-graphql-federation-part-1-ae3557c187e2) (highly recommend if you’re interested in GraphQL)
*   [The New Business of AI (and How It’s Different From Traditional Software)](https://a16z.com/2020/02/16/the-new-business-of-ai-and-how-its-different-from-traditional-software/)
*   [Every Company Will Be a Fintech Company](https://a16z.com/2020/01/21/every-company-will-be-a-fintech-company/)
*   [Kubernetes: A Love Story](https://medium.com/8vc-news/kubernetes-220878279b2f)
*   [Hasura Design Philosophy](https://hasura.io/blog/how-hasura-works/)
