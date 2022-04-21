# Mobile Apps Exploratory Data Analysis

Team member: Archit Agarwal, Varun Gupta, Sheetal Pasam, Phuong Tran, Pankhuri Tyagi, Sricharan Sridhar

## Business problem
Assist our client with a better understanding of the mobile application market as they consider entering this potentially lucrative space. As a team, our job is to investigate and draw insights from data on the market, and present to our client with a well-structured narrative (supported by analysis) in order to assist them in developing a plan to enter this market.

## Execution and Output
In order to provide our client with the best strategy for the mobile application market, we conduct exploratory data analysis on the data crawled from major app stores, which includes features such as device type, app ranking, region, developer, rating count, category, and whether the apps have in-app advertisements or purchases.

In order to measure the success of apps, we wanted to measure user-engagement (proxied by number of ratings) and quality of engagement (proxied by average rating). Currently, we have separate measures for both in our data, which intuitively demands a new success metric that combines the two. Hence, we added a new metric leveraging these features, the Bayesian Average Rating, to create a more reliable comparison between apps. This metric affects apps with low rating counts much more than those that have a higher rating, ensuring that apps with lower rating counts have less weight in the ranking

Our analysis starts with exploring the Category variable. Among all categories, we saw that the Education category has the most potential due to a high Bayesian Average and a low number of total apps, which creates less competition.

When categorizing by region, we find that the US market is more viable for the client than the China market owing to the higher user engagement and lesser competitors.

Next, our team narrowed down our approach by analyzing the type of app store. Based on the data, Google Play would be the most profitable space to enter due to the established user base of applications and relatively small number of competitive developers.

Lastly, we want to determine which types of apps (free or paid) would be the best for our client. Within the Education category in Google Play, the user engagement of free apps is higher than that of paid apps while the Bayesian average rating of free apps is slightly lower than that of paid apps. We believe that clients can start with a free app and then move to in-app purchase afterwards. External research conducted by the Gartner Research Group shows that 24% of users are more likely to interact with in-app purchases over an upfront paid app, making this freemium model the ideal approach.

In addition, in order to effectively break into this market, the client should introduce an app with an average file size of approximately 29.3mb, along with seven screenshots as this is the general trend in the market.

##  Implications and recommendations
Based on the findings from the data, we can conclude that the ideal application in the current marketplace is a freemium educational application on the Google Play store. In addition, our client should primarily focus on the US market as the entry point for their participation in the mobile application market. Selecting these key areas will help ensure that the client’s application enters the marketplace in an advantageous position, ensuring that they will be a visible competitor for their area and gradually gain a dedicated customer base within the category.

We recommend that our client should gather additional information regarding Educational apps to determine the optimal content for their prospective audience. Combined with our preliminary analysis, the strategy will ensure a successful launch of the new application

*Due to restrictions, the data and graphs in the Data Exploration and Execution and Output part have been removed from the analysis. However, very brief description of each graph has been provided so readers can follow along. Approval from instructor has been granted.
