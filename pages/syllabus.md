---
layout: default
title: "Syllabus"
nav_order: 3
has_toc: true
permalink: /syllabus/
---

<h1>Syllabus</h1>
<hr/>


- TOC
{:toc}
{: .fs-2 }

## Course Materials
- There is **no** textbook. But we will rely on several free online resources
	- **Whirlwind Tour of Python**: [https://github.com/jakevdp/WhirlwindTourOfPython/](https://github.com/jakevdp/WhirlwindTourOfPython/)
	- **Python Data Science Handbook**: [https://jakevdp.github.io/PythonDataScienceHandbook/](https://jakevdp.github.io/PythonDataScienceHandbook/)
		This book is available free online or in print.
	- Wallisch, ​Neural Data Science
		https://www.sciencedirect.com/book/9780128040430/neural-data-science
	- Adhikari & DeNero,​ ​The Foundations of Data Science
		https://inferentialthinking.com/chapters/intro.html
- All course materials are provided through **this website**
- Piazza will be used for general Q&A
- Datahub will be used for assignment/project submissions 
- Gradescope will be used for taking quizzes/exams

## Course Objectives
- Think from a “data first” perspective: what data _would_ you need to answer your scientific questions of interest?
- Develop hypotheses specific to big data environments in neuroscience.
- Work with many different neuroscience data types that might include data on behavior, brain structure and connectivity, single-unit spiking, field potential, gene expression, and even text-mining of the peer-reviewed neuroscientific literature.
- Integrate multiple heterogeneous datasets in scientifically meaningful ways.
- Choose statistical model(s) informed by the underlying data.
- Design a big data experiment and integrate data from multiple open data sources. 
- Consider alternative hypotheses and assess for spurious correlations and results

## Grading & Attendance

### Course Components & Points

|  | % of Total Grade | 200 Total Points |
| :--- | :--- | :--- |
| 5 Assignments (lowest score dropped) | 40 | 80 (20 each) |
| 4 Reading Quizzes | 20 | 40 (10 each) |
| Final Project Proposal | 5 | 10 |
| Final Project Notebook | 20 | 40 |
| Final Project Presentation | 5 | 10 |
| 1 Final Exam | 10 | 20 |
| Extra Credit (Guest lecture attendance + Course Surveys + SET) | N/A | 5 (bonus) |

### Final Grades

Your letter grade will be determined using the following grading scale:

| Percentage              | Letter Grade              |
| ----------------------- | ------------------------- |
| 97-100%                 | A+                        |
| 93-96.99%                  | A                         |
| 90-92.99%                  | A-                        |
| 87-89.99%                  | B+                        |
| 83-86.99%                  | B                         |
| 80-82.99%                  | B-                        |
| 77-79.99%                  | C+                        |
| 73-76.99%                  | C                         |
| 70-72.99%                  | C-                        |
| 67-69.99%                  | D+                        |
| 63-66.99%                  | D                         |
| 60-62.99%                  | D-                        |
| <60%                    | F                         |

### Grades
Grades for assignments will be released on Canvas approximately a week after the submission date. Ultimately it is your responsibility to check your final grade and get in touch if you believe there is a problem.

### Regrade Policy
We will work hard to grade everyone fairly and return assignments quickly. But we know you also work hard and want you to receive the grade you’ve earned. Occasionally, grading mistakes do happen, and it's important to us to correct them.

If you think there is a mistake in your grade for an assignment, submit a regrade request to Prof. Khosla and the TA within 72 hours of receipt of the grade. This request should include evidence of why you think your answer was correct (_i.e._, a specific reference to something said in lecture) and should point to the specific part of the assignment for us to reconsider.

**If you think a grading error has occurred please follow these steps:**
- You have 72 hours to request a regrade
- If it is a group project, confer w/ your team first and submit one regrade after your team comes to a consensus)
- Provide evidence for why your answer is correct and merits a regrade (i.e. a specific reference to something said in a lecture, the readings, or office hours)
- We will get back to you within 48 hours after regrades close with our final decision.

### Lecture Attendance
Our goal is to make lecture and discussion section worth your while to attend. However, I will not be taking attendance. But this is a project-based course, where the final project will be a comprehensive notebook demonstrating the work you and your group do. The more time you spend in class and discussions working on this, the better your project will be. All lectures will be recorded. These will be made available to you (UCSD podcast). 

### Sections 
Discussion sections will be used to review content from lectures, discuss readings, help with coding and the Final Project, and guide your assignments, so it is to your benefit to go, participate, and ask questions. Further, groups will be created within sections (usually week 2), so it is especially helpful to attend discussion section that week. 
## Course Assignments & Topics
Neuroscience is a rapidly changing field that is increasingly moving towards ever larger and more diverse datasets that are analyzed using increasingly sophisticated computational statistical methods. There is a strong need for neuroscientists who can think deeply about problems that incorporate information from a wide array of domains including psychology and behavior, cognitive science, genomics, pharmacology and chemistry, biophysics, statistics, and AI/ML. With its focus on combining many large, multidimensional, heterogeneous datasets to answer questions and solve problems, data science provides a framework for achieving this goal.

Determining what data one needs, and how to effectively combine datasets, is a creative process. For example, a neural data scientist might be tasked with combining:

1) _demographic information_ and 2) _multiple cognitive and behavioral measures_, from people from whom we might collect;

3) _biometric data_, 4) _motion capture data_ to understand motor control, and 5) _eye-tracking_ to study attention, along with;

6) _structural connectomic_ and 7) _functional brain imaging_ data collected using methods with different spatial and temporal resolution (such as fMRI and EEG), and then place those results into context relative to;

8) _average human brain gene expression patterns_ and 9) _the existing knowledge embedded within the peer-reviewed neuroscience literature_ (>3,000,000 papers).

These types of data are very different: continuous and ordinal, time-series, video and images, directed graphs, spatial, high-dimensional categorical / nominal, and unstructured natural language. What is the appropriate way to aggregate and synthesize these data? What are the benefits and caveats for, say, aggregating spatially versus temporally? Being able to conceptualize how to carry out this integration is necessary before leveraging any technical skills will even be useful.

### Readings & Quizzes
Quizzes cover the reading material assigned, e.g. Quiz 1 only covers material from reading 1 (R1).

- Four multiple choice (10 questions) quizzes
- No time limit
- Open notes, but you must work alone.
- Taken and submitted through Gradescope

Late reading quizzes will be accepted up to 48 hours; however, they will receive ½ credit.

### Assignments
There are five assignments. Assignments will focus on applying the concepts covered in lecture and ensuring you’re on the right track for your final project.

Assignments will be posted on the Fridays of the week before they’re due, and you have until _Friday at 11:59 PM_ of the following week (so about a week) to complete each assignment. Assignments will be released and submitted on datahub. Assignments are submitted individually. You will receive feedback along with a grade within approximately a week from the due date. 

_Late assignments_ earn fractional credit (75% within one week late; no late assignments accepted after one week). 

### Final Project

For the final project, you will work in groups of 2-3 members. You have two options: 
- Choose a paper that uses a new data analysis technique that has been published no more than 10 years ago (most should have code and data publicly available). Implement this method using a new data set (either your own or from a publicly available source).
- Come up with a neuroscientific research question of your own that is answerable with available data. You can look at some of the public datasets to frame your question. Determine an analytical approach that can be used to answer your question and implement this method.  


**Proposal**
Around mid-quarter, you are required to submit a project proposal. The template will be provided to you. 
- One report submitted through Gradescope per group. 
- One PDF submission per group (ensure all your names and PIDs are on the PDF)
- Your team may resubmit as many times as you like before the deadline
- Late submissions:
  - Late reports have 5 points deducted within the first 24 hours, and an additional 5 points during the following 24 hours.
  - No late reports accepted after 48 hours.
  - 
You should integrate the feedback given on your proposal into your product, and reach out to Dr. Khosla or our TA if you have any questions or concerns.

**Final submission**
Your final product for this project will be a Jupyter Notebook that walks us through the steps of your analysis to answer your experimental question. Ultimately, you should generate three different plots that concisely address your experimental question.

{: .note .fs-2 }
To reiterate, your team will create a jupyter notebook for all project-related work and work on that copy together. Make sure to read all the instructions. You will receive feedback along with a grade typically within a week for the proposal. Feedback from us should be incorporated into the final submission.

### Exam
The final exam is comprehensive and will cover the lectures (and possibly guest lectures). An exam review session will be held during discussion section week 10.

- One multiple-choice exam
- Available for 72 hours on Gradescope
- You have 1 hour to finish once started
- One attempt
- Open notes and open Google/ChatGPT/etc., but you must work alone
- Taken and submitted through Gradescope

No late exams are permitted, except for extenuating circumstances. Please reach out to staff as early as possible if you know something will prevent you from taking the exam on time.

## Other Good Stuff

### Teamwork Expectations
Your team will be working on the final together. We expect all students to, more or less, be equal contributors to the final project. No one person should be doing an entire project; they are meant to be collaborative and give you experience working with people you probably do not know. One successful approach is to first agree on a communication tool/protocol and a schedule. Next, discuss each person’s strengths and divide up responsibilities. Develop a schedule for completing tasks, who is responsible, and a backup person in case an emergency occurs. Finally, check in regularly to ensure progress is being made and leave some time to check and proofread each other's work. 

**Dealing with non-cooperative team members** -- If an issue occurs, first try to work the issue out within your group. Save all documentation, emails, and chats as a record in case you need to contact the course staff later on. If no resolution can be made or the problem resurfaces, you should then contact course staff. We reserve the right to move the student to a new group or grade that student separately from the group, or take any other action to resolve the issue.

**Group work is never easy** -- Teamwork, while difficult, is one of the most important skills you should learn and practice during college. To succeed, communication is critical. You need to be in contact with your group regularly. This will help you keep on top of deliverables and make adjustments if problems should arise. We are always here to help and make use of our experience working on real engineering/science projects.

### Class/Web Conduct
In all interactions in this class, you are expected to be respectful. This includes following the UC San Diego [principles of the community](https://ucsd.edu/about/principles.html).

This class will be a welcoming, inclusive, and harassment-free experience for everyone, regardless of gender, gender identity and expression, age, sexual orientation, disability, physical appearance, body size, race, ethnicity, religion (or lack thereof), political beliefs/leanings, or technology choices.

At all times, you should be considerate and respectful. Always refrain from demeaning, discriminatory, or harassing behavior and speech. Last of all, take care of each other.

If you have a concern, please speak with Prof Khosla or your TA/IAs. If you are uncomfortable doing so, that’s ok! The [OPHD](https://blink.ucsd.edu/HR/policies/sexual/OPHD.html) (Office for the Prevention of Sexual Harassment and Discrimination) and [CARE](https://care.ucsd.edu/) (confidential advocacy and education office for sexual violence and gender-based violence) are wonderful resources on campus.


### Academic Integrity
Don't cheat.

You are encouraged to (and at times will have to) work together and help one another. However, you are personally responsible for the work you submit (quizzes/assignments/exams). For projects, it is your responsibility to ensure you understand everything your group has submitted and to make sure the correct file has been uploaded, that the upload is uncorrupted, and that it renders correctly. Projects may include ideas from other sources, but these other sources must be documented with clear attribution. Please review academic integrity policies [here](http://academicintegrity.ucsd.edu).

We anticipate you all doing well in this course; however, if you are feeling lost or overwhelmed, that’s ok! Should that occur, we recommend: (i.) asking questions in/after class, (ii.) attending office hours, and/or (iii.) reaching out to course staff.

Cheating and plagiarism have been and will be strongly penalized. If, for whatever reason, this website or Gradescope is down, or something else prohibits you from being able to turn in an assignment on time, immediately contact course staff via email (attach your assignment/quiz/exam answers) or else it will be graded as late.

### Disability Access
Students requesting accommodations due to a disability must provide a current Authorization for Accommodation (AFA) letter. These letters are issued by the Office for Students with Disabilities (OSD), which is located in University Center 202 behind Center Hall. These will be sent to the instructor once submitted, and you will receive a response confirming receipt and discussing the accomodations as necessary. However, if you are struggling to get necessary accommodations or want to further discuss your accommodations, please feel free to reach out directly.

Contacting the OSD can help you further:
858.534.4382 (phone)
[osd@ucsd.edu](osd@ucsd.edu) (email)
[http://disabilities.ucsd.edu](http://disabilities.ucsd.edu)

### Difficult Life Situations

Sometimes life outside of academia can be difficult. Please [email me](mailto:mkhosla@ucsd.edu) or come to office hours if stuff outside the classroom prevents you from doing well inside it. I can often refer you on to the help you need.

If you don't have the most essential resources required to thrive as a student, please contact [UCSD Basic Needs](https://basicneeds.ucsd.edu) who can help you access nutritious food and stable housing, and help you seek the means to reach financial wellness.

If you need emergency food, finances, and/or academic and social support you can also contact [UCSD Mutual Aid](https://mutualaiducsd.wordpress.com). They provide mentoring and aid that comes from volunteers among your peers.  If you don't need that kind of support, consider joining them in helping your fellow classmates who do.

If you need counseling or if you are in a mental crisis you can contact [CAPS](https://caps.ucsd.edu). They provide psychiatric services, workshops, and counseling; they also operate a 24/7 crisis hotline at 858.534.3755.

### Questions & Feedback
**How to Get Your Question(s) Answered and/or Provide Feedback**
It’s great that we have many ways to communicate, but it can get tricky to figure out who to contact or where your question belongs, or when to expect a response. These guidelines are to help you get your question answered as quickly as possible and to ensure that we’re able to get to everyone’s questions.

That said, to ensure that we’re respecting their time, TAs and IAs have been instructed they’re only obligated to answer questions between normal working hours (M-F 9am-5pm). However, I know that’s not when you may be doing your work. So, please feel free to reach out whenever is best for you while knowing that, you may not get a response until the next day. As such, do your best not to wait until the last minute to ask a question. If there is an emergency and you need to contact staff immediately, email Prof Khosla and put "EMERGENCY-COGS138" in the subject line. I will get back to you ASAP.

If you have…
- **questions about course content** - these are awesome! We want everyone to see them and have their questions answered, please post questions on Piazza or ask during class/office hours.
- **questions about course logistics** - first, check the syllabus. If the answer is not there, ask in Section, ask a classmate, or ask during class/office hours.
- **something super cool to share related to class** - feel free message on Piazza, email Prof Khosla ([mkhosla@ucsd.edu](mkhosla@ucsd.edu)), or come to office hours. Be sure to include COGS 138 in the email subject line and your full name in your message.
- **something you want to talk about in-depth** - meet in person/digitally during office hours or schedule a time to meet 1:1 by email. Be sure to include COGS 138 in the email subject line. Or it may be missed. [mkhosla@ucsd.edu](mkhosla@ucsd.edu). 
