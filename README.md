# process-configuration-problems
This repository contains the benchmark instances and detailed results for the integrated process configuration and production planning problems used in the paper *Logic-based Benders Decomposition for Integrated Process Configuration and Production Planning Problems* (reference to be updated). This paper considers applications in two different contexts: the printing industry and the steel tube industry. In both contexts, the optimization problem consists on jointly determining the optimal configuration of the production equipment and the optimal production planning decisions. 

* **Optimization problem in the printing industry.** The problem and the benchmark instances considered in this application correspond to the ones introduced by Baumann P, Forrer S, Trautmann N (2015) *Planning of a make-to-order production process in the printing industry. Flexible Services and Manufacturing Journal 27(4):534-560*, and Baumann P, Trautmann N (2014) *Efficient symmetry-breaking formulations for grouping customer orders in a printing shop. 2014 IEEE International Conference on Industrial Engineering and Engineering Management, 506- 510*. The data files appear in the folder `PrintingProblem` with a self-explanatory format.

* **Optimization problems in the steel tube industry**. The problem variants and the benchmark instances considered in this applications correspond to the ones presented in Hajizadeh I, Lee C (2007) *Alternative configurations for cutting machines in a tube cutting mill. European Journal of Operational Research 183(3):1385-1396*, in addition to 50 randomly generated instances. This application considers three different variants of cutting stock problems which appear in the steel tube industry. The data files can be found in the folder `CuttingStockProblems`. Within this folder you will find the file `data_format.txt` with instructions on how to read the data files. 
