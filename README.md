Data Analytics Class (COSC-6380)

Welcome to the Data Analytics Class repository!
This repo contains assignments, projects, and resources for learning data collection, cleaning, visualization, and exploratory analysis.

⸻

📂 Repository Structure

data-analytics-class/
│
├── data/                  # (ignored in git; store local NetCDF datasets here)
│   ├── temp/              # Tmin/Tmax daily temperature
│   ├── precip/            # GPCP precipitation
│   ├── sst/               # ERSST sea surface temperature
│   └── soil/              # CPC soil moisture
│
├── notebooks/             # Jupyter notebooks for analysis
│   ├── 01_temperature.ipynb
│   ├── 02_precipitation.ipynb
│   ├── 03_sst.ipynb
│   ├── 04_soil_moisture.ipynb
│   └── 05_combined_analysis.ipynb
│
├── outputs/               # saved plots/figures/tables
├── cosc6380_env/          # local virtual env (ignored in git)
│
├── requirements.txt       # Python dependencies
├── .gitignore             # ignored files/folders
├── LICENSE                # e.g., MIT license
└── README.md              # project overview


⸻

🚀 Setup Instructions
	1.	Clone the repo:

git clone https://github.com/fullstuffdeveloper/data-analytics-class.git
cd data-analytics-class


	2.	Create a virtual environment & install requirements:

python3 -m venv cosc6380_env
source cosc6380_env/bin/activate
pip install -r requirements.txt


	3.	Launch JupyterLab:

jupyter lab



⸻

📊 Datasets Used

This project uses open climate datasets (NetCDF4 format) from NOAA PSL and UCAR/NCAR:
	1.	Global Daily Temperature (Tmin/Tmax, 2010–2025)
Source: NOAA CPC Global Unified Temperature
Dataset link
	2.	Precipitation (monthly, 1979–present)
Source: GPCP Global Precipitation Climatology Project
Dataset link
	3.	Sea Surface Temperature (SST, 1854–present)
Source: NOAA ERSST v5
Dataset link
	4.	Soil Moisture (monthly, 1948–present)
Source: CPC Soil Moisture Dataset
Dataset link

⚠️ Note: Large .nc datasets are not tracked in Git. Please download them separately into the data/ folder before running notebooks.

⸻

📘 Assignments
	•	Assignment 1: Data Cleaning
	•	Assignment 2: Data Visualization
	•	Assignment 3: Statistical Analysis

⸻

📗 Projects
	•	Project 1: Exploratory Data Analysis
	•	Project 2: Predictive Modeling

⸻

🛠 GitHub Workflow
	1.	Initialize repo locally:

git init
git remote add origin https://github.com/fullstuffdeveloper/data-analytics-class.git


	2.	First commit:

git add .
git commit -m "Initial commit: setup repo structure and notebooks"
git push -u origin main


	3.	Update regularly:

git add notebooks/01_temperature.ipynb
git commit -m "Add temperature analysis starter"
git push



⸻

📚 Resources
	•	Python for Data Analysis
	•	Pandas Documentation
	•	xarray Documentation
	•	NOAA PSL Data Portal

⸻

📬 Contact

For questions, reach out to:
Abhishek Kumar Jha
📧 ajha3@islander.tamucc.edu