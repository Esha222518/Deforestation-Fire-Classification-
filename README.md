Classification of Fire Types in India Using MODIS Satellite Data
This repository contains a data science project that classifies fire types across India using satellite imagery data obtained from the MODIS (Moderate Resolution Imaging Spectroradiometer) sensor. The project leverages machine learning techniques to identify and classify different types of fires such as forest fires, agricultural fires, and others based on features derived from the MODIS dataset.

📌 Project Objectives
Preprocess and analyze MODIS satellite data specific to fire events in India.

Apply classification algorithms to categorize fire types.

Evaluate model performance using various metrics.

Visualize the spatial and temporal distribution of fire incidents.

📁 Project Structure
bash
Copy code
📦Classification_of_Fire_Types
 ┣ 📓 Classification_of_Fire_Types_in_India_Using_MODIS_Satellite_Data.ipynb
 ┣ 📊 data/                         # Folder for satellite data (not uploaded)
 ┣ 📈 outputs/                      # Folder for model outputs, plots
 ┣ 📜 README.md                     # This file
 ┗ 📄 requirements.txt              # Python dependencies (to be added)
🧪 Technologies Used
Python (Jupyter Notebook)

Pandas, NumPy – data wrangling

Matplotlib, Seaborn – data visualization

Scikit-learn – machine learning classification

Geopandas / Folium (optional) – spatial data handling

📊 Dataset
Source: MODIS Fire Products

Region: India

Attributes: Latitude, Longitude, Brightness, Fire Radiative Power (FRP), Acquisition Date, Confidence Level, etc.

🔐 Note: The dataset used is not included in the repo due to size or licensing constraints. Please download it from official NASA or MODIS repositories.

⚙️ Workflow Summary
Data Preprocessing

Handling missing values

Feature selection and engineering

Label encoding

Exploratory Data Analysis

Distribution of fire types

Temporal and spatial trends

Model Building

Classification using Decision Tree, Random Forest, or XGBoost

Model training, testing, and evaluation (accuracy, F1 score)

Visualization

Heatmaps, bar plots, fire maps

📌 Results
The best-performing model achieved an F1 Score.

Successfully identified fire-prone zones and types using satellite-derived metrics.

🚀 How to Run
Clone the repository
git clone https://github.com/yourusername/fire-classification-india.git
cd fire-classification-india
Install required packages:
pip install -r requirements.txt
Launch the notebook:
jupyter notebook Classification_of_Fire_Types_in_India_Using_MODIS_Satellite_Data.ipynb
📌 Future Enhancements
Incorporate deep learning models (e.g., CNNs for spatial data).

Integrate real-time MODIS feeds.

Streamlit dashboard for visual exploration of fire hotspots.

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

🤝 Acknowledgements
NASA for MODIS Fire Datasets.

Indian Forest Survey Reports.

Scikit-learn and Matplotlib communities.







