## EXNO-3-DS

# AIM:
To read the given data and perform Feature Encoding and Transformation process and save the data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Encoding for the feature in the data set.
STEP 4:Apply Feature Transformation for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE ENCODING:
1. Ordinal Encoding
An ordinal encoding involves mapping each unique label to an integer value. This type of encoding is really only appropriate if there is a known relationship between the categories. This relationship does exist for some of the variables in our dataset, and ideally, this should be harnessed when preparing the data.
2. Label Encoding
Label encoding is a simple and straight forward approach. This converts each value in a categorical column into a numerical value. Each value in a categorical column is called Label.
3. Binary Encoding
Binary encoding converts a category into binary digits. Each binary digit creates one feature column. If there are n unique categories, then binary encoding results in the only log(base 2)ⁿ features.
4. One Hot Encoding
We use this categorical data encoding technique when the features are nominal(do not have any order). In one hot encoding, for each level of a categorical feature, we create a new variable. Each category is mapped with a binary variable containing either 0 or 1. Here, 0 represents the absence, and 1 represents the presence of that category.

# Methods Used for Data Transformation:
  # 1. FUNCTION TRANSFORMATION
• Log Transformation
• Reciprocal Transformation
• Square Root Transformation
• Square Transformation
  # 2. POWER TRANSFORMATION
• Boxcox method
• Yeojohnson method

# CODING AND OUTPUT:
![386942962-b984621b-4c52-4ec8-a41f-0a875f0df12b](https://github.com/user-attachments/assets/7b58d8b8-0ce5-4724-9403-c98c714539ab)
![386942969-66bcfa98-2994-4036-ae34-a1bcfd62592e](https://github.com/user-attachments/assets/7598cf3a-c3d5-4cea-b4ba-7d8a9c308811)
![386942984-c51d93b8-d181-48f7-853a-1c0b5e621a60](https://github.com/user-attachments/assets/4ca9aca5-21be-4f3b-8ca7-4107e4dbc3b4)
![386942994-97305da5-35eb-4edf-86b7-e9d934bea7e6](https://github.com/user-attachments/assets/05a0adff-a203-4267-bc8b-f2009d27c681)
![386942999-ae89106f-f34a-424f-9ac6-5581b61204ef](https://github.com/user-attachments/assets/f8bf5861-5ed5-4f5b-9264-d0a469dc5d4f)
![386943016-cbcdc54d-33d3-45bf-b3e6-6721288db1c4](https://github.com/user-attachments/assets/b18a182d-8b52-4aa0-98f8-a2252426e918)
![386943022-d10a71cf-f14b-4a48-bccf-7c0687b5a0d2](https://github.com/user-attachments/assets/8bf324f3-635f-49c4-9efc-938b62126b0f)
![386943027-42df7283-8747-4a41-960b-cc35d0a6bd24](https://github.com/user-attachments/assets/c91db83f-21e4-4874-b204-8a183c19b755)
![386943032-0cdfabb9-60da-4a46-a5a9-36298adff1e6](https://github.com/user-attachments/assets/ea0c2152-3440-4860-a535-5539c45137dc)
![386943052-09b6a575-eb74-417d-816f-af81a4f0d8b1](https://github.com/user-attachments/assets/14fb566a-1193-4fe1-bb77-f8b81560c89c)



# RESULT:
The data was successfully read, feature encoding and transformation were performed.
       
