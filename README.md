# UNP-Machine-Learning-Project-Analysis-of-Bank-Marketing-Dataset-Classification

# About The Data

This data set contains records relevant to a direct marketing campaign of a Portuguese banking
institution. The marketing campaign was executed through phone calls. Often, more than one call
needs to be made to a single client before they either decline or agree to a term deposit
subscription. The classification goal is to predict if the client will subscribe (yes/no) to the term
deposit (variable y).

# Objective

Marketing plays a crucial role in the banking industry, as it helps to create brand awareness, attract
and retain customers, increase profitability, and drive business growth, and with an aim to
maximize profits and achieve customer satisfaction.

# Additional Variable Information
# Input variables:
   # bank client data:
   1 - age (numeric)
   2 - job : type of job (categorical: "admin.","unknown","unemployed","management","housemaid","entrepreneur","student",
                                       "blue-collar","self-employed","retired","technician","services") 
   3 - marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
   4 - education (categorical: "unknown","secondary","primary","tertiary")
   5 - default: has credit in default? (binary: "yes","no")
   6 - balance: average yearly balance, in euros (numeric) 
   7 - housing: has housing loan? (binary: "yes","no")
   8 - loan: has personal loan? (binary: "yes","no")
   # related with the last contact of the current campaign:
   9 - contact: contact communication type (categorical: "unknown","telephone","cellular") 
  10 - day: last contact day of the month (numeric)
  11 - month: last contact month of year (categorical: "jan", "feb", "mar", ..., "nov", "dec")
  12 - duration: last contact duration, in seconds (numeric)
   # other attributes:
  13 - campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
  14 - pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)
  15 - previous: number of contacts performed before this campaign and for this client (numeric)
  16 - poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")

  # Output variable (desired target):
  17 - y - has the client subscribed a term deposit? (binary: "yes","no")
