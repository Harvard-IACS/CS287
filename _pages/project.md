---
layout: page
title: Research Project
permalink: /project
---

You will work in **groups of three** on a custom research project of your choosing. The project will span 12 weeks of the semester and will result in: (1) a high-quality, conference-style short paper (4-5 pages, excluding references); (2) a 8-minute pre-recorded video presentation; and (3) the associated code to reproduce all work.

## MOTIVATION
Since this is a graduate course, I wish to provide students with not only a solid foundation of advanced concepts, but also the opportunity to conduct _research_ within the field of NLP.
That is, students in this course will be expected to demonstrate:
- a strong understanding of the course content, via **pop quizzes** and an **exam**
- the ability to craft real-world solutions to problems, via **homework assignments** that involve implementing models on actual data
- knowledge of a particular NLP research problem; the ability to pose a related, interesting, unsolved research question; principled approaches that aim to answer the research question

Computer Science, especially Machine Learning and NLP, is a field that progresses at an incredible rate. State-of-the-art models from five years ago are often barely sufficient in serving as baseline models for any particular task.
Yet, I want everyone to gain skills that will last them for many years to come. Gaining research experience greatly helps toward this, as it requires critically reading and evaluating the latest, great approaches to a given problem. Then, one must poke holes in the current community-wide state of accepted knowledge (i.e., published research papers at top venues) and formulate specific research questions that the community at large doesn't yet know the answers to. Working toward an answer is immediately fruitful to the problem at hand. More importantly, this process of conducting research, in general, is a healthy mechanism that allows one to continuously learn forever and not rely on knowledge that will inevitably become outdated.

## RESEARCH PAPERS
In the world of research, the currency of knowledge is in the form of _research papers_. Specifically, in Computer Science, the gold standard is **conference papers**, not **journals**, and there are two formats:
- long papers (~8 pages)
- short papers (~4 pages)

Obviously, teaching _how_ to conduct research is beyond the scope of any particular course, as it's the entire purpose of a PhD. However, if you are new to research, please see [my Research Crash Course that I wrote with David Abel](). Very briefly, a research paper should:
- identify a concrete problem/issue (e.g., a new problem or an issue discovered with existing work)
- exhaustively and meticulously review and summarize related work (<span style="background-color: #FFFF00">very important</span>)
- offer novel insights or a solution to the problem
- irrefutably defend the proposed solution (e.g., offer new state-of-the-art results with **thorough experiments**). The reader should be left with no doubt that your work is a viable and useful solution to your important problem. Demonstrating this is the crux of your narrative.
- be objectively written (i.e., doesn't editorialize or use first-person pronouns)
- be specific (e.g., no [weasel words](https://en.wikipedia.org/wiki/Weasel_word) or fluff)
- not over-generalize or make bold claims beyond what its work demonstrates
- summarize your work/findings to varying degrees and styles (via the Abstract, Introduction, and Conclusion)

It is incredibly fun to brainstorm and try out/implement clever ideas you may have to a problem. As a consequence, it is natural to skimp on the literature review and to get excited about your own ideas. Don't fall into this trap, as you'll inevitably suffer the consequences in the long run. For example, it is a horrible experience to spend many weeks or months on a solution, just to later realize that it's already been tried and published. <span style="background-color: #FFFF00">Make sure you thoroughly read related works, as it can save you from unnecessary work and trouble.</span>

### GOLD STANDARD
The top NLP research conferences are:
- ACL
- NAACL (the North American version of ACL)
- EMNLP
- COLING
- AAAI (concerns AI in general, but some NLP papers are accepted)

All published works from these conferences are made available to the public for free. Simply search for any year's "accepted papers" (e.g., `ACL 2021 accepted papers`). Again, the field moves incredibly fast, so papers' results/models from > 5 years tend to be significantly less relevant. However, it is important to be aware of the full history of the problem, including past approaches from > 5 years ago.

## GUIDANCE
In this course, I aim to provide as much structure and guidance as possible so as to help each student gain high-quality, directed (not aimless) experience with NLP research. Toward this, there are several milestones/assessments throughout the project **(percentages listed below are out of the total course grade):**
- Phase 1: Proposal (5%)
- Phase 2: Abstract + Related Work + Introduction (5%)
- Phase 3: Baseline Results (10%)
- Phase 4: Check-in (not graded)
- Phase 5: Check-in (not graded)
- FINAL DELIVERABLES:
  - 4-page short paper, plus your References and Impact Statement (20%)
  - 8-minute pre-recorded presentation of your slides or a poster (5%)
  - Code with instructions on how to run it (5%)

Identifying a well-scoped, important research problem is often difficult. To help with this:
- Each homework assignment will require you to critically read a paper of your choosing and think of ideas, and you will receive credit for this brainstorming
- I will collect all of the aforementioned `Project Ideas` and share them to the class, so that all students benefit from each others' ideas
- The `Project Ideas` will facilitate finding project partners.
- We, the teaching staff, will provide feedback throughout your project.

Each project will be appointed a TF. Harvard allocates 1 TF for every 20 students. Thus, each TF will oversee roughly 7 projects. It is impossible for the TFs to be a priori familiar with everyone's custom problem/project (e.g., the background literature). Instead, you can expect your TF to:
- help you decide if your identified problem is too grand and impossible, easy, inappropriate for research (e.g., too applied and is more of a software development project)
- provide feedback on selecting a reasonable baseline model
- offer suggestions and feedback during designated Office Hours and the **required check-ins**

Further, the last four classes of the semester will be entirely dedicated to your projects; we will have an open format and will be available to help all research groups.

### READING RESEARCH PAPERS
Effectively and efficiently reading research papers is a learned skill. In short though, a common and useful approach is to consider reading each paper in three stages:
- Stage 1: read the Abstract (and optionally Introduction) (2-10 minutes)
- Stage 2: read the Conclusion, then skim most of the paper (10-30 minutes)
- Stage 3: thoroughly read the entire paper, with the goal of being able to understand the intricate details (30 minutes - 3+ hours)

Only proceed to a given stage after you've deemed it necessary from the previous stage. Notice that each subsequent stage requires roughly an order of magnitude more time (2 minutes, 20 minutes, 200 minutes). It's not worth your time to thoroughly read most papers, simply because their work isn't closely related to your work. In other words, **it is completely unnecessary to fully read every paper that looks interesting on the surface (e.g., title)**. This is especially helpful as you are just starting out on a new project, when you are still learning the scope of the field. Moreover, essentially no paper is _perfectly, fully_ understandable; every paper has a page limit, and there's only so much explaining one can detail. Thus, it's often the case that some equations will have some poorly-defined variables, or for there to be tiny details about the data and models that are left out. So, please don't waste your time by treating every paper as an oracle that is important for your work. **Only the most related works are worth spending many hours diving into.**

I highly recommend using [ConnectedPapers](https://www.connectedpapers.com/) to assist in finding related works.

You may find on [arXiv.org](https://arxiv.org/) a few highly-useful papers. Beware, though, **arXiv papers are unvetted, pre-prints that are not peer-reviewed.** It is common practice for authors to first place their paper on arXiv, before submitting it to top-tier conferences (a la flag-planting). So, while some of arXiv papers will go on to become incredibly impactful published papers, the majority will not. If you find any arXiv paper that seems useful to your project, search for it on [Semantic Scholar](https://www.semanticscholar.org/) or [Google Scholar](https://scholar.google.com/) to see if it's been subsequently published in a top-tier research conference. This will help you assess how much stock to place in the given paper.

#### MORALE
I encourage everyone to please not feel intimidated by the breadth and depth of NLP research papers. You are in a safe and structured class environment, and I want to see everyone learn and grow. I hope everyone feels inspired to read tons of papers (even if they seem confusing at first), come up with several research questions and ideas, and execute your envisioned solutions as quickly as possible. In research, most attempted solutions do not work -- this is the case for _everyone_. That's part of the process and the necessary path for successfully contributing new nuggets of knowledge to a field. That's the beauty and fun of science. The key is to "fail fast", learn from each experiment's results, and to document your insightful conclusions and successes.

## EXPECTATIONS

### LITERATURE SEARCH/REVIEW
It is easy to detect when one has conducted an insufficient, non-comprehensive review of past works. For example, the cited papers are old, only loosely related to the problem/project, are too generally related, and only a few are listed. There is no magical number, but it is reasonable to expect that a well-researched short paper's literature review involved <span style="background-color: #FFFF00">each student to skim ~50+ abstracts, skim 25+ papers, and to thoroughly read a dozen papers</span>. Each project varies.

### QUALITY OF RESEARCH
This is likely everyone's first experience conducting NLP research, and that is completely fine. That is truly the point of this course -- to provide a structured yet challenging introduction to the latest, advanced techniques in NLP. Since research papers are the de facto medium for detailing and disseminating new knowledge, we set this as your goal. Specifically, you should write a 4-page short paper, using [the templates found here](https://2021.aclweb.org/calls/papers/#paper-submission-and-templates).

I highly recommend that your team uses [Overleaf](https://www.overleaf.com/) to collaboratively edit your paper.

To be clear, your goal is to produce a paper that is **worthy of submitting to ACL/NAACL/EMNLP**. Of course, we only have one semester together, and research results are always impossible to predict. <span style="background-color: #FFFF00">Thus, you will not be evaluated on if your research results are profound and actually worth submitting to a conference; rather, you will be evaluated on all aspects of how you _conducted_ research</span> (e.g., successfully identifying an important problem, thoroughly reading and summarizing the related work, coming up with reasonable solutions, methodically executing those ideas, effectively writing and orally-presenting your work).

You are also expected to include an Impact Statement and instructions on how to reproduce/run your code. Further details are in the **DELIVERABLES** section below.

### SUCCESSFUL EXAMPLES
- [ACL 2021 Short Papers](https://2021.aclweb.org/calls/papers/#short-papers)
- [NAACL 2021 long and short papers](https://2021.naacl.org/program/accepted/)
- [EMNLP 2020 short papers](https://2020.emnlp.org/papers/main)
- A few years ago, [Sasha Rush](http://rush-nlp.com/) offered a version of CS287r, whereby students [Josh and Joe published their course's research project](https://aclanthology.org/D19-1109.pdf) in EMNLP.
- Jeff Huang maintains a [list of best papers](https://jeffhuang.com/best_paper_awards/) from many conferences. For the purposes of this class, the list of best papers is only useful for inspiration and to get a glimpse into how varying the styles can be amongst great research.

## DELIVERABLES

NOTE: Research projects naturally evolve over time. So, if your project shifts gears as it progresses, that is completely fine. You can answer a _slightly different_ research problem than what you initially set out to answer, as long as it's in the same ballpark. With that said:
- after the Phase 1 deadline, you are expected to settle on a project and team members. We can help with this process.
- all Phase deadlines must be met on time
- if you slightly change focus, you must:
  - discuss this change with us ahead of time
  - "catch up" by re-submitting the previous phases
- projects cannot change team members after Phase 2
- projects cannot change focus after Phase 3.

As an example, after successfully submitting Phase 2, but before Phase 3 is due, you might change focus a bit. If so, by the Phase 3 deadline, you would need to also re-submit Phase 1 and Phase 2 materials that reflect your new research goal. Once you've submitted Phase 3, you are locked in to work on that project with the same team members that you listed by the Phase 2 deadline.

### PHASE 1: PROPOSALS (5%)
For this initial stage, you will brainstorm research project ideas and write a 1-page proposal about one of them. Specifically, you must:
- contribute a few research project ideas (e.g., 1-3) within the `Research Brainstorming` spreadsheet
- within that spreadsheet's `Student Roster` tab, add your name (required) and any additional background information (optional) you'd like to share about yourself. This will help everyone balance their team as they're considering teammates
- for one of your research ideas, write a 1-page summary that:
  - describes the problem in terms of why it's an important one (every published paper's abstract/intro accomplishes this. so, we're looking for something similar, not ground-breaking claims like how it will impact society)
  - lists a few (3-5) related papers and any commentary you may wish to include
  - details the measurement for success (e.g., BLEU score, F1 score, a novel comparison, etc)
  - is there a dataset you have in mind?
  - optionally describe a few ideas (1-2) you have for solving the problem
- indicate in the `Research Brainstorming` spreadsheet which of your ideas you selected for your 1-page writeup.

We'll provide feedback on your proposal, and we'll also help narrow down all projects to a list of just ~20 projects. 

### PHASE 2: ABSTRACT + RELATED WORKS + INTRODUCTION (5%)
Here, you will form teams and you all will collectively refine your **Phase 1 Proposal** and write the first three sections of your research paper (using the LaTeX template):
- Abstract
- Related Works
- Introduction

Since you are still becoming familiar with your project, the Related Works section doesn't have to be perfect or exhaustive yet. The expectation is that you've clearly identified the most similar works and the broader, tangential scope of related works. Likewise, the Introduction should clearly introduce and describe your problem. I expect this section to improve significantly over time, but for now it should be well-organized, such that any outsider could easily follow and digest your problem and the scope of it.

### PHASE 3: BASELINES (10%)
You will improve your Abstract, Related Works, and Introduction, while incorporating feedback from Phase 2. Additionally, you will start new sections titled **Models** and **Experiments**. Specifically, you are expected to explain your system in any way you see fit, which is _usually_ in a section titled **Models** or Methodology. Your experiments section should describe your exact setup, along with your baseline model's results (usually in a sub-section title Results). Again, it is okay if these results aren't good yet, as nobody can perfectly predict the outcome. This is the nature of science and research. However, we do expect to see a reasonable approach for a baseline model, one that is not expected to perform very well but is a simple yet sensible initial approach to the problem. As a reminder, baseline results are critical to your work as they will help inform you of future directions to take, and they will serve as a reference point for your later results. That is, if you later develop a complicated, technical solution, how should one interpret its results? How will we know if its particular accuracy score is actually good? The baseline model provides that contrast and puts all future experiments into perspective.

### PHASE 4: HEAVY EXPERIMENTATION + CHECK-IN (0%)
Before the Phase 4 deadline, update us on your progress via: (1) submitting on Canvas your current working draft of your paper; and (2) speaking to us in Office Hours. You do not need to add any new sections to your paper, such as Discussion or Conclusions. This is because we want to ensure you spend sufficient time on your actual model, results, and refining the current contents of your paper.

### PHASE 5: HEAVY EXPERIMENTATION + CHECK-IN (0%)
Before the Phase 5 deadline, update us on your progress via: (1) submitting on Canvas your current working draft of your paper; and (2) speaking to us in Office Hours or during class time. You do not need to add any new sections to your paper, such as Discussion or Conclusions. This is because we want to ensure you spend sufficient time on your actual model, results, and refining the current contents of your paper.

### FINAL DELIVERABLES (30%)
#### 1. PAPER + IMPACT STATEMENT
- Using the [ACL templates](https://2021.aclweb.org/calls/papers/#paper-submission-and-templates), write a short paper that is exactly 4 pages (when excluding your references and impact statement). To be clear, your references do not count toward this 4-page requirement. So, your paper will likely be 5 pages in total length when you count the references.
- Append your paper+references with an **Impact Statement** that details the possible ethical and societal ramifications of your project. The length should be at least 2 paragraphs. The [full expectations/details can be found here](https://docs.google.com/document/d/1OiDYo0cRj1ybe0n6-4TS7jWlZBNPzxHRBRN3_DsJsIs/edit?usp=sharing), which is also used for my IACS Master's Capstone Research course. This may bring your total page count to 6 pages.

You will be evaluated on:
- all technical aspects of your research, ensuring that you:
  - identified a sound problem
  - conducted a thorough literature review
  - crafted a reasonable approach(es)
  - ran thorough experiments
  - provided a detailed analysis of results
- the clarity of your writing (e.g., ease of reading and understanding, grammatical errors)
- the technical appropriateness of your writing (e.g., no subjectiveness, weasel words, or fluff)
- clear figures with meaningful captions
- your Impact Statement (e.g., is it thoughtful and reasonable?)

**Submission:** Upload your entire 5-6 page paper (`.PDF`) to Canvas.

#### 2. PRESENTATION (PRE-RECORDED)
- Your team should make slides or a poster, whichever you prefer.
- Record your team giving a presentation of it. We recommend using Zoom, due to its ease of presenting/recording. <span style="background-color: #FFFF00"><b>There is a strict maximum limit of 8-minutes!</b></span> If you exceed 8-minutes or speed up the recording (e.g., 1.25x), we will deduct 50% from the maximum presentation grade, meaning the most you can earn is 2.5% of your total course grade instead of 5%. This is strict because we need to present your video during the final class session, and any prolonged or sped-up videos will only hinder the final showcase. It is obvious and distracting when you speed up your video, if even only a little bit. Do not do this.

You will be evaluated solely on:
- the clarity and narrative of your poster or slides
- the clarity of your presentation 

That is, **your presentation grade will not include an evaluation of the technical aspects** of your project. That would be redundant.

**Submission:** Upload (a) your slides or poster; and (b) your video to Canvas.

#### 3. CODE
Make a `.zip` file that includes:
- your code
- a short README file that details how to run your code
- your data, if including your resulting .zip file remains less than 100mb in size. If including your data yields a filesize > 100mb, do not include your data in the .zip file. In this case, post it online (e.g., Google Drive) and describe in your README documentation where the data can be downloaded

You will be evaluated on your documentation and the ease in running/reproducing your results.

**Submission:** Upload your `.zip` file to Canvas.
