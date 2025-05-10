# Regulatory_Compliance_Analysis
<a id = Section1></a>
# **1. Introduction**

According to the Consumer Response Annual Report of the Consumer Financial Protection Bureau (CFPB), the Bureau sent approximately 264,100 (or 80%) of these complaints to companies for review and response, referred 14% of complaints received to other regulatory agencies, and found 4% to be incomplete. At the end of 2018, 0.4% of complaints were pending with the consumer and 1% were pending with the Bureau
**<center>COMPLAINT OUTCOMES IN 2018<center></center>**
<center><img src = "https://raw.githubusercontent.com/insaid2018/Domain_Case_Studies/master/Finance/Customer%20Compalints%20Analysis%201.png"></center>

Companies responded to 96% of the approximately 264,100 complaints that the Bureau sent to them for response in 2018. Companies confirmed a commercial relationship with, and provided responses to, consumers in approximately 91% of these complaints.. 

**<center>HOW COMPANIES HAVE RESPONDED TO CONSUMER COMPLAINTS</center>**
<center><img src = "https://raw.githubusercontent.com/insaid2018/Domain_Case_Studies/master/Finance/Customer%20Complaints%20Analysis%202.png"></center>
<a id = Section2></a>
# **2. Problem Statement**

The problem here is to analyze the complaints of the consumers and identify the category of product it belongs to and then share complaint data to level the playing field and empower consumers to take more control over their financial lives.

<center><img src = "https://raw.githubusercontent.com/insaid2018/Domain_Case_Studies/master/Finance/Customer%20Complaints%20Analysis%203.png"></center>

**<h3>Scenario:</h3>**

One of the primary functions of the Bureau of Consumer Financial Protection (CFPB or Bureau) is collecting, investigating, and responding to consumer complaints. They handle consumer complaints, and analyze and share complaint data to level the playing field and empower consumers to take more control over their financial lives.

Like a cop on the beat, CFPB is responsible for rule-making, supervision, and enforcement of Federal consumer financial protection laws and for restricting unfair, deceptive, or abusive acts or practices against consumers.

The target feature in the acquired dataset is Product, and its values are:.

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

This dataset is based on consumer complaints and is provided by the Consumer Financial Protection Bureau it can be acquired from the <a href="https://www.consumerfinance.gov/data-research/consumer-complaints/">link</a>. The Consumer Complaint Database is a collection of complaints about consumer financial products and services that CFPB sent to companies for response.

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




