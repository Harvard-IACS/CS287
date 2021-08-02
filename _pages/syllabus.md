---
layout: page
title: Syllabus
permalink: /syllabus
---
## INTRODUCTION
Welcome to <font color="#3778AE">AC295/CS287r/CSCI E-115B (DCE)</font>!

Our world is clearly inundated with digitized information nowadays, most of which is text (e.g., webpages, social media posts, news articles, long-format stories, etc). How can we use computers to “understand”, process, and leverage this information to perform meaningful tasks? **Natural Language Processing (NLP)** is concerned with exactly this. This course will provide you with the opportunity to learn the latest, advanced **machine learning/ deep learning** approaches to solve the most popular and powerful NLP tasks. Further, a core component of the course will concern research, as you’ll produce an **original research project** while working in groups of three students.

## LEARNING OBJECTIVES
By the end of the course, you will be able to:
- understand the theoretical concepts behind the common NLP tasks and models
- write effective programming solutions to popular problems in NLP
- tackle your own, novel goals with text data once this course is over (e.g., if you have downloaded thousands of tweets over the past week, you’ll be able to come up with reasonable solutions to (1) identify sentiments about any phrase; (2) make classification predictions; (3) identify aliases for any entity, and much more)
- conduct substantial, original NLP research (e.g., critically read papers published in top conferences, understand them, and execute your own ideas so as to answer novel research questions)

## PREREQUISITES
- **NLP**: No previous experience expected or necessary
- **Programming**: at least one class with substantial object-oriented programming
- **Math**: basic foundation in probability and calculus (e.g., joint probability, conditional probability, partial derivatives) <font color="#7D2790"><b>STAT 110</b></font> or above is sufficient.
- **Machine Learning**: basic knowledge of Machine Learning (e.g., Feed-forward Neural Nets, Backpropagation, what train/dev/test splits are, regularization) Any one of these is sufficient: <font color="#D36B21"><b>CS181</b></font>, <font color="#31493C"><b>MIT’s 6.036</b></font>, <font color="#CC30B2"><b>CS109A</b></font>, or <font color="#4B9214"><b>CS109B</b></font>, etc

## SOFTWARE
You will program using (a) **Python** and (b) **PyTorch** or **TensorFlow**, extensively. If you are not already familiar with TensorFlow or PyTorch, you will be expected to learn it on your own. We will also make use of Python libraries such as **NumPy** and **Scikits-learn**.

## COURSE STRUCTURE
The main delivery of information will be via **Lectures**, which will occur every time class meets (aside from Research Project presentations). Your learning will be assessed via ~eight <font color="#E57A70"><b>pop quizzes</b></font>, one <font color="#7D2790"><b>exam</b></font>, three <font color="#5B90E0"><b>homework assignments</b></font>, and a <font color="#4ECD59"><b>research project (in groups of three students)</b></font>. Your research project will require you to read/skim dozens of research papers on your own, based on your interests.

### LECTURES
Every class session will contain a lecture. When <font color="#E57A70"><b>pop quizzes</b></font> are given, they will occur at the beginning of the lecture and will last ~10 minutes. Lectures will concern:

1. Course Overview + Intro
2. Representations: Bag-of-Words, TF-IDF, word embeddings
3. Language Models: n-grams
4. Language Models: word2vec and GloVe
5. RNNs + LSTMs
6. Bidirectional LSTMs + ELMo
7. seq2seq + Attention
8. Machine Translation
9. Transformers (vanilla)
10. BERT
11. BERT for downstream tasks: Sentiment Analysis and NER
12. GPT-2
13. Summarization
14. Bias and Fairness
15. NLU: Slot-filling and intent recognition
16. Entity Linking
17. Coreference Resolution
18. Commonsense Reasoning
19. Adversarial NLP
20. Interpretability and Probing Tasks

### <font color="#E57A70">POP QUIZZES (10%)</font>
Instead of having exams serve as the only way to assess learning of theoretical content, we wish to provide multiple stages of feedback on any particular topic. So, we will conduct <span style="background-color: #FFFF00">~8 short, unannounced pop quizzes (~10 minutes each)</span>, which will occur at the beginning of lectures (on paper). The content can be from **any previous course content,** including material that was taught in the most recent lecture. 

Quizzes can be viewed as being a gentle assessment and accountability to ensure each student is on the right track. **Each student’s worst three quizzes will be dropped and will not contribute to one’s course grade** (the remaining will comprise 10% of the total course grade).

Make-up quizzes will be only given to students who have a valid excuse (e.g., an approved medical or personal emergency).

**NOTE:** DCE students will access the pop-quizzes and exam online for up to 24 hours after the class session. Upon opening the online version of the quiz and exam, the DCE student will have the same time constraints to complete it as in-person students.

### <font color="#7D2790">EXAM (10%)</font>
One exam will be conducted during lecture and will count **10% of the total course grade.** The exam will concern (a) theoretical concepts, a la quizzes (e.g., multiple choice, fill in the blank, short answer), and (b) practical applications, a la homework questions (e.g., write or assess some code). There will be no questions concerning research or research papers.

**NOTE:** DCE students will access the pop-quizzes and exam online for up to 24 hours after the class session. Upon opening the online version of the quiz and exam, the DCE student will have the same time constraints to complete it as in-person students.

### <font color="#5B90E0">HOMEWORK ASSIGNMENTS (30%)</font>
There will be four equally-weighted, **individual** homework assignments. See the Collaboration Policy below for details. **Students will have a total of three unexcused late days to use throughout the semester without any penalty.** NOTE: valid excuses (e.g., medical excuses) do not count toward your three allotted “free” late days. <span style="background-color: #FFFF00">Any late days used beyond these three will result in a deduction of 10 points per day.</span>

For example, let’s say a student has already used three unexcused late days earlier in the semester, and then turned in another homework assignment one day late. If the graded homework received a 88%, then it will be reduced to a 78% due to being a day late. If that student had turned in the assignment two days late (meaning, a grand total of five late days used), then that particular assignment would have received a 68%, due to being two days late.

If any particular homework assignment is **late beyond three unexcused days, it will not be accepted or graded.** The grade will be 0%.

<font color="#5B90E0"><b>RESEARCH PAPERS:</b></font>
Each homework assignment will require students to select and read one research paper published in ACL, NAACL, or EMNLP in 2020 or 2021. Students will critically evaluate the paper, ask pertinent questions, and draft 1-2 very short research project ideas from it (10% of HW grade).

**Additionally, on each homework assignment, students may “earn back” up to 5 points by writing a summary for a second paper. By “earn back”, I mean that each homework can only receive a maximum of 100 points.** For example, if a student received a 93 on a given homework assignment, they are eligible to receive up to 98 by writing a summary for a second paper. If a student had received a 99, summarizing a second paper can only bring them up to a 100. There’s a lot of rationale behind this -- the biggest reason being that all final grades may need to be curved once the semester is over, and allowing “extra credit” beyond a 100 amplifies the academic performance disparity and nullifies the effects of curving grades.

### <font color="#4ECD59">RESEARCH PROJECT (50%)</font>
Throughout the semester, students will **work in groups of three** on a research project of their choosing. To help facilitate ideas for projects, we will maintain an on-going, collaborative list from all students, which will include the ideas submitted as part of the homework assignments.

**Project assessment (percentages listed below are out of the total course grade):**
- Phase 1: Proposal (5%)
- Phase 2: Abstract + Related Work (5%)
- Phase 3: Baseline Results (10%)
- Phase 4: Check-in (not graded)
- Phase 5: Check-in (not graded)
- FINAL DELIVERABLES:
  - 4-page short paper (20%)
  - 8-minute pre-recorded presentation of your slides or a poster (5%)
  - Code (5%)

[Further details are listed here](project) and will be discussed in class.

The following awards will be given to projects:
- **Marie Curie Award:** best technical solution
- **Steve Jobs Award:** most elegantly simple yet effective solution
- **James Baldwin Award:** best communicated (oral and written) 

<span style="background-color: #FFFF00">These awards will be voted on by all students, and each student from an award-winning team will receive <b>5 extra points to one’s final course grade.</b></span>

## RESOURCES

**No textbook is required.**
- [Canvas (coming soon)](): homework assignments
- [EdStem (coming soon)](): discussion forum/help, question bank, announcements, Extension School's pop quizzes
- [Project Ideas (coming soon)](): on-going spreadsheet to collaboratively find and create research projects
- [Emergency Helpline](mailto:cs287helpline@gmail.com): for private concerns, issues, and questions (not course-content related) 
- [Supplemental Resources](supplemental): a compilation of useful, external resources

## HELP
Students are encouraged to regularly read and actively participate in the **Ed forum.** This is intended to be a shared learning environment for all students in the class. Do not post any code on the forum, though. **Doing so will violate our academic integrity policy.**

TFs and I (Chris) will hold scheduled **Office Hours** throughout every week. The expectation is that you’ve already thought about the content and have very specific questions. That is, the intent of Office Hours is not to simply repeat the same content again, but to help clarify your understanding by addressing issues you’re currently facing. The TFs may help you with your code, if you've demonstrated that you have already put forth significant effort and aren't relying on them. In an attempt to help as many students as I can in a timely fashion, I will not assist in code.

## COURSE POLICIES
### COLLABORATION POLICY
<span style="background-color: #FFFF00"><b>The quizzes, exam, and homework assignments must be conducted individually.</b></span> However, no single student should feel alone in the course. So, we encourage you to talk with and discuss the assignments with your fellow classmates, but this must be at the _conceptual_ level. That is, <span style="background-color: #FFFF00">no student should ever see another student's solutions or code. If you post or share your homework assignment online (even if it only contains the questions and not solutions), this violates our academic policy and you will be reported to the university. This includes posting your assignment on GitHub. Do not do this.</span> In other words, your homework assignment is a private copy that only you can see. If you're unsure if something is allowed, please speak with us first. Any violation to the above constitutes Academic Dishonesty and will be reported.
  
We discourage you from using publicly-available code online, as you'll learn more if you write your code from scratch. However, **if you find useful code online that you wish to use, that is perfectly fine, but you must cite it.**

As a reminder, if a student cheats, it is not only harmful to one's own education but it also impacts everyone else in the course -- as it creates an unfair environment and sacrifices the integrity of the entire course. For this reason, we actively check to ensure your code hasn't been plagiarized or posted online.
  
### ACADEMIC HONESTY
Ethical behavior is an important trait of anyone who works in the fields of Computer Science, Machine Learning, Data Science, NLP -- from ethically handling data, to thinking of the ramifications of one’s models, to attribution of code and work of others. Thus, in AC295, we place strong emphasis on Academic Honesty.

### COMMUNICATION FROM STAFF TO STUDENTS
Class announcements will be through Ed Forum.

### ACCOMMODATIONS FOR STUDENTS WITH DISABILITIES
Students needing academic adjustments or accommodations because of a documented disability must present their Faculty Letter from the [Accessible Education Office (AEO)](https://aeo.fas.harvard.edu/) and speak with Chris by the end of the third week of the term. Failure to do so may result in us being unable to respond in a timely manner. All discussions will remain confidential.

### DCE ACCOMMODATION REQUESTS
Harvard Extension School is committed to providing an inclusive, accessible academic community for students with disabilities and chronic health conditions. The Accessibility Services Office (ASO) (https://extension.harvard.edu/for-students/support-and-services/accessibility-services/) offers accommodations and support to students with documented disabilities. If you have a need for accommodations or adjustments, contact Accessibility Services directly via email at accessibility@extension.harvard.edu or by phone at 617-998-9640. 

### DCE ACADEMIC INTEGRITY.
You are responsible for understanding Harvard Extension School policies on academic integrity (https://extension.harvard.edu/for-students/student-policies-conduct/academic-integrity/) and how to use sources responsibly. Stated most broadly, academic integrity means that all course work submitted, whether a draft or a final version of a paper, project, take-home exam, online exam, computer program, oral presentation, or lab report, must be your own words and ideas, or the sources must be clearly acknowledged. The potential outcomes for violations of academic integrity are serious and ordinarily include all of the following: required withdrawal (RQ), which means a failing grade in the course (with no refund), the suspension of registration privileges, and a notation on your transcript. 

Using sources responsibly (https://extension.harvard.edu/for-students/support-and-services/using-sources-effectively-and-responsibly/) is an essential part of your Harvard education. We provide additional information about our expectations regarding academic integrity on our website. We invite you to review that information and to check your understanding of academic citation rules by completing two free online 15-minute tutorials that are also available on our site. (The tutorials are anonymous open-learning tools.) 
