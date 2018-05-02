# Wei's Tips For College Students on Preparing Coding Interview
Tips for coding interview as college students based on my own experiences.

## Intro
The purpose of this article is not to show solutions for some particular coding questions. This is more like BEST PRACTICES for preparing a coding interview from writing a resume to attending coding interviews based my own experiences. I hope this can help.

Modified Date: 5.1.2018 
Status: v.1.2

## Table of Contents
  - [Resume](#resume)
    - [Keywords](#keywords)
    - [Experiences and Course Projects](#experiences-and-course-projects)
  - [Coding(Technical) Interview](#coding(technical)-interview)
    - [Coding Languages](#coding-languages)
    - [Books](#books)
    - [Online Judge](#online-judge)
    - [Online Forum](#online-forum)
    - [Communication Skill](#communication-skill)
  - [Knowledge Checklist](#knowledge-checklist)
    - [Basic](#basic)
    - [Advance](#advance)

### Resume
As there are so many guides about writing programming related resumes, I will only talk about two oblivious topics: Keywords and Projects.

Having a resume is the very first thing you need when applying for a full time or intern job in a tech company. As big name companies usually receive [millions](https://www.inc.com/michael-schneider/its-harder-to-get-into-google-than-harvard.html) of resumes every year, they will have some sort of machine/HR screening system to do the initial filtering based on keywords/GPA/school/major, etc. So this is quite important for one to have a resume that could pass the initial machine/HR resume screening.

While recruiters look for keywords, engineers usually look for technical details like algorithms, techniques and some niche skills. The projects/experiences section, with technical implementation descriptions, is another vital part of the resume and perhaps the most conclusive one. 

#### Keywords
For most of time, the initial machince/HR screen is inevitable. As some of you may know, if your resume is submitted as an internal referral, the machine screen may not apply to your resume but HR screen can also happen regardless your resume is an external or internal application. Most HR screen will focus on a list of keywords and if your resume doesn't have them, it could be filtered out. Some people call this [Buzzwords Screen](https://qz.com/229570/here-are-most-valuable-skills-in-americas-tech-job-market/). If you are looking for a CS related job, a resume with Electrical Engineering major is more like to be filtered out than an Electrical Engineering major with a specialization in Computer Science or Computer Science Engineering. I know this sounds unfair as I met a lot of people with different majors doing a great job in software/web development, but when the job market is crowded with applicants and the headcounts are limited, a company has to follow its rules to put CS major as its first priority.

Knowing this fact, wording becomes a vital part of your resume.

- If your major is Computer Science related(Computer Science Engineering, Computer System Engineering.....), BE EXPLICIT about your major. Don't use acronyms or jargons that only hands-on developers can understand, printing ink is cheap.
- If Computer Science is your secondary major or minor or your major has some specifications in Computer Science related topics, BE EXPLICIT about it in the major part of your resume, having the buzzword in your major title is much better than simply mentioning it in your coursework.
- If your major has nothing to do with Computer Science but you have done computer science related courses/projects, mention what Computer Science or Software/Web development work you have done in your resume education section.

Here is a list of discussion about Buzzwords, take a look :

- [Resume Buzzwords](http://web.augsburg.edu/strommen/websitedocs/Resume%20Buzz%20Words/computer%20science.pdf)
- [The most valuable keywords to have on a tech resume](https://qz.com/229570/here-are-most-valuable-skills-in-americas-tech-job-market/)
- [Software Engineer Skills List](https://www.thebalance.com/software-engineer-skills-list-2062483)

#### Experiences and Course Projects
For college students who don't have too many external working experiences(which will apply to everyone looking for their first job. Don't worry, nobody born with a software development job), education and course projects will play the biggest part of your resume unless you did lots of side projects.

No HR/Hiring manager is expecting a green college student to have experiences of building a Windows or Facebook. Don't be shy to mention your course projects in your resume even though it is just a homework or group project. All you need to do is having details in your resume where you can show your "engineering way" of solving problems. "Using a sorted hash map to reduce time complexity" is much more interesting than "wrote a class schedule app". Just keep in mind, it's more effective to elaborate your course projects than just put the title and a simple description of the courses in your resume. Your resume is not a mini version of your college syllabus. You should spend more words on explaining what you have done in a course project and the impact your implementation instead of just listing courses contents.

As long as you can detail your work/contribution/learning from a certain project, it is very valuable for their assessment.

### Coding(Technical) Interview
I guess this is the most crucial part of all. No matter how fancy your resume is, in the end, for most software engineer jobs there will be a coding interview. As far as I know, for some very senior software engineer position which is looking for candidates with 10+ years of working experience, the coding interview is still an inevitable part. So it is important for every engineer to build up and maintain a good coding interview skillset. 

#### Coding Languages
Lots of college students asked me for advice in choosing an primary interview language. For most technical companies, languages don't matter as long as you are familiar with one of the main languages. Although some companies(very rare) might be requiring a specific interview language (Bloomberg usually asks interviewees to code in C++), most of the cases knowing one major languages (C++/JAVA/C#/Python/JavaScript) is pretty enough to handle the situation and college students should all be fine as all schools will require them to learn at least one of major languages. When scheduling your interviews with your HR, you can ask them or they will usually ask you first about your language preference. 

The other question is how well you should know the language. I think as long as you know the basic syntax like for/while loop, class, variable, array, list and common operations including functions/methods(print/sum/abs..), casting, exceptions and basic OOP related things(class/interface/overloading/overriding), you should be ok. It is totally normal to make syntax errors during coding interviews. Most interviewers should understand and tolerate syntax errors as long as you are able to explain your thoughts with pseudo code and not make significant language specific logic errors(things like writing a pointer in JAVA or using {} instead of indention in Python). A good technical company should have their technical interviews focus on problem-solving skills, algorithm, smartness or even computer sciences but never on syntax details. 

Unfortunately, recently some companies will require their candidates to write compilable and runnable code on actual test cases(As far as I know Snapchat is doing this) which I personally believe is very stupid. The good thing is you can always ask the company if they will require so before attending the interview. If you know your interview is requiring you to write compilable codes during the interview you can pick a language you are most familiar with.

Here is an article I highly recommend you to read about interview languages:
- [Choosing a Programming Language for Interviews](http://blog.codingforinterviews.com/best-programming-language-jobs/)

#### Books
There are so many books you can read but I think the famous [Cracking the Coding Interview](https://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/098478280X) is pretty enough if you only have time to read one. Overall, this book is more like a guidebook instead of an almighty bible. As the competition is growing daily, lots stuff in this book have become either too simple or too-well-known-to-ask. For starters, I think you should definitely read this book (mostly focus on the coding questions) and build a clear understanding on

- **what data structure and algorithm are** 
- **what kind of coding question you will be asked during a technical interview**

However, don't spend too much time on reading this book as it's too well known and you still need to do real coding challenges instead of just reading. My preferred way of dealing with a coding interview question in this book is to look at the question and if you can not solve it or at least you think you can not solve it in an efficient way within 5 mins, go to the solution. This may sound frustrating (actually it does make people feel very frustrating), but trust me this is the most effective way to "crack" coding interview. As more solutions you have seen, you will gain more experiences or I will call it "common senses" on handling an algorithm question and eventually you will become independent enough to solve something similar all by yourself. 

#### Online Judge
Online Judge might be the handiest tool for preparing coding interviews as they offer real coding experiences and a whole bunch of fresh questions that you may actually face during an interview. I only used [LeetCode](https://leetcode.com/) but I also heard [LintCode](https://www.lintcode.com/) is also good. My general philosophy on doing Online Judge is it's not a competition of knowing the most interview questions but building up a systematical skillset. Your focus should be on a qualitative result not quantitative. I know a few engineers who don't even know the existence of LeetCode or LintCode but they can nail every single interview and I also know some candidates who did every single question in LeetCode but still have difficulty getting an offer. In short, when practicing in Online Judges, focus on what you are actually learning rather than how many questions you have solved. 

Here are my advice based on my experiences about using LeetCode:

1. Reading through Cracking Code Interview book to know the all common things about data structures and algorithm, if you can answer following questions you are ready to proceed:
    - Can you write a quick sort and what is the time complexity?
    - Give an example of using DFS to solve a interview question 
    - Give an example of using BFS to solve a interview question 
    - Write a double-linked list
    - What is the difference between Stack and Queue 

2. As you started solving questions one-by-one, applying the strategy as I mentioned before about reading the book: 
    
    - **Step1**. Look at the question, try to come up with a good and efficient idea (not the actual code solution, just thoughts) within 5 mins. If you have no confidence in your idea, go to Step 4. If you believe your solution could work start coding.
    
    - **Step2**. If you can not finish your code solution within 20 mins, go to step 4
    
    - **Step3**. No matter if your solution passes the Online Judge or not, go to step 4
    
    - **Step4**. Google the MOST STANDARD(EFFICIENCY AND SIMPLICITY) solution you can find and ask yourself: 
        - **What kind of algorithm does the solution use?** 
        - **What is the time/space complexity?** 
        - **Do you think this solution is better than yours(If you have one) or not? Why?**
    * These steps help you to gain more out of solving a problem. A common problem lots of people have, especially those focus on quantity, is to have a very limited knowledge gain. If your goal is just to pass the Online Judge, you are missing the point in a big time.

3. For some algorithm solution(Dijkstra, heap sort, trie, or even quicksort), you may have difficulty fully understanding it, then try to memorize the solution template and practice writing from memory. I was once having difficulties writing a 100% correct heap sort including insertion/deletion/search, so I memorized it (about 50 lines of python code) and eventually, it helped me on fully understanding it.

4. For Dynamic Programming, my advice is don't worry too much about it. As you may know, lots of people including myself consider DP as the most difficult part of the algorithm but it is actually not that bad in technical interviews. Recently years, lots of company start to avoid DP in interviews as a DP question cannot help the interviewer to assess candidates. Understand most easy/medium DP questions from OJ is enough. Don't waste your time in hard DP question, this is about cracking the interview, not algorithm science.

#### Online Forum
There is a lot of online forum where people talk about interview experiences and particular interview questions. Spending few minutes a day on them could be quite beneficial. The one I used the most is [1point3acres](https://www.1point3acres.com/bbs/) where most contributors are Chinese and you can get lots of useful info and also share your own experiences. Another good place to go is [GeeksforGeeks](https://www.geeksforgeeks.org) where recently it got some major updates and has become a very professional coding interview preparation community. As most of the Chinese students would prefer 1point3acres as it is mainly written in Chinese, I strongly encourage you to take a look at GeeksforGeeks for 
    
- **Getting familiar with understanding/discussing your algorithm questions IN ENGLISH.**
- **Reading well formatted and professional articles about solving an algorithm problem in ENGLISH.** 
    
Most posts I found in 1point3acres are more like casual chats and it is not easy to systematically understand a solution thru those posts but there are lots of well-written articles on GeeskforGeeks where posters show their step-by-step thoughts with lots of serious comments to help. 

For preparation, you should spend more time on online forums instead of online judge sites when it's getting closer to your interview date.  

#### Communication Skill
Based on what I've seen for the past 5 years, lots of candidates are struggling with poor communication skills. I have seen some candidates who believe they showed the correct solution in the interview but still failed the interview. The reason is pretty simple: the interviewers cannot understand candidates' solution or the way they tackle the question as candidates don't know how to clearly explain their thoughts in Enligsh. If you think technical interviews and programming are only about typing and coding, you are totally wrong. It is far more important to verbally express your thoughts and problem-solving skills than just writing your code. Interviewers are looking for ways they can assess your abilities as a day-to-day working programmer and if you don't talk them through your solution you are not offering enough materials to your interviewers to write their assessments. 

Here are few suggestions for building up your communication skills:

  1. Practice explaining your solution in English. This is a very oblivious point that lots of people missed in their preparation. No matter how excellent your code solution is, you will need to explain your code to your interviewers so I highly recommend you practice explaining your solution verbally while solving it. It may sound a little bit silly but you will gain a lot from doing this. 

  2. Get a good amount of feedback regarding your communication skills from someone with whom you interact regularly or who are working in the industry. Try to book your TAs/professors' office hour for doing some communication training where your focus is on explaining your solutions and thoughts and ask them to correct or refine your language. 

  3. Attend interviews as many as possible even for companies you are not considering at all or do mocking interviews from online websites and school job fair events. The more interviews you had, the more experiences you accumulated.

### Knowledge Checklist
Below is a table of key concept/algorithm/data structure you should be familiar with in a certain level: 
 - Concept:  Know the mechanism and Time/Space compliexity
 - Use Case: Know why and when to use
 - Implementation: Be able to code the implementation for solving a (Easy/Medium/Jard based on LeetCode classification) question

If you can match this requirement with good communication skill you will be able to pass most tech companies' full time position interview.

##### Basic
|              Topics             | Concept | Use Case | Implementation |
|:-------------------------------:|:-------:|:--------:|:--------------:|
|     Array/Hashmap/Dictionary    |    X    |     X    |      Hard      |
|             Pointer             |    X    |     X    |      Hard      |
|    Single/Double Linked-List    |    X    |     X    |      Hard      |
|              Queue              |    X    |     X    |      Hard      |
|              Stack              |    X    |     X    |      Hard      |
|           Binary Tree           |    X    |     X    |      Hard      |
|            Buble Sort           |    X    |     X    |     Medium     |
|          Selection Sort         |    X    |     X    |     Medium     |
|         Merge/Quick Sort        |    X    |     X    |     Medium     |
|         Topological Sort        |    X    |     X    |     Medium     |
|          Tree Traversal         |    X    |     X    |     Medium     |
|          Binary Search          |    X    |     X    |     Medium     |
| Depth-first Search/Backtracking |    X    |     X    |     Medium     |
|       Breadth-first Search      |    X    |     X    |     Medium     |
|            Recursion            |    X    |     X    |     Medium     |
|              Greedy             |    X    |     X    |     Medium     |
|          Divide Conquer         |    X    |     X    |     Medium     |
|         Bit Manipulation        |    X    |     X    |     Medium     |
|    Directed/Undirected Graph    |    X    |     X    |     Medium     |

##### Advance
|              Topics             | Concept | Use Case | Implementation |
|:-------------------------------:|:-------:|:--------:|:--------------:|
|      Minimum Spanning Tree      |    X    |     X    |                |
|        Shortest-path tree       |    X    |     X    |     Medium     |
|               Trie              |    X    |     X    |     Medium     |
|          Union Finding          |    X    |     X    |     Medium     |
|               Set               |    X    |     X    |     Medium     |
|        Binary Search Tree       |    X    |     X    |     Medium     |
|              B-tree             |    X    |          |                |
|          Heap/Heapsort          |    X    |     X    |     Medium     |
|           Segment tree          |    X    |          |                |
|      Directed Acyclic Graph     |    X    |     X    |     Medium     |
|    Detecting Cycles in Graphs   |    X    |     X    |     Medium     |
