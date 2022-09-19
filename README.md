# Solubility App

# Watch the tutorial video

**[Building a Bioinformatics Web App in Python - Streamlit Tutorial #7](https://youtu.be/iZUH1qlgnys)**

<a href="https://youtu.be/iZUH1qlgnys"><img src="http://img.youtube.com/vi/iZUH1qlgnys/0.jpg" alt="Building a Bioinformatics Web App in Python - Streamlit Tutorial #7" title="Building a Bioinformatics Web App in Python - Streamlit Tutorial #7" width="400" /></a>

# Demo

Launch the web app:

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/dataprofessor/solubility-app/main/solubility-app.py)

With the help of this [awesome discussion over in the Streamlit Discuss board](https://discuss.streamlit.io/t/can-i-add-conda-package-in-requirements-txt/8062/4) and the awesome [GitHub repo from iwatobipen](https://github.com/iwatobipen/chem_streamlit/) for ideas in getting rdkit installed via conda.

# Reproducing this web app
To recreate this web app on your own computer, do the following.

### Create conda environment
Firstly, we will create a conda environment called *ml*
```
conda create -n solubility python=3.7.9
```
Secondly, we will login to the *solubility* environement
```
conda activate solubility
```
### Install prerequisite libraries

Download requirements.txt file

```
wget https://raw.githubusercontent.com/dataprofessor/solubility-app/main/requirements.txt

```

Pip install libraries
```
pip install -r requirements.txt
```

Install rdkit
```
conda install -c conda-forge rdkit rdkit
```

###  Download and unzip contents from GitHub repo

Download and unzip contents from https://github.com/dataprofessor/solubility-app/archive/main.zip

###  Launch the app

```
streamlit run app.py
```
