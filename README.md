# getting_and_clean_data_samsung_activities
a repo for data science project: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
# How to use
data is already downloaded and included in this repo called data.zip. if you want to download the data again, please make sure you download it and rename it to `data.zip`, the downloading script is also included in `run_analysis.R`, see line 5 to 8.

1. clone this repo to your local machine.
2. run `run_analysis.R` with R Studio(best choice).
3. the script will download zip file if there's not one and unzip it. the script will find those .txt files and read them into data.tables before perform any analysis.
4. the script needs `plyr` package to perform certain anaylsis, if you don't have this package installed, please do `install.packages('plyr')` to install it.
5. run the script will give you all the variables for your R session.
6. type `x_all`, `y_all`, `subject_all`, `clean_data`, `final_tidy` to check all variables.
