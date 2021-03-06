# Data Mining Python
Data Mining python scripts for social scientists
[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org:/repo/napsternxg/dataminingpython)

## Installation instructions
* Install python 2.7 using Anaconda distribution from https://www.continuum.io/downloads. 
  * **Make sure you install the 2.7 version** [Screenshot for Windows](https://github.com/napsternxg/DataMiningPython/blob/master/images/Anaconda%20Windows.PNG) | [Screenshot for Mac](https://github.com/napsternxg/DataMiningPython/blob/master/images/Anaconda%20Mac.PNG)
  * More details at: https://docs.continuum.io/anaconda/install
* Download this project file: https://github.com/napsternxg/DataMiningPython/archive/master.zip and unzip it in a folder (we will refer to this as **Project Directory**). 
* Open the command line of your OS and **navigate to the Project Directory**.
* If you unzipped the files to `/user/ABC/DataMining` (For linux or Mac) or `C:/Users/ABC/DataMining`
* Make sure the `environment.yml` file is in the project directory. If it is not there then you need to go to the directory which has the `environment.yml` file.
* From the folder which has the `environment.yml` file, type the following command:
```
conda env create -n datamining python=2
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
* Give a unique name to your app. Try `DataMining-FA2016LIS590DTL-<yourname>` [See [Image](https://github.com/napsternxg/DataMiningPython/blob/master/images/Create%20Tweet%20App.PNG)]
* Once app is created go to **Keys and Access Tokens tabs** [See [Image](https://github.com/napsternxg/DataMiningPython/blob/master/images/Consumer%20Key%20Tokens.PNG)]
* Click on the button **Create my access token** [See [Image](https://github.com/napsternxg/DataMiningPython/blob/master/images/Access%20Tokens.PNG)]
* Now on the page you should have values for the fields **Consumer Key, Consumer Key Secret, Access Token, and Access Token Secret**
* Open your `twitter_config.json` in a text editor. 
* Copy the values of the fields from the respective sections of the web page between the quote in front of the similar field names. 



## Pre class checks for working packages
* Click on the `Check installs.ipynb` and then from the toolbar click on **Cell > Run All**
* All the cells in the given web page should run successfully and the output should look like the file: https://github.com/napsternxg/DataMiningPython/blob/master/Check%20installs.ipynb
* Click on the `NLP checks.ipynb` and then from the toolbar click on **Cell > Run All**
* All the cells in the given web page should run successfully and the output should look like the file: https://github.com/napsternxg/DataMiningPython/blob/master/NLP%20checks.ipynb
* Click on the `Twitter checks.ipynb` and then from the toolbar click on **Cell > Run All**
* All the cells in the given web page should run successfully and the output should look like the file: https://github.com/napsternxg/DataMiningPython/blob/master/Twitter%20Checks.ipynb


## You are ready for class. 
If you have any issues please feel free to contact me. 


## Class material

* **[Part 1: Getting Started](https://github.com/napsternxg/DataMiningPython/blob/master/Lecture%20Notebooks/Getting%20Started.ipynb)**
* **[Part 2: Redoing Weka Stuff](https://github.com/napsternxg/DataMiningPython/blob/master/Lecture%20Notebooks/Redoing%20Weka%20stuff.ipynb)**
* **[Part 3: Text Data Mining](https://github.com/napsternxg/DataMiningPython/blob/master/Lecture%20Notebooks/Text%20Data%20Mining.ipynb)**
* **[Part 4: Twitter Analysis](https://github.com/napsternxg/DataMiningPython/blob/master/Lecture%20Notebooks/Twitter.ipynb)**


## FAQ

  * **Make sure you install the 2.7 version** [Screenshot for Windows](https://github.com/napsternxg/DataMiningPython/blob/master/images/Anaconda%20Windows.PNG) | [Screenshot for Mac](https://github.com/napsternxg/DataMiningPython/blob/master/images/Anaconda%20Mac.PNG)
    * You can check if the version of python installed is indeed 2.7 by running the following commands in order:
    ```
    source activate datamining
    python --version
    ```
    * The last command should show you the version of python. Make sure it is 2.7 and not 3.5. 
  * Anaconda installation shows the message similar to could not establish the PATH and menus.
  Suggested fixes:
    * After installation is complete try restarting the machine. Then from the project directory run the conda commands.
    * If above fails by error messages similar to `"conda" isn't a recognized command`, then that means that your system cannot find conda command. You can add conda command by adding the following to the end of your system path (on windows): `;E:\Anaconda;E:\Anaconda\Scripts; E:\Anaconda\DLLs;`. Please replace E:\Anaconda with the path to where you installed Anaconda. Details on editing system PATH can be found at: http://www.howtogeek.com/118594/how-to-edit-your-system-path-for-easy-command-line-access/. You need to restart the maching after this and rerun the `activate` commands.
    * If the above fails. Try uninstalling any other python version, then restarting machine, then reinstalling conda, and then restarting machine again. It should be able to add the path variables correctly this time. 


I will keep updating this FAQ as I hear about more issues.
