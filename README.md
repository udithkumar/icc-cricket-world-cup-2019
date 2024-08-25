# ICC 2019 Cricket World Cup Prediction using Machine Learning

This repository contains the complete workflow for predicting the winner of the ICC Men's Cricket World Cup 2019 using machine learning techniques. The 12th edition of the tournament took place in England and Wales from May 30th to July 14th, 2019. The competition featured 10 teams playing in a single round-robin format, with the top four teams advancing to the semi-finals.

## Introduction

Predicting the outcome of a sports event like the Cricket World Cup is both exciting and challenging. Accurate predictions can provide a competitive advantage, whether it's in sports betting, team strategy, or fan engagement. By leveraging machine learning, we aim to bring a data-driven approach to this task, analyzing past performances, player statistics, and other relevant factors to forecast the tournament's results.

## Applications

The primary goal of this project is to enhance the accuracy of predicting match outcomes, which can be valuable for improving team strategies, fan engagement, and overall game analysis. A successful prediction model can also support decision-making in various business aspects, such as sponsorships, merchandising, and broadcast rights.

## Data

Real-world data is often messy and requires extensive preprocessing before it can be used for modeling. For this project, we scraped data from Cricbuzz and Kaggle, including:

- **Team Rankings (May 2019)**: Current ICC team rankings.
- **World Cup 2019 Fixtures**: Details of all matches scheduled for the 2019 World Cup.
- **Historical World Cup Performance**: Data on each team's past performance in previous World Cups.
- **ODI Matches (2010-2017)**: Historical One Day International (ODI) match data.

The data was then cleaned, filtered, and formatted to create a dataset suitable for building machine learning models.

## Environment and Tools

The project was developed using the following tools:

- **Jupyter Notebook** for development and analysis.
- **NumPy** and **Pandas** for data manipulation and preprocessing.
- **Seaborn** and **Matplotlib** for data visualization.
- **Scikit-learn** for building and evaluating machine learning models.

## Machine Learning Workflow

The machine learning workflow followed in this project includes:

1. **Data Cleaning and Formatting**: Initial data exploration, cleaning, and preparation.
2. **Exploratory Data Analysis (EDA)**: Visualizing and understanding data patterns and relationships.
3. **Feature Engineering and Selection**: Transforming raw data into meaningful features for the model.
4. **Model Comparison**: Evaluating different machine learning models, including Logistic Regression, Support Vector Machines, Random Forests, and K-Nearest Neighbors.
5. **Hyperparameter Tuning**: Optimizing the best-performing model (Random Forest) to improve accuracy.
6. **Model Evaluation**: Assessing model performance on the test dataset.
7. **Interpretation and Prediction**: Interpreting the model's results and making final predictions.
8. **Conclusions**: Summarizing findings and documenting the entire process.

## Results

- **Training Accuracy**: 70%
- **Test Accuracy**: 67.5%
- **Final Prediction**: According to the model, England was predicted to win the ICC Cricket World Cup 2019, which they did.

## How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/icc-2019-world-cup-prediction.git
   cd icc-2019-world-cup-prediction
   ```
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Jupyter Notebooks**: Explore data and build models by running the notebooks in the `notebooks/` folder.
4. **Make Predictions**: Use the trained model to predict match outcomes by following the steps in the final notebook.

## Project Structure

```
icc-2019-world-cup-prediction/
│
├── data/               # Raw and processed data files
├── notebooks/          # Jupyter Notebooks for analysis and modeling
├── models/             # Trained models and scripts
├── results/            # Prediction results and visualizations
├── src/                # Source code for data processing and modeling
├── requirements.txt    # List of required Python packages
└── README.md           # Project overview and instructions
```

## Conclusion

This project provides a comprehensive approach to predicting the ICC Cricket World Cup 2019 using machine learning. While the model's accuracy is limited by the available data, it offers valuable insights and serves as a foundation for further refinement.

## Contributing

Contributions are welcome! Please feel free to fork the repository and submit a pull request with your improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgments

Special thanks to Cricbuzz and Kaggle for providing the datasets, and to the open-source community for making this project possible.
