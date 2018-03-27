# Wei's General Suggestions For College Students on Preparing Coding Interview
A simple general guide for college students to prepare coding interviews based on my own experiences.

## Modified Date: 3.26.2018 ##
## Status: Draft

## Table of Contents
  - [Preparation Strategy](#preparation-strategy)
    - [Resume](#resume)
      - [Keywords](#keywords)
      - [Education and Course Projects](#education-and-course-projects)
    - [Technical(Coding) Interview](#technical(coding)-interview)
      - [Coding Languages](#coding-languages)
      - [Books](#books)
      - [Online Judge](#online-judge)
      - [Online Forum](#online-forum)
      - [Communication Skill](#communication-skill)
  - [Knowledge Checklist](#knowledge-checklist)
    - [Basic](#basic)
    - [Advance](#advance)

## Preparation Strategy
Again, the purpose of this article is not for showing how to solve a specific coding problem. This is more close to a roadmap for preparing a code interview from writing resume to attending onsite interviews based my own experiences. I hope this strategy could help.

### Resume
Having a resume is the first thing you need to do when apply for a full time or intern job. As big name companies usually receive [millions](https://www.inc.com/michael-schneider/its-harder-to-get-into-google-than-harvard.html) of resumes every year, they will have some sort of machine/HR screening system to do the intial filtering based on keywords/gpa/school/major,etc. So this is quite important for one to have a resume that could pass the first round machine/HR resume screen.

#### Keywords
As some of you may know, if your resume is submitted as an internal referral, the machine screen may not apply to your resume but HR screen may also happen regardless your resume is an external or internal application. Most HR screen will follow a list of keywords and if your resume don't have them, you could be filtered out.Some people call this Buzzwords Screen. If you are looking for a CS related job,a resume with Electrical Engineering major is more like to be filtered out than a Electrical Engineering major with specialization in Computer Science or Computer Science Engineering. I know this sounds unfair as I met a lot of people with different majors doing great job in software development, but when they job market are crowded with appliers and the headcounts are limited, a company has to follow its rules to put CS major as first priority.

Knowing this fact, wording becomes a vital part of your resume.
- If your major is Computer Science related(Computer Science Engineering, Computer System Engingeering.....), be really really really explicit about your major. Don't use short names, printing ink is cheap.
- If Computer Science is your secondary or minor or specifications, still be explicit about it in the Major title part of your resume, having the word in your major title is much better than simply mentioning it in your course work.
- If your major has nothing to do with Computer Science but you are looking for one, metion what Computer Sciense/Software development work you have done in your course projects/job experiences/side projects,etc.

Here is a list of discussion about Buzz Words, take a look if you have time:

- [Resume Buzz Words](http://web.augsburg.edu/strommen/websitedocs/Resume%20Buzz%20Words/computer%20science.pdf)
- [The most valuable keywords to have on a tech resume](https://qz.com/229570/here-are-most-valuable-skills-in-americas-tech-job-market/)
- [Software Engineer Skills List](https://www.thebalance.com/software-engineer-skills-list-2062483)

#### Education and Course Projects
For college students who don't have too many external working experiences(which will apply to everyone looking for their first job. Don't worry, nobody born with a software development job), education and course projects will play the biggest part of your resume unless you did lots of side projects.

No HR/Hiring manager is expecting a green college student to have experiences of building a Windows or Facebook. Don't be shy to mention your course projects in your resume even though it is just a homework or group project. Just keep in mind, it's more effective to elaborate your course projects than just put the title and contents of the courses in your resume. Your resume is not a mini version of your college syllabus. You should spend more words on explaining what you have done in a course project instead of just listing courses contents.

As long as you can detail your work/contribution/learning from certain project, it is very valuable for their assessment.

### Technical(Coding) Interview
I guess this is the most crucial part of all. No matter how fancy your resume is, in the end, for most software engineer jobs, there will be a coding interview, or technical interview. As I know, for some very senior software engineer position which is looking for candidates with 12+ years of working experinece, coding interview is still an inevatable part. So it is important for every engineer to build up and maintain a good coding interview skillset. 

#### Coding Languages
Lots of college students asked me about what they should do in choosing an interview primary language. For most technical companies, languages don't matter as long as you are familiar with one of the main languages. Although some companies(very rare) might be requiring a specific interview language (Bloomberg usually asks interviewees to code in C++), most of the cases knowing one major languages (C++/JAVA/C#/Python/JavaScript) is pretty enough to handle the situation and college students should all be ok as all schools will require them to learn at least one of them. When scheduling your interviews with your HR, you can ask them or they will usually ask you first about your language preferrence. 

The other question is about how well you should know the language. I think as long as you know the basic syntax like for/while loop, class, variable, array, list and common operations including functions/methods(print/sum/abs..),casting, exceptions and basic OOP related things(class/interface/overloading/overriding), you should be ok. It is totally ok to make syntax mistakes during interviews, your interviewers should understand that as long as you are  able to explain your thinkings/idea with pseudo code and not making siginificant language specific logic mistakes(things like writing a pointer in JAVA or using {} instead of indention in Python). A good technical company should have their technical interview focus on problem solving skills, algorithm, smartness or even computer sciences but never on syntax details. 

Here is a article I found really useful:
- [Choosing a Programming Language for Interviews](http://blog.codingforinterviews.com/best-programming-language-jobs/)

#### Books
There are so many books you can read but I personally think the famous [Cracking the Coding Interview](https://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/098478280X) is pretty enough. Overall, this book is serving more as a guide book instead of an ultimate bible. As the competition is growing daily, lots staff in this book have become either too simple or too-well-known-to-ask. For starters, I think you should definetely read this book (mostly focus on the coding questions) and build a clear understanding of 
  
  1.what data structure and algorithm is and 
  2.what kind of coding question you will be asked during a technical interviews. 

However, don't spend too much time on reading this book as it's too well known and you still need code in real instead of just reading. My general idea on dealing with a technical interview question in this book and also the following Online Judge section is to look at the question and if you can not solve it or at least you think you can not solve it in an efficent way within 5 mins, go to the solution. This may sound frustrating (actually it does make people feel very frustrating),but trust me this is the most effeint way to "crack" coding interview. As more solutions you have seen, you will gain more experiences or I will call it "common senses" on handling an algorithm question and eventually you will become independent enough to solve something similar all by yourself. 

#### Online Judge
Online Judge might be the handiest tool for preparing technical interviews as they offer real coding experiences and a whole bunch of fresh questions that you may actually face in an interview. I only used [LeetCode](https://leetcode.com/) and I also heard [LintCode](https://www.lintcode.com/) is also good. My general philosophy on doing Online Judge is it's not a competition of knowing the most interview questions but building up a systematical skillset. Your focus should be on a qualitative result not quantitative. I know a few engineers who don't even know the existance of LeetCode or LintCode but they can pass every interview and I also know some candiates who did every single question in LeetCode but still have diffculties getting an offer. In short, when practising in Online Judges, focus on what you are actually learning rather than how many qestions you have solved. 

Here is my advices based on my experiences about using LeetCode:

  1.Reading through Cracking Code Interview to know the all common things about data strctures and algorithm, if you can answer following questions you are ready to proceed:
    - Can you write a quick sort and what is the time complexity?
    - Give an example of DFS 
    - Give an example of BFS
    - Give an example you need a double-linked list
    - What is the difference between Stack and Queue 

  2.As you started solving questions one-by-one, applying the strategy as I metioned before for reading the book questions: 
    Step1. Look at the question, try to come up with a good and efficent idea (not the actualy code solution, just the thoughts) within 5 mins. If you have no idea or no confidence in your idea, go to Step 4. If you believe your solution could work start coding.
    Step2. If you can not finish your code solution within 20 mins, go to step 4
    Step3. No matter your solution pass or not pass the OJ, go to step 4
    Step4. Google the MOST STANDARD solution you can find and understand: 
      1. What kind of algorithm does the solution use? 
      2. What is the time/complexity? 
      3. Do you think this solution is better than yours(If you have one) or not? Why?
  These steps help you to gain more out of solving a problem. A common problem lots of poeple have, espcially those focus on quantity, is to have a very limited knowledge gain. If your goal is just to pass the Online Judge, you are missing the point in a big time.

  3.For some algorithm solution(Dijkstra, heap sort, trie, or even quick sort), you may have difficuties fully understanding it, then try to memory the solution template and practise writing from memory. I was once having difficuties writing a 100% correct heap sort including insertion/deletion/search, so I memorized it (about 50 lines of python code) and eventaully it helped me on fully understanding it.

  4.For Dynamic Programming, my advise is don't worry too much, As you may know, lots of people inculding myself consider DP as the most difficult part of algorithm but it is actually not that bad in technical interviews. Recently years, lots of comapny start to avoid DP in interviews as a DP question can not help the interviewer to assess candidates. Understand most easy/medium DP questions from OJ is enough. Don't waste your time in hard DP question, this is about passing the interview not algorithm science.

#### Online Forum
There a lot of online forum where people talked about interview experiences and particular interview questions. Spending few minitues a day on them could be quite beneficial. The one I used most is [1point3acres](https://www.1point3acres.com/bbs/) where most contributers are Chinese and you can get lots of useful info and also share your own experiences. Another good place to go is [GeeksforGeeks](https://www.geeksforgeeks.org) where recently it got some major updates and become a very professional Coding Interview Preparation Commnunity. As most of Chinese students would prefer 1point3acres as it is mainly written in Chinese, I strongly encourage you to take a look at GeeksforGeeks for 1.Getting familiar with understanding/discussing your alogrithm questions in English; 2.Reading more well formatted and professional articles about solving a alogrithm problem in English. Most posts I found in 1point3acres are more closed to casual chats and it is not easy to systematically understand a solution thru those posts but therea are lots of well written aritcles on GeeskforGeeks where posters showed their step-by-step thoughts with lots of serious comments to help. 
For preparation, you should spend more time on online forums instead of online judge sites when it's getting closer to your interview date.  

#### Communication Skill
Based on what I've seen for the past 5 years, lots of candidates are struggling with poor communication skills. I have seen people with great GPAs and went through hundreds and hundreds of Online Judge interview questions but still failed interviews. The reason is pretty simple: the interviewers can not understand their solution or they way they tackle the problem. If you think technical interviews and programming are only about coding, coding and coding, you are 100% wrong. It is far more important to express your thoughts and problem solving skills than just writing your code. Interviewers are looking for ways they can assess your abilities as programmer and if you don't talk them through your solution you are not offering enough materials to your interviewers to write their assessments. 
Here are few suggestions for building up your communication skills:

  1.Practice explaining your solution in English. This is a very oblivous point lots of people missed in their preparation. No matter how execellent your code solution is, you will need to explain your code to your interviewers so I highly suggested you to practice explaining your solution verbally while solving it. It may sound a little bit silly but you will gain a lot from do this. 

  2.Get a good amount of feedback regarding your communication skills from someone with whom you interact regularly or who is working in the industry.Try to book your TAs/professors' office hour for doing some communication training where your focus is on explaning your solutions and throughts and ask they to correct or refine your language. 

  3.Attend interviews as many as possible even for companies your are not considering at all or do mocking interviews from online websites to school job fair events. The more interviews you had, the more experiences you accumulated.

### Knowledge Checklist
Below is a list of key concept/alogirtm/data structure you should be familiar with in a certain level. 

##### Basic
      - Array/Hashmap/Dictionary
      - Pointer
      - Single/Double Linked-List
      - Queue
      - Stack  
      - Binary Tree
      - Buble Sort
      - Selection Sort
      - Merge/Quick Sort
      - Topological Sort
      - Simple Graph (adjacency matrix/adjacency list representation)
      - Tree Traversal
      - Binary Search
      - Depth-first Search/Backtracking
      - Breadth-first Search
      - Recursion
      - Greedy
      - Divide Conquer
      - Bit Manipulation
##### Advance
      - Minimum Spanning Tree
      - Shortest-path tree(Dijkstra's algorithm / Bellman–Ford algorithm)
      - Trie 
      - Union
      - Set
      - Binary Search Tree
      - B-tree
      - Heaps
      - Trie
      - Segment tree
      - Graph
      - Directed Acyclic Graph
      - Heap/Heapsort
      - Union Finding
      - Segment Tree
  
