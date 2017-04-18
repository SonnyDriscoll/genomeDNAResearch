# genomeDNAResearch
Python framework files for the research supporting the paper "Predicting the next character in a DNA genome sequence using data analysis and machine learning techniques"

The following lines explain the purpose of groups of files:

'Galaxy9 -(Pseudomonas_aeruginosa_PA7_Genome.fna).fata.txt'
This file is the original raw datafile that was used for the experiments.
Further details and the download link can be found here: https://www.ncbi.nlm.nih.gov/pubmed/20107499


'classifierResults.xlsx'
This file contains the full detailed results from all experiments conducted.


'dataAnalyticalCharts.ipynb' & 'dataAnalyticalCharts_best_worst_analysis.ipynb'
These files contain various visualisations and visulaisation attempts of the experiment results.


Files beginning with 'dataClassifier' e.g. 'dataClassifier_10_6_1.ipynb'
These files import the required data and arrange it in to input and output variables.
The data is then classified by the following classifiers: DT, Random Forest, Neural Net, SVM.
The first number denotes the length of the data inputs, the second number denotes the number of inputs,
and the third number denotes the length of target variable.
So in the case of 'dataClassifier_10_6_1.ipynb'
Length of input variable = 10
Number of input variables = 6
Length of target variable = 1


Files 'dataClassifier_TESTING.ipynb' & 'dataClassifier_TESTING_2'
These files were used as the testing of the classifiers.
Files 'geneData_TEST.xlsx' & 'geneData_TEST_2.xlsx' were created and used for this purpose.


Files beginning with 'dataPrepMaster' e.g. 'dataPrepMaster_120_1_1.ipynb'
These files were used to prepare the original datafile in to a new file, with one input variable.
For the file 'dataPrepMaster_120_1_1.ipynb' the pattern in the new file would be as follows:
Length of input variable = 120
Number of input variables = 1
Length of target variable = 1


Files beginning with 'dataPrep_STEP' e.g. 'dataPrepSTEP_10_6_1.ipynb'
These files were used to prepare the original datafile in to a new file with multiple input variables.
These file was used to prepare data for the experiments 'data split method two', which took a step of N length along the 
original string before taking new characters for both input and output.
For the file 'dataPrepSTEP_10_6_1.ipynb' the pattern in the new file would be as follows:
Length of input variable = 10
Number if input variables = 6
Length of target variable = 1
This file also has a seperate variable for the length of 'step' to be taken along the string.
This hard-coded variable is named 'lengthOfSteps'.


Files beginning with 'masterDataPrep' e.g. 'masterDataPrep_4_3_1.ipynb'
These files were used to prepare the original datafile in to a new file with multiple input variables.
These file was used to prepare data for the experiments 'data split method one', which took a step of length 1 along the 
original string before taking new characters for both input and output.
For the file 'masterDataPrep_4_3_1.ipynb' the pattern in the new file would be as follows:
Length of input variable = 4
Number if input variables = 3
Length of target variable = 1


Files beginning with 'geneData' e.g. 'geneData_12_5_1.xlsx' are the files which are newly prepared from the original dataset,
and used for further analysis.
For the file 'geneData_12_5_1.xlsx' the pattern contained within the excel sheet would be as follows:
Length of input variable = 12
Number if input variables = 5
Length of target variable = 1


Files beginning with 'stepDataPrep' e.g. 'stepDataPrep_12_5_1.xlsx' are the files which are newly prepared from the original dataset,
and used for further analysis.
These files were created by the scripts contained within the files starting 'dataStepPREP', and follow the same stepped splitting 
method as already explained.
For the file 'geneData_12_5_1.xlsx' the pattern contained within the excel sheet would be as follows:
Length of input variable = 12
Number if input variables = 5
Length of target variable = 1
