# Data Science for Cybersecurity Notebooks

This project documents how to analyze cybersecurity data with machine learning tools and techniques in python.  The tutorials run in [Jupyter Notebooks] (http://jupyter.org/install.html) and depend on the environment described in the environment.yml file.  

## Dependencies
1. Clone this repository
`git clone https://github.com/carriegardner428/cybersecurity_datascience.git`
2. Ensure Anaconda is installed
`conda --v`  
  <em> If it's not installed, please visit (https://conda.io/docs/user-guide/install/index.html) </em>
3. `cd cybersecurity_datascience`
4. Create the conda environment
`conda env create -f environment.yml`

## Organization
cybersecurity_datascience/  
|-tutorials  
|--data  ** Will be added soon  
|---nsl_kdd  
|---- KDDTest+.txt  
|---- KDDTrain+.txt  
| Datasets.ipynb: Lists cybersecurtiy datasets  
| environment.yml: Basic pynthon conda configuration file  
| environment_mlbook.yml: Extensive python conda configuration file with deep   learning and other packages  
| README.md:  What you are reading right now :)  

## Get Started
1. Look through data in Datasets.ipynb
2. Familiarize yourself with pandas in the Pandas Intro.ipynb
3. Familiarize yourself with matplotlib and seaborn in Plotting Intro.ipynb (to be added)
4. Familiarize yourself with machine learning in ML Intro.ipynb (to be added)
5. Familiarize yourself with security logging and data in Security Monitoring.ipynb (to be added)
6. Step through the rest of the tutorials in chronological order

***Please submit a pull request to add or modify content***
