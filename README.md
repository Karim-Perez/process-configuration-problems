# process-configuration-problems
This repository contains the benchmark instances and detailed results for the integrated process configuration and production planning problems used in the paper *Logic-based Benders Decomposition for Integrated Process Configuration and Production Planning Problems* (reference to be updated). This paper considers applications in two different contexts: the printing industry and the steel tube industry. In both contexts, the optimization problem consists on jointly determining the optimal configuration of the production equipment and the optimal production planning decisions. 

* **Optimization problem in the printing industry.** The problem and the benchmark instances considered in this application correspond to the ones introduced in the following papers:
  * Baumann, P., Forrer, S., Trautmann, N. (2015): *Planning of a make-to-order production process in the printing industry*. Flexible Services and Manufacturing Journal 27, 534-560. by Baumann P, Forrer S, Trautmann N (2015) 
  * Baumann P, Trautmann N (2014) *Efficient symmetry-breaking formulations for grouping customer orders in a printing shop. 2014 IEEE International Conference on Industrial Engineering and Engineering Management, 506- 510*. 

  The original data for this problem can be found in the repository created by the original authors at [https://github.com/phil85/FSMJ15-Instances](https://github.com/phil85/FSMJ15-Instances). For convenience, we have also include this data in  the folder `PrintingProblem` with a self-explanatory format.

* **Optimization problems in the steel tube industry**. The problem variants and the benchmark instances considered in this applications correspond to 50 randomly generated instances and the ones presented in the paper:
  * Hajizadeh I, Lee C (2007) *Alternative configurations for cutting machines in a tube cutting mill*. European Journal of Operational Research 183(3):1385-1396.
  
  This application considers three different variants of cutting stock problems which appear in the steel tube industry. The data files can be found in the folder `CuttingStockProblems`. Within this folder you will find the file `data_format.txt` with instructions on how to read the data files. 

* **Detailed Results.** The detailed results reported in the main paper appear in the Excel file `DetailedResultsOnline.xlsx`. The detailed results of each application is presented in a separate worksheet: `Open-ended CSCP`, `Closed-Ended CSCP`, `Knife-Dependent CSCP`, which correspond to the three variants of the problem in the steel tube industry, and `Printing application`, which corresponds to the detailed results of the problem in the printing industry. All results are presented according to the classification of the benchmarks into Sets A, B, C and D, as described in the main paper. 
