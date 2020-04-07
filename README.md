Assessing the fit between data and results of a system dynamics simulational model is part of a larger set of confidence buidling tests (Sterman, 2000). Specifically, in the behavior reproduction test, one is seeking to replicate observed behavior in the real system. In system dynamics, observed behavior usually means the reference mode or some longitudinal pattern that is the focus of a system dynamics study, but observed behavior can also include patterns of association such as a correlation or covariance matrix, a distribution, phase space, and really any other way that behavior may be observed. 

Sterman (1984) succintly describes the limitations of previous arguments on the matter of establishing validity, and put forwards a set of tests for assessing fit that are consistent with Forrester and Senge's (1980) emphasis on how to view behavior reproduction tests. However, these tests are rarely used despite being relatively easy to implement. 

This project provides a set of structures for isee Systems STELLA that can be used to calculate fit statistics as proposed by Sterman (1984, 2000). This includes the use of a module that calculates a set of fit statistics, some or all of which can be used within a model, and a set of macros that return each statistic. 

The main difference between the two approaches is their implementation. While the use of macros as user defined built-in functions may be easier for the modeler, it's computationally "more expensive" as each macro needs to calculate all the values on which it depends leading to a significant amount of duplicated calculations. 

# References
Forrester, J. W., & Senge, P. M. (1980). Tests for building model confidence in system dynamics models. In G. P. Richardson (Ed.), *Modelling for Management: Volume II: Simulation in Support of Systems Thinking.* (pp. 413--432). Brookfield, VT: Dartmouth Publishing Company, Ltd.

Sterman, J. D. (1984). Appropriate summary statistics for evaluating the historical fit of system dynamics models. *DYNAMICA*, 10(2), 51-66. 

Sterman, J. D. (2000). *Business dynamics: Systems thinking and modeling for a complex world.* Irwin McGraw-Hill.
