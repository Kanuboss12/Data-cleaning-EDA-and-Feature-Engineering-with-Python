# 𝙀𝙭𝙥𝙡𝙤𝙧𝙖𝙩𝙤𝙧𝙮 𝘿𝙖𝙩𝙖 𝘼𝙣𝙖𝙡𝙮𝙨𝙞𝙨 𝙤𝙛 𝙍𝙚𝙙 𝙬𝙞𝙣𝙚 𝘿𝙖𝙩𝙖𝙨𝙚𝙩 𝙪𝙨𝙞𝙣𝙜 𝙋𝙮𝙩𝙝𝙤𝙣 

### 🎯Project Focused on Evaluating the Quality of Red Wine Based on its Chemical Properties and Sensory Attribute (Quality). 

### 📖 Steps Involved:-

1️⃣ 𝗗𝗮𝘁𝗮 𝗢𝘃𝗲𝗿𝘃𝗶𝗲𝘄:- The dataset related to red variants of the Portuguese "Vinho Verde" wine obtained from Kaggle. With 1599 samples of red wine with 11 input and 1 output feature. Higher value, better the wine. Imported dataset in Python using Pandas. 

2️⃣ 𝗗𝗮𝘁𝗮 𝗖𝗹𝗲𝗮𝗻𝗶𝗻𝗴:- No missing value in the dataset and Dropped 240 Duplicate records from data set.

3️⃣ 𝗘𝗗𝗔:-  

➡ 𝗦𝘁𝗮𝘁𝗶𝘀𝘁𝗶𝗰𝗮𝗹 𝗔𝗻𝗮𝗹𝘆𝘀𝗶𝘀:- 6 different types of red wines available depending on the Quality ranging from 3 to 8, with average of 5.64. 

➡ 𝗩𝗶𝘀𝘂𝗮𝗹𝗶𝘇𝗮𝘁𝗶𝗼𝗻 𝘂𝘀𝗶𝗻𝗴 𝗠𝗮𝘁𝗽𝗹𝗼𝘁𝗹𝗶𝗯 𝗮𝗻𝗱 𝗦𝗲𝗮𝗯𝗼𝗿𝗻:- Key relationship between input variables and Wine Quality. Identified Outliers. Vizualization are as Follow:-

A) 𝗖𝗼𝗿𝗿𝗲𝗹𝗮𝘁𝗶𝗼𝗻 𝗜𝗻𝘀𝗶𝗴𝗵𝘁𝘀 with 𝗛𝗲𝗮𝘁 𝗠𝗮𝗽:- Fixed Acidity, Citric acid, and Alcohol are Positively correlated with quality while Volatile acidity, Free sulfur dioxide, and pH have negative impact. 

B) 𝗕𝗮𝗿 𝗚𝗿𝗮𝗽𝗵:-Dataset is Imbalanced that means Most of the wines are rated either 5 or 6 in terms of quality. These are average-quality wines and make up the bulk of the dataset. 

C) 𝗣𝗿𝗼𝗯𝗮𝗯𝗶𝗹𝗶𝘁𝘆 𝗗𝗶𝘀𝘁𝗿𝗶𝗯𝘂𝘁𝗶𝗼𝗻 using 𝗛𝗶𝘀𝘁𝗼𝗴𝗿𝗮𝗺:-The distribution seems skewed to the right, with most samples concentrated between 9 and 12% alcohol content suggesting higher alcohol content (above 12%) is less common. 

D) 𝗣𝗮𝗶𝗿 𝗣𝗹𝗼𝘁:- Used for Univariate, Bivariate, Multivariate Analysis. Compare 1 feature with the other. It shows Strong linear relationship among the variables. 

E) 𝗖𝗮𝘁𝗲𝗴𝗼𝗿𝗶𝗰𝗮𝗹 𝗣𝗹𝗼𝘁:- Boxplot Shows General positive relationship between alcohol content and quality. Higher-quality wines (7 and 8) generally have higher alcohol content, while lower-quality wines (3 to 5) have lower alcohol content. There are several outliers in the 5th quality category. 

F) 𝗦𝗰𝗮𝘁𝘁𝗲𝗿𝗽𝗹𝗼𝘁:- Shows the relationship between alcohol content and pH in wine samples, with color indicating quality ratings. Lower pH means higher acidity, with values mostly between 3.0 and 3.6, and alcohol content between 9% and 14%. Higher-quality wines (darker points) are more scattered across these ranges.

#### 📖 Tools Used: Pandas, Matplotlib, and Seaborn

#### 📖 𝗙𝘂𝗿𝘁𝗵𝗲𝗿 𝗔𝗻𝗮𝗹𝘆𝘀𝗶𝘀: These insights set stage for machine learning models that try to predict wine quality. 

