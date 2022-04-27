# Final_Project

This repo is about the how Covid-19 has affected the football(soccer) industry in terms of team wins and social media engagement.

Note: In order to run the codes, all files are in the inputs under data folder. The path in order to read the Datas must be changed as I have them linked with my desktop so make sure to change the path before running the codes.

The following code's paths need to be changed:
1. early <- read.csv("C:/Users/deeps/Desktop/STA304 Final project/1920.csv")
2. later <- read.csv("C:/Users/deeps/Desktop/STA304 Final project/2021.csv")
3. twitter_engagement <- read.csv("C:/Users/deeps/Desktop/STA304 Final project/Twitter-Engagement-Pre-PostCovid.csv",stringsAsFactors=FALSE)
4. twitter_postsJulyDec2020 <- read.csv("C:/Users/deeps/Desktop/STA304 Final project/Twitter-EngagementJuly-Dec2020.csv", stringsAsFactors=FALSE)
5. PRECOVID <- read.csv("C:/Users/deeps/Desktop/STA304 Final project/wins1920.csv", stringsAsFactors=FALSE)
6. comp <- read.csv("C:/Users/deeps/Desktop/STA304 Final project/comp.csv",stringsAsFactors=FALSE) %>% filter(Comp =="Premier League")

It is organised as follows:

Abstract: Gives a general overview of the paper

Introduction: This section talks about what the paper is about and what results we expect to learn from this paper.

Scope of the Report: This section introduces our 2 main research questions which we will answer throughout our paper

Data collection: This section provides with the tools used to collect the data. A bunch of website was used to put together this report.

Exploratory Data Analysis: This section is divided into two subsection which will mention briefly the 2 research questions we have mentioned.

Results and Methodology: This is the main section where we see visuals such as graphs and table in order to prove our research questions. The section is divided into 4 subsections which some subsections are divided into more mini subsections. This part of the paper is the most important as it will answer all the questions you may have regarding the topic.

Conclusion: Finally, this question will give a briefly summary of the results found from the previous section and provide future implements which could help in making this report much better. 

References: The paper ends with mentioning all the references used which were needed in order to put this paper together.