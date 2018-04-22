# SQL BASE

Basics
-
---

1. [x] `SELECT`ing columns from a table
2. [x] Aggregates Part 1: `COUNT`, `SUM`, `MAX`/`MIN`
3. [x] Aggregates Part 2: `DISTINCT`, `GROUP BY`, `HAVING`

Intermediate
-
---

4. [x] `JOIN`s, ANSI-89 and ANSI-92 syntax
4. [x] `UNION` vs `UNION ALL`
5. [x] `NULL` handling: `COALESCE` & Native NULL handling
7. [x] Subqueries: `IN`, `EXISTS`, and inline views
8. [x] Subqueries: Correlated
2. [x] `WITH` syntax: Subquery Factoring/CTE
1. [x] Views

Advanced Topics
-
---

- Functions, Stored Procedures, Packages
- Pivoting data: CASE & PIVOT syntax
- Hierarchical Queries
- Cursors: Implicit and Explicit
- Triggers
- Dynamic SQL
- Materialized Views
- Query Optimization: Indexes
- Query Optimization: Explain Plans
- Query Optimization: Profiling
- Data Modelling: Normal Forms, 1 through 3
- Data Modelling: Primary & Foreign Keys
- Data Modelling: Table Constraints
- Data Modelling: Link/Corrollary Tables
- Full Text Searching
- XML 
- Isolation Levels
- Entity Relationship Diagrams (ERDs), Logical and Physical
- Transactions: `COMMIT`, `ROLLBACK`, Error Handling


------------------


## Beginner
`
- [x] Where clauses (in, between, etc)
- Update syntax
- Inner vs left vs right join understanding and usage
- Syntax for altering and creating structures
- Temp tables and their usage
- Cursors
- Basic idea what indexes are for, though not how they work
- Understanding of what foreign keys are for and how to work around them (cascading deletes etc)
- Understands basics of transactions
- Understands constraints
`
## Intermediate
`
- How indexes work, difference between clustered, non-clustered, etc, what a page is and how they layout
- Understanding of subqueries, and can think through using them in joins and wheres
- Pivots
- Can think through joining a table on itself when relevant
- Can generate complex data reports via group bys with aggregate functions
- Can do basic profiling just in a monitoring/debugging capacity like reading a log
- Understands the difference between OLAP and OLTP and when/where to use OLAP structures
- Knows how to use triggers and not to use them
- Understands transactions and can layer them handling failures up the stack
`

## Advanced
`
- Can read an execution plan, and understand how the different parts of the query effect it
- Can tune queries with execution hints without screwing up performance (parallelism hints, index hints, loop hints, et al)
- Can profile and use traces for identifying and understanding statistics of executions under real-world load
- Knows what the data structures are on the disk
- Can use performance counters and understand what the database load and behaviour is from monitoring them
- Knows how to design an OLAP cube and do advanced data mining with one
- Knows how to use triggers and how to use them safely, with minimal risk
- Knows how to use distributed transactions even with layers
`
