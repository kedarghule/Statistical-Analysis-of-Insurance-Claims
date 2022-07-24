# Statistical-Analysis-of-Insurance-Claims

## Problem Statement
Leveraging customer information is of paramount importance for most businesses. In the case of an insurance company, attributes of customers like the ones in the given dataset below can be crucial in making business decisions. The problem statement aims at finding out different relationships and correlations between the different attributes in the dataset and gather information about the dataset.

## Dataset
Link to Dataset: https://www.kaggle.com/datasets/mirichoi0218/insurance

Dataset Information:

- age: age of primary beneficiary

- sex: insurance contractor gender, female, male

- bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9

- children: Number of children covered by health insurance / Number of dependents

- smoker: Smoking

- region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.

- charges: Individual medical costs billed by health insurance

Our dataset has the following types of variables:
- Categorical varibles: sex, smoker, region, children
- Quantitative variables: age, bmi, charges. Here children is a discrete variable where as age, bmi, and charges are continous variables.

## Descriptive Statistics

![image](https://user-images.githubusercontent.com/41315903/180665051-8aea4ddb-deea-4e53-9179-4171e7f78010.png)

![image](https://user-images.githubusercontent.com/41315903/180665085-f42e4097-48dd-4da3-9796-6f45b3861323.png)

## Exploratory Data Analysis

### Univariate Analysis

#### Box Plot
![image](https://user-images.githubusercontent.com/41315903/180665123-ffb167eb-d2ec-4b0d-958e-95934c8bcc25.png)

#### Histogram and Rug Plot
![image](https://user-images.githubusercontent.com/41315903/180665160-ba35129d-5916-4b66-b188-9fbff5607ebb.png)
![image](https://user-images.githubusercontent.com/41315903/180665176-b4bb7c86-b1f7-4380-ac08-e97011fd787f.png)
![image](https://user-images.githubusercontent.com/41315903/180665186-0b6212f7-1a09-4295-98a6-09e3b084988a.png)
![image](https://user-images.githubusercontent.com/41315903/180665210-15a798ab-d6a1-4303-b47d-0e910cf53be9.png)

#### Bar Plot
![image](https://user-images.githubusercontent.com/41315903/180665235-55774c8e-f88d-4b3e-94d1-150440aa5231.png)

### Bivariate and Multivariate Analysis
#### Correlation among Features
![image](https://user-images.githubusercontent.com/41315903/180665257-34064c07-e476-4c73-a87b-984e9d89f59d.png)
#### Pair Plot
![image](https://user-images.githubusercontent.com/41315903/180665279-fe776373-b5a2-48ee-b181-f272ae3686d1.png)
![image](https://user-images.githubusercontent.com/41315903/180665303-17d938d1-a224-42a6-85cc-efac9efc6292.png)
#### Sex vs All Numerical Features
![image](https://user-images.githubusercontent.com/41315903/180665343-f6574201-883b-410e-a303-d1b07c9275dc.png)
![image](https://user-images.githubusercontent.com/41315903/180665370-1bb07e3a-07b6-4309-8625-610ae34e6112.png)
#### Smokers vs All Numerical Features
![image](https://user-images.githubusercontent.com/41315903/180665382-a0118005-7639-4845-b10e-bb566dd16b4b.png)
![image](https://user-images.githubusercontent.com/41315903/180665392-769a381b-162a-45f4-bf43-8fe896daa9bd.png)
#### Region vs All Numerical Features
![image](https://user-images.githubusercontent.com/41315903/180665410-6d2b7b56-4f64-4a09-99c2-f31bad1896f0.png)
![image](https://user-images.githubusercontent.com/41315903/180665432-5450f09f-c6c0-4d35-b8f1-439be5322147.png)

#### Comparing Categorical Features
![image](https://user-images.githubusercontent.com/41315903/180665492-0362d997-aee9-4518-8689-5595a54657d4.png)
![image](https://user-images.githubusercontent.com/41315903/180665511-b6517a5e-fb48-4754-8f26-62562d0ffb7b.png)
![image](https://user-images.githubusercontent.com/41315903/180665519-91d6b581-5d04-4afa-9ef5-0bfcd3451bfd.png)
![image](https://user-images.githubusercontent.com/41315903/180665531-cf597934-c44b-43a6-923c-8c9ca56eee6d.png)
![image](https://user-images.githubusercontent.com/41315903/180665539-5f5423a8-82b6-48c0-8dce-08022e7ab1c7.png)

#### Comparing Numerical Features and Categorical Features
![image](https://user-images.githubusercontent.com/41315903/180665544-d8bd2f22-1bc9-435d-ad00-c1bd2212f529.png)
![image](https://user-images.githubusercontent.com/41315903/180665569-32ccb7dc-4115-405a-94ac-9f1ebfb84e4e.png)
![image](https://user-images.githubusercontent.com/41315903/180665591-7f9eebbe-fb47-4f5a-a33b-6b2a1e79cce3.png)
![image](https://user-images.githubusercontent.com/41315903/180665601-b69ce5d9-732b-4a1e-bf60-bcfd0b9a7d7b.png)
![image](https://user-images.githubusercontent.com/41315903/180665614-c9b913bc-4269-44c8-b19a-d2aab67cb589.png)

#### BMI by Age Group Comparison
![image](https://user-images.githubusercontent.com/41315903/180665636-78b427a6-0f33-4b09-8d80-2cdb2dc7313d.png)
#### Age Group by Charges Comparison
![image](https://user-images.githubusercontent.com/41315903/180665658-3d0fb14e-5a9c-4ee7-8cb3-61398f103861.png)

#### More EDA
![image](https://user-images.githubusercontent.com/41315903/180665673-b7eff280-099b-4b4d-8e63-68b375d70232.png)
![image](https://user-images.githubusercontent.com/41315903/180665681-0c2176c6-da1d-47a4-93c0-59e607a2e129.png)
![image](https://user-images.githubusercontent.com/41315903/180665692-3216d817-aad8-4ef7-b150-928fa9bf4593.png)
![image](https://user-images.githubusercontent.com/41315903/180665703-acc7a099-0f02-44c7-9dcf-9452ea7b46df.png)
![image](https://user-images.githubusercontent.com/41315903/180665721-06d08204-2429-46c1-887b-f5ce7411254b.png)

## Statistical Analysis
![image](https://user-images.githubusercontent.com/41315903/180665740-9b55bf3d-3e19-493f-a174-e0b6b3a564bc.png)
![image](https://user-images.githubusercontent.com/41315903/180665759-729c98b5-d293-41a6-b8bd-a7de087fdb8e.png)
![image](https://user-images.githubusercontent.com/41315903/180665771-64a19ee6-0542-4010-a517-33d75c370bdd.png)
![image](https://user-images.githubusercontent.com/41315903/180665778-3e5b8e22-e5c6-4362-b8de-092d6100fbe0.png)
![image](https://user-images.githubusercontent.com/41315903/180665786-e7b696df-5788-4886-be36-5f1f0653daab.png)
![image](https://user-images.githubusercontent.com/41315903/180665798-fa55524c-9062-4a4c-92fb-b59400588e1f.png)
![image](https://user-images.githubusercontent.com/41315903/180665804-8e619af2-f8da-4ff5-b8ea-6cbff5bfc13d.png)
![image](https://user-images.githubusercontent.com/41315903/180665810-32ed5847-d93d-4511-a624-b2934e1c28af.png)





