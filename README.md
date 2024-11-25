# Prediction-of-On-time-Flight-Performance
 A project that aims to use machine learning to predict flight delay in most accurate measure

## Dataset
The dataset of this project is to large to host on this repository, it is therefore hosted on dropbox.com as a compressed zip file, it can be downloaded through the link below

https://www.dropbox.com/scl/fi/k17vegip5rp0mf3mb8un3/Flight_Delay_Project_Data.zip?rlkey=9oek4g0lcqyshvv1a3ahkm2cv&st=gc00efx4&dl=0

You can also download this dataset directly from the source at, however make sure you comply with the expected naming of monthly .csv files so that data for year is places under data/2022 and data/2023 respectivly, and inside these the monthly .csv files is stored as 01_2022.csv, 02_2022.csv, ..., 12_2022.csv, same goes for the year 2023
https://www.transtats.bts.gov/Fields.asp?gnoyr_VQ=FGJ

## Setup instructions

### A. It is recommended that you run this solution at an isolated conda environment as shown below.

- If you do not wish to do this and you are ok installing pip packages in the same environment you can proceed to step B. But keep in mind that you need to have python=3.12.4 and pip tool installed on you local environment.

- Install Anaconda on your local machine
https://docs.anaconda.com/anaconda/install/

- Create a new conda environment with python installed
```
conda create --name prediction-of-on-time-flight-performance python=3.12.4
```

- Activate the conda environment
```
conda activate prediction-of-on-time-flight-performance
```

### B. Install required packages and run the notebooks in this solution
In order to run the notebooks in this solution you can follow the step below
- Navigate to this root directory
```
cd '.\Prediction-of-On-time-Flight-Performance\'
```

- Install the required packages
```
pip install -r requirements.txt
```

- Run jupyter notebook
```
jupyter notebook
```