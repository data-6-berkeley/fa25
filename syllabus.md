---
layout: page
title: "&#x1F4DC; Syllabus"
nav_order: 2
description: >-
    Course policies and information.
---

{: .warning }
⚠️ This content is archived as of March 2026 and is retained exclusively for reference. [Find current offerings.](https://data6.org/)

# Syllabus
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## About &#x1F9D0;

Hi! Welcome to Data 6 Fall 2025! We’re excited to have you on board this semester. This course is specifically designed without any prerequisites or assumed prior knowledge of computer science or statistics. Along the way, you’ll gain practical experience working with data and using Python code to extract useful insights from real-world data sets. Even if this is the last data science class you ever take, we hope you’ll learn useful skills that you can apply to your own major or field of study.

### Course Description
<!--Data 6 is an introduction to computational thinking and quantitative reasoning, designed to prepare students for further coursework in data science, computer science, and statistics. This course emphasizes the use of computation to gain insight about quantitative problems with real data from the social sciences.-->

This foundational Data Science course is an introduction to computational thinking as applied to the fundamentals of quantitative social inquiry. Apply critical concepts and skills in computer programming to conduct quantitative social science research in various contexts, including economic outcomes, public health, environmental justice, privacy, bioethics, and social networks. Understand the process of using data for quantitative analysis and how to develop a variety of figures, combined with text, to communicate their findings. The focus is on data exploration and identifying patterns relevant to social concepts, rather than inferences and predictions.

This class serves a different purpose than several other classes that may sound similar. Specifically:

* [**Data 8**](https://www.data8.org/) (Foundations of Data Science) is the first required course for the UC Berkeley Data Science major and minor. While some topics may be similar, Data 6 does not cover nearly as much statistics and inference. Instead, we dive deeper into the mechanics of Python and how to use Python to generate insights from data using real-world data sets. After taking Data 6, you will be more than well-equipped to take (and succeed in) Data 8.
* [**CS 10**](https://cs10.org/sp25/) (The Beauty and Joy of Computing) is a similar class to Data 6 in that it is intended as an introduction to computing that assumes no prior experience with programming. However, CS 10 focuses less on Python and data science, and more on abstract ideas in computer science. It is a fantastic alternative (or complement) to Data 6.
* [**CS 61A**](https://cs61a.org/) (Structure and Interpretation of Computer Programs) and [**Data C88C**](https://cs88-website.github.io/sp25/) (Computational Structures in Data Science) also teach Python, but serve a slightly different purpose than Data 6 — namely, these courses are designed to introduce students to computer science, not to computing *in* data science. They cover the Python language in far greater detail than we will, but they do not cover how to work with real-world data. After taking Data 6, you will be more than well-equipped to adapt to the faster pace of CS 61A and Data C88C.

### Course Materials and Resources

All web platforms are available on our course website: [{{site.url}}{{ site.baseurl }}/]({{site.url}}{{ site.baseurl }}/)

* **Course Website**: The day-to-day happenings of the course (and links to all the platforms below) can be found on our front page. Consult the [front page]({{site.url}}{{ site.baseurl }}/) for a schedule of course topics, assignments, and due dates. Consult the [Calendar]({{site.url}}{{ site.baseurl }}/calendar) page for the times/locations for all weekly engagements.
* **Edstem**: This will be our main Q&A platform, where you can ask (and answer) questions and see announcements. The front page has a button to our [course EdStem](https://edstem.org/us/courses/{{ site.ed_course_id }}/discussion).

    Ed is a formal, academic space. Posts in this forum must relate to the course and be in alignment with [Berkeley’s Principles of Community](https://diversity.berkeley.edu/principles-community) and the [Berkeley Campus Code of Student Conduct](https://conduct.berkeley.edu/code-of-conduct/). We expect all posts to demonstrate appropriate respect and consideration for others. Please be friendly and thoughtful; our community draws from a wide spectrum of valuable experiences. Posts that violate these standards will be removed. 
* **DataHub**: This is where you will complete Python assignments on Jupyter Notebooks, an interactive scientific notebook popular in data science applications and Data courses. Access via [https://datahub.berkeley.edu/](https://datahub.berkeley.edu/) or by clicking coding books on the front page.
* **Gradescope**: This is where you will submit all assignments, including weekly reading assignments. The front page has a button to our [course Gradescope](https://www.gradescope.com/courses/{{ site.gradescope_course_id }}).
* **Google Drive**: Lecture resources are on Google Slides (accompanied by notebooks you can access on DataHub). You will occasionally need to submit surveys via Google Forms.
* **bCourses**: At the moment, there's not much here. We also won't plan much here, so please contact staff via Ed or email.

### Support

You are not alone in this course! The staff and instructors are here to support you as you learn the material. It’s expected that some aspects of the course will take time to master, and the best way to master challenging material is to ask questions. For questions, use [Ed](https://edstem.org/us/courses/{{ site.ed_course_id }}/discussion), not bCourses. We will also hold in-person office hours that offer drop-in help on assignments and course material. Instructor "Tea Hours" are for advising and are also drop-in (welcome!). See our [Calendar]({{site.url}}{{ site.baseurl }}/calendar) for office hour times.

We are a much smaller course than many of the Data Science classes you may encounter at Berkeley. Use this fact to your advantage! The instructor, TAs and UCS1s are here to support you, so please lean on your course staff if you need more support in the class or have any questions/concerns.

## Course Components	&#x1F4D2;

### Lecture

* **Lecture**: Monday and Wednesdays 11AM-12PM @ [Mulford 240](https://www.berkeley.edu/map/mulford-hall/)

Lectures are live, in-person, and not recorded. Lectures aim to introduce new ideas and concepts in programming and data science. All lecture resources (slides, code, notes) will be linked on the course website. We recommend skimming the notes beforehand if you can.

[update 9/3] Attendance is not required, with the exception of guest lectures (TBD). However, the class is small for a UC Berkeley computing class, and we want to make the most of it. Class activities will be interactive and involve discussion; this is as much a critical part of learning as passively absorbing content. <!--Credit for attending will be through answering a class question in PollEverywhere; this question will double as a "concept check" to help understand the material we're currently covering.-->

<!--You have **5 lecture drops**, meaning you can miss up to 5 lectures without penalty, after the first lecture. These drops are not intended to be “free-passes” to skip lectures: please reserve them for unexpected personal or family emergencies, sickness, etc.-->

### Lab Section

* **Section**: Fridays 9-11AM @ Cory 285, 12-2PM @ Evans 85

Weekly section include a discussion worksheet covering recent material and a programming-based lab assignment that develops skills with computational concepts. The problems in section are good preparation for similar (and harder) problems you will see on your homework assignments! Section materials will be released Thursdays each week.

The first hour focuses on a discussion worksheet and group problem-solving. Sometimes, discussion topics will include social science issues in computing and data, supplemented by reading assignments. We encourage you to ask questions, raise new points, connect to past readings, and make connections to your own experiences. We further encourage no use of technology during this portion of the lab (all materials required will be available at the lab section). The second hour is dedicated to completing a programming-based assignment.

**80% of lab credit will be attendance-based. The remaining 20% of credit will be awarded for submitting the lab to Gradescope by the Friday 5 pm deadline with all public test cases passing.** To earn attendance credit, students must attend the entire discussion and lab section unless they have approval from their GSI to arrive late or leave early. Failure to attend the entire section without prior communication will result in losing attendance credit for that week.

You have **2 lab drops** to use in the event of extenuating circumstances that prevent them from completing the assignment. To use a lab drop, you must message your TA at least one hour prior to the start of your lab, informing them that you will not be in attendance. Note that like lecture drops, lab drops are expected to be used only in the case of illness, emergencies, or other circumstances that prevent you from attending. For specific concerns related to your lab section, contact your TA.

### Readings

Readings are designed to complement the lecture content and prepare you for discussion in section. Readings will generally be lecture notes and, occasionally, external readings with a focus on ethical and social issues. Submit the weekly reading assignment on Gradescope for credit. Reading assignments will be released Tuesday evenings and due **Thursday at 11:59PM**, the evening before section.

### Assignments
You learn data science by **doing** data science, not by just listening to lectures or reading a textbook. As such, homework assignments will be your primary source of learning in this class.

#### Homework Assignments

Homework assignments will consist mainly of programming problems that challenge you to apply the skills you learned in recent lectures to accomplish tasks involving real data. The homeworks use autograder tests that will tell you if you are on the right track. There are additional autograder tests that will not be visible to you that we will use to grade your work, so don’t assume that just because the public autograder tests are passing that your answers are all correct. **Always remember to double check your code!** Most homeworks will also include a few written response problems, where you will have to type your answer in text. These problems will be manually graded by a human on course staff, and often there is no single ‘right’ solution. We are mainly looking for you to show understanding of what you are doing and to explain your reasoning behind certain answers.

Homework assignments will generally be released ~~Wednesdays~~ Thursdays and due the following ~~Wednesday at 5PM~~ **Thursday at 8PM** (last updated 10/27/25). Access homework by clicking a homework link on the front page, which will bring you to your own copy of the homework notebook in DataHub, which allows you to work on the homework online. Once you’re done with the homework, you will run the very last cell in the notebook to generate a `.zip` file, which you will then upload to [Gradescope](https://www.gradescope.com/courses/1064926) so that we can grade it. We will go over this process in more detail in lecture.

#### Projects

A few homework assignments will be "projects" where you will analyze real-world datasets. The experience of solving the problems in this project will prepare you for exams (and life in a data scientist role). On each project, you may work with a single partner; your partner must be from the lab you enrolled in. You will generally have two weeks to complete projects; projects share the same weekly deadlines as homework assignments unless otherwise stated.

Don’t share your code with anybody but your partner. You are welcome to discuss questions with other students but don’t share the answers. If someone (who is not your partner) asks you for the answer, resist! Instead, you might demonstrate how you would solve a similar problem.

The projects can seem long and difficult, but you are not alone! Come to office hours, post on Ed, and talk to your classmates. If you want to ask about the details of your solution to a problem, make a private Ed post and the staff will respond. If you’re ever feeling overwhelmed or don’t know how to make progress, email your TA or tutor for help. You can find contact information for the staff on the course website. We highly recommend starting early.

### Quizzes and Exams
There are 3 in-class quizzes and one final exam. The final exam is required for a passing grade. The below quiz dates are CONFIRMED: <!--TENTATIVE:-->

* Quiz 1: Monday, September 22, in-class
* Quiz 2: Monday, October 13, in-class
* Quiz 3: Monday, November 10, in-class
* Final Exam: Monday, December 17th, 11:30am-2:30pm

There will not be alternate exams. All exams will be held in-person. More details about quizzes and exams will be posted ot Ed.

## Policies &#x1F4D1;

### Grading

Here's how we will calculate your final grade:

| **Component** | **Weight** | **Notes** |
| Surveys | 0.75% | - 3 course surveys |
| Readings | 6.5% | - 13 readings |
| Lab Section | 12.75% | - 14 labs with 2 drops |
| Assignments | 40% | - 5 homework assignments (4% each) <br/> - 2 projects (5% each)<br/> - Final Project (10%)|
| Exams | 40% | - 3 quizzes (9% each) <br/> - Final Exam (13%) |

Updates:

* [as of 9/19] Assignment grade components were updated to accommodate one less project.
* [as of 11/3] One fewer reading.

We will share information later in the semester regarding grade bins or letter grades. Please consult Berkeleytime for historical distributions of grade bins!
ear
Grades for Homeworks, Projects, and Labs will be posted on Gradescope within a timely manner after the assignment’s due date. It is up to you to check the solutions and request a regrade request before the regrade deadline on Gradescope. Any regrade request past the deadline will not be looked at; this is to enforce the same deadline across all students, so again: please do not delay reviewing your work.

### Submitting Assignments

All assignments (homework, labs, and projects) will be submitted on Gradescope. Please refer to [this tutorial](https://drive.google.com/file/d/1JU-p1qYKEFQBRoI6p24tx_-Cj0dySN9h/view) for submitting assignments.

We understand that the submission process is new for many students taking the course. To account for this, we will do our best to accommodate submission-related issues (submitting to the wrong assignment, not saving files correctly, autograder timing out) up until the third week of the course. After the third week, it is your responsibility to confirm you have submitted your work correctly. We reserve the right to impose penalties for having to resubmit students’ work beyond this point.

### Late Submissions
The deadline for all assignments in this course is 5 PM PT for programming assignments (lab, homework, project assignments) and reading assignments (Gradescope "quizzes"). Submissions after this time will be accepted for 24 hours and will incur a 20% penalty. Any submissions later than 24 hours after the deadline will not be accepted.

**Extensions**: We understand that life happens and want to provide you with the support you need. We don't want to penalize you because of circumstances that are out of your control. If you have an ongoing situation that prevents you from completing course content, please contact the course instructor and/or TA. This includes assignment extension requests, in which case you must notify us within 24 hours before the deadline. As long as your request is within reason, there's a good chance of it being granted, in which case we will add the extension to your submission on Gradescope.

### Accommodations

We honor and respect the different learning needs of our students, and are committed to ensuring you have the resources you need to succeed in our class. If you need religious or disability-related accommodations, if you have emergency medical information you wish to share with us, or if you need special arrangements in case the building must be evacuated, please share this information with us as soon as possible.

**DSP**: We will provide appropriate accommodations to all students enrolled in Berkeley’s Disabled Students Program (DSP). To ensure that you receive the appropriate accommodations, have your DSP specialist submit a letter confirming your status and accommodations.

If you’re not enrolled in DSP, or are in the process of being onboarded by DSP, you may still be eligible for accommodations. We also aim to provide fair and appropriate accommodations to any students who, because of extenuating circumstances, may need them. Please reach out to us in this case.

**Religious Observance**: If you require accommodation for religious observance, please contact us at least a week before the deadline in question to make arrangements.

**Privacy**: All accommodations-related materials for this course are kept in a repository separate from the rest of the course materials that is visible only to the instructors and TA.


### Academic Honesty and Learning Collaboratively
This may be the first class you take at UC Berkeley --— we know that taking your first class can be stressful. But the main point of this class (and of data science in general) is to try things out and learn from your mistakes, not necessarily to get everything right on the first try. This class is designed to encourage you to learn through exploration, so we hope you focus on learning skills that you might use later, instead of focusing on getting a good grade.

Data science is a collaborative activity. As such, we encourage you to discuss homework and lab assignments at a high level with other students. With that said, you must write all code and solutions individually in your own words. **Rather than copying someone else's work, ask for help.** You are not alone in this course! We're here to help you succeed, and if you invest the time to learn the materal and complete the assignments, you won't need to copy any answers. If you use code you found online, please cite it in a comment and briefly explain what the code does.

Make a serious attempt at every assignment yourself. If you get stuck, read the textbook and go over the lectures and lab discussion. After that, go ahead and discuss any remaining doubts with others, especially the course staff. That way, you will get the most out of the discussion. It is important to keep in mind the limits of collaboration. As noted above, you and your peers are encouraged to discuss course content and approaches to problem solving. But you cannot share your code or answers with other students. Doing so is considered academic misconduct, and it won’t help your peers either. Sharing answers will set them up for trouble on upcoming assignments and exams.

**You are not permitted to turn in answers or code that you have obtained from any generative AI tools, including but not limited to ChatGPT.** Not only does such copying count as academic misconduct, but it also circumvents the pedagogical goals of an assignment. You must solve problems with the resources made available in the course. You should never look at or have solutions in your possession from another student or another semester. Late in the semester, we will have an opportunity to learn how to use generative AI tools for coding _constructively_ later in the semester. Until then, please ask us questions about appropriate use and prioritize getting familiar with the code first.

Please read Berkeley’s [Code of Conduct](https://sa.berkeley.edu/code-of-conduct) carefully. Penalties for academic misconduct in Data 6 are severe and include reporting to the [Center for Student Conduct](https://sa.berkeley.edu/conduct). They might also include an F in the course or even dismissal from the university. It’s just not worth it!

## Campus Resources &#x1F3EB;

### Technology Resources
Since all Data 6 material is accessible online, there are no requirements in terms of specific computer hardware. All you need is a laptop with internet and a web browser (Google Chrome or Firefox tend to work best). If you looking to purchase, rent, or borrow a laptop for college, Prof. Lisa Yan put together this [helpful guide](https://docs.google.com/document/d/1avUDkT5yvW_XycvVYP9LevJP791a9CdxuCAzQB1tYfc/edit?usp=sharing).

Here are a few helpful resources when it comes to technology:
* Read this [Berkeley IT website](https://technology.berkeley.edu/wi-fi) to learn how to connect to the campus WiFi network, Eduroam.
* **Device lending options**: The [Student Technology Equity Program](https://technology.berkeley.edu/STEP) provides free laptop loans for students.

### Data Science Student Climate
[Data Science Undergraduate Studies](https://cdss.berkeley.edu/dsus) faculty and staff are committed to creating a community where every person feels [respected, included, and supported](https://data.berkeley.edu/equity-inclusion). We recognize that incidents may happen, sometimes unintentionally, that run counter to this goal. There are many things we can do to try to improve the climate for students, but we need to understand where the challenges lie. If you experience a remark, or disrespectful treatment, or if you feel you are being ignored, excluded or marginalized in a course or program-related activity, please speak up. Consider talking to your instructor, but you are also welcome to contact Executive Director Christina Teller at [cpteller@berkeley.edu](mailto:cpteller@berkeley.edu) or report an incident anonymously through this [online form](https://docs.google.com/forms/d/e/1FAIpQLSfBwaUe7VMQz6VzkYFvf4KYwNSTve9iJlBSQyAmsXoSE0LnWw/viewform).


We are committed to creating a learning environment welcoming of all students that supports a diversity of thoughts, perspectives and experiences and respects your identities and backgrounds (including race, ethnicity, nationality, gender identity, socioeconomic class, sexual orientation, language, religion, ability, and more.) To help accomplish this:

* If your name and/or pronouns differ from those that appear in your official records, please let us know.
* If you feel like your performance in the class is being affected by your experiences outside of class (e.g., family matters, current events), please don’t hesitate to come and talk with us. We want to be resources for you.

#### Be Aware of Your Actions

Sometimes, the little things add up to creating an unwelcoming culture to some students. For example, you and a friend may think you are sharing in a private joke about other races, genders, or cultures, but this can have adverse effects on classmates who overhear it. There is a great deal of research on something called “stereotype threat,” which finds simply reminding someone that they belong to a particular culture or share a particular identity (on whatever dimension) can interfere with their course performance.

Stereotype threat works both ways: you can assume that a student will struggle based on who they appear to be, or you can assume that a student is doing great based on who they appear to be. Both are potentially harmful.

Bear in mind that diversity has many facets, some of which are not visible. Your classmates may have medical conditions (physical or mental), personal situations (financial, family, etc.), or interests that aren’t common to most students in the course. Another aspect of professionalism is avoiding comments that (likely unintentionally) put down colleagues for situations they cannot control. Bragging in open space that an assignment is easy or “crazy,” for example, can send subtle cues that discourage classmates who are dealing with issues that you can’t see. Please take care, so we can create a class in which all students feel supported and respected.

#### Be an Adult

Beyond the slips that many of us make unintentionally are a host of behaviors that the course staff, department, and university do not tolerate. These are generally classified under the term harassment; sexual harassment is a specific form that is governed by federal laws known as Title IX.

UC Berkeley’s [Title IX website](https://ophd.berkeley.edu/) provides many resources for understanding the terms, procedures, and policies around harassment. Make sure you are aware enough of these issues to avoid crossing a line in your interactions with other students. For example, repeatedly asking another student out on a date after they have said no can cross this line.
Your reaction to this topic might be to laugh it off, or to make or think snide remarks about “political correctness” or jokes about consent or other things. You might think people just need to grow a thicker skin or learn to take a joke. This isn’t your decision to make. Research shows the consequences (emotional as well as physical) on people who experience harassment. When your behavior forces another student to focus on something other than their education, you have crossed a line. You have no right to take someone else’s education away from them.

This issue is very important to your instructors. Therefore, if we cannot appeal to your decency and collegiality, let us at least appeal to your self-interest. Do not mess around on this matter. It will not go well for you.


#### Issues with Course Staff

Professionalism and respect for diversity are not just matters between students; they also apply to how the course staff treat the students. The staff of this course will treat you in a way that respects our differences. However, despite our best efforts, we might slip up, hopefully inadvertently. If you are concerned about classroom environment issues created by the staff or overall class dynamic, please feel free to talk to us about it. The instructors and DSUS welcome any comments or concerns regarding conduct of the course and the staff.

### Additional Campus Resources

* [University Health Services](https://uhs.berkeley.edu/)
* [UHS Counseling and Psychological Services](https://uhs.berkeley.edu/caps)
* [UC Berkeley Sexual Violence Services](https://svsh.berkeley.edu/)
* [Campus Academic Accommodations Hub](https://evcp.berkeley.edu/programs-resources/academic-accommodations-hub)
* [ASUC Student Advocate's Office](https://advocate.berkeley.edu/)
* [Basic Needs Center](https://basicneeds.berkeley.edu/)
* [Student Learning Center](https://slc.berkeley.edu/)

---

## Acknowledgments 🙏

Data 6 has been taught by many instructors: Jedi Tsang, Atticus Ginsborg, Edwin Vargas NAvarro, James Weichert, Jonathan Ferrari, Will Furtado, Suraj Rampure, Ian Castro, and Isaac Merritt. Data 6 and Data 94 are loosely based on Data C6, taught by Ian Castro in Summer 2020 at UC Berkeley, which in turn was based on Data 8R, taught by Henry Milner in Summer 2017, also at UC Berkeley. These classes were based on [Data 8](https://data8.org/) at UC Berkeley.
