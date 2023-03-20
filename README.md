# data-cleaning
# Ex-01_DS_Data_Cleansing
# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# ALGORITHM
## STEP 1
Read the given Data

## STEP 2
Get the information about the data

## STEP 3
Remove the null values from the data

## STEP 4
Save the Clean data to the file

# CODE
import pandas as pd
df=pd.read_csv("Data_set.csv")
printf(df)
df.head(10)

df.info()

df.isnull()

df.isnull().sum()

df['show_name']=['show_name'].fillna(df['aired_on'].mode()[0])
df['aired_on']=df['aired_on'].fillna(df['aired_on'].mode()[0])
df['original_network']=df['original_network'].fillna(df['aired_on'].mode()[0])
df.head()

df['rating']=df['rating'].fillna(df['rating'].mean())
df['current_overall_rank']=df['current_overall_rank'].fillna(df['current_overall_rank'].mean())
df.head()

df['watchers']=df['watchers'].fillna(df['watchers'].median())
df.head()

df.info()

#code 2

import pandas as pd
df=pd.read_csv("Loan_data.csv")
printf(df)
df.head(10)

df.info()

df.isnull()

df.isnull().sum()

df['show_name']=['show_name'].fillna(df['aired_on'].mode()[0])
df['aired_on']=df['aired_on'].fillna(df['aired_on'].mode()[0])
df['original_network']=df['original_network'].fillna(df['aired_on'].mode()[0])
df.head()

df['rating']=df['rating'].fillna(df['rating'].mean())
df['current_overall_rank']=df['current_overall_rank'].fillna(df['current_overall_rank'].mean())
df.head()

df['watchers']=df['watchers'].fillna(df['watchers'].median())
df.head()

df.info()

# OUPUT
![img1](https://user-images.githubusercontent.com/107982953/226191154-08ba4f16-b6f7-43b7-b3f9-cc4e12fc7219.png)
![img2](https://user-images.githubusercontent.com/107982953/226191247-3f0c538e-bb22-44db-92ad-d8ddd8872267.png)
![img3](https://user-images.githubusercontent.com/107982953/226191394-36f23c92-673f-47bb-8ebb-9216ca76ab98.png)
![img4](https://user-images.githubusercontent.com/107982953/226191472-d508cbb3-4ddc-4c9b-b6dc-379456b58b3e.png)
![img5](https://user-images.githubusercontent.com/107982953/226191524-72fcf8ee-6aff-4b55-88ef-45ad1bd528e4.png)
![img6](https://user-images.githubusercontent.com/107982953/226191597-65dfaed2-4c61-4077-a748-11da06defc0b.png)
![img7](https://user-images.githubusercontent.com/107982953/226191653-63c4cd72-cfd8-4f48-b2ae-e1845632d9eb.png)
![img8](https://user-images.githubusercontent.com/107982953/226191697-386809d9-0194-49f0-acc8-e9b4037c369f.png)





