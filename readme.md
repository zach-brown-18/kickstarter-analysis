# Optimize Your Kickstarter Campaign

• Dataset of 42,000 Campaigns from May 2009 to July 2012  
• Recommendations based on two key factors:  
    • Success rate of campaigns  
    • Average amount pledged  

In short, the analysis of this dataset yields the following recommendations.
## 1) Keep Campaigns Short - 30 days or less
## 2) Music is the safest category, Design is the highest paying category
## 3) Set a Goal of $4-6k
## 4) Focus marketing on increasing the number of backers - Even if they pay less

### 1) Keep Campaigns Short - 30 days or less
The data shows a clear trend: Shorter campaigns are more likely to succeed.  
    • Pearson Correlation Coefficient: -.875  
This is due in part to the positive correlation of a campaign's goal to the planned duration.  
![Duration Success](/images/success_rate_by_duration.png)  
The average amount pledged peaks around 45 days. Thus if a project requires more funding and has a strong social media / marketing presence, the 45 day duration may be worth the risk.  
![Duration Pledged](/images/avg_pledged_by_duration.png)  

### 2) Music and Design
The category you choose affects your chance of being funded, as well as how much you will raise.  
    • Fashion campaigns secure funding less than 35% of the time  
    • Nearly 70% of Music and Theater campaigns succeed  
![Category Success](/images/success_rate_by_category.png)  
Games and Design categories offer the highest earning potential. These are higher risk, as campaigns in these categories succeed 20% less often than Music and Theater campaigns.  
![Category Success](/images/avg_pledged_by_category.png)  

### 3) Set a Goal of $4-6k
The goal for a campaign depends largely on the specific project's needs.  
The goal of $4-6k is a safe bet that guarantees both  
    • A high success rate of 57-65%
    • A significant profit from the campaign ($5070-$7600)
![Category Success](/images/success_rate_by_goal.png)![Category Success](/images/avg_pledged_by_goal.png)  

### 4) Reach as Many People as Possible
The success of a campaign grows rapidly as the number of backers increase.  
![Category Success](/images/success_rate_by_backers.png)  
    • A campaign with 20 backers has a 62% success rate  
    • 40 backers yields 87% success rate  