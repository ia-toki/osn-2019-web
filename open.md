---
layout: single-page-md
title: TOKI OSN Open Contest 2019 (English)
key: open
---

### Preface

- **TOKI OSN Open Contest 2019** is an open competition mirroring the National Science Olympiad in Informatics 2019 in Indonesia (**OSN Informatika 2019** in Bahasa).
- OSN Informatika is a national olympiad in informatics for high school students. It is the one of the stages required for Indonesian students to represent Indonesia in IOI (International Olympiad in Informatics)
- The problemset is the same as the problemset in OSN Informatika 2019, and will be given in Bahasa Indonesia and English.
- The contest will be held on [TLX (TOKI Online Judge)](https://tlx.toki.id/contests) (you may need to register for a TLX account if you do not have one already).
- If you have any questions please contact [sc-osn-2019@googlegroups.com](mailto:sc-osn-2019@googlegroups.com).

<br>

### Rules Overview

* There will be **one trial session** and **2 (two) competition days**.
* Result of trial session does **not** affect scoring.
* There will be **3 (three) problems** on each day to be solved in **5 (five) hours**.
* Each contestant may submit up to **50 submissions** for each problem.
* The supported programming languages are **C, C++, and Pascal**.
* During the competition, each contestant can only see their own scores.

<br>

### Schedule and Technical Details

- The contests will be held at the following time ranges:
* **Day 0**: [2 July 2019 08:35 - 23:05 UTC](https://www.timeanddate.com/worldclock/fixedtime.html?msg=TOKI+OSN+Open+Contest+2019+Day+0&iso=20190701T1535&p1=108&ah=14&am=30) (trial session)
* **Day 1**: [3 July 2019 02:35 - 23:05 UTC](https://www.timeanddate.com/worldclock/fixedtime.html?msg=TOKI+OSN+Open+Contest+2019+Day+1&iso=20190702T0935&p1=108&ah=20&am=30)
* **Day 2**: [4 July 2019 02:35 - 23:05 UTC](https://www.timeanddate.com/worldclock/fixedtime.html?msg=TOKI+OSN+Open+Contest+2019+Day+2&iso=20190703T0935&p1=108&ah=20&am=30)

- Each contestant can select **any 5-hour window** within the time range to do the contest for each competition day.
- All three contests are now available on [TLX](https://tlx.toki.id/contests). Please register in those contests.
- Each contestant may start the contest any time within the time range, by clicking the timer button.
- There will be no additional time given if a contestant starts the contest in less than 5 hours before the contest ends.
- The open contest doesn't support clarifications, but all important announcements from the original contest will be broadcast as well.

<br>

### Problems Types

- There are 3 possible problem types. There may be some problem type that is not given.

- **Batch** problems:
  * The most common problem type.
  * Given input, contestants write a program that reads input from **stdin** and writes output to **stdout**.
  * The program must run within the given time and memory limits.
  * Example: [Pekanbaru Defense, OSN 2017](https://training.ia-toki.org/problemsets/91/problems/469/)

- **Interactive** problems:
  * Contestants write a program that interacts with judge's program: judge's program writes to **stdout** and is given as the **stdin** for contestant's program, then contestant's program writes to **stdout** and is given as the **stdin** for judge's program, and the interaction continues until a given goal is reached.
  * Contestant's program must output answer within the given time and memory limits.
  * Example: [Lands and Glaciers, OSN 2017](https://training.ia-toki.org/problemsets/91/problems/471/)

- **Output-only** problems:
  * Contestants will be given all the input test cases.
  * Contestants submit **output** for each input test case.
  * Contestants **do not have to** write a program; the outputs may be solved manually.
  * Example: [Tourism in Palembang, OSN 2016](https://training.ia-toki.org/problemsets/54/problems/259/).

<br>

### Problem Scoring

* There are two types of scoring: **standard** and **creative**.
* Creative problems will be stated explicitly in problem description.

* **Standard** scoring:
  * For batch and interactive problems:
    * A problem consists of **multiple subtasks** with various points.
    * A subtask consists of **multiple test cases** that are grouped into some **test groups**.
    * A submission gets a subtask's points if it solves **all of its test groups**.
    * To solve a test group, a submission have to solve **all of its test cases**.
    * A problem may have **open subtasks** where the test cases are given to contestants.
  * For output-only problems:
    * A problem consists of **multiple test cases** with various points.
    * A submission gets the test case's points if it produces the correct output.

* **Creative** scoring:
  * The scoring formula will vary for each problem and will be explicitly stated in problem description.
  * Example:
    * Batch: [Membaca, OSN 2012](https://training.ia-toki.org/problemsets/45/problems/224/).
    * Interactive: [Cat Rumah, OSN 2014](https://training.ia-toki.org/problemsets/39/problems/202/).
    * Output-only: [Tourism in Palembang, OSN 2016](https://training.ia-toki.org/problemsets/54/problems/259/).

<br>

### Contestant Scoring

* For batch and interactive problems:
  * On creative scoring, for each submission, score of a subtask is the minimum score among all its test cases.
  * A subtask final score is **maximum of its score** among all submissions.
  * Contestant's score on a problem is the sum of all its subtasks final score.
  For example, if the first submission got 30 on first subtask and 0 on second subtask, and second submission got 0 on first subtask and 40 on second subtask, then the contestant's score on the problem is 70.
* For output-only problems:
  * A test case final score is the **maximum of its score** among all submissions.
  * Contestant's score on a problem is the sum of all its test cases final score.
* A contestant's total score is sum of **all of problems score** on **both days**.
* Contestants will be ranked by total score (descending).
* Two contestants with **same** total score will get **same** rank.
* Submission submit time **will not affect** contestant rank at all.

### Grading System

* Grading system that will be used is [TLX](https://tlx.toki.id).
* Source code limit for each submission is **300 KB**.
* For each test case, the grader will output one of:
  * **AC** (Accepted): program solved the problem within the given time and memory limits.
  * **WA** (Wrong Answer): program stopped within given time and memory limits, but produced the wrong output.
  * **RTE** (Runtime Error): program crashed or exceedeed the memory limit.
  * **TLE** (Time Limit Exceeded): program exceeded the time limit.
  * Skipped: test case is not graded because there was a test case in the same subtask that was not solved.
