Note: The dataset and company used for this project were fabricated and was to be used by participants of the KPMG-AU Data Analytics virtual internship experience on the Forage platform (www.theforage.com). I participated in and completed the program.

# Marketing-strategy-optimization-analysis

### Background Information

Sprocket Central Pty Ltd is a medium size bikes & cycling accessories organisation that is keen to learn more about KPMG’s expertise in its Analytics, Information & Modelling team. 
Primarily, Sprocket Central Pty Ltd needs help with its customer and transactions data. The organisation has a large dataset relating to its customers, but their team is unsure how to effectively analyse it to help optimise its marketing strategy. 
The client provided KPMG with 3 datasets:

1. Customer Demographic 

2. Customer Addresses

3. Transactions data in the past 3 months

### Tasks and solutions

1. Review of the data quality to ensure that it was ready for the analysis in phase two while taking note of any assumptions or issues so as to get back to the client via email. As well as giving recommendations going forward to mitigate current data quality concerns. The data quality framework was used as a guideline (see more details in the attachments).

2. A new list of 1000 potential customers with their demographics and attributes was given. However, these customers did not have prior transaction history with the organisation. The marketing team at Sprocket Central Pty Ltd is sure that, if correctly analysed, the data would reveal useful customer insights which could help optimise resource allocation for targeted marketing. Hence, improve performance by focusing on high value customers. Based on this, the existing 3 datasets (Customer demographic, customer address and transactions) were to be used as a labelled dataset to recommend which of the 1000 new customers would be targeted to drive the most value for the organisation. To analyze the 3 datasets, I merged the Customer demographic and customer address tables into the transactions table using VLOOKUP. I transformed the merged datasets by adding some relevant columns and performing some calculations, and develped a model using the RFM technique. I used the RFM  method sine we needed to  determine how recently the customers' purchased bikes, how often, and how much they spent. I determined the R-score, F-score, and M-score for each customer (See the excel sheet for details of formulas).

3. Presentation to the client was done using powerpoint. The new list of the 1000 potential customers was used to determine which customers were to be focused on. This was achieved after analyzing the existing customers' information in task 2. A dashboard showing which potential customers should be targeted was developed using Looker.

### Interpretation

The major interpretations from the exploratory analysis are given below.
- The major customers of Sprocket Central Pty Company are the middle-aged group who are not in the high-net worth or affluent class.
- Many existing and potential customers reside in the state of New South Wales.
- More focus should be on marketing customers who work in the manufacturing, financial services and the health sectors.
- They have more female customers who patronize them more than the males.
- Promotions and rewards should be offered to the platinum and gold customers to encourage patronage.
- VIP and custom services should be part of the package for bike purchase.


