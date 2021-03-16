---
layout: single-page-md
title: APIO 2021 Competition Rules
key: rules
---

The following are the APIO 2021 Competition Rules. Delegation Leaders have the responsibility of ensuring that all members of their delegation fully understand these rules and abide by them.

<span style="color:red">**Java will not be supported in APIO 2021.**</span>

<span style="color:red">**Please do not share the tasks after the contest within 2 days since the competition is not held within the same time range.**</span>

<br>

### A. General

* APIO 2021 consists of **1 practice problemset** and **1 competition day**.
* Result of the practice problemset **does not** affect scoring.
* There will be **3 (three) tasks** on the competition day to be solved in **5 (five) hours**.
* The supported programming language is **C++**.
* During the competition, each contestant can only see their own scores.

<br>

### B. Submission

* The source program provided by the contestant must be contained in one source file as specified in the task statement.
* Submissions must not perform explicit input and output operations; instead data must only be exchanged through the interfaces specified in the task statement.
* For each programming task, the contestants can download a zip file for a programming task from the grading system.
  * The zip file contains interface files, a sample grading program, a compile script, and a skeleton implementation of a required source file.
  * The skeleton exercises an interface, but it does not solve the task.
  * The provided sample grader would not be the same as the official grader used by the grading system.
  * The provided compile script in the task attachment would not run the same compilation command as the one used by the grading system to accommodate various compiler implementations that contestants have.
* Each contestant may submit a solution to each task at most once per minute. This restriction does not apply within 15 minutes before the end time of the contestant.
* Each contestant may submit up to **50 submissions** for each task unless otherwise stated in the task statement.

<br>

### C. Scoring

* The final score for each task will be calculated as follows:
  * For each submission, the score for each test case is calculated according to your program or output, rounded to the nearest 2 decimal places.
  * For each submission, the score for each subtask is the minimum of the scores for the test cases in the subtask unless otherwise stated in the task statement.
  * The final score for each subtask is the maximum of the scores for this subtask across all submissions.
  * The final score for each task is the sum of the scores for its subtasks.

For example, consider a contestant who made two submissions on a task that contains two subtasks. If the first submitted solution got 30 points for the first subtask and 10 points for the second subtask, and the second solution got 0 points for the first subtask and 40 points for the second subtask, then the final score for this task will be 70.

<br>

### D. Clarification

* A contestant can submit a clarification request concerning competition tasks, rules, and/or grading using the grading system during the competition.
* Clarification requests must be expressed only in English and will be answered only in English.
* Clarification requests concerning competition tasks will be answered with one of the following:
   * "YES"
   * "NO"
   * "ANSWERED IN TASK DESCRIPTION (EXPLICITLY OR IMPLICITLY)" - The task description contains sufficient information. The contestant should read it again carefully.
   * "INVALID QUESTION" - The question is most likely not phrased so that a yes/no answer would be meaningful. The contestant is encouraged to rephrase the question.
   * "NO COMMENT" - The contestant is asking for information that the Scientific Committee cannot give.

<br>

### E. Feedback

* For every submission, the grading system reports the score for each subtask.
* If a subtask is not fully solved, the grading system gives a feedback only for the first test case among the lowest scored test cases in the subtask.
* The feedback includes the test case number and one of the following reasons:
  * "Output is correct"
  * "Output isn’t correct"
  * "Execution timed out"
  * "Execution killed (could be triggered by violating memory limits)"
  * "Execution failed because the return code was nonzero"
  * "Protocol violation"
* For task with partial scores, the feedback might also include a "Output is partially correct" reason.
* Submissions performing any of the following actions may result in an unspecified
grading verdict (typically "Protocol violation"):
  * read from the standard input, write to the standard output, or interact with any other file,
  * call `exit()`

<br>

### F. Collaboration and Access

* All submissions from each contestant must be written by the contestant.
* Each contestant is allowed to use any code written before the competition, as long as the code is written by the contestant.
* Each contestant is prohibited to talk or discuss anything related to the content of the competition with anyone, including other contestants, except to the committee of the competition using the clarification request explained in the earlier section.
* Each contestant is allowed to use any sources of information on the Internet, as long as the contestant does not violate the previous rule. In particular, it is forbidden to copy-paste somebody else's code on the internet, or posting anything related to the content of the competition in an online forum.
* For the sake of respecting the fairness of this online contest format, each contestant is expected to show good sportsmanship by following the above rules honestly. Any violation of the rules can be subject to disqualification.
