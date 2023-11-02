# Facebook-Stock-Analysis

For the Code Louisville data analysis final project, I wanted to extend my work from the last cohort. This desire drove me to investigate Facebook.

In my data breaches analysis, I found that Facebook had experienced the most reported data breaches. In order to pursue this investigation into Facebook, I located and downloaded a dataset of their stock history found on Kaggle. I wanted to see if there were any effects from a financial perspective.

<details>
  <summary>Table of Contents</summary>
  <ol type="I">
    <li><a href="#project-requirments">Project Requirements</a></li>
    <li><a href="#project-hierarchy">Project Hierarchy</a></li>
    <li><a href="#project-instructions">Project Instructions</a></li>
    <li><a href="#investigation">Investigation</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#data">Data</a></li>
    <li><a href="#conclusion">Conclusion</a></li>
  </ol>
</details>

## Project Requirements
Note: I started working on this project using Anaconda which utilized python 3.9.13. After careful consideration and a failed update, I decided to try python 3.10.9.

Special Instructions: The pre-release version of Jupyter needs to be installed within Visual Studio Code.

Use the following syntax to install the required packages:
```
pip install <package>
```

### Required Packages to Install
* pandas
* seaborn
* matplotlib
* statistics

## Project Hierarchy
<dl>

<dt>Data Breach Analysis</dt>
<dd>This notebook is an altered version of the original analysis, where it has been appended to build a pivot table of annual averages of compromised records pertaining to Facebook. Then, it outputs the derived pivot table to a CSV file. <dd>

<dt>Facebook Stock Analysis</dt>
<dd>This notebook builds a pivot table of monthly stock averages and outputs it to a CSV file.</dd>

<dt>Effects on Facebook Stocks</dt>
<dd>This notebook merges the pivot tables built from the Data Breach Analysis and Facebook Stock Analysis notebooks. Then, it outputs the merged data to a CSV file.</dd>

<dt>Looker Studio</dt>
<dd>The dynamic visualization tool that I utilized to construct an interactive dashboard of the data. There is a link under the data section.</dd>

</dl>

## Project Instructions
Please build and run the jupyter notebooks in the following order:

1.  [Data Breaches Analysis](./ipynb/FB_db_analysis.ipynb)
 
    * Made a pivot table
    * Wrote in Jupyter's markdown cells explaining my thought process and code.

2.  [Facebook Stock Analysis](./ipynb/FB_stock_analysis.ipynb)
   
    * Made a pivot table
    * Wrote in Jupyter's markdown cells explaining my thought process and code.

3.  [Effects on Facebook Stocks](./ipynb/FB_stock_effects.ipynb)

    * Performed a pandas merge with two data sets,then calculated some new values based on the new data set.
    * Wrote in Jupyter's markdown cells explaining my thought process and code.

## Investigation
Upon investigation, I found some questions to ask against the dataset:
<ul>
<li>What are the highest and lowest prices of stock?</li>
<li>What are the highest and lowest numbers of traded stocks?</li>
<li>Is there a relationship between the price of a stock and the number of traded stocks?</li>
</ul>

## Features

* Read two data files (JSON,CSV, Excel, etc.)
* Performed a pandas merge with two data sets, then calculated some new values based on the new data set.
* Made a dashboard to display the data.
* Made a pivot table.
* Built a custom data dictionary.
* Wrote in Jupyter's markdown cells explaining my thought process and code.

## Data
<p align="center">Sources</p>

* https://www.kaggle.com/datasets/hishaamarmghan/list-of-top-data-breaches-2004-2021

* https://www.kaggle.com/datasets/kalilurrahman/facebook-stock-data-live-and-latest 

<br>
<p align="center">Facebook Data Dictionary</p>
<link href="css/dict_style.css" rel="stylesheet">
<table>
  <tr>
    <th>Column</th>
    <th>Description</th>
    <th>Data Type</th>
    <th>Field type</th>
  </tr>
    <tr>
    <td>Date</td>
    <td>Time Format: MM/DD/YYYY  </td>
    <td>Object</td>
    <td>Origin</td>
   </tr>
   <tr>
    <td>Year</td>
    <td>Component of the Date </td>
    <td>int32</td>
    <td>Origin</td>
   </tr>
   <tr>
    <td>Month</td>
    <td>Component of the Date </td>
    <td>int64</td>
    <td>Origin</td>
   </tr>
   <tr>
    <td>Formatted Date</td>
    <td>Combination of Year and Month </td>
    <td>object</td>
    <td>Formulated</td>
   </tr>
   <tr>
    <td>Breach</td>
    <td>Indication that a breach occurred</td>
    <td>int64</td>
    <td>Formulated</td>
   </tr>
    <tr>
    <td>Records</td>
    <td>The number of records that were compromised in a breach</td>
    <td>object</td>
    <td>Origin</td>
   </tr>
     <tr>
    <td>Open</td>
    <td>The opening price of stock</td>
    <td>float64</td>
    <td>Origin</td>
   </tr>
    <tr>
    <td>High</td>
    <td>The highest price of stock</td>
    <td>float64</td>
    <td>Origin</td>
    </tr>
     <tr>
    <td>Low</td>
    <td>The lowest price of stock</td>
    <td>float64</td>
    <td>Origin</td>
    </tr>
     <tr>
    <td>Close</td>
    <td>The closing price of stock</td>
    <td>float64</td>
    <td>Origin</td>
    </tr>
    <tr>
    <td>Volume</td>
    <td>The number of traded stocks</td>
    <td>float64</td>
    <td>Origin</td>
    </tr>
</table>
</br>

###  Facebook Stock Dashboard

https://lookerstudio.google.com/s/h-TjNVlXEvk

## Conclusion
[Results](./ipynb/conclusion.ipynb)





