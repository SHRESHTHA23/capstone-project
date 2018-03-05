# capstone-project
Analysis of email marketing campaign dataset

1. Find the Click to Open Rate (CTOR)
A. Overall CTOR (use CLICK_FLG   and OPEN_FLG  column) 
B. CTOR by Gender (use I1_GNDR_CODE   column) 
C. CTOR by Time of the day (use mailed_date column) 
D. CTOR by Day of the week(use mailed_date column) 
E. CTOR by Month (use mailed_date column) 
F. CTOR by Lead’s Income Group (use TRW_INCOME_CD_V4 column) 
G. CTOR by Lead’s Ethnicity (use ASIAN_CD column) 
H. CTOR by Lead’s Household Status (use I1_INDIV_HHLD_STATUS_CODE  column


2. Household Members Information
A. Find count of leads with information about members of their household. If a  lead has information about 3 members, and another has information about 2  members and another has none, then the answer to this question is 2. (use statcd_hh_mem1  - statcd_hh_mem8     column)
B.  Find count of total number of household members information is available.For  example, if a lead has 3 household members, and another has about 2  members, and the other has none, then the totalcount of household members  is 3+2+0 = 5.
C. Find count of household members by type (Head of Household, Spouse etc.).
D. %age of household members type. For example, if there are 5 Head of  Household, 10 Spouse and 85 in the other categories, then the %age of  Spouses is10.

2. Household Members Information
E. How many known households havechildren? (use PRESENCE_OF_CHLDRN    column) F.   Overall, how many children are there? (use NUMBER_OF_CHLDRN_18_OR_LESS   column  and         PRESENCE_OF_CHLDRN )
G. How many of the children are male and how many are female? (use GNDR_OF_CHLDRN_0_3  - GNDR_OF_CHLDRN_13_18   column)
