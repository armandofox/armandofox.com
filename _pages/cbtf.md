---
title: "CBTF"
permalink: /cbtf
type: page
layout: single
sidebar:
  nav: "random"
  test: "main_sidebar"
---


# Computer-Based Testing at UC Berkeley

We care about computer-based testing both because it is a key
ingredient of scalable mastery learning and because it provides an
important level of academic integrity for summative assessments.
Read whichever background speaks to you most...


<style>
  .responsive-row { display: flex; flex-direction: column; gap: 20px; }
  @media (min-width: 600px) {
    .responsive-row { flex-direction: row; }
    .responsive-row > div { flex: 1; }
  }
</style>

<div class="responsive-row">
  <div>
  <h2> Mastery Learning</h2>

  As far back as 1968, Benjamin Bloom and others recognized that if
  you give students <i>schedule flexibility</i> when working through
  material (since some students learn certain concepts faster than
  others) and <i>multiple opportunities to practice</i> (and to
  demonstrate mastery, such as through second-chance or re-take
  exams), you can narrow learning and achievement gaps among those
  students &mdash; particularly important when some of them may come
  from socioeconomically disadvantaged backgrounds.  This approach is
  called <i>mastery learning</i>, and computer-based testing allows us
  to effect some important ingredients of it economically at scale.

  </div>
  <div>
  <h2> AI</h2>


<a href="https://www.theatlantic.com/ideas/2026/05/princeton-ai-honor-code/687144/">So much for honor codes:</a>
The AI "cheating crisis"
<a href="https://www.theatlantic.com/ideas/2026/08/ai-use-college-cheat/688451/">is real</a>,
and some
<a href="https://www.nytimes.com/2025/08/26/opinion/culture/ai-chatgpt-college-cheating-medieval.html">have</a>
<a href="https://www.economist.com/united-states/2025/11/20/ai-is-accelerating-a-tech-backlash-in-american-classrooms">suggested</a>
going back to proctored exams and handwritten blue books.
Yes to human proctors!  But UIUC professor
<a href="zilles.cs.illinois.edu">Craig Zilles</a> and I strongly agree that going back
to "blue books" is a good idea:Advances in technology make 
<a href="https://www.insidehighered.com/opinion/views/2026/03/19/blue-books-are-not-answer-ai-opinion">computer-based testing a far superior alternative.</a>
  </div>
</div>

<br>
<br>
Inspired by the work pioneered at the University of Illinois, [Dan
Garcia](https://www.cs.berkeley.edu/~ddgarcia) and I
became the faculty leads for developing Computer-Based Testing at UC
Berkeley, including onboarding new faculty, (cheer)leading the
efforts to establish computer-based testing facilities (CBTFs) on
campus, showing the benefits achieved through mastery learning and accessibility as
well as academic integrity, and even [teaching students how to create
and evaluate](https://eecs.link/star) rich authentic assessments that
work with [PrairieLearn](prairielearn.org).

# Short Reads

* Craig Zilles and Armando Fox,
[Blue Books Are Not the Answer to the AI Cheating Crisis](https://www.insidehighered.com/opinion/views/2026/03/19/blue-books-are-not-answer-ai-opinion). Inside Higher Ed, 2026-03-19.  Why you shouldn't conflate "proctored exams" with "blue book exams," and why computer-based testing is far superior to blue books in most cases.

* Armando Fox and Craig Zilles,
[Scalable Exam Administration: The Proctoring Crisis Requires a SEA Change](/assets/pdf/SEAChangeInAssessment-CACM.pdf), submitted to Communications of the ACM.  The key ingredient to scalable exam administration: not all students take the exam simultaneously.  This entails three other requirements: no real-time answers to clarifying questions, no paper cheatsheets, uniform-length exam slots.  Once you take on board "not simultaneous," the other derived requirements follow.  Here's why non-simultaneous is key to scalability, and how you meet both that requirement and the derived ones.

* Armando Fox,
[Bootstrapping a Computer-Based Testing Facility Using Shared Lab Space](https://drive.google.com/file/d/1k51QI2ZprXv7exWdve0vO85ZPbEQzLcP/view?usp=drive_link).  An experience report of growing our CBTF efforts from 230 student in 1 course using shared lab space to over 5,500 students in over 20 courses using a dedicated 100-seat facility.

# Updates

![Moffitt CBTF photo](/assets/img/2026-09-01-moffitt-cbtf.jpg){: .img-right}

On Monday, August 31, 2026, UC Berkeley's brand-new 100-seat CBTF in
the remodeled Moffitt Library went into production!


This is a major milestone for us.  It was only in Fall 2023
that we tried a pilot of a "proto-CBTF" using shared lab space and
serving a single ~230-student course for a final exam only.  As of
August 2026, the newly-opening CBTF has already scheduled nearly
40,000 student-exam-hours across more than 20 courses for Fall 2026.

[This SIGCSE
Virtual 2026 paper](https://drive.google.com/file/d/1k51QI2ZprXv7exWdve0vO85ZPbEQzLcP/view?usp=drive_link)
discusses that bootstrapping process and lessons learned, and should
persuade you that **you can do this at your institution too, without
boiling the ocean all at once.**  The latter was not a foregone
conclusion, given that we heavily modeled our approach on that
developed organically over several years at the University of Illinois
and other institutions.

