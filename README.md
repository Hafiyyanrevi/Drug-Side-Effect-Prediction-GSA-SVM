
# Drug-Side-Effect-Prediction-GSA-SVM
This is my final project research, aiming to predict drug side effects with a focus on eye disorder cases using the Gravitational Search Algorithm (GSA) method for feature selection and Support Vector Machine (SVM) as a prediction model. The model development process is done by tuning hyperparameters on Linear, Polynomial, and Radial Basis Function (RBF) kernels. The best results were obtained on the RBF kernel with an accuracy value of 0.6391 and F1-score of 0.7163, showing the potential of the GSA-SVM method in early identification of drug side effects.

## Project Background
This is my final project research, aiming to predict drug side effects with a focus on eye disorder cases using the Gravitational Search Algorithm (GSA) method for feature selection and Support Vector Machine (SVM) as a prediction model. The model development process is done by tuning hyperparameters on Linear, Polynomial, and Radial Basis Function (RBF) kernels. The best results were obtained on the RBF kernel with an accuracy value of 0.6391 and F1-score of 0.7163, showing the potential of the GSA-SVM method in early identification of drug side effects.

Project Background

Adverse drug reactions (ADRs) are unwanted and often harmful pharmacological effects that occur following the use of a drug.  It is estimated to be the fourth leading cause of death in the United States, resulting in approximately 100,000 deaths each year. The biggest challenge in detecting adverse drug events is that the process is expensive, time-consuming, and has limitations in efficiency.

As concerns over drug toxicity increase, there is a need to speed up and reduce costs in the drug discovery process by using machine learning to identify potential side effects early. Approaches such as Gravitational Search Algorithm (GSA) and Support Vector Machine (SVM) have shown promising results in various ADR prediction studies. GSA has the advantage of finding the global optimal solution, which is helpful in feature selection to improve prediction accuracy, while SVM is known to excel in classification capabilities.

This study focuses on the case of eye disorders, using the GSA-SVM approach, this research aims to develop a prediction model that can help identify drug side effects more efficiently and accurately, thus supporting efforts to mitigate the risk of ADRs in the drug development process.

## About The Dataset
About The Dataset

The Side Effect Resource (SIDER) is a database of marketed drugs and adverse drug reactions (ADR). The version of the SIDER dataset in DeepChem has grouped drug side effects into 27 system organ classes following MedDRA classifications measured for 1427 approved drugs.

The data file contains a csv table, in which columns below are used:
     "smiles" - SMILES representation of the molecular structure
     "Hepatobiliary disorders" ~ "Injury, poisoning and procedural complications" - Recorded side effects for the drug
	Please refer to http://sideeffects.embl.de/se/?page=98 for details on ADRs.

References:
Kuhn, Michael, et al. "The SIDER database of drugs and side effects." Nucleic acids research 44.D1 (2015): D1075-D1079.
Altae-Tran, Han, et al. "Low data drug discovery with one-shot learning." ACS central science 3.4 (2017): 283-293.
Medical Dictionary for Regulatory Activities. http://www.meddra.org/

Paper link of this project: 
https://ieeexplore.ieee.org/document/10732772