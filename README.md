# Comedy-Pacing-Analysis
This project is an integration of the most popular form of entertainment - Cinema, for which the technical aspects demand solutions through the application of Data Science. Using 15 Hollywood comedy movies, this project aims at understanding the pacing mechanism of humor through editing and dialogues, to determine the audiences' final reaction.  

# Project Overview
This project, titled -*The Comedy Cadence: The Math behind the Movie Magic*, integrates cinematic technical aspects with data science to analyze the pacing mechanisms of Hollywood comedy movies over a 50-year period (1977–2024). By quantifying Cuts Per Minute ($CPM$) and Words Per Second ($WPS$), I engineered a framework to predict audience tension and establish technical benchmarks for filmmakers.

# Tools and Techniques
**Data Collection** – Smartphone (Self recording)
**Data Storage & Cleaning** – Microsoft Excel 
**Exploratory Data Analysis (EDA)** – Google Collab Notebook / Python - (NumPy, Pandas, Matplotlib, Seaborn) 
**Statistical Testing & Modelling** – R programming - (ANOVA, Ordinal Logistic Regression)
**Prediction using Machine Learning** – Google Collab Notebook / Python - (Scikit-Learn, Random Forest Regressor)
**Data Visualization** – Tableau Public (Link: https://public.tableau.com/app/profile/binni.thomas/viz/Comedy_Cadence_Project_BT/Dashboard?publish=yes) 

# Key Insights 
1. Comedies are moving away from long conversations and toward fast-paced action. A trend suggests that by 2026, movies will need roughly 18 camera cuts every minute just to keep our modern, shorter attention spans engaged.
2. To make a scene feel more intense, adding more camera cuts is far more effective than adding more talking, where every extra cut raises the tension by about 4.5%, while more dialogue actually makes the scene feel less exciting.
3. A "vibe calculator" was created to predict exactly how an audience will feel based on the number of words and camera cuts used, helping filmmakers perfectly tune the energy of a scene during the editing process.
4. To keep a modern audience happy, a movie’s ending needs to be at least 29% faster and more energetic than its beginning to ensure people stay hooked until the very last frame.

# Model Performance
Developed a Random Forest Regressor to predict Tension Scores with a Mean Absolute Error ($MAE$) of 2.09. 
