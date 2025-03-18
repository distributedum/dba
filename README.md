
# 2024/2025

A course on database systems technology providing a bottom-up perspective of database administration, based on the assumption that solid knowledge of the main performance, reliability, and scale challenges in data management allows administrators to diagnose problems, formulate testable hypotheses, and apply creative solutions in a variety of current data management systems.

This approach contrasts with the common but limiting view of database administration as the repetitive application of recipes prescribed for a specific system. Therefore, this course addresses the concerns of database administrators facing a growing diversity of tools, but also application developers and integrators where data management is their greatest challenge.

## Learning outcomes

- Explain the main performance, reliability, and scale challenges in data management systems.
- Describe query processing and transactional mechanisms in database management systems.
- Plan and apply data management solutions that combine, compose, and configure data management mechanisms.
- Estimate and assess the behavior of data management systems.

## Grading

The grade has two components:

- Group project (50%), with discussion required for grades over 16/20.
- Written exam (50%), with at least 8/20.

The default project is the assessment and tuning of a hybrid transactional analytical application in a cloud environment in groups of 4 students. As an option, a limited set of research and development projects will be proposed for groups of 2 students.

Submitted projects must be fully authored by the students and must not contain materials (text, code, ...) from third parties, obtained online, or using AI tools unless explicitly marked and authorized by the instructors. See [Academic Regulations and Code of Ethical Conduct](https://alunos.uminho.pt/pt/estudantes/paginas/infouteisregulamentos.aspx) for more information.

## Schedule

| # | Date       | Topic | Mat.       | Read |
|:-:|:----------:|:------|:------:|:-------:|
| T1 | 4/2/25 | Introduction. | [&#128462;](materials/00-intro.pdf) | B2; P1
| T2 |  | Physical representation. | [&#128462;](materials/01-relational.pdf) | B1 13 |
| T3 | | Query execution (1). | [&#128462;](materials/02-relational.pdf) | B1 15; P2 |
|   | 11/2/25 | [SEI](https://seium.org/) | |
| PL1 | 18/2/25  | Lab 1: Resources. | [pdf](materials/lab1.pdf) [zip](materials/skelbench.zip) |
| PL2 | 25/2/25  | Lab 2: Execution. | [pdf](materials/lab2.pdf) [zip](materials/lab2.zip) |
| T4 | 11/3/25 | Query execution (2). | [&#128462;](materials/03-relational.pdf) | B2 15,20 |
| T5 | | Indexes and materialized views. | [&#128462;](materials/04-relational.pdf) | B1 8,14|
| T6 | | Query optimization. | [&#128462;](materials/05-relational.pdf) | B1 16; P3 |
| PL3 | 18/3/25  | Lab 3: Redundancy. | [pdf](materials/lab3.pdf) [weights](https://storage.googleapis.com/abd25/lab3.zip) |
| PL4 | 25/3/25  | Lab 4: Optimization. | |
| T7 | 1/4/25 | Transactional recovery. | | B1 17 |
| T8 |  | Transactional isolation (1). | | B1 18 |
| T10 | | Transactional isolation (2). | | B1 19; P4 |
| PL5 | 8/4/25  | Lab 5: Transactions. | |
| T9 | 22/4/25  | Talk (to be confirmed). | |
| PL6 |   | Project. | |
| T10 | 29/4/25  | Talk (to be confirmed). | |
| PL7 |   | Project. | |
| PL8 | 6/5/25  | Project. | |
| PL9 | 13/5/25  | Project. | |


- Subject to change, watch Blackboard for notifications.
- T - Lectures; PL - Labs.

## Bibliography

| # |  Title | 
|:-:|------------|
| B1 | H. Garcia-Molina, J. Ullman and J. Widom. [Database Systems: The Complete Book](http://infolab.stanford.edu/~ullman/dscb.html). Prentice-Hall, 2006 (2nd Edition).
| B2 | J. M. Hellerstein, M. Stonebraker, and J. Hamilton. [Architecture of a Database System](https://dsf.berkeley.edu/papers/fntdb07-architecture.pdf) Foundations and Trends® in Databases, vol. 1, no. 2, pp. 141–259, 2007.
| P1 | M. Stonebraker and A. Pavlo. [What Goes Around Comes Around... And Around](https://db.cs.cmu.edu/papers/2024/whatgoesaround-sigmodrec2024.pdf) SIGMOD Record, vol. 53, no. 2, p. 21, 2024. | 
| P2 | T. Kersten, V. Leis, A. Kemper, T. Neumann, A. Pavlo, and P. Boncz, [Everything you always wanted to know about compiled and vectorized queries but were afraid to ask](https://doi.org/10.14778/3275366.3284966). In Proceedings VLDB Endowment, vol. 11, no. 13, pp. 2209–2222, Jan. 2019. |
| P3 | Y. Zhang, Y. Chronis, J. Patel, and T. Rekatsinas, [Simple adaptive query processing vs. Learned query optimizers: Observations and analysis](https://doi.org/10.14778/3611479.3611501). In Proceedings VLDB Endowment, vol. 16, no. 11, pp. 2962–2975, Jul. 2023. |
| P4 | A. Prout et al., [Cloud-Native Transactions and Analytics in SingleStore](https://doi.org/10.1145/3514221.3526055). In Proceedings of the 2022 International Conference on Management of Data, SIGMOD’22, 2022. |

## Projects

The default project will be proposed before 29/3/25.

The R&D project focuses on executing [Trampoline-Style Queries for SQL](https://vldb.org/cidrdb/papers/2025/p1-lambrecht.pdf). Interested students should contact instructors ASAP.

### Group registration

Document with the information about each group: [Google Sheets](https://docs.google.com/spreadsheets/d/1AuE9QCOCohBLbDCZz7CgWuYxq7QSER9fR-lKU6aE2ag/edit?usp=sharing).
