🧠 **Objective**
The goal of this project is to identify the key factors that influence diamond pricing. Using the built-in ggplot2::diamonds dataset, I explored how attributes like carat, cut, color, and clarity correlate with price.

📦 Dataset
* Source: ggplot2 package in R
* Observations: 53,940
* Features:
  * carat: weight of the diamond
  * cut: quality of the cut (Fair to Ideal)
  * color: diamond color, from J (worst) to D (best)
  * clarity: measurement of how clear the diamond is
  * price: in USD
  * x, y, z: dimensions in mm
        
❓ Key Questions
Which feature most strongly predicts a diamond’s price?
Does better clarity or color always increase price?

🔍 Methodology
Data Exploration: Used str(), summary(), and visual checks.
Data Cleaning: Verified missing values, checked data types.
Correlation Analysis: Quantified relationships to price.
Visualizations: Used ggplot2 to explore distributions and relationships.

📊 Key Findings
Carat had the strongest correlation with price (~0.92).
Higher clarity and better cut generally led to higher price, but with diminishing returns beyond certain thresholds.
Some lower-grade color diamonds priced unexpectedly high, likely due to other influencing features (like carat size).

🛠️ Tools Used
* R
* ggplot2
* dplyr
* R Markdown

📸 Visuals
For visuals, check the pdf file within the directory.
