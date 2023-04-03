# Course Syllabus

(Last updated: Feb 27, 2023)

:::{admonition} What is data science?
:class: tip
Data science is about turning rich data into **actionable insight** and making data **impactful**!
:::

This course aims to familiarize you with various data science pipelines using examples with different data types.
This course is suitable for students who already have some experience in processing data and will work (or are currently working) with a large amount of data, especially focusing on obtaining insights from data through prediction or explanation techniques.
This course is not intended to cover all topics in data science exhaustively.
Instead, it introduces ways of working with structured (e.g., sensor measurements) and unstructured data (e.g., text and image).
Also, this course will cover human-centered approaches in data science for social impact.

It is important to keep in mind that this course does not aim to teach you details in programming, machine learning, statistics, or visualization.
Instead, this course will teach you how to integrate various techniques (e.g., data wrangling, statistical analysis, data modeling, data visualization) together to perform a data science task.
Also, notice that this course assumes someone already collected datasets for you and does not teach you how to collect data in the real world.
Data collection is a topic that could take a very long time to explain and is mostly out of the scope of this course.

:::{note}
Notice that the course instructor writes the syllabus from the first-person perspective.
:::

## Learning Goals

By the end of the course, we expect you to be able to:
- Explain and execute the entire data science pipeline (including data pre-processing, wrangling, analysis, modeling, evaluation, and visualization).
- Perform data science tasks with images (e.g., object recognition), text (e.g., topic modeling), and structured data (e.g., those from sensor networks) using the Python programming language.
- Critically reflect on the model performance using various metrics and obtain meaningful insights from data analysis.

## Prerequisites

This course expects you to have the following prior knowledge:
- Intermediate level of Python programming (e.g., knowing different data types and data structures, knowing how to set up the Jupyter Notebook programming environment)
- Basic level of machine learning (e.g., knowing what supervised and unsupervised learning means, understanding the differences between classification and regression)
- Basic level of information visualization (e.g., knowing how to draw plots using python packages, understanding the differences between a bar chart and histogram)
- Basic level of research methods (e.g., knowing what "research questions" mean, understanding basic hypothesis testing methods like t-test)

## Course Structure

This course has 8 weeks in total.
Among them, weeks 4 and 8 will be used for mid-term and final exams.
Except weeks 4 and 8, each week has two lectures (hoorcollege) and a work session (werkcollege).
Week 4 has only one lecture for discussing the mid-term exam (no work sessions).
Week 8 only has the final exam (no lectures nor work sessions).
Refer to the [overview page](home#schedule-outline) for the course schedule.

Lectures will be given in English, as well as all the teaching materials.
Work sessions will given in either Dutch or English, depending on the TA's choice.

Course materials contain slide decks, Jupyter notebooks, and three modules.
Each module contains preparation, turorials, and assignments for learning how to perform different data science tasks.
Modules are designed to have you work to have hands-on experiences.

## Virtual/Physical Settings

In principle, I will give the lecture in person in the physical classroom.
I will open a virtual classroom link to live stream the lectures (refer to Canvas for the links).
If I cannot give the physical lecture due to unexpected situations, I will make an announcement on Canvas to give the lecture in the virtual classroom.

It is important to notice that when I give the lecture in the physical classroom, the virtual classroom will be muted and not be actively monitored.
It is very challenging for me to pay attention to both the physical and virtual audiences, and priority will be given to people who attend the physical classroom.

I will also do my best to record the lectures (with the camera pointing to my face only) and make the recordings available on Canvas.
However, there is no professional support for recording in my course, so there is no guarantee of the recording quality.
For example, you may experience poor sound quality or incomplete lectures in the recorded video.

In principle, the work sessions (werkcollege) are in-person only.
If the TAs cannot attend the physical classroom due to unexpected situations, they may give the sessions virtually.

## Grading: Exams and Assignments

Your final grade is based only on exams (the mid-term exam is 40% weight, and the final exam is 60% weight).
There is one resit for the course, which counts as 100% weight.
According to the [UvA rule](https://www.uva.nl/en/about-the-uva/policy-and-regulations/rules-and-regulations/teaching/teaching.html#Model-regulations), the most recent grade will apply in the event of a resit regardless of the outcome.
This means that if you take the resit, your resit score will override the weighted sum of your mid-term and final exam grades.

The base grade for the exam is 1, and there is no minimum grade requirement for each exam.
However, according to the [OER rule](https://student.uva.nl/onderwerpen/onderwijs-en-examenregelingen-oer), you need to get at least 5.5 in the final score (i.e., the weighted sum of the scores of two exams) to pass the course.
After each exam, the teaching team will grade the exam and release the grades within 20 working days.
After the grade is released, we will announce on Canvas how students can inspect their exam results.

### Exams

Exam instructions and materials will all be in English.
We tried to write questions in Dutch, but we found that the Dutch version of the questions are ambiguous, as the course materials are in English.
Providing materials in English allows us to match the exam questions clearly with course materials.

Exam is onsite.
It is not allowed to do exams at home.

The exam may have multiple-choice, passive-coding, and active-coding questions.
The multiple-choice questions will be used to test your general knowledge of data science.
The passive-coding questions are in the form of multiple-choice questions to test your coding knowledge.
For example, we may put some code in the question description and ask you to select the option that best explains what the code is doing (or the expected output of the code).
The active coding question is similar to the coding assignments.
We will provide only one mock-up exam before the mid-term exam for you to practice.

:::{warning}
The final exam and the resit will be more difficult than the mid-term exam, since you have more time to study the materials.
The resit will be at least as difficult as the final exam.
:::

:::{warning}
The University of Amsterdam owns the materials in this exam (e.g., the question sets), which means the materials are copyright-protected. You must keep the exam content confidential and are not allowed to copy or distribute the content in any form.
:::

#### Multiple-Choice Questions

The formal exam will be conducted using the [ANS sytem](https://ans.app/).
If the exam has multiple-choice questions, we will use guess correction for your score on the multiple-choice questions.
Details about how the ANS system uses guess correction is in [this online document](https://support.ans.app/hc/en-us/articles/360014340098-Guess-correction).

#### Coding Questions

If the exam has coding questions, we will provide a Jupyter notebook with instructions.
Then, the notebooks that you handed in will be auto-graded with hidden test cases using the [nbgrader package](https://nbgrader.readthedocs.io/en/stable/index.html).

Coding questions in the exams may have restrictions on functions (i.e., the ones that you are not allowed to use).
Please pay attention to the question instructions.

:::{warning}
Using the restricted functions will result in a 0 score for the corresponding question.
:::

Your score for each coding question is based on the number of passed hidden test cases (excluding the one that we will provide).

:::{warning}
We do not give scores to failed test cases or syntax errors.
Also, if you forgot to upload the code for the exam, the grade will be zero for the coding part (we do not accept answers by email or in other ways, and we also cannot upload your script for you).
:::

Before submitting the coding exam, you need to check if there are errors and fix them by running the entire provided Jupyter notebook from scratch (i.e., click on the “Restart All Kernels and Run All Cells” in the “Kernel” menu on the JupyterLab interface).
We will provide test cases in the exam Jupyter notebook for you to self-check.

:::{note}
You will have no internet access during the exams.
However, you can use the question mark "?" syntax to [access the IPython help](https://ipython.readthedocs.io/en/stable/interactive/python-ipython-diff.html#accessing-help) to check the documentation of functions.
:::

<a name="cheat-sheet"></a>
#### Cheat Sheet

During the exam, you may bring an A4-size cheat sheet with you.
You can choose to handwrite or print the content on both sides of the cheat sheet.
Please keep in mind that you are not allowed to bring other materials, such as books.
You are also not allowed to bring or use any other digital devices (besides the computer for the exam).
After the exam, you can take the cheat sheet back with you.

The cheatsheet is designed to reduce your workload in memorizing details (e.g., math equations) and also help you prepare for exams.
For example, maybe there are parts that confuse you when you study course materials, and you may put them in the cheatsheet.
Another example is that you may put bullet points that can help you recall information (e.g., some important concepts).

#### Important Notice During the Exam Day

- There are scrap papers at the exam location, and we will provide them to you if you need them.
- Please make sure to bring your ID. We will check your ID at the exam location.
- Please remember to sign the attendance list after someone has checked your ID.
- You are allowed to enter the exam room up to 30 minutes past the exam starting time. Anyone who arrives later cannot participate in the exam.
- You are not allowed to leave the exam room during the first 30 minutes and last 15 minutes of the normal exam schedule. The purpose of the rule is to prevent fraud (during the first 30 minutes) and disturbance (during the last 15 minutes). 

### Assignments

Assignment instructions and materials will all be in English.

Assignments are not graded, but you should do them as they are essential in improving your data science skills.
You also do not need to submit the assignments.
We expect you to do the assignments by yourself and discuss them with the TAs in the work sessions.
The questions in mid-term and final exams can have similar questions as those in the assignments.
Doing the assignments will also help you greatly in preparing for the exams.

## Hygiene

Please follow [the advice from RIVM](https://www.rivm.nl/en/coronavirus-covid-19/recommendations-companies-and-institutions) (National Institute for Public Health and the Environment) regarding coronavirus measures.
If you have symptoms associated with COVID-19, please stay home.
You can use the online lecture live stream, the lecture recordings, and TicketVise on Canvas to participate in the course, as documented in the [virtual/physical settings](#virtual-physical-settings) and [communication principles](#communication-principles).

<a name="register"></a>
## Course Registration

For general course registration, please refer to the [UvA document](https://student.uva.nl/en/topics/course-registration).
The Faculty of Science handles registration procedures.
I do not handle course registration matters.
If you want to register for the course but you are late, or if you have problems signing up for the course, please get in touch with the following email: vakaanmelding-fnwi@uva.nl

<a name="change-group"></a>
## Change Groups

The course groups are automatically assigned.
If you need to change groups, please refer to the instruction in the [course registration document](https://student.uva.nl/en/topics/course-registration) to submit a request using the GLASS system.

## Course Attendance

I do not track the attendance of this course (e.g., lectures, work sessions) and expect students to follow their own learning progress.
You do not need to notify me in case of absence.

## Fraud and Plagiarism

This course follows the [UvA Fraud and Plagiarism Regulations](https://student.uva.nl/en/topics/plagiarism-and-fraud).
When in doubt, please consult the “Regulations Governing Fraud and Plagiarism for UvA Students” document in [this UvA link](https://www.uva.nl/en/about-the-uva/policy-and-regulations/rules-and-regulations/teaching/teaching.html#Rules-and-regulations).

## Communication Principles

Class members are expected to treat others with mutual respect and appreciation regardless of any differences.
It is my intent that students from all diverse backgrounds and perspectives be well served by the course.

The best ways to contact TAs and me outside the lectures and work sessions are via email or TicketVise (similar to the discussion board) on Canvas.
Please keep in mind that responses from TAs and me could be delayed due to weekends or holidays.

All course announcements will be on Canvas.
I expect students to monitor Canvas periodically for any changes in deadlines, or any other announcements.

:::{admonition} Moving the Discussion at the Speed of Trust
In group discussions, lectures, and all the sessions, please follow the principles below:
- Practice mutual respect
- Be an active listener
- Do not make assumptions, ask questions
- Suspend judgment
- Invite and honor the diverse range of opinions and experiences
:::

## Academic Code of Conduct

- OK to discuss assignments with classmates
- OK to use existing solutions as part of your projects or assignments (but you need to clarify your contributions and cite the source properly)
- OK to publish your project portfolio (e.g., source code) after the course is over
- `NOT OK` to ask someone to do assignments or projects for you
- `NOT OK` to copy solutions or written content from classmates
- `NOT OK` to pretend that someone’s solution or idea is yours
- `NOT OK` to post solutions for your assignment or course exams online
- ASK the teaching team if unsure

## Support for Students Wellness

If you experience mental health concerns or stressful events that can interfere with learning and daily activities (such as strained relationships, increased anxiety, substance use, feeling down, difficulty concentrating, and lack of motivation), UvA services are available.
You can learn more about (confidential) mental health services available on campus in [this UvA link](https://student.uva.nl/en/topics/mental-health).

## Accommodations for Students with Disabilities

If you have a disability and require accommodations, please take a look at [this UvA link](https://student.uva.nl/en/topics/studying-with-a-disability-dyslexia-or-chronic-illness) to request special facilities or additional resources.

## Resources

We curated a [list of resources](resources) that inspired the development of this course. The course instructor greatly appreciates them.

## Q&A

Below is a list of commonly asked questions and their answers.

**Q1: Can I take exams remotely?**
- You have to do the exams on-site (in the physical exam room). It is not allowed to do exams remotely (e.g., at home).

**Q2: What should I do if I have missed (or need to miss) an exam, such as due to medical issues or personal reasons?**
- The best option is to take the resit, which is designed for these situations. The resit schedule is on [datanose](https://datanose.nl).
 
**Q3: I want to change the study group. What should I do?**
- Read details in the [Change Group section](#change-group) in this syllabus.

**Q4: I need help in course registration (e.g., I register the course late). What should I do?**
- Read details in the [Course Registration section](#register) in this syllabus.

**Q5: What is the cheatsheet for the exam and how should I prepare for that?**
- Read details in the [Cheatsheet section](#cheatsheet) in this syllabus.

**Q6: What to do if I have conflicts with my exam schedule (e.g., two exams are at the same time)?**
- Contact the program coordinator or [study adviser](https://student.uva.nl/en/topics/study-adviser) for solutions.

## Acknowledgements

We greatly appreciate the help from the teaching administration and management team of the UvA Informatics Institute in supporting this course.
We also greatly thank the following open-sourced course for inspiring the set-up of this course:
- [IOB4-T3: Machine Learning for Design in TU Delft](https://ml4design.com/ml4design.2021-2022/)
