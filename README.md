# 🔍 San Francisco Crime Data Analysis & Prediction
This project analyzes crime incidents in San Francisco using data mining techniques such as clustering and classification to discover hidden patterns and predict crime behavior.

## 📊 Key Features
Exploratory Data Analysis:

Visualized top crime categories, hotspots, and time-based patterns (hour, day, month).

## Clustering:

Applied K-Medoids to group similar crime incidents by time, location, and district.

## Classification:

Used Decision Tree and Random Forest to predict the cluster label for new crime incidents.

## Interactive Visualization Dashboard:

Built with Streamlit to explore crime patterns dynamically.
👉  Try the App
Click below to explore the Streamlit app:
(https://blank-app-q6vuw44zxl.streamlit.app/))

## 📂 Dataset
Source: Public dataset of San Francisco 

Fields Used: Category, Date, Hour, DayOfWeek, PdDistrict, Coordinates(X,Y)

## 📌 ML Techniques Used
Clustering: KMedoids from sklearn_extra.cluster

Classification: DecisionTreeClassifier, RandomForestClassifier

Dimensionality Reduction: PCA for 3D visualization

Encoding: Label Encoding for categorical variables

## 📈 Visualizations Included
Crime distribution by category (Bar Chart)

Crime hotspots on map (Scatter + DarkMap)

Crime by time of day (Line Chart)

Correlation heatmap of features

3D clustering visualization using PCA

## ⚙️ Technologies
Python, Pandas, Seaborn, Matplotlib, Plotly, Streamlit

Scikit-learn, sklearn_extra, LabelEncoder, PCA

Confusion matrices and evaluation reports

