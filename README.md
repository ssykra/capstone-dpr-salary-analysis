# capstone-dpr-salary-analysis
# Analysis of Public Opinion on DPR Salary Issue
## Project Overview
This project analyzes public sentiment and opinion on the issue of DPR (Dewan Perwakilan Rakyat) members' salaries in Indonesia. The analysis is conducted using scraped tweets from X, focusing on discussions about DPR salary, performance, ethics, and transparancy.
The project leverages **IBM Granite** through Replicate API to classify and summarize the tweets into clear categories of sentiment and topics.

## Raw Dataset Link
Download Tweets Raw Dataset (CSV) [https://drive.google.com/drive/folders/1Rq1F62Zakn6W0wZrmGinI3MwSopIMcj1?usp=sharing]

## Insight & Findings
### Sentiment Distribution 
- Negative : 10 tweets (71%)
- Neutral : 3 tweets (21%)
- Positive : 2 tweets (14%)
**Overall, the majority of tweets show dissatiffaction, with only a small portion being neutral or positive**

### Key Topics 
- **Salary** : 8 mentions
  Main concern, with frequent comparison to citizens' income
- **Transparency & Ethics** : 4 mentions
  Issue about fairness and the integrity of DPR members
- **Tax Increases** : 3 mentions
  Complaints about higher taxes alongside DPR salary hikes
- **Performance / Work Ethic** : 2 mentions
  Criticism of DPR's contribution compared to their pay
- **Other (celebrity involvement, comparisons with other countries)** : 5 mentions
  Broader disvussions around context and public figures opinions

### Main Argument Types
- **Economic** : 7 tweets (50%)
  Salary levels, tex increases, and financial burdens on citizens
- **Ethical / Moral** : 5 tweets (36%)
  Corruption issues, fairness, and moral integrity of politicians
- **Political** : 3 tweets (21%)
  Presidential involvement, political motives, and accountability
- **Emotional** : 4 tweets (28%)
  Strong frustration, anger, and disappointment, with some calls for empathy

### Summary of Findings
The overall public sentiment toward DPR salaries is predominantly **Negative**. Most citizens perceive the salary levels as disproportionate compared to their economic reality. Ethical concerns arise from corruption-related issues, while discussions around tax increases amplify dissatisfaction. Emotional reactions further highlight frustration and distrust toward DPR members. 

### Policy Recommendations 
1. **Implement a transparent salary structure** for DPR members, aligned with national median income.
2. **Establish fair and strict anti-corruption mechanisms**, ensuring no privileges for individuals with corrupt histories.  
3. **Review tax policy changes with public consultation**, ensuring fairness and clear communication about benefits.

## AI Support Explanation
- **Model:** IBM Granite 3.3-8B Instruct via Replicate API.
- **Use Cases:**
  1. **Classification:** Categorizing tweets into Positive, Negative, Neutral, or Mixed.
  2. **Summarization:** Generating structured insights about main topics and arguments.  
- **Benefit:** Automates the sentiment analysis and topic extraction process, ensuring consistency and scalability in analyzing large-scale public opinion data.
