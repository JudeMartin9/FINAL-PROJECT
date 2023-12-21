Independent Project 2 by Jude

In this project, I worked with:

Powerpoint slides(For presentation)

Where the code is;
FINAL PROJECT.ipynb

With four CSV files;

1. netflix_titles.csv (original dataset chosen for the project)
2. idmb_top_1000.csv (related dataset chosen to merge with the first one )
3. merged_dataet.csv (result if merging title columns of the first and second dataset)
4. past_df.csv (the final name for the dataset I worked with after handling missing   values in the 'merged_dataset.csv')


MERGING 1ST AND 2ND DATASETS : 
In this case, I chose to merge the title columns of these datasets, hence checking column names to see if they had the same name 'title'. The idmb dataset column name was 'series_title' so it wouldn't be possible to merge with a different column name. So I changed the column name 'series_title' to 'title' as shown in the jupyter notebook. Upon completing the renaming of columns, I was able to merge the two datasets and saved the final dataset to a CSV file (merged_dataset.csv) 

DEALING WITH MISSING VALUES IN NEWLY MERGED DATA :
I loaded the merged dataset and named it past_data. Then to find missing values, I used a code that prints the number of missing values in each column of the past_df.(refer to the FINAL PROJECT.ipynb). Originally, the column 'director' had 8 missing values and the 'country' column had 2 missing values. So I filled the missing values of both columns with the parameter 'N/A' which stands for not available. To confirm whether there were any missing values left, I saved the past_df to a CSV file and checked to see if the columns that had missing values were replaced with 'N/A' (Refer to past_df.csv)

Upon handling missing values, I checked for unique values in the past_df and went on to discuss distributions using visualizations. (Refer  to the PowerPoint slide presentation or FINAL PROJECT.ipynb)
