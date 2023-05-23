# Big-data-project-Is twitter data a credible source of info for educational trends 

This project focuses on analyzing a collection of Twitter data related to education to determine if Twitter can be considered a credible source of information reflecting emerging trends in the field. The dataset consists of approximately 100 million tweets (around 500GB) collected on topics such as education, schools, universities, learning, and knowledge sharing. The objective is to identify spikes in Twitter activity and shifts in geographical distribution in relation to important educational topics, such as the "Florida math book ban." The analysis aims to determine whether higher tweet volumes indicate the emergence of new hot topics in education or if they are related to other events like sports, viral social media posts, university application cycles, or admissions.

The project also involves profiling the Twitter users (referred to as "Twitterers") who tweet about K-12 or higher education. The analysis aims to identify the types of organizations represented among these Twitterers, such as government institutions, universities, credible non-profit organizations, news outlets, social media influencers, or individual users discussing their experiences with schools, teachers, applications, and attitudes toward education. Additionally, the project examines the originality of the tweets and assesses whether messages are predominantly unique or if users tend to copy and retweet existing content.

Data Access
The Twitter data is stored in Google Cloud Storage at the following location: gs://msca-bdp-tweets/final_project. The data comprises individual JSON files, which need to be combined to create a consolidated dataset. The dataset consists of around 100 million tweets, totaling approximately 500GB. The tweets are focused on education-related topics, but only a subset of them is directly relevant to primary, secondary, or higher education.

Project Steps
To complete the project, the following steps were followed:

Discarded irrelevant tweets: Tweets that were not related to education were filtered out using a combination of exploratory data analysis (EDA) and relevant keywords.
Performed thorough EDA: Exploratory data analysis was conducted to identify the variables that could be used to profile the Twitterers. Some variables with limited data were discarded.
Identified prolific/influential Twitterers: The most active and influential Twitterers were determined based on their tweet volumes and retweet counts. Differentiation was made between original content creators and users who primarily retweeted others' messages.
Determined Twitterers' profiles: Twitterers were categorized into different types of organizations, such as government entities, universities, schools, nonprofit organizations, news outlets, or social media influencers.
Visualized tweet/retweet volume distribution: Visualizations were created to demonstrate the distribution of tweet and retweet volumes based on the types of organizations represented among the Twitterers.
Analyzed Twitterers' locations: The geographical distribution of Twitterers was determined, and any relationship between the emergence of new educational issues and the progression and locations of these Twitterers was examined. The geographical distribution was visualized.
Analyzed tweet timelines: The timelines of the tweets were studied to identify significant peaks and valleys in Twitter activity. An assessment was made to identify any data collection gaps.
Visualized tweet timelines: Visualizations were created to display the timelines of the tweets, highlighting any notable patterns or trends.
Assessed message uniqueness: The uniqueness of the tweets was evaluated by analyzing whether they were mostly original or predominantly copies of the same text. Techniques such as Jaccard similarity, cosine similarity, simhash, or minhash were employed to measure uniqueness and similarity.
Visualized message duplication: Visualizations were generated to illustrate the level of message duplication among different groups of Twitterers, such as government entities, health organizations, news outlets, social media influencers, and others.
Performed analysis on Twitterer profiles: The focus was on analyzing the profiles of Twitterers rather than the actual text messages of the tweets.
