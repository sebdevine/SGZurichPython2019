# SGZurichPython2019
Extra material for SG Zurich Python courses (2019)

## Install Python
**Please visit [Anaconda](https://www.anaconda.com/distribution/)**
- Select Windows or MacOS
- Click download for **Python 3.7 version**
- Save it (.exe or .dmg), it's ~ 600 megs
- Launch the installer (.exe or .dmg)
- Follow the steps (not need to change the defaults) and install.

A `Anaconda` folder should be created, either in the start menu (Windows) or the app launcher (MacOS). In that folder you should see a **Jupyter Notebook** application with the following icon :

![JupyterLogo](250px-Jupyter_logo.svg.png)

If not found: please type "Jupyter" right after opening the Windows start menu / or in MacOS finder:
![Looking for Jupyter Image](Looking_for_Jupyter.png)

It will launch a new window (text based console application), and it will open a link in your default web browser (Chrome, safari, Firefox or Edge are fine), the [Jupyter notebook file browser](http://localhost:8888/tree)

**Do not close that window:**

![Console](jupyter_console.png)

We will work in the web browser from here, it's a web based file browser, usually you can see your home folder, and manage notebooks/folders from here :

![fileBrowser](jupyter_file_browser.png)

Next, create a new notebook : 

![openNotebook](open_new_notebook.png)

It will open a new tab in the current web browser (and create a notebook file in your home folder), with the following content (here in french):

![NewNotebook](new_notebook.png)


Nice ! Now try some coding, type :
```python
2+2
```

And hit `Shift` + `Enter` to execute.

Wow !

![wow](wow.png)

## EmailAccount

- Site : [GMX](https://gmx.com)
- login : sgzurich2019
- password : will be given in time


## MarketData
### Install [pandas_datareader](https://pandas-datareader.readthedocs.io/en/latest/index.html) :
- Open a terminal on Windows: Windows key + R, type: cmd, hit enter
- Open a termnial on Mac: lookup in the app launcher for `terminal`

Type and hit enter for each line :
```batch
pip install alpha_vantage
pip install pandas_datareader
```
### Download and run the notebook
Open this link, then right click on `[Raw]` and select `Save As|Download As` (depends on your browser) => saves the file in your home folder where you can open it with the Jupyter file browser.

[Simplified pricing notebook](https://github.com/sebdevine/SGZurichPython2019/blob/master/SGZurich2019_simplified_pricing.ipynb)

