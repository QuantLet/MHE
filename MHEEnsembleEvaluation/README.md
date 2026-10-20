<div style="margin: 0; padding: 0; text-align: center; border: none;">
<a href="https://quantlet.com" target="_blank" style="text-decoration: none; border: none;">
<img src="https://github.com/StefanGam/test-repo/blob/main/quantlet_design.png?raw=true" alt="Header Image" width="100%" style="margin: 0; padding: 0; display: block; border: none;" />
</a>
</div>

```
Name of QuantLet: MHEEnsembleEvaluation

Published in: MHE - Performance Analysis and Comparison of Metaheuristics for Generating Ensembles of Classifiers

Description: Accumulates outputs of MHEMetaheuristicEnsembles and performs test set predictions of ensembles. Predictions are tested for differences among scores and among metaheuristics by means of the Friedman test. The four best metaheuristics are compared to best base model, simple average ensemble, greedy optimization technique, ensemble selection and LASSO regression.

Inputs: A string path for the initial working directory. This working directory must contain a folder named datasets in which data sets in .txt-format are stored, and another folder named predictions that contains outputs produced by MHEModelClassifiers and MHEMetaheuristicEnsembles.

Output: MHEEnsembleEvaluation_01   -	Mean ranks of scores in Friedman test regarding score differences in AUC MHEEnsembleEvaluation_02   -	Boxplots of scores regarding computation time MHEEnsembleEvaluation_03   -	Corrected p-values in post hoc test regarding AUC MHEEnsembleEvaluation_04   -	Mean ranks of scores in Friedman test regarding computation time MHEEnsembleEvaluation_05   -  	Mean ranks of scores in Friedman test regarding sparsity MHEEnsembleEvaluation_06   -  	Corrected p-values in post hoc test regarding differences of scores in sparsity MHEEnsembleEvaluation_07   -	Boxplots of scores regarding percentage of zero weights MHEEnsembleEvaluation_08   -	Boxplots of metaheuristics regarding computation time MHEEnsembleEvaluation_09   -	Mean ranks of metaheuristics in Friedman test regarding Brier score MHEEnsembleEvaluation_10   -	Mean ranks of metaheuristics in Friedman test regarding H-measure MHEEnsembleEvaluation_11   -	Corrected p-values in post hoc test regarding differences of metaheuristics in H-measure MHEEnsembleEvaluation_12   -	Mean ranks of metaheuristics in Friedman test regarding difficulty MHEEnsembleEvaluation_13   -	Mean ranks of metaheuristics in Friedman test regarding interrater agreement MHEEnsembleEvaluation_14   -	Mean ranks of metaheuristics in Friedman test regarding computation time MHEEnsembleEvaluation_15   -	Mean ranks of metaheuristics in Friedman test regarding percentage of zero weights MHEEnsembleEvaluation_16   -	Corrected p-values in post hoc test regarding differences of metaheuristics in computation time MHEEnsembleEvaluation_17   -	Corrected p-values in post hoc test regarding differences of metaheuristics in sparsity MHEEnsembleEvaluation_18   -	Boxplots of metaheuristics regarding percentage of zero weights MHEEnsembleEvaluation_19   - 	Table of best metaheuristics compared to other techniques based on Brier score relative to global optimum.

Keywords: data mining, Testing, LASSO, classification, statistics, machine learning, ensemble of classifiers, metaheuristic

See also: MHEModelClassifiers, MHEMetaheuristicEnsembles

Author: Ringolf Thomschke

Datafile: datasets, predictions

```
<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/MHE/master/MHEEnsembleEvaluation/MHEEnsembleEvaluation_01.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/MHE/master/MHEEnsembleEvaluation/MHEEnsembleEvaluation_02.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/MHE/master/MHEEnsembleEvaluation/MHEEnsembleEvaluation_03.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/MHE/master/MHEEnsembleEvaluation/MHEEnsembleEvaluation_04.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/MHE/master/MHEEnsembleEvaluation/MHEEnsembleEvaluation_05.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/MHE/master/MHEEnsembleEvaluation/MHEEnsembleEvaluation_06.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/MHE/master/MHEEnsembleEvaluation/MHEEnsembleEvaluation_07.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/MHE/master/MHEEnsembleEvaluation/MHEEnsembleEvaluation_08.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/MHE/master/MHEEnsembleEvaluation/MHEEnsembleEvaluation_09.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/MHE/master/MHEEnsembleEvaluation/MHEEnsembleEvaluation_10.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/MHE/master/MHEEnsembleEvaluation/MHEEnsembleEvaluation_11.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/MHE/master/MHEEnsembleEvaluation/MHEEnsembleEvaluation_12.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/MHE/master/MHEEnsembleEvaluation/MHEEnsembleEvaluation_13.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/MHE/master/MHEEnsembleEvaluation/MHEEnsembleEvaluation_14.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/MHE/master/MHEEnsembleEvaluation/MHEEnsembleEvaluation_15.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/MHE/master/MHEEnsembleEvaluation/MHEEnsembleEvaluation_16.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/MHE/master/MHEEnsembleEvaluation/MHEEnsembleEvaluation_17.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/MHE/master/MHEEnsembleEvaluation/MHEEnsembleEvaluation_18.png" alt="Image" />
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/QuantLet/MHE/master/MHEEnsembleEvaluation/MHEEnsembleEvaluation_19.png" alt="Image" />
</div>

