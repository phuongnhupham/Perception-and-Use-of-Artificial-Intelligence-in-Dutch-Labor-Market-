# Perception and Use of Artificial Intelligence in Dutch Labor Market
## Objectives
This project aims to answer two questions: _What is the general perception of AI among the Dutch population?_ and _What is the current and expected adoption of AI among Dutch workers, and the current adoption of AI among Dutch companies?_ 

This project consists of 3 main stages: 
1) **Data Wrangling**: Cleaned and transformed raw survey data using Python/Pandas, handled missing values, reshaped wide-format data into a tidy structure, standardized categorical labels, merged different datasets, and prepared analysis-ready datasets for visualization.
2) **Data Analysis**: Analyzed survey data using Python/Pandas to identify patterns in AI adoption and public perceptions, calculated response proportions, weighted scores, and adoption gaps, and compared AI use across demographic groups and technologies over time.
3)  **Data Visualization**: Created data-driven visualizations using Matplotlib and Plotly, including grouped bar charts, dumbbell charts, time-series plots, and custom comparative graphics to communicate trends, differences, and patterns in AI adoption and perceptions.

## Table of Content 
[Dataset used](*dataset-used) <br>
[Step 1: Data Wrangling](*step-1-data-wrangling) <br>
[Step 2: Data Analysis](*step-2-data-analysis) <br>
[Step 3:  Data Visualization](*step-3-data-visualization) <br>
[Key Findings](*key-findings)
## Dataset used 
This project uses four datasets that are specifically about AI and the labor market, which are part of a larger survey, AI in society: experiences and opinions, conducted on the Dutch population aged 18 and above in 2025. It includes responses from different demographic groups to statements about AI. 
More information about the dataset can be found at the following link:
CBS website: https://www.cbs.nl/nl-nl/publicatie/2026/08/ai-in-de-samenleving-ervaringen-en-opinies
## Step 1: Data Wrangling 

<img width="528" height="262" alt="Image" src="https://github.com/user-attachments/assets/2ee48102-55a3-4dad-9f86-9244651ddc06" />


**- Inspect data, I did the same for the following datasets**

<img width="800" height="362" alt="Image" src="https://github.com/user-attachments/assets/416f3749-530f-4112-98f9-80a6530b848d" />


**- Remove empty values & rows**

<img width="312" height="72" alt="Image" src="https://github.com/user-attachments/assets/6628e7c4-5eb0-4ace-a4f7-34733c8cd6ba" />


**- Reshape data format**

<img width="642" height="606" alt="image" src="https://github.com/user-attachments/assets/e10847a8-edf8-4ead-81b5-5253a2bbf692" />

<img width="768" height="72" alt="image" src="https://github.com/user-attachments/assets/f9e4e771-72d0-43e8-93ae-1548db6975a8" />

<img width="913" height="571" alt="image" src="https://github.com/user-attachments/assets/f83a92c8-c9f7-453e-aafb-c169de14284d" />

**- Standardize variables**

<img width="1015" height="563" alt="image" src="https://github.com/user-attachments/assets/bb441b9c-0b3c-4df6-a8e2-d970a02958a6" />

<img width="952" height="102" alt="image" src="https://github.com/user-attachments/assets/9890b2fa-0802-4c64-b38a-47b1e05c1d3d" />

**- Merge the two datasets together**

<img width="1290" height="493" alt="Image" src="https://github.com/user-attachments/assets/7ed66012-ec0a-47b6-8523-8aaab073574a" /> 


## Step 2: Data Analysis 

**-Reverse code negative questions**

<img width="545" height="607" alt="image" src="https://github.com/user-attachments/assets/3cad20ba-b5f7-4e8a-8ff5-e3ecde83a22c" />

**- Calculate response proportion & overall balance**

<img width="462" height="420" alt="image" src="https://github.com/user-attachments/assets/ca57d9d4-ba7b-4961-87cf-1074d6484313" />

**- Calculate AI adoption gap**

<img width="376" height="115" alt="image" src="https://github.com/user-attachments/assets/6d1cd97a-079e-451a-a7b7-beca0939a277" />

## Step 3: Data Visualization & Key Findings

### Question 1: What is the general perception of AI among the Dutch population?
#### Graph 1
**Key findings**: Different statements are divided into "Possible Benefits" & "Possible Risks" categories. This chart shows that **Dutch citizens recognize AI’s benefits but are more concerned about its potential risks.** The main concerns are **job loss (75.4%)** and **loss of knowledge and skills (64%)**. At the same time, a notable share of respondents answered **“maybe,”** indicating a great amount of uncertainty about AI’s impact. 

<img width="1917" height="907" alt="Image" src="https://github.com/user-attachments/assets/e0e5bcc7-7ee1-4f01-b962-4e958fa6e7a6" />

#### Graph 2
**Key findings**: The distribution of **Dutch citizens' responses leans toward Negative & Uncertain than Positive,** with the response balance at 45.3% (· Positive= 1 · Uncertain = 0.5 · Negative= 0)

<img width="1475" height="1020" alt="Image" src="https://github.com/user-attachments/assets/77a03449-949c-4d41-8afd-8c741443585c" />

### Question 2: What is the current and expected adoption of AI among Dutch workers, and the current adoption of AI among Dutch companies?
#### Graph 3
**Key findings**: All demographic groups expect higher use of AI in the next 10 years. 

- **Lowest adoption among Primary/VMBO/MBO** , while **Highest among HBO/WO** (56% now → 81% expected). 
- **Men currently use AI slightly more than women** and also expect higher future use. 
-  **Ages 25–45 show the highest adoption** and strongest future expectations. 
- **Higher-income groups use AI the most today** and expect the highest future use. 

<img width="1747" height="1077" alt="Image" src="https://github.com/user-attachments/assets/841bf9f4-7d91-4784-983d-a396fec7b9e0" />

#### Graph 4

**Key findings**: The growth of AI adoption between 2020 and 2024 was driven primarily by language-based and generative AI technologies rather than traditional machine learning applications. Text mining became the leading AI technology (13.5%) while Natural Language Generation reached 12.3%.
<img width="1542" height="755" alt="Image" src="https://github.com/user-attachments/assets/486deb1c-ae84-4b33-b377-273e8976e691" /> 

#### Graph 5

**Key findings**: AI adoption has more than doubled in Dutch companies in the span of 4 years.
<img width="1475" height="741" alt="Image" src="https://github.com/user-attachments/assets/7651a0e9-6998-44cf-a442-e6205b7c275f" />
