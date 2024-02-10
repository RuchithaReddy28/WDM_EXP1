### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 10.02.2024
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
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
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
sunny,85.0,85.0,false,no
overcast,80.0,90.0,true,no
sunny,83.0,86.0,false,yes
rainy,70.0,86.0,false,yes
rainy,68.0,80.0,false,yes
rainy,65.0,70.0,true,no
overcast,64.0,65.0,false,yes
sunny,72.0,95.0,true,no
sunny,69.0,70.0,false,yes
rainy,75.0,80.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
#### Training Data Set -> Employee Table
<img width="279" alt="303812601-4c3dc9db-ac44-4f90-b39c-1242b8a42a4a" src="https://github.com/RuchithaReddy28/WDM_EXP1/assets/93427261/e9b791e5-c65a-40b3-af1f-459c4031bd07">

#### Training Data Set -> Weather Table
<img width="294" alt="303812615-ccbb6a4a-f630-4768-9985-76e3e3590abb" src="https://github.com/RuchithaReddy28/WDM_EXP1/assets/93427261/db505c29-eae7-4ecb-bf0d-fddf304c6f22">



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
#### Employee Table after adding new attribute ADDRESS:
<img width="358" alt="303816967-1f43aa2a-a91d-42f6-9ccf-bea92b68c385" src="https://github.com/RuchithaReddy28/WDM_EXP1/assets/93427261/991a89b6-530c-45b7-a808-87202da07c30">

#### Weather Table after adding new attribute CLIMATE:
<img width="374" alt="303817032-6f5da986-e8e3-46f3-8985-63a5d7205331" src="https://github.com/RuchithaReddy28/WDM_EXP1/assets/93427261/7fdbef3e-f37b-4a2d-a209-18650e86f678">

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
#### Employee Table after removing attributes SALARY,GENDER:
<img width="178" alt="303817269-2b026531-be09-49dc-a0d9-4857c55d8128" src="https://github.com/RuchithaReddy28/WDM_EXP1/assets/93427261/4c6586da-ef57-4712-a338-f6a1be1327c8">

#### Weather Table after removing attributes WINDY,PLAY:
<img width="190" alt="303817260-674872b1-12f9-4f28-bbf9-b38abaf966a8" src="https://github.com/RuchithaReddy28/WDM_EXP1/assets/93427261/b9472594-289d-4db5-9c5e-e0a93e4d4ba8">

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
#### Employee Table after Normalizing ID,EXP,PHONE:
<img width="262" alt="303817248-370c495a-fbef-4206-a1eb-2d19ae54ab18" src="https://github.com/RuchithaReddy28/WDM_EXP1/assets/93427261/29241030-15ec-494c-bb04-1baa71447d57">

#### Weather Table after Normalizing TEMPERATURE,HUMIDITY:
<img width="266" alt="303817243-1826f1a5-6aa5-49ff-a821-3e69eb0c756f" src="https://github.com/RuchithaReddy28/WDM_EXP1/assets/93427261/4da4492a-8625-4d7c-b1cd-b94c1f6e5bab">

### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
