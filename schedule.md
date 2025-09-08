# Class Schedule

*Please note that this schedule is subject to change. (And open to pull requests.) Class progress through early materials may warrant a change in the schedule or assigned work.*

<br/>

General weekly schedule:

**Tuesday** – submit previous week's assignment; **quiz by the beginning of class** about the assignment; review/discuss/clarify last assignment; introduce new topic and readings 
**Midweek homework** - reading assignment   
**Thursday** – **quiz by the beginning of class** on assigned readings; review quiz results and clarify difficulties revealed by quiz; in‑class partner/small‑group work applying readings; introduce Colab notebook assignment; if time, begin the notebook in class  
**Weekend homework** – Colab notebook  
**Following Tuesday** – submit notebooks; clicker quiz; review/clarify; introduce new topic and readings; etc.

# UNIT 1: Relational Databases (MySQL)

## Week 1: Thursday, August 21

### Prep

- Bring laptop.
- Read: [What is a relational database](https://www.ibm.com/think/topics/relational-databases)

### In class

- Introductions and course/unit overview
- Introduction to SQL and MySQL.  
- Colab warm‑up: connect to MySQL from Python (connector provided), run first `SELECT`.  
- Query basics: `SELECT`, `WHERE`, `ORDER BY`, `LIMIT`; basic pattern matching with `LIKE` and wildcards.  
- **Notebook 1 released:** "Getting Data Out."

<br/>

## Week 2: Tuesday, August 26

### Prep

#### Reading

- _MySQL Tutorial_ (PDF): Intro + Basic Queries — **pp. 5–7** (mysql-tutorial.pdf on Canvas)

#### Official MySQL docs

_These documentation articles will have more information than you need, and they will reference some things we haven't covered yet. However, it is important to be familiar with them. Glean from them what you need in reference to the assigned notebook and class discussions, and tuck the rest away for later._

- SELECT statement (overview) — [dev.mysql.com/doc/en/select.html](https://dev.mysql.com/doc/en/select.html)
- Pattern matching (LIKE) — [dev.mysql.com/doc/en/pattern-matching.html](https://dev.mysql.com/doc/en/pattern-matching.html)
- String functions (reference) — [dev.mysql.com/doc/en/string-functions.html](https://dev.mysql.com/doc/en/string-functions.html)

#### Videos (optional)

- [SELECT Statement in MySQL](https://www.youtube.com/watch?v=HYD8KjPB9F8)
- [WHERE Clause in MySQL](https://www.youtube.com/watch?v=MARn_mssG4A)

#### For reference

- _Master SQL in 16 Pages_ (on Canvas) — **pp. 1–5** (SELECT, WHERE, ORDER BY, LIMIT, LIKE)
- _SQL Cheat Sheet_ (on Canvas) — **pp. 1–2**


#### Assignment

- **Submit _Notebook 1_ to Canvas by the start of class.** The notebook is in Colab, and linked from Canvas under Assignments.
- Submit Reading Quiz 1 on Canvas under Quizzes (also covers Notebook 1, so be sure to complete Notebook 1 before the quiz).

### In class
- Review Notebook 1 results.
- **Introduce new topic:** Aggregation + string/math functions; preview of **core joins (INNER, LEFT)**.

<br/>

## Week 2: Thursday, August 28

### Prep

#### Quiz

Reading Quiz #2 in Canvas (after doing the following readings).

#### Reading

- _MySQL Tutorial_ (PDF): **pp. 13–25** (mysql-tutorial.pdf on Canvas).  

#### Official MySQL docs

_These documentation articles will have more information than you need, and they will reference some things we haven't covered yet. However, it is important to be familiar with them. Glean from them what you need in reference to the assigned notebook and class discussions, and tuck the rest away for later._

- Aggregate functions (overview) — [dev.mysql.com/doc/refman/8.4/en/aggregate-functions.html](https://dev.mysql.com/doc/refman/8.4/en/aggregate-functions.html)
- MySQL handling of `GROUP BY` — [dev.mysql.com/doc/refman/8.4/en/group-by-handling.html](https://dev.mysql.com/doc/refman/8.4/en/group-by-handling.html)
- GROUP BY modifiers (`WITH ROLLUP`) — [dev.mysql.com/doc/refman/8.4/en/group-by-modifiers.html](https://dev.mysql.com/doc/refman/8.4/en/group-by-modifiers.html)

#### Other helpful reference material

#### Videos (optional)

- [GROUP BY and ORDER BY in MySQL](https://www.youtube.com/watch?v=zgYqUP_PhQo)


### In class

- Quiz debrief.
- Grouping and aggregation practice.
- If time: begin Notebook 2 in class.

<br/>

## Week 3: Tuesday, September 2

### Prep

- Submit **Notebook 2** by the start of class.

### In class

- Review Notebook 2 results.
- **Introduce new topic:** Subqueries, CTEs (`WITH`), and joins.


<br/>

## Week 3: Thursday, September 4

#### Quiz

Reading Quiz #3 in Canvas (after doing the following readings).

### Prep

#### Primary reading

- _MySQL Tutorial_ (PDF): Using more than one table (intro to joins) — **pp. 25–27** (mysql-tutorial.pdf on Canvas)
- [Introduction to MySQL joins](https://planetscale.com/blog/introduction-to-mysql-joins)
- [An Overview of Joins](https://planetscale.com/learn/courses/mysql-for-developers/queries/an-overview-of-joins?autoplay=1)
- [Subqueries](https://planetscale.com/learn/courses/mysql-for-developers/queries/subqueries)
- [Common Table Expressions (CTEs)](https://planetscale.com/learn/courses/mysql-for-developers/queries/common-table-expressions-ctes)
- [Unions](https://planetscale.com/learn/courses/mysql-for-developers/queries/unions)

#### Official MySQL docs

- CTEs (`WITH`) — [dev.mysql.com/doc/refman/8.4/en/with.html](https://dev.mysql.com/doc/refman/8.4/en/with.html)
- Subqueries — [dev.mysql.com/doc/mysql/en/subqueries.html](https://dev.mysql.com/doc/mysql/en/subqueries.html)
- JOIN Clause - [https://dev.mysql.com/doc/refman/8.4/en/join.html](https://dev.mysql.com/doc/refman/8.4/en/join.html)
- Set operations (UNION, INTERSECT, EXCEPT) — [dev.mysql.com/doc/refman/8.4/en/set-operations.html](https://dev.mysql.com/doc/refman/8.4/en/set-operations.html)

#### Other helpful reference material (optional)

- _Master SQL in 16 Pages_ — **p. 6** (subqueries) (Master_SQL_in_16_Pages.pdf on Canvas)
- _Master SQL in 16 Pages_ — **pp. 7–9** (JOINS) (Master_SQL_in_16_Pages.pdf on Canvas).  
- _Master SQL in 16 Pages_ — **p. 10** (set operations) (Master_SQL_in_16_Pages.pdf on Canvas)

#### Videos (optional)

_Videos are embedded in the primary readings this week. I highly recommend watching them, as well as reading the articles, particularly for any concepts that are new for you._

### In class

- Quiz debrief.
- Small‑group refactors: rewrite a subquery as a CTE and as a join; compare approaches.
- **Notebook 3 released:** **Subqueries, CTEs, and basic joins**.
- If time: begin Notebook 3 in class.


<br/>

## Week 4: Tuesday, September 9

### Prep

- Submit **Notebook 3** by the start of class.  

### In class

- Review Notebook 3.  
- More work on joins.


<br/>

## Week 4: Thursday, September 11

### Prep

#### Quiz

Reading Quiz #4 in Canvas (after doing the following readings).

#### Primary reading



#### Official MySQL docs

- [Installing MySQL on Windows](https://dev.mysql.com/doc/refman/8.4/en/windows-installation.html) (if you're a Windows user)
- [Installing MySQL on macOS Using Native Packages](https://dev.mysql.com/doc/mysql-installation-excerpt/5.7/en/macos-installation-pkg.html) (if you're a Mac user)
- [Getting Started with MySQL](https://dev.mysql.com/doc/mysql-getting-started/en/)
 
#### Short videos

- [SQL Create Table and Insert Data](https://youtu.be/LAP9-vu-KgU)
- [MySQL Workbench Tutorial](https://www.youtube.com/watch?v=X_umYKqKaF0)

### In class

- **Quiz debrief.**
- Install and troubleshoot MySQL and [MySQL Workbench](https://www.mysql.com/products/workbench/) on your laptop (if you haven't already).
- Make and break some database(s).


<br/>

## Week 5: Tuesday, September 16

### Prep

- Submit **Assignment 4** at the start of class.

### In class

- **Clicker quiz at the start (attendance)** on Notebook 4.  
- Quiz debrief: constraint violations, foreign key best practices, data loading pitfalls.  
- **Introduce new topic:** Query performance and optimization — indexing strategies, query execution plans, and optimization techniques.  
- Workshop time: begin applying indexes to your project schemas.  


<br/>

## Week 5: Thursday, September 18

#### Quiz

Reading Quiz #5 in Canvas (after doing the following readings).

### Prep

#### Primary reading

[//]: # (- _MySQL Tutorial_ &#40;PDF&#41;: Multi-table queries & joins — **pp. 23–30** &#40;mysql-tutorial.pdf on Canvas&#41;)

[//]: # (- MySQL Performance primer &#40;PDF&#41; — "Indexing and Query Optimization" — **pp. 1–6** &#40;[mysql-performance-primer.pdf]&#40;mysql-performance-primer.pdf&#41;&#41;)

#### Official MySQL docs

[//]: # (- SELECT + JOIN clause &#40;syntax & examples&#41; — [dev.mysql.com/doc/en/select.html]&#40;https://dev.mysql.com/doc/en/select.html&#41;)

[//]: # (- CREATE INDEX — [dev.mysql.com/doc/refman/8.4/en/create-index.html]&#40;https://dev.mysql.com/doc/refman/8.4/en/create-index.html&#41;)

[//]: # (- EXPLAIN &#40;plan inspection&#41; — [dev.mysql.com/doc/en/explain.html]&#40;https://dev.mysql.com/doc/en/explain.html&#41;)

[//]: # (- EXPLAIN output formats — [dev.mysql.com/doc/en/explain-output.html]&#40;https://dev.mysql.com/doc/en/explain-output.html&#41;)

#### Short videos

[//]: # (- MySQL indexing basics — "MySQL Indexes Explained" &#40;[YouTube]&#40;https://www.youtube.com/watch?v=HubezKbFL7E&#41;&#41;)

[//]: # (- EXPLAIN walkthrough — "MySQL EXPLAIN Tutorial" &#40;[YouTube]&#40;https://www.youtube.com/watch?v=oqVXHpklk9w&#41;&#41;)

### In class

- Quiz debrief: indexing strategies, B-tree concepts, composite vs single-column indexes.  
- `EXPLAIN` walkthroughs on representative queries from your projects.  
- Peer review: query plan round‑robin—diagnose and improve slow queries.  
- Work session with instructor roaming; finalize mid‑term checklist.  
- **Mid‑term submission portal opens** (accepts until Tue, Sep 30, 10:00 am).


<br/>

## Week 6: Tuesday, September 23

### Prep

- Midterm project, ready to demo work-in-progress.

### In class

- Lightning demos (2–3 min per team): schema overview + one "before/after" query plan.  
- Peer feedback, followed by brief work/(re)planning time.  


<br/>

## Week 6: Thursday, September 25

### Prep

- Continue midterm project work.

### In class

- **Clicker quiz at the start (attendance only)**.  
- Midterm debugging and feedback, unit wrap‑up.
- Introduction to Unit 2: NoSQL databases.


<br/>

## Week 7: Tuesday, September 30

- **Mid‑term project due** by 10:00 am (schema SQL, load scripts/notebooks, sample queries, brief report).

### Prep

- TBA

### In class

- TBA


<br/>

## Week 7: Thursday, October 2

### Prep

- TBA

### In class

- TBA


<br/>

## Week 8: Tuesday, October 7

### Prep

- TBA

### In class

- TBA


<br/>

## Week 8: Thursday, October 9

NO CLASS!!!

### Prep

- TBA

### In class

- TBA


<br/>

## Week 9: Tuesday, October 14

### Prep

- TBA

### In class

- TBA


<br/>

## Week 9: Thursday, October 16

### Prep

- TBA

### In class

- TBA


<br/>

## Week 10: Tuesday, October 21

### Prep

- TBA

### In class

- TBA


<br/>

## Week 10: Thursday, October 23

### Prep

- TBA

### In class

- TBA


<br/>

## Week 11: Tuesday, October 28

### Prep

- TBA

### In class

- TBA


<br/>

## Week 11: Thursday, October 30

### Prep

- TBA

### In class

- TBA


<br/>

## Week 12: Tuesday, November 4

### Prep

- TBA

### In class

- TBA


<br/>

## Week 12: Thursday, November 6

### Prep

- TBA

### In class

- TBA


<br/>

## Week 13: Tuesday, November 11

### Prep

- TBA

### In class

- TBA


<br/>

## Week 13: Thursday, November 13

### Prep

- TBA

### In class

- TBA


<br/>

## Week 14: Tuesday, November 18

### Prep

- TBA

### In class

- TBA


<br/>

## Week 14: Thursday, November 20

### Prep

- TBA

### In class

- TBA


<br/>

## Week 15: Tuesday, December 2

### Prep

- TBA

### In class

- TBA


<br/>

## Week 15: Thursday, December 4

### Prep

- TBA

### In class

- TBA

