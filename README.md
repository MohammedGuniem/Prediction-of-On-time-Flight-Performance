# Flight-Delay-Prediction
 A project that aims to use machine learning to predict flight delay in most accurate measure

## Dataset
The dataset of this project is to large to host on this repository, it is therefore hosted on dropbox.com as a compressed zip file, for access to this dataset on dropbox please contact the owner of this repository at mghunime@yahoo.no 

You can also download this dataset directly from the source at
https://www.transtats.bts.gov/Fields.asp?gnoyr_VQ=FGJ

## Setup instructions

### A. It is recommended that you run this solution at an isolated conda environment as shown below.

- If you do not wish to do this and you are ok installing pip packages in the same environment you can proceed to step B. But keep in mind that you need to have python=3.12.4 and pip tool installed on you local environment.

- Install Anaconda on your local machine
https://docs.anaconda.com/anaconda/install/

- Create a new conda environment with python installed
```
conda create --name flight-delay-prediction python=3.12.4
```

- Activate the conda environment
```
conda activate flight-delay-prediction
```

### B. Install required packages and run the notebooks in this solution
In order to run the notebooks in this solution you can follow the step below
- Navigate to this root directory
```
cd '.\Flight-Delay-Prediction\'
```

- Install the required packages
```
pip install -r requirements.txt
```

- Run jupyter notebook
```
jupyter notebook
```