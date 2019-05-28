# Eskwelabs Capstone Proposal 1

## Milestone 1 (05/27)

### What is the question you hope to answer?

Government are now using social media to manipulate public opinion on national issues. Having the knowledge if a specific account is being used to spread a biased message might help increase self-awareness of other social media users to let them form their own opinion on the issue.

"Is this Twitter account a troll?" is the question I want to answer.

### What data are you planning to use to answer that question? What do you know about the data so far?

Social media has a broad scope. For my capstone, I want to limit my project to focus on Twitter only.

Tweets, replies, mentions, and who a user follows are public by default. Those data can be pulled from the official Twitter API. I can collect and store it in a database for data processing and analysis.

Things I initially plan to look out for:
- Which account does this account follow?
- Which account does this account usually replies to? 
- What is the profile's posting schedule?
  - Does it have a pattern of posting on specific time period (e.g. 9:00 AM to 6:00 PM, doesn't post on weekends, etc)?

Additional data on twitter accounts can by added manually to increase likelihood of correctness.  This data will include the following:  
- Is this account is pro-government, anti-government, or neutral? 
- Is this a public official's account?
  - Which political party does the account belong to?

At the end of the analysis, the tool will output a score on confidence on how likely a particular accounts is an internet troll.

Overall goal is to provide a trustworthy tool to quickly check if a Twitter account is a likely an internet troll. 


### Why did you choose this topic?

Knowing is half the battle. Not everyone even knows that social media trolls exists. If a tool is readily available to check an account, people who know will be able to produce a more informed opinion.



