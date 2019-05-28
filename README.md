# Eskwelabs Capstone Proposal 1

## Problem statement and hypothesis

Government are now using social media to manipulate public opinion on national issues. Having the knowledge if a specific account is being used to spread a biased message might help increase self-awareness of other social media users to let them form their own opinion on the issue.

Social media has a broad scope. For my capstone, I want to limit my project to focus on Twitter only.  Tweets and replies are public by default. On top of it, the availability of Twitter API makes is easy to collect data.

Things I initially plan to look out for:
- Which account does this account follow?
- Which account does this account usually replies to? 
- What is the profile's posting schedule?
  - Does it have a pattern of posting on specific time period (e.g. 9:00 AM to 6:00 PM)?
- Etc

Additional data on twitter accounts can by added manually to increase likelihood of correctness.  This data will include the following:  
- Is this account is pro-government, anti-government, or neutral? 
- Is this a public official's account?
  - Which political party does the account belong to?

At the end of the analysis, the tool will output a score on confidence on how likely a particular accounts is an internet troll.

Overall goal is to provide a trustworthy tool to quickly check if a Twitter account is a likely an internet troll. 
