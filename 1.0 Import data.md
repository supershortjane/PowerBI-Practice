# PowerBI-Practice (Import data)

## Introduction
There are two main ways to load data into PowerBI:<br/>
Direct Query:<br/>
◆ nearly real time<br/>
◆ not sutible for data bigger than 1 GB<br/>
Import:<br/>
◆ would make a copy to PowerBI desktop<br/>
◆ sutible for data smaller than 1 GB<br/>

## Process
In this practice, I would try 3 types of connection based on my data stored in different format. <br/>
## 1.Connect data from Web
Step1. click "取得資料" <br/>
Step2. click "web" under "其他" tab (since our data comes from a website)<br/>
<img width="681" alt="1" src="https://user-images.githubusercontent.com/32606310/106082035-f0cc4c80-6154-11eb-8875-284794210597.PNG"><br/>
Step3. The data is documented in Chinese, choose "UTF-8" as our encoding<br/>
<img width="701" alt="2" src="https://user-images.githubusercontent.com/32606310/106082045-f2961000-6154-11eb-973c-f8898158d5c0.PNG"><br/>
<img width="633" alt="3" src="https://user-images.githubusercontent.com/32606310/106085720-ab5f4d80-615b-11eb-94fb-797fddcd7b32.PNG"><br/>

## 2.Connnect data from relation database
For small databases, the default connection would be "load", and for bigger databases, users would have to choose their preferred type of connection. <br/>

Step1. click "取得資料" <br/>
Step2. click "MySQL資料庫" under "資料庫" tab (since our data comes from MySQL)<br/>
<img width="628" alt="4" src="https://user-images.githubusercontent.com/32606310/106086069-5e2fab80-615c-11eb-8cac-1650d210644b.PNG"><br/>
p.s. if you encounter the following message, you should click the link provided to download the element needed<br/>
<img width="627" alt="錯誤" src="https://user-images.githubusercontent.com/32606310/106086162-91723a80-615c-11eb-909c-0d4c9ae492df.PNG"><br/>
Step3. tpye in your server name and database's name <br/>
<img width="636" alt="5" src="https://user-images.githubusercontent.com/32606310/106086107-7273a880-615c-11eb-9171-f0e7f8498864.PNG"><br/>
## 3.Connect data from Excel
Step1. click "Excel" <br/>
Step2. Click "載入"
If you would like to reshape data or process your data further, you could click "轉換資料" instead.
<img width="661" alt="9" src="https://user-images.githubusercontent.com/32606310/106086675-997eaa00-615d-11eb-88d8-a00afbb76dee.PNG">
<img width="634" alt="10" src="https://user-images.githubusercontent.com/32606310/106086677-9a174080-615d-11eb-9672-bfb13ea3407f.PNG">

