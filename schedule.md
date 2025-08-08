# Class Schedule

*Please note that this schedule is subject to change. (And open to pull requests.) Class progress through early materials may warrant a change in the schedule or assigned work.*

<br/>

General weekly schedule:

**Tuesday** – submit previous week's assignment; **clicker quiz at the beginning of class (counts for attendance)** about the assignment; review/discuss/clarify last assignment; introduce new topic and readings 
**Midweek homework** - reading assignment   
**Thursday** – **clicker quiz at the beginning of class (counts for attendance)** on assigned readings; review quiz results and clarify difficulties revealed by quiz; in‑class partner/small‑group work applying readings; introduce Colab notebook assignment; if time, begin the notebook in class  
**Weekend homework** – Colab notebook  
**Following Tuesday** – submit notebooks; clicker quiz; review/clarify; introduce new topic and readings; etc.

# UNIT 1: Relational Databases (MySQL)

## Week 1: Thursday, August 21

### Prep

- None (first day). Bring laptop.  

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

- _MySQL Tutorial_ (PDF): Intro + Basic Queries — **pp. 1–12** ([mysql-tutorial.pdf](mysql-tutorial.pdf))
- _Master SQL in 16 Pages_ — **pp. 1–5** (SELECT, WHERE, ORDER BY, LIMIT, LIKE) ([Master_SQL_in_16_Pages.pdf](Master_SQL_in_16_Pages.pdf))
- (Optional quick reference) _SQL Cheat Sheet_ — **pp. 1–2** ([SQL-Cheat-Sheet.pdf](SQL-Cheat-Sheet.pdf))

#### Official MySQL docs

- SELECT statement (overview) — [dev.mysql.com/doc/en/select.html](https://dev.mysql.com/doc/en/select.html)
- Pattern matching (LIKE) — [dev.mysql.com/doc/en/pattern-matching.html](https://dev.mysql.com/doc/en/pattern-matching.html)
- String functions (reference) — [dev.mysql.com/doc/en/string-functions.html](https://dev.mysql.com/doc/en/string-functions.html)

#### Short videos (optional)

- SELECT (intro) — "MySQL Tutorial for Beginners 8: Using SELECT" ([YouTube](https://www.youtube.com/watch?v=ZqlSPEIHBPg))
- WHERE — "MySQL WHERE Clause" ([YouTube](https://www.youtube.com/watch?v=cfY9BkYdAh0))
- ORDER BY — "MySQL ORDER BY Clause" ([YouTube](https://www.youtube.com/watch?v=L7QXspb2NHk))
- LIMIT — "MySQL LIMIT Clause" ([YouTube](https://www.youtube.com/watch?v=WEnavAPW4dk))
- LIKE — "MySQL LIKE Operator" ([YouTube](https://www.youtube.com/watch?v=wubZMlkgxCM))

#### Assignment

- Submit **Notebook 1** by the start of class.  


### In class
- **Clicker quiz at the start (attendance)** on Notebook 1 experience and outcomes.
- Review Notebook 1 results and common pitfalls (NULL logic, filter order, off‑by‑one with `LIMIT`).
- **Introduce new topic:** Aggregation + string/math functions; preview of **core joins (INNER, LEFT)**.

<br/>

## Week 2: Thursday, August 28

### Prep

#### R reading

- _MySQL Tutorial_ (PDF): Aggregates & GROUP BY — **pp. 13–18** ([mysql-tutorial.pdf](mysql-tutorial.pdf)).  
- _Master SQL in 16 Pages_ — **pp. 6–8** (COUNT, SUM/AVG, MIN/MAX, GROUP BY, HAVING) ([Master_SQL_in_16_Pages.pdf](Master_SQL_in_16_Pages.pdf)).  
- _MySQL Tutorial_ (PDF): Multi‑table queries (INNER/LEFT only) — **pp. 23–25** ([mysql-tutorial.pdf](mysql-tutorial.pdf)).  
- (Micro‑handout) **NULLs & COALESCE/IFNULL** (1 page; on LMS).

#### Official MySQL docs

- Aggregate functions (overview) — [dev.mysql.com/doc/refman/8.4/en/aggregate-functions.html](https://dev.mysql.com/doc/refman/8.4/en/aggregate-functions.html)
- MySQL handling of `GROUP BY` — [dev.mysql.com/doc/refman/8.4/en/group-by-handling.html](https://dev.mysql.com/doc/refman/8.4/en/group-by-handling.html)
- GROUP BY modifiers (`WITH ROLLUP`) — [dev.mysql.com/doc/refman/8.4/en/group-by-modifiers.html](https://dev.mysql.com/doc/refman/8.4/en/group-by-modifiers.html)

#### Short videos

- Aggregate functions — "More on Aggregate Functions" ([YouTube](https://www.youtube.com/watch?v=0pfKXxB6aD8))
- GROUP BY — concise refresher ([YouTube](https://www.youtube.com/watch?v=vYS-pqVSMiI))


### In class

- **Clicker quiz at the start (attendance)** on the readings.
- Quiz debrief and practice examples, as necessary.
- Partner challenge: explore descriptive questions on the sample DB using `GROUP BY` and `HAVING`.
- Introduce **INNER** and **LEFT JOIN** on two tables; briefly note **RIGHT** as read‑only and **FULL OUTER** as a conceptual workaround (LEFT/RIGHT + `UNION`).
- **Notebook 2 released:** Aggregates + **core joins (INNER/LEFT)** + string/math helpers.
- If time: begin Notebook 2 in class.

<br/>

## Week 3: Tuesday, September 2

### Prep

- Submit **Notebook 2** by the start of class.

### In class

- **Clicker quiz at the start (attendance)** on Notebook 2.
- Review Notebook 2 results: join selectivity, grouping pitfalls (non‑aggregated columns), and `HAVING` vs `WHERE`.
- **Introduce new topic:** **Subqueries first** (uncorrelated → correlated), compare to joins; brief intro to **CTEs (`WITH`)** as a refactor/readability tool.


<br/>

## Week 3: Thursday, September 4

### Prep

#### Primary reading

- _MySQL Tutorial_ (PDF): Subqueries (intro) — **pp. 19–22** ([mysql-tutorial.pdf](mysql-tutorial.pdf))
- _Master SQL in 16 Pages_ — **pp. 9–11** (subqueries + set ops) ([Master_SQL_in_16_Pages.pdf](Master_SQL_in_16_Pages.pdf))
- _Master SQL in 16 Pages_ — **pp. 14–16** (CTEs vs. subqueries) ([Master_SQL_in_16_Pages.pdf](Master_SQL_in_16_Pages.pdf))

#### Official MySQL docs

- CTEs (`WITH`) — [dev.mysql.com/doc/refman/8.4/en/with.html](https://dev.mysql.com/doc/refman/8.4/en/with.html)
- Subqueries (focus on uncorrelated) — [dev.mysql.com/doc/mysql/en/subqueries.html](https://dev.mysql.com/doc/mysql/en/subqueries.html)
- Set operations (UNION, INTERSECT, EXCEPT) — [dev.mysql.com/doc/refman/8.4/en/set-operations.html](https://dev.mysql.com/doc/refman/8.4/en/set-operations.html)

#### Short videos

- CTEs — "Common Table Expressions (WITH clause)" ([YouTube](https://www.youtube.com/watch?v=QphfWQXZaJ4))
- Subqueries — "Subqueries in MySQL | Intermediate MySQL" ([YouTube](https://www.youtube.com/watch?v=Vj6RqA_X-IE))

### In class

- **Clicker quiz at the start (attendance)** on the readings.
- Quiz debrief: when to use CTEs vs subqueries vs joins; readability trade‑offs.
- Small‑group refactors: rewrite a subquery as a CTE and as a join; compare approaches.
- **Notebook 3 released:** **Subqueries + CTEs** + `UNION/UNION ALL` (focus on practical applications).
- If time: begin Notebook 3 in class.


<br/>

## Week 4: Tuesday, September 9

### Prep

- Submit **Notebook 3** by the start of class.  

### In class

- **Clicker quiz at the start (attendance)** on Notebook 3.  
- Review Notebook 3: CTE best practices and performance considerations.  
- **Introduce new topic:** Database design fundamentals — ER modeling, normalization (1NF, 2NF, 3NF), and schema design principles.  
- Mid‑term project brief released (requirements, rubric, deliverables, sample datasets).  


<br/>

## Week 4: Thursday, September 11

### Prep

#### Primary reading

- _MySQL Tutorial_ (PDF): Creating tables & basic DML — **pp. 31–40** ([mysql-tutorial.pdf](mysql-tutorial.pdf))
- Database design primer (PDF) — "Entity-Relationship Modeling and Normalization" — **pp. 1–8** ([db-design-primer.pdf](db-design-primer.pdf))

#### Official MySQL docs

- CTEs (`WITH`) — [dev.mysql.com/doc/refman/8.4/en/with.html](https://dev.mysql.com/doc/refman/8.4/en/with.html)
- CREATE TABLE — [dev.mysql.com/doc/refman/8.4/en/create-table.html](https://dev.mysql.com/doc/refman/8.4/en/create-table.html)
- MySQL data types — [dev.mysql.com/doc/refman/8.4/en/data-types.html](https://dev.mysql.com/doc/refman/8.4/en/data-types.html)
- Constraints and foreign keys — [dev.mysql.com/doc/refman/8.4/en/constraint-foreign-key.html](https://dev.mysql.com/doc/refman/8.4/en/constraint-foreign-key.html)
- INSERT — [dev.mysql.com/doc/en/insert.html](https://dev.mysql.com/doc/en/insert.html)
- UPDATE — [dev.mysql.com/doc/refman/8.4/en/update.html](https://dev.mysql.com/doc/refman/8.4/en/update.html)
- DELETE — [dev.mysql.com/doc/en/delete.html](https://dev.mysql.com/doc/en/delete.html)
 
#### Short videos

- ER modeling basics — "Entity Relationship Diagram (ERD) Tutorial" ([YouTube](https://www.youtube.com/watch?v=QpdhBUYk7Kk))
- MySQL Workbench basics (official MySQL channel) — "MySQL Workbench Tutorial" ([YouTube](https://www.youtube.com/watch?v=X_umYKqKaF0))

#### Project prep
 
- Decide whether you prefer **GUI (Workbench/Beekeeper)** or **terminal** tooling, local or cloud for your project build.
- Install MySQL in a platform of your choice (local or cloud).

### In class

- **Clicker quiz at the start (attendance)** on the readings.
- Quiz debrief: common design errors, normalization principles, MySQL data type choices.
- **Connection verification:** confirm your **pre‑class install** (local or cloud) using a short checklist; resolve blockers quickly.
- Team studio: draft initial ER diagram; validate normalization; translate to `CREATE TABLE` statements.
- **DML mini‑lab:** `INSERT`, `UPDATE`, `DELETE`; quick demo of `LOAD DATA` for bulk CSV **(if time)**.
- **Notebook 4 released:** DDL + DML on your own instance (start in class if time).


<br/>

## Week 5: Tuesday, September 16

### Prep

- Submit **Notebook 4** at the start of class.

### In class

- **Clicker quiz at the start (attendance)** on Notebook 4.  
- Quiz debrief: constraint violations, foreign key best practices, data loading pitfalls.  
- **Introduce new topic:** Query performance and optimization — indexing strategies, query execution plans, and optimization techniques.  
- Workshop time: begin applying indexes to your project schemas.  


<br/>

## Week 5: Thursday, September 18

### Prep

#### Primary reading

- _MySQL Tutorial_ (PDF): Multi-table queries & joins — **pp. 23–30** ([mysql-tutorial.pdf](mysql-tutorial.pdf))
- MySQL Performance primer (PDF) — "Indexing and Query Optimization" — **pp. 1–6** ([mysql-performance-primer.pdf](mysql-performance-primer.pdf))

#### Official MySQL docs

- SELECT + JOIN clause (syntax & examples) — [dev.mysql.com/doc/en/select.html](https://dev.mysql.com/doc/en/select.html)
- CREATE INDEX — [dev.mysql.com/doc/refman/8.4/en/create-index.html](https://dev.mysql.com/doc/refman/8.4/en/create-index.html)
- EXPLAIN (plan inspection) — [dev.mysql.com/doc/en/explain.html](https://dev.mysql.com/doc/en/explain.html)
- EXPLAIN output formats — [dev.mysql.com/doc/en/explain-output.html](https://dev.mysql.com/doc/en/explain-output.html)

#### Short videos

- MySQL indexing basics — "MySQL Indexes Explained" ([YouTube](https://www.youtube.com/watch?v=HubezKbFL7E))
- EXPLAIN walkthrough — "MySQL EXPLAIN Tutorial" ([YouTube](https://www.youtube.com/watch?v=oqVXHpklk9w))

### In class

- **Clicker quiz at the start (attendance)** on the reading.  
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

- **Clicker quiz at the start (attendance)**: quick reflection on project process/lessons.  
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

