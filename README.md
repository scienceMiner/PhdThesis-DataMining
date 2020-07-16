# Phd Thesis- Data Mining
---
## Data Mining Temporal and Indefinite Relations using Numerical Dependencies.

###Department of Computer Science, University College London, University of London
---

We propose that data mining, the search for useful, non-trivial and previously unknown information within a database,
can be successfully performed with Numerical Dependencies (NDs), a generalisation of Functional Dependencies (FDs), to model the data, together with resampling, 
a computationally intensive statistical sampling process, which allows us to make inferences from temporal and indefinite databases.

We use NDs to model relations containing temporal and indefinite information. We extend the theory of NDs by presenting measures for data mining and generalise 
the chase procedure, a method for updating a relation to satisfy a constraint set, for NDs. We motivate NDs in real-world applications by introducing a database 
design tool incorporating evolutionary algorithms.

The consistency problem, that of attempting to find a relation satisfying a set of FDs within an indefinite relation, known to be NP-complete, is studied in the 
context of using NDs for approximation. We employ resampling, based on taking samples of definite relations from indefinite ones, on incremental
sample sizes until an approximate fixpoint is reached, denoting an upper bound on the required sample size. Extensive simulations highlight that resampling 
to find upper bounds in conjunction with the chase for indefinite relations returns valid approximate solutions.

We also study NDs in temporal sequences of relations for knowledge discovery purposes. Each relation within a sequence is mined for a set of NDs
which evolve with updates in data. We introduce a temporal logic for the discovery of rules and properties within these sequences, or
subsequences, which includes statistical functions within the temporal operators for time series analysis. We also show that time series data may be analysed
using a restricted set of the logic. We apply discovery algorithms to both sequences and resampled sequences, allowing smoothing for trend detection. 
Investigations, presented herein, show these rules to provide interesting and practicable results.

All simulations were implemented in C++.

### Copyright
The work herein is Copyright 1999-2029 Ethan Collopy and The University of London. No rights are given to reproduce or modify this work without permission.

###Plagiarism
No point!

### LaTeX compilation
Written before pdflatex so use latex->dvi->ps
