# Generic Buy Now, Pay Later Project

<<<<<<< HEAD
Group members:
Jiaming Zheng 1173102
Honghao Ou 1170567
Jiaqi Tang 1074453
Jie Xie 1174437
Jie Zhang 1053428
            


**Research Goal:** Build a ranking system to determin what type of merchants are the most suitable for the BNPL system. 
**Timeline:** Timeline of the data is from 28/2/2021 to 28/8/2022.

To run the pipeline, please visit the `notebook` directory and run the files from 1-8 in order:
1. `1.preliminary analysis.ipynb`: This notebook reads and  preprocesses the raw data, outputs the details of transactions and merchants to the`data/curated` directory.
2. `2.Geovisualisation.ipynb`: This notebook reads the income by postcode data then creates visualization of income by postcode and consumer distribution and outputs them to `plots/`.
3. `3.merchant main postcode.ipynb`:This notebook adds the merchants' main postcode as a new feature and outputs merchant details to the 'data/curated
4. `4.Missing value and outliers` : This notebook determines the presence and imputes the missing values, takes transformation of features, removes outliers and outputs the filtered data to `data/curated`.
5. `5.read transaction data with month`: This notebook reads the transaction data with its date, computes the monthly income for each merchant, and outputs the data to `data/curated`.
6. `6.compute monthly profit growth`: This notebook computes the monthly profit growth for each merchant, outputs the result to `data/curated`.
7. `7.fraud probability imputation.ipynb`: This notebook computes the fraud probability for each merchant, outputs the result to `data/curated`.
8. `8.ranking system.ipynb`: This notebook constructs the ranking system and illustrates the top 10 merchants for each category.
9. `Summary of Project`: This notebook summary the approach and result of the project.
`