Regulatory Compliance Analysis: Consumer Financial Complaints
<a id="Section1"></a>

1. Introduction
The Consumer Financial Protection Bureau (CFPB) plays a critical role in safeguarding consumers by addressing financial complaints. According to their 2018 Consumer Response Annual Report:

80% (264,100 complaints) were sent to companies for response.

14% were referred to other agencies.

4% were deemed incomplete.

1.4% remained pending (0.4% with consumers, 1% with the Bureau).

<center>COMPLAINT OUTCOMES IN 2018</center>

<center><img src="https://raw.githubusercontent.com/insaid2018/Domain_Case_Studies/master/Finance/Customer%20Compalints%20Analysis%201.png" alt="Complaint Outcomes 2018"></center>
Company Response Rates (2018):

96% of complaints received responses.

91% included confirmation of a commercial relationship and resolution details.

<center>COMPANY RESPONSE TO COMPLAINTS</center>

<center><img src="https://raw.githubusercontent.com/insaid2018/Domain_Case_Studies/master/Finance/Customer%20Complaints%20Analysis%202.png" alt="Company Responses"></center>
<a id="Section2"></a>

2. Problem Statement
Objective:
Analyze consumer complaints to:

Categorize complaints by financial product.

Identify patterns in company responses.

Empower consumers through transparent data sharing.

<center><img src="https://raw.githubusercontent.com/insaid2018/Domain_Case_Studies/master/Finance/Customer%20Complaints%20Analysis%203.png" alt="Complaint Analysis Flow"></center>
CFPB's Role:
Primary Functions:

Complaint collection, investigation, and resolution.

Data analysis to promote fair financial practices.

Regulatory Authority:

Enforces laws against deceptive/abusive practices.

Oversees compliance for mortgages, credit cards, loans, etc.

The **target feature** in the acquired data set is **Product** and it's values are:

|Target Feature|Potential Values|
| :-- | :-- |
|**Product**|01. Credit reporting, credit repair services, or other personal consumer reports|
||02. Mortgage|
||03. Debt collection|
||04. Credit reporting|
||05. Credit card|
||06. Bank account or service|
||07. Credit card or prepaid card|
||08. Checking or savings account|
||09. Student loan|
||10. Consumer Loan|
||11. Vehicle loan or lease|
||12. Money transfer, virtual currency, or money service|
||13. Payday loan, title loan, or personal loan|
||14. Payday loan|
||15. Money transfers|
||16. Prepaid card|
||17. Other financial service|
||18. Virtual currency|

<a id=Section4></a>
# **4. Data Acquisition & Description**

This data set is **based on consumer complaints** and is provided by Consumer Finance Protection Bureau and can be acquired from the <a href="https://www.consumerfinance.gov/data-research/consumer-complaints/">link</a>. The **Consumer Complaint Database** is a collection of complaints about consumer financial products and services that CFPB sent to companies for response.

| Records | Features | Dataset Size |
| :-- | :-- | :-- |
| 1511240 | 18 | 890 MB|

| Id | Features | Description |
| :--| :--| :--|
|1|**Date received**|Complaint received date.|
|2|**Product**|Category of product under which complaint was filed.|
|3|**Sub-product**|Category of sub product under which complaint was filed.|
|4|**Issue**|Issue with the product and sub-product under complaint filed.|
|5|**Sub-issue**|Sub-issue with respect to product and sub-product.|
|6|**Consumer complaint narrative**|A complete description of issue about the product|
|7|**Company public response**|A public response broadcasted on the issue.|
|8|**Company**|Name of the Company with which the product is associated.|
|9|**State**|State where the company resides.|
|10|**ZIP code**|Zip code of the area where company resides.|
|11|**Tags**|Tags associated with the product i.e. Servicemember, Older American.|
|12|**Consumer consent provided?**|Whether the consent is provided or not.|
|13|**Submitted via**|Complaint filed via Web, Referral, Phone, Postal mail, Fax, Email|
|14|**Date sent to company**|Date when this issue was forwared to the respective company.|
|15|**Company response to consumer**|Response provided by the company to the consumer.|
|16|**Timely response?**|Response time of the complaint filed by the consumer.|
|17|**Consumer disputed?**|If there was any dispute over the product filed complaint.|
|18|**Complaint ID**| Complaint ID|

Download zip file
https://files.consumerfinance.gov/ccdb/complaints.csv.zip




