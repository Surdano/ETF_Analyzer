# ETF_Analyzer
![Photo of ETF with a line graph and plot marks](https://www.etftrends.com/wp-content/uploads/2020/04/Best-of-Both-Worlds-An-Introduction-to-Semi-Transparent-Active-ETFs.jpg)

This program analyzes an exchange-traded-fund using a virtual SQL database. This program creates visualizations that can be displayed in a web browser using Voila or within JupyterLab.

---
## Technologies:
This program runs on Python 3.7 and utilizes the following libraries:

* [Jupyter Lab](https://jupyter.org/)

* [SQLAlchemy](https://www.sqlalchemy.org/)

* [Pandas](https://pandas.pydata.org/)

* [hvplot](https://hvplot.holoviz.org/)

* [Voilà](https://voila.readthedocs.io/en/stable/)

---
## Installation Guide:
This progam can run in Jupyter Lab where the following imports are required:

```python
import numpy as np
import pandas as pd
import hvplot.pandas
import sqlalchemy
```
To utilize Voila, run the following in terminal:

```python
pip install viola
```

---
## Usage:

To use Viola, navigate to the program folder in the terminal and run:

`viola etf_analyzer.ipynb`

A Web browser page will automatically open and the following plots will start generating:

![Screen shot of daily and cumulative returns](https://user-images.githubusercontent.com/89755088/141738831-8b42fcfb-fbca-496b-acc0-4a3a7fb33195.png)

![Screen shot of ETF portfolio cumulative returns](https://user-images.githubusercontent.com/89755088/141739212-9199fb3d-3473-4770-9b54-2df00b1a48b4.png)

---
## Contributors:
Code was written by Thomas Leahy, thomasleahy6@gmail.com, In conjunction with © 2020 - 2021 Trilogy Education Services, a 2U, Inc. brand.

---
## Licence:
MIT

2021 Thomas Leahy