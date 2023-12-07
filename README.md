# datasci_9_data_prep

## objective: the goal of this assignment was to focus on selecting datasets suitable for a machine learning experiment, with an emphasis on data cleaning, encoding, and transformation steps necessary to prepare the data. Since proper data preparation is crucial in machine learning and can significantly impact the performance of our models, we were to pay attention to the details of each dataset and the specific requirements of the machine learning tasks we plan to perform.


## Part 1: Datasets selection


### dataset 1: https://catalog.data.gov/dataset/crime-data-from-2020-to-present

### description of dataset: This dataset reflects incidents of crime in the City of Los Angeles dating back to 2020. This data is transcribed from original crime reports that are typed on paper and therefore there may be some inaccuracies within the data. Some location fields with missing data are noted as (0°, 0°). Address fields are only provided to the nearest hundred block in order to maintain privacy. 


### dataset 2: https://catalog.data.gov/dataset/u-s-chronic-disease-indicators-cdi   


### description of dataset: CDC's Division of Population Health provides cross-cutting set of 124 indicators that were developed by consensus and that allows states and territories and large metropolitan areas to uniformly define, collect, and report chronic disease data that are important to public health practice and available for states, territories and large metropolitan areas.

## Part 2: Desired Machine Learning Task: Classification

### The dataset referenced here has been utilized in the model_dev_1 directory.

### To organize within model_dev_1, establish three directories: data, model, and scripts.

### Under the data directory, create two additional folders named processed and raw.

### - Inside the scripts directory, generate three Python files: p1_extract.py, p2_transform.py, and p3_compute.py.

### - In p1_extract.py, load the dataset and store it as both a CSV and a pickle file within the raw folder.

### - Within p2_transform.py, load the pickle file located in the raw folder. For data cleansing:


### Cleanse column names by eliminating white spaces, special characters, and converting all letters to lowercase.
### Validate data types and adjust any mismatches as necessary.
### Identify and discard rows containing missing data.
### Choose relevant columns for computation while discarding unnecessary ones.



## For data transformation:

### - Implement ordinal encoding on chosen categorical value columns.
### - Create an encoding DataFrame with corresponding mappings.
### - the mappings as a CSV file in the processed folder.
### - Repeat the encoding process for the required columns.
### - Save a temporary CSV file of the encoded DataFrame into the processed directory.
### - Ensure all values within the new DataFrame are numerical.


## Desired machine learning task: Regression. This specific dataset was used in the model_dev_2 folder. Repeat the same procedures applied to the dataset 1 but done in the model_dev_2 directory.


## Part 3 Issues: I think that the datasets were too big because every time i tried to push it to github i got an error stating that " ". So I took screenshots of all my work and uploaded them in a folder that I put in github. If you need screenshots of anything else, please let me know. Also, an image of the github upload error is in the folder as well. 
