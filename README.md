# Facebook-Stock-Analysis

For the Code Louisville data analysis final project, I wanted to extend my work from the last cohort.This desire drove me to investigate Facebook.

In my data breaches analysis, I found that Facebook had experienced the most reported data breaches based on my dataset. In order to pursue this investigation into Facebook, I located and downloaded an dataset of their stock history found on Kaggle. I wanted to see if there were any effects from an financial perspective.

Upon investigation, I found some questions to ask against the dataset:
<ul>
<li>*What is the highest and lowest prices of stock?</li>
<li>What is the the highest and lowest number of traded stocks?</li>
<li>Is there relationship between the cost of stock and value of traded stocks?</li>
<li>Does the effects of an breach become minimal depending on the organization's size?</li>
</ul>

Note: I started working on this project using anaconda which utilized python 3.9.13. After condsideration and failed update, I decided to try python 3.10.9.

Special Instructions: The pre-release version of Jupyter needs to be installed within Visual Studio Code.

<u>Required packages to install</u>
* Pandas
* Seaborn
* Matplotlib
* Statistics

<u>Current implemented features</u>
* Read two data files (JSON,CSV, Excel, etc.)
* Performed a pandas merge with two data sets,then calculate some new values based on the new data set.
* Made a dashboard to display the data.
* Made a pivot table.
* Built a custom data dictionary.
* Wrote in Jupyter's markdown cells explaining my thought process and code.


<u>Date Sources</u></br>

https://www.kaggle.com/datasets/hishaamarmghan/list-of-top-data-breaches-2004-2021

https://www.kaggle.com/datasets/kalilurrahman/facebook-stock-data-live-and-latest

<u>Facebook Stock Dashboard</u>

https://lookerstudio.google.com/s/h-TjNVlXEvk

<iframe width="600" height="450" src="https://lookerstudio.google.com/embed/reporting/df836a0b-e61d-41a7-940e-90b846ce9a20/page/p_a7zz9a233c" frameborder="0" style="border:0" allowfullscreen></iframe>

<p style="text-align:center"></br>Facebook Data Dictionary</p>
<table>
  <tr>
    <th>Column</th>
    <th>Description</th>
    <th>Data Type</th>
  </tr>
   <tr>
    <td>Year</td>
    <td>Component of the Date </td>
    <td>int32</td>
   </tr>
   <tr>
    <td>Month</td>
    <td>Component of the Date </td>
    <td>int64</td>
   </tr>
   <tr>
    <td>Formatted Date</td>
    <td>Combination of Year and Month </td>
    <td>object</td>
   </tr>
   <tr>
    <td>Breach</td>
    <td>Indication that a breach occured</td>
    <td>int64</td>
   </tr>
    <tr>
    <td>Records</td>
    <td>The number of records that were compromised in a breach</td>
    <td>object</td>
   </tr>
     <tr>
    <td>Open</td>
    <td>The opening price of stock</td>
    <td>float64</td>
   </tr>
    <tr>
    <td>High</td>
    <td>The highest price of stock</td>
    <td>float64</td>
    </tr>
     <tr>
    <td>Low</td>
    <td>The lowest price of stock</td>
    <td>float64</td>
    </tr>
     <tr>
    <td>Close</td>
    <td>The closing price of stock</td>
    <td>float64</td>
    </tr>
    <tr>
    <td>Volume</td>
    <td>The number of traded stocks</td>
    <td>float64</td>
    </tr>
</table>







