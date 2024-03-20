# Learning_Labs-4-TURF-analysis-in-Excel
This tutorial will help you set up and interpret a TURF analysis in Excel using the XLSTAT statistical software.

## Dataset for running a TURF analysis and goal of this tutorial
The data comes from ratings by 185 customers on 27 dishes. Scores are given on a scale of 1 to 5 in response to the question "Would you buy the product?" (1: no, not at all to 5: Yes, quite sure). The goal here is to obtain a product line consisting of 5 dishes that will be sold in some stores. It should be constructed such that the market share of this line is as strong as possible.

We use the TURF method (Total Unduplicated Reach and Frequency), which provides a product line that has the highest penetration. All combinations of 5 products among all products are tested in order maximize the chance that at least one of these products is consumed.

## Setting up a TURF analysis
After opening XLSTAT, select the XLSTAT / Sensory data analysis / TURF command, or click on the corresponding button of the XLSTAT-Sensory data analysis button (see below).
![image](https://github.com/LangatErick/Learning_Labs-4-TURF-analysis-in-Excel/assets/124883947/1c6b41c5-5017-409b-97ce-4ec59c72e1d8)
![image](https://github.com/LangatErick/Learning_Labs-4-TURF-analysis-in-Excel/assets/124883947/f37e8aa8-8d2f-470e-ad5d-d4648193ed71)
- Once the button is clicked, the dialog box appears. You can then select the data on the Excel sheet. You must select all products as data.

- The Variable labels option is left enabled because the first line of the column of data includes the product name.

- The size of the subset is 5. The scale being 1 to 5, we select as a scale 1-5.
  ![image](https://github.com/LangatErick/Learning_Labs-4-TURF-analysis-in-Excel/assets/124883947/835edd7a-2fb2-4a98-ae34-68ed0a38fb83)
- In the options tab, the number of combinations to be displayed is 10.

Thus, the 10 best lines of 5 products will be displayed. Then, you define the goal. In our case, we consider that a consumer will buy the product if he gives a score of 4 or 5. The method used is the enumeration that will necessarily give the optimal result.
![image](https://github.com/LangatErick/Learning_Labs-4-TURF-analysis-in-Excel/assets/124883947/25db7b42-2be0-46a1-a37b-e24d7fbea4c8)
Once you have clicked the OK button, the calculations start, and the results are displayed.
## The Results 
![image](https://github.com/LangatErick/Learning_Labs-4-TURF-analysis-in-Excel/assets/124883947/8160147b-9b5f-4269-9557-adb5a602088f)

![image](https://github.com/LangatErick/Learning_Labs-4-TURF-analysis-in-Excel/assets/124883947/740adc83-d9ef-4a95-91fe-ebd19924b5cf)

## Interpreting the results of a TURF analysis
The first table includes the frequencies at which the objective is achieved for each product separately.

The following table gives the 10 best combinations obtained, each time with the reach and the frequency obtained. The reach is the number of consumers who intend to buy at least one product of the line (it will be worth up to 185), the frequency is the number of times a product line has received a score of 4 or 5 (maximum of 5 * 185 = 925).
