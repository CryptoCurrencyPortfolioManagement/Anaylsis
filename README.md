# Analysis

This directory contains all code which was used to evaluate the performance data generated by running the different types of algorithms with different parameters. This analysis is split in two parts, the main_textextraction.py analysis the performance by the different text extraction models. This is extended by the main_local.py script which runs the same analysis for the models trained locally (linear regression with and without price). The main_portfolioconstruction script on the other hand compares the models with different portfolio construction techniques with each other. Lastly, gdriveHandler.py and utils provide helper functions for the other scripts to get data from Google Drive and Weights and Biases.

### data
Directory containing the data, namely the Content.parquet and Price.parquet generated by the Data Collection repository. Furthermore, the results generated by the local models are stored in the sub-directory "localApproaches".

### other
Directory containing various scripts and their outputs in particular:
- Analysis of the price data (analysisPriceData.py, generateCcReturnPlot.py)
- Analysis of the text data (analysisTextData.py)
- Analysis of certain attributes / parameters of the models (plot_complexityVsPerformance.py, plot_fullVsLimitedLookback.py, plot_transformerFrozen.py, plot_w2vComparisson.py, plot_positionsVsInformationCriteria.py)

### output_portfolioconstruction
Plots, .csv and .tex files generated by the portfolio construction evaluation script.

### output_textextraction
Plots, .csv and .tex files generated by the text extraction evaluation scripts.

### testPerformance
Directory conatining the scripts to generate the plots evaluating the test set performance and comparing it to the evaluation set performance.


