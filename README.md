# Milan Rent Prices Forecasting (May 2025)

📖 Overview  

This project explores how apartment characteristics and spatial features have different effects on rent prices in Milan.

🎯 Research Goal  

To find an appropriate Machine Learning procedure to predict rent prices in Milan.

🗂 Dataset
- Source: Milan rent announcements in Immobiliare.it (4500 observations, 11 features).
- Key features: square meters and average price per zone.
- Preprocessing: mostly Bayesian imputation for missing values.

🛠 Methodology

The model that performed the best is CatBoost with MinMaxScaler. The report contains a summary of the path to reach my final solution, the step-by-step guidelines and all the codes necessary to obtain exactly my predictions, and an accessible and clear description of the methods comprising my solution.

🚀 Technologies Used

- 🐍 Python (NumPy, Pandas, Matplotlib, Seaborn)
- 📊 Statistical analysis & visualization
- 🏡 Geopy geocoder to compute the distance from the center
