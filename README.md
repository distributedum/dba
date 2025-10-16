
# 2025/2026

A course on database systems technology providing a bottom-up perspective of database administration, based on the assumption that solid knowledge of the main performance, reliability, and scale challenges in data management allows administrators to diagnose problems, formulate testable hypotheses, and apply creative solutions in a variety of current data management systems.

This approach contrasts with the common but limiting view of database administration as the repetitive application of recipes prescribed for a specific system. Therefore, this course addresses the concerns of database administrators facing a growing diversity of tools, but also application developers and integrators where data management is their greatest challenge.

## Learning outcomes

- Explain the main performance, reliability, and scale challenges in data management systems.
- Describe query processing and transactional mechanisms in database management systems.
- Plan and apply data management solutions that combine, compose, and configure data management mechanisms.
- Estimate and assess the behavior of data management systems.

## Instructors

- [José Pereira](https://jopereira.github.io/)
- [Nuno Faria](https://nuno-faria.github.io/)

## Grading

The grade has two components:

- Group project (50%), with discussion required for grades over 16/20.
- Written exam (50%), with at least 8/20.

The default project is the assessment and tuning of a hybrid transactional analytical application in a cloud environment in groups of 4 students. As an option, a limited set of research and development projects will be proposed for groups of 2 students.

Submitted projects must be fully authored by the students and must not contain materials (text, code, ...) from third parties, obtained online, or using AI tools unless explicitly marked and authorized by the instructors. See [Academic Regulations and Code of Ethical Conduct](https://alunos.uminho.pt/pt/estudantes/paginas/infouteisregulamentos.aspx) for more information.

## Schedule

| # | Date       | Topic | Mat.       | Read |
|:-:|:----------:|:------|:------:|:-------:|
| T1 | 25/9/25 | Introduction. |  [&#128462;](materials/01-relational.pdf) | B2; P1
| T2 |    | Physical Representation.| [&#128462;](materials/01-relational.pdf) | B1 13 |
| PL1 |   | Lab 0: Benchmark. | [pdf](/materials/lab0.pdf) [zip](materials/skelbench0.zip) |
| PL2 | 2/10/25  | Lab 1: Resources. | [pdf](/materials/lab1.pdf) [zip](materials/skelbench.zip) |
| T3 | 9/10/25   | Query execution. | [&#128462;](materials/02-relational.pdf) | B1 15 |
| PL3 |   | Lab 2: Execution. | [pdf](/materials/lab2.pdf) [zip](materials/lab2.zip) |
| PL4 |   | Lab 3: Execution. | [pdf](/materials/lab3.pdf) [zip](https://storage.googleapis.com/abd_data/embedding.zip) |

- Subject to change, watch Blackboard for notifications.
- T - Lectures; PL - Labs.

## Bibliography

| # |  Title | 
|:-:|------------|
| B1 | H. Garcia-Molina, J. Ullman and J. Widom. [Database Systems: The Complete Book](http://infolab.stanford.edu/~ullman/dscb.html). Prentice-Hall, 2006 (2nd Edition).
| B2 | J. M. Hellerstein, M. Stonebraker, and J. Hamilton. [Architecture of a Database System](https://dsf.berkeley.edu/papers/fntdb07-architecture.pdf) Foundations and Trends® in Databases, vol. 1, no. 2, pp. 141–259, 2007.
| B3 | B. Ding, V. R. Narasayya, and S. Chaudhuri, [Extensible Query Optimizers in Practice](https://www.microsoft.com/en-us/research/publication/extensible-query-optimizers-in-practice/). Foundations and Trends® in Databases, 2024.
| P1 | M. Stonebraker and A. Pavlo. [What Goes Around Comes Around... And Around](https://db.cs.cmu.edu/papers/2024/whatgoesaround-sigmodrec2024.pdf) SIGMOD Record, vol. 53, no. 2, p. 21, 2024. | 
| P2 | T. Kersten, V. Leis, A. Kemper, T. Neumann, A. Pavlo, and P. Boncz, [Everything you always wanted to know about compiled and vectorized queries but were afraid to ask](https://doi.org/10.14778/3275366.3284966). In Proceedings VLDB Endowment, vol. 11, no. 13, pp. 2209–2222, Jan. 2019. |
| P3 | V. Leis, A. Gubichev, A. Mirchev, P. Boncz, A. Kemper, and T. Neumann, [How good are query optimizers, really?](https://15721.courses.cs.cmu.edu/spring2024/papers/16-costmodels/p204-leis.pdf), Proceedings VLDB Endowment, vol. 9, no. 3, pp. 204–215, Nov. 2015. |
| P4 | A. Prout et al., [Cloud-Native Transactions and Analytics in SingleStore](https://doi.org/10.1145/3514221.3526055). In Proceedings of the 2022 International Conference on Management of Data, SIGMOD’22, 2022. |

## Projects

The default project will be proposed before 31/10/25.

The R&D project focuses on an experimental assessment of the internals of query optimization in Postgresql as described in ["An elephant under the microscope: Analyzing the interaction of optimizer components in PostgreSQL"](https://dl.acm.org/doi/pdf/10.1145/3709659) and the [PostBOUND tool](https://github.com/rbergm/PostBOUND). Interested students should contact instructors ASAP.

## Past editions

- [2024/2025](./editions/2024_2025/)


