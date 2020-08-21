# BuildWithAI_2020
Winners of NLP Challenge in HackMackers- BuildWithAI hackathon
Team: Infodemic Warriors
Title: What is in a tweet?

Sharing all the code used for the HackMakers - BuildWithAI hackathon.

Note: This code is clumsy since it is quickly written in one day for tha hackathon.

Theme: We are not just fighting a pandemic but an Infodemic too!

Solution:

Utilize Natural Language Processing (NLP) to assess the tweets of media and influential personalities on Twitter and identify how they influence public sentiment

Understand public perception and the influence of misinformation on public sentiment to
* Help Policymakers with data-driven decision making to introduce checks and balances to curb the spread of misinformation
* Inspire Media and influential personalities to be cognizant of their influence and share the right news
* Wake-up General Public to be more conscious about their new consumption.


## What is the process and what are part of the final Solution?

* Scope and Use Case Definition
* Data gathering
* Data pre-processing
* Analyzing data for sentiment and tonality
* Data Visualization using Tableau
* Insight Gathering

NLP process Involved:
 * Data Preprocessing
 * Bert based Semantic Search

## Bert based Semantic Search

* We identified key global events, public fears and conspiracy theories during the time frame of June 26, 2020 to July 27, 2020
   * Global Events: Trump supporting and wearing a mask publicly
   * Public Fears: Mental health, new corona way of living
   * Conspiracy theories: 5G linked to COVID mishap and conspiracy around Bill Gates
* Prepared Topic query phrases and words
* Generated BERT sentence embeddings for both tweets and topic queries
* Perform Semantic Search of tweets by estimating their Cosine similarities.
* Tweets with similarity scores greater than 0.4 to the query embedding are considered belonging to the topic.
 
Our final Dashboard
https://riponcs.github.io/Contest/index.html
