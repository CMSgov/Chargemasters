# Chargemasters
**The Chargemaster.csv will come with the following headers:**

CCN - CCN of the hospital (allows for one file to detail several hospitals or sub-facilities)
NPI - NPI of the hospital (allows for one file to detail several hospitals or sub-facilities)
HPID - "master" if this is the Charge data is the "master", otherwise this is the HPID of the respective payer
Charge_Code - The internally specified Charge Code
Charge_Code_Description - A short clinical description of the charge without abbreviations whenever possible
Code_Source - HCPCS/CPT/ICD Procedure/DRG
Code_Version - CPT is currently '4' ICD is currently '10' etc etc.
Code - The actual HCPCS or CPT or DRG etc etc
Price - The dollars and cents charged, without commas.. so 1500.00 not "1,500.00"
Price_Date - The Date this price was released in MM-DD-YYYY format
