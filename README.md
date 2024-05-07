# Generalized Architectural Decision Records [![part of ADR](https://img.shields.io/badge/part_of-ADR-blue.svg)](https://adr.github.io)

An [Architectural Decision Record](https://adr.github.io/) (ADR) is recording an architectural decision (AD).
Such a decision might be to use Gradle instead of Maven as build tool.
In another project, Maven might be preferred over Gradle.
The pros and cons of each decision might be somewhat general (appearing in both projects) or local (appearing in the context of one project only).
GADRs are about capturing the general options and their pros and cons.
[Prof. Dr. Olaf Zimmermann](https://www.ifs.hsr.ch/Olaf-Zimmermann.11623.0.html) coined the terms "Decision Required" and "Decisions Made" in his [PhD thesis](http://dx.doi.org/10.18419/opus-2665).
An overview is in the article [Decisions Required vs. Decisions Made](http://soadecisions.org/download/zimmermann_chap_mistrik_book.pdf).
He also distinguishes between "Problem Space" and "Solution Space" (see O. Zimmermann et al. [Architectural Decision Guidance across Projects](http://www.ifs.hsr.ch/fileadmin/user_upload/customers/ifs.hsr.ch/Home/projekte/ADMentor-WICSA2015ubmissionv11nc.pdf), IEEE/IFIP WICSA 2015).

| Model Type | Problem Space | Relation | Solution Space |
| -- | -- | -- | -- |
| Reach/Level | Asset (Community) | | Project |
| Owner | Knowledge Engineer | | Software Architect |
| Purpose | Design Guidance | | Decision (Back-)Log |
| Need for Architectural Decision | Problem <br> `\--raises-^` | `--1-instantiates-n-->` | Problem Occurrence |
| Design Candidates | Option | `--1-instantiates-n-->` | Option Occurrence |

We collect generalized architectural decisions based on categories:

| Category | Repository |
| -- | -- |
| Java | <https://github.com/adr/gadr-java> |
| LaTeX | <https://github.com/latextemplates/gadr-latex-packages> |
| Misc | <https://github.com/adr/gadr-misc> |

ADRs taken when designing GADR are recorded at [docs/adr](docs/adr).

Scientific paper: [Oliver Kopp and Anita Armbruster: Generalized Markdown Architectural Decision Records: Capturing the Essence of Decisions (short paper). ZEUS 2019: 55-57](https://dblp.org/rec/conf/zeus/KoppA19)
