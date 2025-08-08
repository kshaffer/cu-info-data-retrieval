# Class Schedule

*Please note that this schedule is subject to change. (And open to pull requests.) Class progress through early materials may warrant a change in the schedule or assigned work.*

<br/>

General weekly schedule:

**Tuesday** – submit previous week’s assignment; **clicker JiTT quiz at the beginning of class (counts for attendance)** about the assignment; review/discuss/clarify last assignment; introduce new topic and readings  
**Thursday** – **clicker JiTT quiz at the beginning of class (counts for attendance)** on assigned readings; review quiz results; in‑class partner/small‑group work applying readings; introduce Colab notebook assignment; if time, begin the notebook in class  
**Weekend homework** – Colab notebook  
**Following Tuesday** – submit notebooks; clicker quiz; review/clarify; introduce new topic and readings; etc.

## Week 1: Thursday, August 21

### Prep

- None (first day). Bring laptop with Google account access.  
- Ensure you can open the course Colab template (link on LMS).

### In class

- Introductions and course/unit overview
- Introduction to SQL and MySQL.  
- Colab warm‑up: connect to MySQL from Python (connector provided), run first `SELECT`.  
- Query basics: `SELECT`, `WHERE`, `ORDER BY`, `LIMIT`; basic pattern matching with `LIKE` and wildcards.  
_- **Assign Reading for Tue:** Query fundamentals & filtering; `LIKE` patterns; result ordering._  
- **Notebook 1 released:** “Getting Data Out.”

<br/>

## Week 2: Tuesday, August 26

### Prep

- Submit **Notebook 1** by the start of class.  
- Skim the example schema diagrams for our sample databases (**_LINK_**).

### In class

- **Clicker quiz at the start (attendance)** on Notebook 1 experience and outcomes.  
- Review Notebook 1 results and common pitfalls (NULL logic, filter order, off‑by‑one with `LIMIT`).  
- **Introduce new topic:** Aggregation + string/math functions; preview of core joins.  
__- **Assign Reading for Thu:** `GROUP BY`, `HAVING`; `COUNT/SUM/AVG`, `MIN/MAX`; basic string functions (`UPPER/LOWER/CONCAT/SUBSTRING`), arithmetic.__

<br/>

## Week 2: Thursday, August 28

### Prep

- Complete reading on aggregation, string, and math functions.

### In class

- **Clicker quiz at the start (attendance)** on the readings.  
- Quiz debrief and practice examples, as necessary.  
_- Partner challenge: explore descriptive questions on the sample DB using `GROUP BY` and `HAVING`._  
- Introduce **INNER** and **LEFT JOIN** on two tables; demo join‑on‑key vs join‑on‑expression.  
_- **Notebook 2 released:** Aggregates + basic joins + string/math helpers._  
- If time: begin Notebook 2 in class.

<br/>

## Week 3: Tuesday, September 2

### Prep

- Submit **Notebook 2** by the start of class.

### In class

- **Clicker quiz at the start (attendance)** on Notebook 2.  
- Review Notebook 2 results: join selectivity, grouping pitfalls (non‑aggregated columns), and `HAVING` vs `WHERE`.  
- **Introduce new topic:** Subqueries (focus on uncorrelated first, then correlated); `UNION` vs `UNION ALL`; join vs subquery trade‑offs.  
_- **Assign Reading for Thu:** Subquery patterns (IN, EXISTS, scalar subqueries), dedup vs append with `UNION`._


<br/>

## Week 3: Thursday, September 4

### Prep

- Complete subquery & set‑ops reading.

### In class

- **Clicker quiz at the start (attendance)** on the readings.  
- Quiz debrief: when to use subqueries; recognizing accidental Cartesian effects.  
- Small‑group refactors: rewrite a subquery as a join and vice versa; validate equivalence.  
- **Notebook 3 released:** Subqueries + `UNION/UNION ALL` (no `INTERSECT/EXCEPT`).  
- If time: begin Notebook 3 in class.


<br/>

## Week 4: Tuesday, September 9

### Prep

- Submit **Notebook 3** by the start of class.  
_- Skim ER‑modeling primer (entities, attributes, relationships, 1NF–3NF) on LMS._

### In class

- **Clicker quiz at the start (attendance)** on Notebook 3.  
- Review Notebook 3: equivalence checks and performance notes.  
_- **Introduce new topic:** ER modelling & schema design → DDL basics (`CREATE TABLE`, primary/foreign keys, constraints)._  
- Mid‑term project brief released (requirements, rubric, deliverables, sample datasets).  
_- **Assign Reading for Thu:** DDL & constraints guide; quick key/foreign‑key design._


<br/>

## Week 4: Thursday, September 11

### Prep

_- Complete DDL & constraints reading; optionally watch 10‑min video on key design._  
_- Decide whether you prefer **GUI (Workbench/Beekeeper)** or **terminal** tooling, local or cloud for your project build._

### In class

- **Clicker quiz at the start (attendance)** on the readings.  
- Quiz debrief: common design errors, key choices, normalization trade‑offs.  
- Install session: **local or cloud MySQL** (**_guided checklist_**).  
- Team studio: draft initial ER diagram; translate to `CREATE TABLE` statements.  
- **DML mini‑lab:** `INSERT`, `UPDATE`, `DELETE`; quick demo of `LOAD DATA` and GUI for bulk CSV.  
- **Notebook 4 released:** DDL + DML on your own instance (start in class if time).


<br/>

## Week 5: Tuesday, September 16

### Prep

- Submit **Notebook 4** at the start of class.

### In class

- **Clicker quiz at the start (attendance)** on Notebook 4.  
- Quiz debrief and indexing basics: B‑tree indexes, composite keys, covering indexes; when *not* to index.  
- `EXPLAIN` walkthroughs on representative queries from your projects.  
- Workshop time: apply indexes; re‑run `EXPLAIN`; record observations for project report.  
_- **Assign Reading for Thu:** short tuning case study + `EXPLAIN` primer._


<br/>

## Week 5: Thursday, September 18

### Prep

- Complete tuning case study reading.

### In class

- **Clicker quiz at the start (attendance)** on the reading.  
- Quiz debrief: common indexing myths; fixing slow queries.  
- Peer review: query plan round‑robin—diagnose and improve.  
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

- **Mid‑term project due** by 10:00 am (schema SQL, load scripts/notebooks, sample queries, brief report).

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

