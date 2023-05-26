# Childhood Family Residential Mobility and Long-run Education \& Labor Outcomes
**Authors: Sifei Liu, Bhavya Pandey, Yicheng Zhang**  
This git repositiory is for the final project of University of Chicago ECMA31320 (Spring, 2023)

* Codes folder:
    1. [clean_data.ipynb](https://github.com/iefis/ecma31320_gp_LPZ/blob/7b6fac5eb0db20f4ecb1dd3efb35bd619c788422/replication_pkg_lpz/code/clean_data_final.ipynb): contains the initial data wangling steps to be executed in Python environment.
    2. [Edu-Move.Rmd](https://github.com/iefis/ecma31320_gp_LPZ/blob/7b6fac5eb0db20f4ecb1dd3efb35bd619c788422/replication_pkg_lpz/code/Edu-Move_Final.Rmd) contains R code and results for data analysis and visualization of family mobility on children's educational outcomes. The code should be executed in R environment.
    3. [Income-Move_Final.Rmd](https://github.com/iefis/ecma31320_gp_LPZ/blob/7b6fac5eb0db20f4ecb1dd3efb35bd619c788422/replication_pkg_lpz/code/Income-Move_Final.Rmd) contains R code and results for data analysis and visualization of family mobility on children's labor outcomes. The code should be executed in R environment.

* Data folder:
    1. [full_sample.csv.zip](https://github.com/iefis/ecma31320_gp_LPZ/blob/88240d88e36f6e36319bc2c0f8d5318b4ab645cb/replication_pkg_lpz/data/full_sample.csv.zip) is the compressed file of the raw data requested from [**PSID**](https://psidonline.isr.umich.edu) that contains the full data sample we used in this project.
    2. [full_sample_output.csv](https://github.com/iefis/ecma31320_gp_LPZ/blob/88240d88e36f6e36319bc2c0f8d5318b4ab645cb/replication_pkg_lpz/data/fullsample_output.csv) is the output file running *clean_data* code on *full_sample.csv*. It is also the input file for data analysis.

* To replicate the results:
    1. Unzip [full_sample.csv.zip](https://github.com/iefis/ecma31320_gp_LPZ/blob/88240d88e36f6e36319bc2c0f8d5318b4ab645cb/replication_pkg_lpz/data/full_sample.csv.zip)
    2. Change the file path to the corresponding file path of the unzipped full_sample.csv in [clean_data.ipynb](https://github.com/iefis/ecma31320_gp_LPZ/blob/7b6fac5eb0db20f4ecb1dd3efb35bd619c788422/replication_pkg_lpz/code/clean_data_final.ipynb) and run the entire script. An output of csv file will be produced.
    3. Change the file path in Rmd files to the path of the output file and run the R script.

