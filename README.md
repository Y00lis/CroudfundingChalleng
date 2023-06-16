# CroudfundingChalleng
Excel
Notes for Excel challenge: 

Prep for Couwdfunding tab:

1.	Added columns  for percent funded and from conditional formatting changed the colors. 
Used conditional formatting (added a rule) for Outcome as well for failed, successful, live and canceled.
Added a formula to separate the sub and parent categories [=TEXTSPLIT(R2,"/") ]
2.	Created a new sheet for Parent Category
Selected all data from “crowdfunding” tab
Inserted a PicotChart to show a pivot table and a chart
Selected only field I wanted to show on the pivot and chart
3.	Created a new sheet for Subcategory.
Selected all data from “crowdfunding” tab
Inserted a PicotChart to show a pivot table and a chart
Selected only field I wanted to show on the pivot and chart
4.	Created a “Deadline” sheet
Converted the Date created launched at and Date ended per https://www.extendoffice.com/documents/excel/2473-excel-timestamp-to-date.html
Added chart and pivot table to show only desired data. To show Successful and failed
5.	Create Goal Analysis sheet 
Created rows for number ranges 
Added formulas to bring over data from crowdfunding
[=COUNTIFS(Crowdfunding!G2:G1001, "Successful", Crowdfunding!D2:D1001, "<1000")]
Countif was retrieved from
https://www.ablebits.com/office-addins-blog/excel-countifs-multiple-criteria/
next rows under that formulas were retrieved from.
https://www.got-it.ai/solutions/excel-chat/excel-tutorial/countif/countif-between-two-values
count if less than or equal to
https://www.ablebits.com/office-addins-blog/excel-countif-function-examples/#:~:text=COUNTIF%20greater%20than%2C%20less%20than,are%20always%20enclosed%20in%20quotes.

For the Data chart summary 
I went back to the main crowd funding data filtered for only “successful” and pasted that to new tab summary and same with the unsuccessful. 
Median, max, min with help of askBCS and going back to recordings of class pertaining to “standard deviateion;

For the mean, you will use the =AVERAGE function, the median is =MEDIAN, the minimum is =MIN, max is =MAX, =VAR.S for the variance, and =STDEV for standard deviation


