# Alzheimer's  Drug Discovery Prediction Application

<!-- # Watch the tutorial video

Used the following Tutorial to create this application: [Video](https://youtu.be/htBIP17S-20) -->

# Reproducing this web app
To recreate this web app on your own computer, do the following.

### Create conda environment
Firstly, we will create a conda environment called *bioactivity*
```
conda create -n bioactivity python=3.7.9
```
Secondly, we will login to the *bioactivity* environement
```
conda activate bioactivity
```
### Install prerequisite libraries

Download requirements.txt file

```
wget https://github.com/AnshMittal1811/AlzheimerDrugDiscovery/blob/main/App/requirements.txt

```

Pip install libraries
```
pip install -r requirements.txt
```

###  Download and unzip contents from GitHub repo

Download and unzip contents from https://github.com/AnshMittal/AlzheimerDrugDiscovery/archive/main.zip

### Generating the PKL file

The machine learning model used in this web app will firstly have to be generated by successfully running the included Jupyter notebook [bioactivity_prediction_app.ipynb](https://github.com/AnshMittal1811/AlzheimerDrugDiscovery/blob/main/App/bioactivity_prediction_app.ipynb). Upon successfully running all code cells, a pickled model called acetylcholinesterase_model.pkl will be generated.

###  Launch the app

```
streamlit run app.py
```
