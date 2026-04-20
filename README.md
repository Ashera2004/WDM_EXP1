### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 20/04/2026
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name {x,y,z,a,b}
@attribute ID numeric
@attribute salary {low,medium,high}
@attribute Experience numeric
@attribute gender {male,female}
@attribute phone numeric
@data
x,101,low,2,male,250311
y,102,high,3,female,251665
z,103,medium,1,male,240238
a,104,low,5,female,200200
b,105,high,2,male,240240

--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,40.0,85.0,false,no
overcast,45.0,90.0,true,no
sunny,35.0,80.0,false,yes
rainy,30.0,75.0,true,no
rainy,33.0,70.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
## Employee 

<img width="493" height="242" alt="2026-04-20 10_15_30-Viewer" src="https://github.com/user-attachments/assets/ffa4e361-94e4-4f8b-88c7-5008b44245be" />


## Weather

<img width="441" height="233" alt="2026-04-20 10_18_41-Viewer" src="https://github.com/user-attachments/assets/d91194d6-d44b-43bb-a0fc-879e38c192c8" />


### PREPROCESSING

### Procedure:

#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
## Employee 

<img width="1919" height="1200" alt="2026-04-20 10_27_00-" src="https://github.com/user-attachments/assets/4fbc21d4-e0c4-4c86-a0e6-a7adeb80edca" />


<img width="576" height="226" alt="2026-04-20 10_37_48-Viewer" src="https://github.com/user-attachments/assets/780ec160-ad9c-4597-99ac-a5d5b6ff513b" />

## Weather

<img width="978" height="731" alt="2026-04-20 10_44_38-Weka Explorer" src="https://github.com/user-attachments/assets/9f9058d5-3e93-4657-bcb5-36df5dcace6c" />


<img width="592" height="271" alt="2026-04-20 10_46_08-Viewer" src="https://github.com/user-attachments/assets/d807db7d-656d-4b6f-89a6-8f8c334764ae" />


### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:

## Employee

<img width="990" height="742" alt="2026-04-20 10_38_59-Weka Explorer" src="https://github.com/user-attachments/assets/92c7e9e5-3476-4766-bb3b-60ccb89c4ca8" />


<img width="519" height="249" alt="2026-04-20 10_40_07-Viewer" src="https://github.com/user-attachments/assets/48fcf139-60a0-4162-9096-3af5b7e2216d" />


## Weather

<img width="982" height="738" alt="2026-04-20 10_47_14-Weka Explorer" src="https://github.com/user-attachments/assets/49674581-80fa-41b3-b5a7-914848793478" />


<img width="1232" height="738" alt="2026-04-20 10_47_52-Viewer" src="https://github.com/user-attachments/assets/2107e59d-ad8d-4cab-80c1-4bfdb6d5b0ac" />



### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:
## Employee

<img width="976" height="735" alt="2026-04-20 10_41_18-Weka Explorer" src="https://github.com/user-attachments/assets/d555b6d2-3e1b-4369-a645-3cba50c8c467" />


<img width="506" height="253" alt="2026-04-20 10_41_51-Viewer" src="https://github.com/user-attachments/assets/71d6c179-fc01-4485-bc7a-cbbb90f5958e" />


## Weather

<img width="977" height="738" alt="2026-04-20 10_49_01-Weka Explorer" src="https://github.com/user-attachments/assets/112b1325-48b2-4717-b660-2b5113737fb0" />


<img width="464" height="273" alt="2026-04-20 10_49_26-Viewer" src="https://github.com/user-attachments/assets/8aeaed4b-5614-4e96-b0af-cd0e32dd944e" />



### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
