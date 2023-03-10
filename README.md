# Facebook-Stock-Analysis

For the Code Louisville data analysis final project, I wanted to extend my work from the last cohort.This desire drove me to investigate Facebook.

In my data breaches analysis, I found that Facebook had experienced the most reported data breaches based on my dataset. In order to pursue this investigation into Facebook, I located and downloaded an dataset of their stock history found on Kaggle. I wanted to see if there were any effects from an financial perspective.

Upon investigation, I found some questions to ask against the dataset:
*What is the highest and lowest prices of stock?
*What is the the highest and lowest number of traded stocks?
*Is there relationship between the cost of stock and value of traded stocks?
*Does the effects of an breach become minimal depending on the organization's size?

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
* Made a Pivot table.
* Wrote in Jupyter's markdown cells explaining my thought process and code.


Source:https://www.kaggle.com/datasets/kalilurrahman/facebook-stock-data-live-and-latest


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







