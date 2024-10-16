Jupyter notebook-Visualization

---Introduction

This notebook aims to visualize in detail the performance of the portfolios generated by the SandBox R code. The data is visualized for MPT statistics, 3 holding periods, different ranking periodicities, and the different portfolio styles viz. Top Quintile (TQ), Bottom Quintile (BQ), Top and Bottom Quintile (TBQ), and Rest Quintile excluding top and bottom quintile (RQ), and all quintiles (AQ). Cartesian, histogram, line, and distribution plots are used for the visualizations.


-Input
The code receives as input all comma-separated values (CSV) files that start with Average_Summary _... (where portfolio performance is stored, such as annualized excess returns, annualized excess volatility, information ratio, alpha, beta, drawdowns, tracking error, etc.). These files are previously generated by SandBox R code.




---Requirements
To run this code, you will need:
Anaconda Navigator with Python 3.8.8 or later (https://www.anaconda.com/products/individual)



---Installation
After the installation of Anaconda Navigator is completed some packages will need to be installed. Open the Anaconda Prompt and type:



conda install pandas
conda install numpy
conda install -c conda-forge altair
conda install -c conda-forge prettytable



Versions used:
pandas - 1.2.4
python - 3.8.8
altair - 4.1.0
numpy - 1.20.1
prettytable - 3.0.0
Anaconda Navigator 2.0.3




---Input files
/All_SP100: Average_Summary_....CSV files generated by the R code for S&P100.
...
/All_SP100.txt: text file containing information about S&P100.
...
/Groups-information.txt: text file containing the paragraphs at the beginning of each pdf. 
