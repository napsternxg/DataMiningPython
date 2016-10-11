# Data Mining Python
Data Mining python scripts for social scientists

## Installation instructions
* Install python 2.7 using Anaconda distribution from https://www.continuum.io/downloads. **Make sure you install the 2.7 version**. More details at: https://docs.continuum.io/anaconda/install
* Download this project file: https://github.com/napsternxg/DataMiningPython/archive/master.zip and unzip it in a folder (we will refer to this as **Project Directory**). 
* Open the command line of your OS and **navigate to the Project Directory**. 
* Type the following command:
```
conda env create -n datamining
```
* Above step should take some time and install all the required projects.
* Once the everything is installed. Type the following in the command line:
**MAC or Linux users**
```
source activate datamining
```

**Winows users**
```
activate datamining
```

* Finally, type this command in your command line:
```
jupyter notebook
```

* The above command should open a page in your web browser. It should show a list of files. 

## Twitter API keys

* In the project directory copy the file `twitter_config.sample.json` to `twitter_config.json`
* Go to https://apps.twitter.com/app/new to create a new twitter app. 
* Give a unique name to your app. Try `DataMining-FA2016LIS590DTL-<yourname>`
* Once app is created go to **Keys and Access Tokens tabs**
* Click on the button **Create my access token**
* Now on the page you should have values for the fields **Consumer Key, Consumer Key Secret, Access Token, and Access Token Secret**
* Open your `twitter_config.json` in a text editor. 
* Copy the values of the fields from the respective sections of the web page between the quote in front of the similar field names. 



## Pre class checks for working packages
* Click on the `Check installs.ipynb` and then from the toolbar click on **Cell > Run All**
* All the cells in the given web page should run successfully and the output should look like the file: https://github.com/napsternxg/DataMiningPython/blob/master/Check%20installs.ipynb
* Click on the `NLP checks.ipynb` and then from the toolbar click on **Cell > Run All**
* All the cells in the given web page should run successfully and the output should look like the file: https://github.com/napsternxg/DataMiningPython/blob/master/NLP%20checks.ipynb
* Click on the `Twitter checks.ipynb` and then from the toolbar click on **Cell > Run All**
* All the cells in the given web page should run successfully and the output should look like the file: https://github.com/napsternxg/DataMiningPython/blob/master/Twitter%20checks.ipynb


## You are ready for class. 
If you have any issues please feel free to contact me. 
