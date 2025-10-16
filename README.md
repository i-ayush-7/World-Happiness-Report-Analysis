# World-Happiness-Report-Analysis

Here is a summary of the provided Jupyter Notebook project, which analyzes the **World Happiness Report Dataset**.

![LOGO]()

## Project Summary: World Happiness Report Analysis

This notebook performs **Exploratory Data Analysis (EDA)** on the World Happiness Report dataset using the Python libraries **Pandas** and **Matplotlib**. The primary goal is to explore key features and their relationship to the **Happiness Score** across various countries and regions.

### Data Overview
* The dataset contains **158 entries** and **12 columns**.
* The data includes columns like: **Country**, **Region**, **Happiness Rank**, **Happiness Score**, and several contributing factors such as **Economy (GDP per Capita)**, **Family**, **Health (Life Expectancy)**, **Freedom**, **Trust (Government Corruption)**, and **Generosity**.
* Initial inspection confirms there are **no missing values** in the dataset.

### Key Analysis and Findings

The analysis addresses several specific questions, resulting in the following key insights:

1.  **Top 10 Happiest Countries:** A horizontal bar chart visualizes the countries with the highest **Happiness Score**.
2.  **Average Happiness by Region:** A bar chart shows the average happiness score, revealing which **Regions** tend to have the highest and lowest overall reported happiness.
3.  **Relation between GDP per Capita and Happiness Score (Q3 & Q9):**
    * A **scatter plot** shows a positive general correlation between **Economy (GDP per Capita)** and **Happiness Score**, suggesting that higher GDP tends to be associated with higher happiness.
    * A filtered bar chart identifies specific countries with a **High Economy (GDP per Capita)** (score $> 1.0$) but a **Low Happiness Score** (score $< 5.0$), highlighting outliers where economic strength doesn't translate to high happiness.
4.  **Countries with High Freedom but Low Happiness Score (Q5 & Q6):**
    * The project filters and visualizes countries that report a **High Freedom** score (score $> 0.3$) but a **Low Happiness Score** (score $< 4.0$), using two different plotting methods (Pandas `.plot()` and Matplotlib's explicit API) to confirm the results.
5.  **Countries with High Trust Level and Generosity (Q7):** A horizontal bar chart visualizes countries that score highly in both **Trust (Government Corruption)** (score $\ge 0.3$) and **Generosity** (score $\ge 0.4$).
6.  **Countries with High Health and Happiness Score (Q8 & Q10):**
    * A filtered bar chart highlights countries with a **High Health (Life Expectancy)** score (score $> 0.75$) but a **Low Happiness Score** (score $< 5.5$).
    * A bar chart identifies the **Top 10 Countries with the Best Health (Life Expectancy)** score.

In summary, the notebook successfully imports, explores, and visually analyzes the World Happiness Report data to identify top-ranking nations and uncover relationships between key social, economic, and health factors and a country's overall reported happiness.

## Project By: Ayush Shukla
