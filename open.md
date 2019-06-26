---
layout: single-page-md
title: TOKI OSN Open Contest 2018 (English)
key: open
---

### Preface

- **TOKI OSN Open Contest 2018** is an open competition mirroring the National Science Olympiad in Informatics 2018 in Indonesia (**OSN Informatika 2018** in Bahasa Indonesia).
- OSN Informatika is a national olympiad in informatics for high school students. It is the one of the stages required for Indonesian students to represent Indonesia in IOI (International Olympiad in Informatics)
- The problemset is the same as the problemset in OSN Informatika 2018, and will be given in Bahasa Indonesia and English.
- The contest will be held on [TLX (TOKI Online Judge)](https://tlx.toki.id/competition) (you may need to register for a TLX account if you do not have one already).
- If you have any questions please contact [scientific@toki.or.id](mailto:scientific@toki.or.id).

<br>

### Rules Overview

* There will be one trial session and 2 (two) competition days.
* There will be 3 (three) problems on each day to be solved in 5 (five) hours.
* Each contestant may submit up to 50 solutions for each problem.
* The supported programming languages are C, C++, and Pascal.
* During the competition, each contestant can only see their own scores.

<br>

### Schedule and Technical Details

- The contests will be held at the following time ranges:
* **Day 0**: [2 July 2018 08:35 - 23:05 UTC](https://www.timeanddate.com/worldclock/fixedtime.html?msg=TOKI+OSN+Open+Contest+2018+Day+0&iso=20180702T1535&p1=575&ah=14&am=30) (trial session)
* **Day 1**: [3 July 2018 02:35 - 23:05 UTC](https://www.timeanddate.com/worldclock/fixedtime.html?msg=TOKI+OSN+Open+Contest+2018+Day+1&iso=20180703T0935&p1=575&ah=20&am=30)
* **Day 2**: [4 July 2018 02:35 - 23:05 UTC](https://www.timeanddate.com/worldclock/fixedtime.html?msg=TOKI+OSN+Open+Contest+2018+Day+2&iso=20180704T0935&p1=575&ah=20&am=30)

- Each contestant can select **any 5-hour window** within the time range to do the contest for each competition day.
- All three contests are now available on [TLX](https://tlx.toki.id/competition). Please register in those contests.
- Each contestant may start the contest any time within the time range, by clicking the timer button.
- There will be no additional time given if a contestant starts the contest in less than 5 hours before the contest ends.
- The open contest doesn't support clarifications, but all important announcements from the original contest will be broadcast as well.

<br>

### Problems Types

- There are 3 possible problem types.

- **Batch** problems:
  * The most common problem type.
  * Given input, contestants write a program that reads input and writes output satisfying the problem description.
  * The program must run within the given time and memory limits.

- **Interactive** problems:
  * Contestants write a program that interacts with judge's program.
  * Judge's program writes to stdout and is given as the input for contestant's program.
  * Contestant's program writes to stdout and is given as the input for judge's program.
  * The intreaction continues until a given goal is reached.
  * Contestant's program must output answer within the given time and memory limits.

- **Output-only** problems:
  * Contestants are be given a set of input test cases.
  * Contestants submit output for each input test case.
  * Contestants do not have to write a program; the outputs may be solved manually.

<br>

### Scoring

* There are two types of scoring: standard and creative.
* Creative problems will be stated explicitly in problem description.

* **Standard** scoring:
  * For batch and interactive problems:
    * A problem consists of multiple subtasks with various points.
    * A subtask consists of multiple test cases.
    * A submission gets a subtask's points if it solves all of its test cases.
    * A problem may have open subtasks where the test cases are given to contestants.
  * For output-only problems:
    * A problem consists of multiple test cases with various points.
    * A submission gets the test case's points if it produces the correct output.

* **Creative** scoring:
  * The scoring formula will vary for each problem and will be explicitly stated in problem description.

<br>

### Grading System

* Source code limit for each submission is 300 KB.
* For each test case, the grader will output one of:
  * AC (Accepted): program solved the problem within the given time and memory limits.
  * WA (Wrong Answer): program stopped within given time and memory limits, but produced the wrong output.
  * RTE (Runtime Error): program crashed or exceedeed the memory limit.
  * TLE (Time Limit Exceeded): program exceeded the time limit.
  * Skipped: test case is not graded because there was a test case in the same subtask that was not solved.