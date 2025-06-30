![The_Data_Lifecycle](fig/The_Data_Lifecycle.jpeg)

# DSC 100: Introduction to Data Management  
**Summer Session I 2025 — Fully Remote & Asynchronous (all lectures pre‑recorded)**  

---
## Description

Databases are at the heart of modern commercial application development. Their use extends beyond this to many other environments and domains where large amounts of data must be stored for efficient update, retrieval, and analysis. This course provides a comprehensive introduction to data management, covering topics such as the relational data model, SQL, formal query languages, query evaluation, data storage and indexes, NoSQL databases, conceptual design, integrity constraints, design theory, normal forms, and data quality. Through **pre‑recorded video lectures**, demos, and hands‑on exercises, students will gain a strong foundation in database‑management concepts and practices, with a focus on the use of SQL and the relational model.

The course begins with an overview of course organization and an introduction to the relational data model, followed by lessons on SQL basics and different types of joins in SQL. In the following weeks, students will learn advanced SQL queries, formal query languages, and query evaluation. The course also covers topics related to data storage and indexing, including hard‑disk and file organization, index organization, and creating indexes in SQL. In the latter half of the course, students will study NoSQL databases, conceptual design, integrity constraints, and design theory, culminating in a discussion of normal forms. The course includes a discussion of data quality, including techniques for dealing with missing data and entity deduplication. Upon completing the course, students will be equipped with the skills and knowledge necessary for designing, querying, and maintaining a relational database.

## Instructional Team

- **Instructor**: [Babak Salimi](https://bsalimi.github.io/)  
  Contact: bsalimi@ucsd.edu

- **Teaching Assistant**: Haoquan Guan  
  Contact: h3guan@ucsd.edu

### Office Hours (Zoom — links on Canvas)

- **Babak Salimi**: Wednesdays, 4–5 p.m. PT  
- **Haoquan Guan**: TBD

---
## Delivery & Communication
- **Lectures:** Fully asynchronous. New video modules released **Mondays–Thursdays at 09:00 PT** (see calendar).  
- **Discussion / Q&A:** Piazza — <https://piazza.com/ucsd/summer2025/dsc100> (access code on Canvas).  
- **Submissions & Exams:** Canvas.  
- **Announcements:** via Canvas — please enable notifications.

---
## Course Workload *(subject to change)*
* **Homework (30 %)** — weekly written/programming assignments (25 %) + web‑quizzes (5 %). Teams of ≤ 2. Three 24‑hour late‑day tokens (max 1 per assignment).
* **Midterm (20 %)** — covers material through Formal Query Languages; remote **Wed 16 Jul 2025, 14:00 – 16:00 PT**.
* **Final Exam (50 %)** — comprehensive; remote **Sat 02 Aug 2025, 15:00 – 17:59 PT**.

---
## Important Summer‑I Dates

- **Mon 30 Jun 2025**: Instruction begins  
- **Fri 04 Jul 2025**: **Independence Day holiday** — no new content  
- **Wed 16 Jul 2025**: Remote Midterm (14:00–16:00 PT)  
- **Fri 01 Aug 2025**: Instruction ends  
- **Sat 02 Aug 2025**: Remote Final Exam (15:00–17:59 PT)  

*(All assignment due dates appear on the Canvas calendar.)*





---
## Full Summer Calendar & Resources *(subject to change)*

> **Video Link:** placeholder to be updated once recordings are uploaded.

| Week | Lecture Date (2025) | Course Topic | Lecture Description | Assignments / Deadlines | Slides / Demos | Discussion | Optional Reading | Lecture Motivation | **Video Link** |
|------|---------------------|--------------|---------------------|-------------------------|----------------|------------|------------------|-------------------|---------------|
| **1** | **Mon Jun 30** | Course organization & Introduction | Covers syllabus, grading, course materials, and the role of databases in modern society. | **HW 1 released** (SQLite & SQL Basics) | [Slide-Part 1](https://drive.google.com/file/d/10Ts2iRj7IBpWQkwxa07vRdT7czFcfmQs/view?usp=sharing) . [Slide-Part 2](https://drive.google.com/file/d/104OGPAmhHFlfDM_1MJ9ChH5tDz7xtfEz/view?usp=sharing)  . [Slide-Part 3](https://drive.google.com/file/d/10X1VrgLcrKPssW1w48ThejDb3ieedCnJ/view?usp=sharing) | — | *Textbook* §2.1 / *Blog* [Data Management 101](https://www.tableau.com/learn/articles/what-is-data-anagement#:~:text=Data%20management%20helps%20minimize%20potential,market%20changes%20and%20customer%20needs.) | Course goals & objectives. |  [Recording-Part 1](https://drive.google.com/file/d/1l85Hy_nIcxMXem62dKVWz2PxsfPg1IHV/view?usp=sharing) [Recording-Part 2](https://drive.google.com/file/d/10CqTVmNFQNwtrdfFIg73DgLcvsDvt20j/view?usp=sharing) [Recording-Part 3](https://drive.google.com/file/d/10IpNPfkfWf33XZOAcuYSvbzUqGs6QaoV/view?usp=sharing) [Slide-Part 4](https://drive.google.com/file/d/10ZB4yHge97742CVLUa_yWgKxbLCGIch_/view?usp=sharing) [Recording-Part 4](https://drive.google.com/file/d/10DfiDpHk1jESO6f5r3VnTK20iegqLT2t/view?usp=sharing) [Demo 1](https://drive.google.com/file/d/1-iCciQ_A6DI_gQR1KLFf196axsJpbM3n/view?usp=sharing) [Source](https://drive.google.com/file/d/1-jtOOESAnOPfDDShXydoQQayLQMxI7YN/view?usp=sharing)   |
| | **Tue Jul 1** | Relational Data Model | Introduces tables, keys, DataFrame connection; SQLite demo. | Web Quiz 1 released | [SQL_Basics.pdf](https://drive.google.com/file/d/1NOftxlPRxpkZNRug0gODZkUCRGA4StCA/view?usp=sharing) | — | — | Foundation for DB work. | `[TBD]` |
| | **Wed Jul 2** | Joins in SQL Part 1 | Inner, outer, cross joins; combining tables. | — | same slides | — | — | Combines multi‑table info. | `[TBD]` |
| | **Thu Jul 3** | Joins in SQL Part 2 | Practical join patterns; SQLite demo. | — | [Joins.pdf](https://drive.google.com/file/d/1sixL7Ud7yYNQBSivSoJF8R5eAzFfz3kZ/view) | — | — | Mastering joins. | `[TBD]` |
| **2** | **Mon Jul 7** | Grouping & Aggregation | GROUP BY, HAVING, analytics demo. | **Web Quiz 1 due** (Sun 23:59); **Web Quiz 2 released** | [Grouping demo](https://colab.research.google.com/drive/1tv0zwEQh8bUIinqQhW0gzrjyx3loBHfT?usp=sharing) | — | — | Summarizing data. | `[TBD]` |
| | **Tue Jul 8** | Advanced SQL Queries Part 1 | Nested & correlated queries. | — | [Agg & Grouping slides](https://drive.google.com/file/d/1yLEqcT0urui7Ens7f_wXj2mOoKwtcEJ4/view?usp=sharing) · [Demo](https://drive.google.com/file/d/1oD6reMIaQK4eovqwecS--6z13UcxOFdu/view) | — | — | Complex querying. | `[TBD]` |
| | **Wed Jul 9** | Advanced SQL Queries Part 2 | Expression quantifiers; monotone vs non‑monotone. | **HW 1 due**; **HW 2 released** | [Nested Queries](https://drive.google.com/file/d/1eKUUFnwstPUVkqj7Q08mXYkdQgEjGNkR/view) | — | — | Deeper SQL logic. | `[TBD]` |
| | **Thu Jul 10** | Set Operations in SQL | UNION, INTERSECT, EXCEPT. | Web Quiz 3 released; **HW 3 released** | [Set Operations](https://drive.google.com/file/d/1gPbR--RJz2asCqTP0wn5Kf7P3EnLQbOh/view) | — | — | Combining result sets. | `[TBD]` |
| **3** | **Mon Jul 14** | Formal Relational Query Languages Part 1 | Basics of relational algebra & links to SQL/DataFrames. | **Web Quiz 2 due**; **Web Quiz 4 released** | [Formal QL slides](https://drive.google.com/file/d/1z67dErSbW5z-5HIoJLmRwXKeHzYuy8Ue/view?usp=sharing) · [Demo](https://colab.research.google.com/drive/1C6BbngbKD_Hxsty4WE_e7kCwrGVmiTa5?usp=sharing) | — | — | Understand DB internals. | `[TBD]` |
| | **Tue Jul 15** | Formal Relational Query Languages Part 2 | Continued algebra→SQL mapping. | — | same | — | — | — | `[TBD]` |
| | **Wed Jul 16** | Interactive Data Analysis Using SQL | Live notebook demo for exploratory analysis. | **Remote Midterm 14:00–16:00 PT** | — | — | — | Hands‑on skills. | `[TBD]` |
| | **Thu Jul 17** | Data Storage, Indexes & Size Estimation Part 1 | Disks, files, clustered/unclustered indexes. | — | [Storage Slides](https://drive.google.com/file/d/1JJApnoiAHcVYQy-D6Hu0rUoPL61mv_fA/view) · [Demo](https://colab.research.google.com/drive/1Fw5r2I1RnkM1ZKYXyo2j6u2Xn5RbIsPL?usp=sharing) | — | — | Performance fundamentals. | `[TBD]` |
| **4** | **Mon Jul 21** | Data Storage, Indexes & Size Estimation Part 2 | Creating indexes in SQL; cost estimation. | **Web Quiz 3 due**; **HW 2 due** | same | — | — | Query optimization. | `[TBD]` |
| | **Tue Jul 22** | Recursive Queries & Conceptual Design | ER modeling & recursion. | **Web Quiz 5 released** | [ER Slides](https://drive.google.com/file/d/1D9O798xF5KuL4z4a-1uT5vvdP6CPoxa7/view?usp=sharing) · [Demo](https://colab.research.google.com/drive/1Fw5r2I1RnkM1ZKYXyo2j6u2Xn5RbIsPL?usp=sharing) | — | — | Structuring DBs. | `[TBD]` |
| | **Wed Jul 23** | Design Theory | Functional dependencies, closure algorithm. | **HW 3 due**; **HW 4 released** | [Design Theory](https://drive.google.com/file/d/10sLHofXYuA_DjagNRjsY_IbMqSUbl-BZ/view) · [ER Diagrams](https://drive.google.com/file/d/1ps1fVNFHevJYTzeb3eEL5P15xrLHv5hy/view) · [Demo](https://colab.research.google.com/drive/1fbZSoemx3jOK2fo_veEr6bPSEnKNm-fH?usp=sharing) | — | — | Basis for normalization. | `[TBD]` |
| | **Thu Jul 24** | Normal Forms | BCNF, integrity & performance. | Web Quiz 6 released | [BCNF Slides](https://drive.google.com/file/d/1ptC4KwaKSpuWa4pQB7ovKVgPk7jHzAcB/view) | — | — | Redundancy‑free schema. | `[TBD]` |
| **5** | **Mon Jul 28** | Normal Forms (continued) | More BCNF examples & practice. | **Web Quiz 4 due**; **HW 4 due** | same | — | — | — | `[TBD]` |
| | **Tue Jul 29** | Final Exam Review | Comprehensive walkthrough & Q&A. | — | — | Live Piazza session | — | Prepare for final. | `[TBD]` |
| | **Sat Aug 02** | **FINAL EXAM** | Remote‑proctored, comprehensive. | 15:00 – 17:59 PT | — | — | — | — | — |


## Grading Scheme

The grading scheme is a hybrid of absolute and relative grading. The absolute cutoffs are based on your absolute total score. The relative bins are based on your position in the total score distribution of the class. The better grade among the two (absolute-based and relative-based) will be your final grade.

| Grade | Absolute Cutoff (>=) | Relative Bin (Use strictest) |
|-------|----------------------|-------------------------------|
| A+    | 97                   | Highest 5%                    |
| A     | 94                   | Next 10% (5-15)               |
| A-    | 91                   | Next 15% (15-30)              |
| B+    | 85                   | Next 15% (30-45)              |
| B     | 80                   | Next 15% (45-60)              |
| B-    | 70                   | Next 15% (60-75)              |
| C+    | 65                   | Next 5% (75-80)               |
| C     | 60                   | Next 5% (80-85)               |
| C-    | 55                   | Next 5% (85-90)               |
| D     | 50                   | Next 5% (90-95)               |
| F     | < 50                 | Lowest 5%                     |


## Textbook

Although a textbook is not required in the course, the following textbook is optional and recommended. Lecture slides and recorded videos would be sufficient for this class.

Database Systems: The Complete Book, by Hector Garcia-Molina, Jeffrey D. Ullman, and Jennifer Widom. 2nd Edition. Prentice Hall. 2008.

## Canvas

All weekly homework assignments and web quizzes should be turned in via Canvas.

## Communication

All important announcements will be sent through Canvas.

## Piazza

All questions that may be of general interest to the class should be directed to Piazza. You will get your questions answered faster on Piazza than via personal emails to the instructional team, because Piazza is monitored closely by everybody in the class, not just the course staff. You are highly encouraged to answer each other's questions on Piazza (you will get extra credit for the number of good answers on Piazza!) and the 
instructional team would endorse/add to those answers.



*Note:*  Some slides are adopted from the UW database group. 


## Related Groups:

- [UCSD Database Group](https://dbucsd.github.io/)

- [SIGMOD (Special Interest Group on Management of Data)](https://www.google.com/url?q=https%3A%2F%2Fsigmod.org%2F&sa=D&sntz=1&usg=AFQjCNEv9sM8CpuOZ7oxWFX_20353W6NZw)

- [VLDB (Very Large Data Base Endowment Inc.)](https://www.google.com/url?q=https%3A%2F%2Fwww.vldb.org%2F&sa=D&sntz=1&usg=AFQjCNEN7a3TJIOhpq3OC7bw9DKWHhki-w)

- [PODS (Symposium on Principles of Database Systems)](https://www.google.com/url?q=https%3A%2F%2Fsigmod.org%2Fpods%2F&sa=D&sntz=1&usg=AFQjCNEy52V8Padws9vrgz2GoFYinNgG9Q)

- [ICDT(IEEE International Conference on Data Engineering)](http://ieee-icde.org/)

- [CIDR (Conference on Innovative Data Systems Research)](http://www.google.com/url?q=http%3A%2F%2Fcidrdb.org%2F&sa=D&sntz=1&usg=AFQjCNHZ5MTU545Lei9xcYfQR9fHHLan5w)

