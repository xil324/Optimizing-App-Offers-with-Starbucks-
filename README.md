# Optimizing-App-Offers-with-Starbucks-

This project analyzes Starbuck customers’ behaviors to learn how people make their purchasing decisions and how those decisions are influenced by promotional offers. Customer profile, promotions and customer purchasing events datasets are available for this analysis. 

There are three goals for this project:
1.	Identify a cohort whose purchasing decision is not affected by the promotional offers
2.	Build a classification model to identity cohort who will be most likely to purchase with promotional offers
3.	Identify an efficient way to send promotional offer to customer 

Dataset: 

profile.json
  The profile dataset contains 17000 Reward program users’ information with the following 5 fields: 
  1.	Gender (categorical): male, female, other, null 
  2.	Age (numeric): customer’s age; missing values are encoded as 118
  3.	Id (hash/string): customer id 
  4.	became_member_on: when customer became a member with Starbuck
  5.	income (numeric): customer’s income 

portfolio.json
  The portfolio dataset contains promotional offers sent during 30-day test period with the following 6 fields: 
  1.	reward (numeric): money awarded for the amount spent
  2.	channels: offer delivered through web, email, mobile and social
  3.	difficulty (numeric): money required to be spent to receive reward
  4.	duration (numeric): time for offer to be open, in days
  5.	offer_type (string): bogo (buy one get one), discounts informational
  6.	id (string/ hash): promotional offer id

transcript.json
  The transcript datasets contain 306648 offer events with the following 6 fields: 
  1.	person (string/hash): customer id
  2.	event (string): offer received, offer viewed, offer completed, transactions (not using offer)
  3.	amount(numeric): money spent in purchasing event
  4.	offer_id(string/hash): promotional offer id
  5.	reward (numeric): money gained from “offer completed” 
  6.	time (numeric): hours after start of test 
  
  Final results and detailed analysis can be found in the word document, "Optimizing App Offers with Starbucks "
 
