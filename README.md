# Titanic Exploratory Data Analysis (EDA)

Welcome to the **Titanic Exploratory Data Analysis** project! This repository contains an analysis of the Titanic dataset, providing insights into passenger demographics, survival rates, and key factors influencing survival.

The RMS Titanic was a British passenger liner that famously sank on its maiden voyage in April 1912 after hitting an iceberg in the North Atlantic. At the time, it was the largest and most luxurious ship ever built. The Titanic carried over 2,200 passengers and crew, with more than 1,500 lives lost in the disaster. The tragedy led to significant changes in maritime safety regulations.

---

## Project Overview

The Titanic dataset is one of the most famous datasets used for data analysis and machine learning. This project focuses on understanding the data through visualizations and statistical exploration.

Key objectives:
- Perform data cleaning and preprocessing.
- Explore relationships between features (e.g., age, gender, class) and survival.
- Visualize trends and insights.

---

## Features of the Analysis

- **Data Cleaning:** Handle missing values, format columns, and prepare the dataset for analysis.
- **Descriptive Statistics:** Summarize key statistics for numerical and categorical features.
- **Visualizations:**
  - Distribution of passengers by class, age, and gender.
  - Survival rates by demographic groups.
  - Heatmaps to show correlations between variables.
- **Key Insights:**
  - Families with more members were not able to survive
  - Passenger from Deck B and also belonged to Pclass1, survived the most
  - Children had higher survival rates than adults and a lot of old citizens were not able to survive.
  - First-class passengers were more likely to survive compared to those in second or third class.
  - Females had a significantly higher survival rate compared to males.
  - A lot of casualties occured in the M deck and belonged to Pclass3
  - A large number of people who boarded from Cherbourg are in Pclass 1 which indicates that Cherbough could be a very wealthy place (55% (most) of the people survived who boarded from Cherbourg (C))

---

## Requirements

The following Python libraries are required to run the notebook:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `jupyter`

You can install these dependencies using:

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

---

## Getting Started

1. Clone the repository:

   ```bash
     https://github.com/hydraharish123/Titanic-Survival-Analysis.git
   ```

2. Navigate to the project directory:

   ```bash
   cd titanic-Survival-Analysis
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Open the Jupyter Notebook:

   ```bash
   jupyter notebook titanic-eda.ipynb
   ```

5. Run the notebook cells sequentially to explore the analysis.

---

## Dataset

The Titanic dataset is sourced from [Kaggle's Titanic Competition](https://www.kaggle.com/c/titanic). It contains information on passengers, such as age, gender, class, and survival status.

---


## Folder Structure

```
├── titanic-eda.ipynb       # Jupyter Notebook containing the analysis
├── README.md               # Project documentation
└── requirements.txt        # List of required libraries
```

---

## Credits

This project was created by [P S Harish].

The dataset is courtesy of [Kaggle](https://www.kaggle.com).

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.
