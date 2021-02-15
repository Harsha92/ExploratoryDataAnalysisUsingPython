---
# **Table of Contents**


1. [**Introduction**](#Section1)<br>
 * 1.1 [**Reception**](#Section1.1)<br>
 * 1.2 [**Impact**](#Section1.2)<br>
   + 1.2.1 [**Scope**](#Section1.2.1)<br>
   + 1.2.2 [**Economy**](#Section1.2.2)<br>
2. [**Problem Statement**](#Section2)<br>
3. [**Python libraries**](#Section3)<br>
4. [**Solution Approach**](#Section4)<br>
5. [**Data Acquisition & Description**](#Section5)<br>

---
[![Facebook](https://img.etimg.com/thumb/msid-75184637,width-650,imgsize-432571,,resizemode-4,quality-100/facebook-ap.jpg "Facebook")](https://img.etimg.com/thumb/msid-75184637,width-650,imgsize-432571,,resizemode-4,quality-100/facebook-ap.jpg "Facebook")

---
<a name = Section1></a>
# **Introduction**
The world's most popular social networking web site, Facebook enables users to connect with friends and family by sharing status updates, personal photos and other items of interest. Founder [Mark Zuckerberg](https://en.wikipedia.org/wiki/Mark_Zuckerberg "Mark Zuckerberg"), along with fellow Harvard College students [Eduardo Luiz Saverin](https://en.wikipedia.org/wiki/Eduardo_Saverin "Eduardo Luiz Saverin"), [Andrew McCollum](https://en.wikipedia.org/wiki/Andrew_McCollum "Andrew McCollum"), [Dustin Moskovitz](https://en.wikipedia.org/wiki/Dustin_Moskovitz "Dustin Moskovitz"), and [Chris Hughes](https://en.wikipedia.org/wiki/Chris_Hughes "Chris Hughes") created Facebook in 2004 as a means for other university students to communicate and to socialize online. The idea quickly spread from there and has become a global phenomenon, with more than 160 million users in the United States alone. 


<a name = Section1.1></a>
## **Reception**
Facebook's rapid growth began as soon as it became available and continued through 2018.
Facebook passed 100 million registered users in 2008, and 500 million in July 2010. According to the company's data at the July 2010 announcement, half of the site's membership used Facebook daily, for an average of 34 minutes, while 150 million users accessed the site by mobile.
In October 2012 Facebook's monthly active users passed one billion, with 600 million mobile users, 219 billion photo uploads, and 140 billion friend connections. The 2 billion user mark was crossed in June 2017.
Facebook popularity as Active users of Facebook increased from just a million in 2004 to over 2.3 billion in 2018.

<a name = Section1.2></a>
## Impact

  <a name = Section1.2.1></a>
### Scope
A commentator in The Washington Post noted that Facebook constitutes a "massive depository of information that documents both our reactions to events and our evolving customs with a scope and immediacy of which earlier historians could only dream". Especially for anthropologists, social researchers, and social historians—and subject to proper preservation and curation—the website "will preserve images of our lives that are vastly crisper and more nuanced than any ancestry record in existence".

  <a name = Section1.2.2></a>
### Economy
Economists have noted that Facebook offers many non-rivalrous services that benefit as many users as are interested without forcing users to compete with each other. By contrast, most goods are available to a limited number of users. E.g., if one user buys a phone, no other user can buy that phone. Three areas add the most economic impact: platform competition, the market place and user behavior data.

Facebook began to reduce its carbon impact after Greenpeace attacked it for its long-term reliance on coal and resulting carbon footprint.[487]

Facebook provides a development platform for many social gaming, communication, feedback, review, and other applications related to online activities. This platform spawned many businesses and added thousands of jobs to the global economy. [Zynga Inc.,](https://en.wikipedia.org/wiki/Zynga "Zynga Inc.,") a leader in social gaming, is an example of such a business. An econometric analysis found that Facebook's app development platform added more than 182,000 jobs in the U.S. economy in 2011. The total economic value of the added employment was about $12 billion.

---
<a name = Section2></a>
# **Problem Statement**
Facebook has become quite popular in the recent few years with people all over the world using it as a medium to share their status,thoughts and pictures with their friends. With the mobile app , it has become even more popular and easier to access. People from all age groups are connected to facebook, however there are certain differences in their way of using it such as with respect to initiating friendships and sending likes . We are trying to study the dataset provided to identify certain patterns with respect to how the users are making use of this most popular social networking app depending on their age group,gender etc.

---
<a name = Section3></a>
# **Python libraries**
To do Data Science with Python, I use Python with the following software libraries:
- **Numpy:** it contains many functions for numerical computation (vectors, matrices, polynomials, etc.).
- **Matplotlib:** it allows to trace and visualize data in the form of graphs.
- **Pandas:** it allows to manipulate and analyze data (dataframes).
- **Seaborn:** it complements Matplotlib by providing attractive statistical graphics.

---
<a name = Section4></a>
# **Solution Approach** 
The problem was divided into several steps:
1. **Data Collection:** Data was collected in a csv file and here is the  [facebook data](https://raw.githubusercontent.com/insaid2018/Term-1/master/Data/Projects/facebook_data.csv "facebook data") which we used for analysis.
2. **Data Wrangling:** The datasets were uploaded to a dataframe and explored. Null values were filled in wherever appropriate and polluted values were discarded or wrangled.
3. **EDA:** Extensive data visualisation and summary statistics were used to extract insights and pattern from the data. 

---
<a name = Section5></a>
# **4. Data Acquisition & Description**
- After having the data available and understanding the meaning of each data items, I started the data selection phase, that is, the data I want to keep for my Data Science study.

Here are the data I want to keep:

|Id|Feature|Description|
|:--|:--|:--|
|01| userid                 | A numeric value uniquely identifying the user.|
|02| age                    | Age of the user in years.|
|03| gender                 | Gender of the user.| 
|04| tenure                 | Number of days since the user has been on FB.|
|05| friend_count           | Number of friends the user has.|
|06| friendships_initiated  | Number of friendships initiated by the user.|
|07| likes                  | Total number of posts liked by the user.|
|08| likes_received         | Total Number of likes received by user's posts.|
|09| mobile_likes           | Number of posts liked by the user through mobile app.|
|10| mobile_likes_received  | Number of likes received by user through mobile app.|
|11| www_likes              | Number of posts liked by the user through web.|
|12| www_likes_received     | Number of likes received by user  through web.| 
| 13  | age_group  | Derived from age column for analysis  |
