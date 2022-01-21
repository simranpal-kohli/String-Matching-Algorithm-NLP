# Rule-Based-Match-Algorithm
Matching the strings entity with a huge set of data repository with multiple probable suggestions.
The idea of fuzzy logic could also been adopted here but here I intend to build a string matching engine with the combination of
Natural Language Processing (NLTK) & rule based algorithm.

# Projects Application
Code Files: The Rule based algorithm has been applied in two applications as highlighted below.
### 1) Manual_Match_Script_V1.6.ipynb
## Brief Description: 
A Data file contains weekly file from partners where transactional & customers information are shared. This file needs to be use to check if a customer is an existing customer or a new customer based on the number of fields e.g. Customer name (Company Name), Country Code (EMIEA Region based countries), Address (With postcodes), Contact Details (Number) etc. The customer (company) can be based in UK, France etc. but with different name as suffix for e.g. xyz co uk (UK) & xyz fr (France) but both are the same company name in the end of the day. This needs to be addressed as one single company name entity by the matching algorithm. So, the algorithm does the similar work in a Sophisticated manner.
The above file is matched with the Historical CRM Feeds on many grounds.

### 2) NCR_CRT_TARS_Match_V1.ipynb
## Brief Description: 
Here, a similar matching is done but the data feeds are different.

# Note: For Data, please reach out to me at simranpalkohli07@gmail.com

