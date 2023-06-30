# KNN-Tribo

# KNN-Tribo is a Python software that implements a k-nearest neighbors regression model to predict the coefficient of friction (COF) of porous Al–Al2O3 composites infiltrated with a tin-based alloy (B83) under dry sliding conditions.

# Installation

# The software requires Python 3.6 or higher and the following packages: pandas, numpy, sklearn, matplotlib. To install the software, clone or download current repo to your local machine.

# Usage

# To run the software, open a terminal window in the folder where the software is located and type:

python KNN-Tribo.py

# The software requires the names of the Excel files containing the experimental data of COF and time for each dataset of material B83 to be entered manually in the code. For example, in the line 12 of the KNN-Tribo.py file, the file names should be assigned to the variables file1, file2, and file3 as follows:

file1 = "composite_1.xlsx"
file2 = "composite_2.xlsx"
file3 = "composite_3.xlsx"

# The software will then perform the data preprocessing, model building, model evaluation, and data visualization steps. The output files containing the descriptive statistics, merged data, performance metrics, and plots will be saved in same folder where software is located.

# Support

# For any questions or issues, please contact mihail-15@github.com.

# License

# KNN-Tribo is released under the MIT License. See LICENSE file for details.
