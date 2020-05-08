## [![license](https://img.shields.io/github/license/DAVFoundation/captain-n3m0.svg?style=flat-square)](https://github.com/kritika-srivastava/Random-Password-Generator/blob/master/LICENSE)![Project Status](https://img.shields.io/badge/Project-Completed-orange)[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)
## ![Python Badge](https://img.shields.io/badge/Python-3.5%7C3.6%7C3.7-success)![Pandas Badge](https://img.shields.io/badge/Dependencies-Pandas|requests|json-critical)

# Reviews Scrapping of google places using Google Place ID 
#### *Welcome to Google Place Id Reviews Scrapping’s documentation! Here, I shall give an overview of all the steps you need to know to get started with this project.*
&nbsp;

![](readme%20docs/Scrapping%20Reviews.gif)
&nbsp;

&nbsp;

## Technical Stack
- Jupyter Notebook
- Pandas (Python)
- Requests (Python)
- json (Python)
- Anaconda

&nbsp;


## Installing required Plugins
#### *The installation procedure is written keeping **anaconda** distribution as the base. However you can install the given plugins in any distribution.*
Open the anaconda prompt and activate your environment (if you prefer to work in any other virtual environment other than base) by typing the following command.
``` 
conda activate your_env_name  
```
*Run the given command in the anaconda prompt to install requests .*
``` 
pip install requests  
```
A list of package to be installed or to be updated shall appear on terminal and you will be prompted to select [y/n].Select y and press Enter.Now wait till the package is installed .
&nbsp;

*Run the given command in the anaconda prompt to install Pandas.*
``` 
conda install -c anaconda pandas  
```
*json is in-built in Python.*
&nbsp;

As of now, this project runs on Python 3.x . Make sure that all the given should be installed in any of your python distributions. To start the program first clone this [github repository](https://github.com/kritika-srivastava/Google-place-ID-Reviews-Scrapping).
&nbsp;

## Steps to Run the code
#### *First open your IDE and activate the virtual environment in which all the plugins are installed and cd to the directory where you cloned this repository.*
Note: The kernel of jupyter notebook will not start unless you have ipython kernel installed in your virtual environment.For installing the kernel tpye the following in your anaconda prompt.
``` 
conda activate your-env-name
python -m ipykernel install --user --name your-env-name --display-name "Python (your-env-name)" 
```
-  Now type :
``` 
jupyter notebook 
```
- Once the jupyter window appears in the window, from the homepage open [API Key.txt](https://github.com/kritika-srivastava/Google-place-ID-Reviews-Scrapping/blob/master/API%20Key.txt) and place your api key within the inverted commas. Save the file.
&nbsp;

- Open the following jupyter notebook from homepage[Google Place ID reviews Scrapping.ipynb](https://github.com/kritika-srivastava/Google-place-ID-Reviews-Scrapping/blob/master/Google%20Place%20ID%20reviews%20Scrapping.ipynb). Now place the place ID of the place for which you want to extract reviews in line number 8 of cell 3 .
- Run all the cells in order.
- If everything worked so far, you shall see the output as shown in the gif above.
 &nbsp;

## References
#### - [Web Scrapping Tutorial](http://tutorials.iq.harvard.edu/Python/PythonWebScrape/PythonWebScrape.html)
#### - [json Documentation](https://docs.python.org/3/library/json.html)
#### - [requests Documentation](https://pypi.org/project/requests/)
#### - [Pandas Documentation ](https://pandas.pydata.org/docs/)
