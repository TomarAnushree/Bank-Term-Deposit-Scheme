# Bank-Term-Deposit-Scheme
amex-ai-ml-hackathon-geek-goddess-2021
![](https://github.com/TomarAnushree/Bank-Term-Deposit-Scheme/blob/main/Bank%20Term%20Deposit%20Scheme/Capture.PNG)

The banks are moving with the pace of technology and incorporating different techniques to get the clients on-board. There are multiple marketing techniques in the market different banks are resorting to get people involved into different banking schemes. One such technique is phone calling the clients, getting their details and letting them know about the different schemes. It might require multiple calls to the same client to figure out if the client will be on-board or not. It is where Machine Learning can be incorporated and the result can be predicted based on the information received. This information will be valuable to pay more attention to the customers who might be willing to get on-board and be in their contact. The models can be trained on the data set and the banks can plan out a strategy which will be beneficial for them. 

# [Dataset Source:](https://www.techgig.com/geekgoddess/amex-ai-ml-hackathon-geek-goddess-2021)

The data sets are provided with the details of the campaign which we used to build a model which can predict if the client will say ‘yes’ or ‘no’ for the scheme. The scheme in question is term deposit and is the same for all the clients. If the client gets on-board, it is denoted with ‘yes’ and if he does not, it is denoted with ‘no’.


# Data Description:

The data set consists of the 21 attributes along with their values. The term deposit is denoted with variable `y`. The data can be understood in the 4 parts:

1. Bank client data attributes

2. Related with the last contact of the current campaign attributes

3. Other Attributes

4. Social and Economic Context Attributes



# 1.	Bank client data attributes

|Attribute |	Values      |
|----------|--------------|
|key       |	1, 2. 3, 4….|
|age       |	numeric     |
|job       |	type of job (categorical:'admin.','blue-collar','entrepreneur','housemaid',|
|          |    'management','retired','self-employed','services','student','technician','unemployed','unknown')|
|marital   |	marital status (categorical: 'divorced','married','single','unknown';|
|          |   note: 'divorced' means divorced or widowed)|
|education |	categorical: 'basic.4y','basic.6y','basic.9y','high.school','illiterate',|
|           |     'professional.course','university.degree','unknown'|
|default|	has credit in default? (categorical: 'no','yes','unknown')|
|housing|	has housing loan? (categorical: ‘no’, ‘yes’, ‘unknown’)
|loan	|has personal loan? (categorical: 'no','yes','unknown')|



# 2. Related with the last contact of the current campaign attributes

|Attributes	|Values|
|-----------|------|
|contact    |	contact communication type (categorical: 'cellular','telephone')|
|month      |	last contact month of year (categorical: 'jan', 'feb', 'mar', ..., 'nov', 'dec')|
|day_of_week|	last contact day of the week (categorical: 'mon','tue','wed','thu','fri')|
|duration  	|last contact duration, in seconds (numeric)|


`*Note*: duration attribute highly affects the output target (e.g., if duration=0 then y='no').
Yet, the duration is not known before a call is performed. Also, after the end of the call y 
is obviously known.`



# 3. Other Attributes

|Attributes	|Values|
|-----------|------|
|campaign	|number of contacts performed during this campaign and for this client (numeric, includes last contact)|
|pdays|	number of days that passed by after the client was last contacted from a previous campaign |
|     |  (numeric; 999 means client was not previously contacted)|
|previous	|number of contacts performed before this campaign and for this client (numeric)|
|poutcome	|outcome of the previous marketing campaign (categorical: 'failure','nonexistent','success')|




# 4. Social and Economic Context Attributes

|Attributes	|Values|
|------------|------|
|emp.var.rate|employment variation rate - quarterly indicator (numeric)|
|cons.price.idx|consumer price index - monthly indicator (numeric)|
|cons.conf.idx|consumer confidence index - monthly indicator (numeric)|
|euribor3m|euribor 3 month rate - daily indicator (numeric)|
|nr.employed|number of employees - quarterly indicator (numeric)|


# Data Dictionary

Here's a brief version of what you'll find in the data description file.

|Variable	|Description|
|----------|----------|
|key|	Unique Key|
|y|	If the client would say yes or no for the deposit scheme|


