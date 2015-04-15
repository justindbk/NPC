# NPC
Nonparametric Combination of Hypothesis Tests for R

Author: Devin Caughey, devin.caughey@gmail.com

NPC is a package for performing nonparametric combination (Pesarin and Salmaso 2010), a permutation-based procedure for jointly testing multiple hypotheses. The tests are conducted under the global "sharp" null hypothesis of no effects, and the component tests are combined on the metric of their p-values. A key feature of nonparametric combination is that it accounts for the dependence among tests under the null hypothesis. In addition to the "NPC" function, which performs nonparametric combination itself, the package also contains a number of helper functions, many of which calculate a test statistic given an imput of data.
