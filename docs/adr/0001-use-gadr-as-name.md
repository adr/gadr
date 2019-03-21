# Use GADR (Generalized Architectural Decision Records) as name for GADRs

* Status: accepted

## Context and Problem Statement

In the paper [Architectural Decision Guidance across Projects by Olaf Zimmermann, Lukas Wegmann, Heiko Koziolek and Thomas Goldschmidt](https://doi.org/10.1109/WICSA.2015.29), it is distinguished between "problem space" and "solution space"

![Problem/solution space model elements and their link types](0001-problem-solution-space-model)

Currently, we offer "MADR" as concept for the "solution space", where concrete solutions are written down.
In addition, it can be abstracted from the solution space to the "problem space" to offer a collection of solutions, where one can pick from.

For instance: Concidered Options: "Maven, Gradle, Ant".
They all have their "global" pros and cons.
When going "locally", i.e., to a concrete project, new pros/cons are added and one option is chosen.
Moreover, a context is added.
That means, the format of the "global MADRs" differs from the format of the "local MADRs".

Question: How should the "global MADRs" be called?

## Decision Drivers

* Consistent name to "MADR"
* Keep "MADR" as name
* Consistent name pairs newname/MADR to problem space / solution space
* Easy to read
* No "WTF" moments when reading

## Considered Options

* GADR (for "Generalized Architectural Decision Records")
* GMADR (for "global MADR") - keep MADR
* GMADR (for "generic MADR") - keep MADR
* PMADR (for "problem MADR") - possibly SMADR (for "solution MADR")
* AMADR (for "abstract MADR") - IMADR (for "instanitated MADR")
* AADR (for "abstracted architectural decision record")
* AMADR (for "abstracted markdown architectural decision record")
* CMADR (for "challenge MADR") - SMADR (for "solution MADR")
* GMADR (for "generic MADR") - SMADR (for "specialized MADR")

## Decision Outcome

Chosen option: "GADR (for Generalized Architectural Decision Records)", because

* keeps name "MADR"
* the name states the relation to concrete ADRs: they are "generalized"
* "AADR" and "AMADR" sound bad
