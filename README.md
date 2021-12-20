# Mobile-App-Research-Survey

<br><h2>Team 15 : Unsupervised Learning Team Analysis</h2>
<h4>DAT-5303 | Machine Learning</h4>
By: Alliyah Thompson, Belinda Darko, Jian Li, Khoa Le <br>
Hult International Business School<br><br><br>

# EXECUTIVE SUMMARY

The dataset below will be analyzed by our team to asset the behavior of mobile app users using PCA, Scree plots, Clustering, Dendrogram, and Boxplots. <br>The dataset is based on survey answers of a sample of 1552 people, varying in age and technology knowledge. There were initially 88 columns with 16 questions with multiple parts. The questionnaire was divided into three groups psychometrics (agree – disagree), behavior and demographics. From these groups, we were able to build personas to create a marketing strategy for the department.  <br>



<strong>Insights derived from our analysis of mobile app behavior:</strong> 

<strong>Majority of our samples have these demographical traits:</strong> 
- Part of the younger segment between 18-34 years old
- College graduates
- Mostly married, but a good number are also single
- Evenly distributed between having children vs. not
- Majority of our sample identify as White or Caucasian, followed by Black or African American, Other race and Asians. 
- Evenly distributed in identification as Hispanic/Latino vs not.
- Evenly distributed between male and female, however females dominate slightly.
- 50 % have the income range from 0 to 59,999 dollars, where the many of the respondents specifically have the income range of 40,000 - 49,999 dollars.

<strong>Regarding mobile behavioral traits, the following was deiscovered:</strong> 
- Many own an iphone compared to other smartphone devices
- They use apps such as music & sound identification, gaming, social networking (i.e. Facebook), and general news (i.e., Yahoo! News)
- People had a range of different number of apps as well as apps that are free to download
- 50 % of the mobile users very frequently visit Facebook & Youtube, sometimes Netflix, rarely Twitter and never MySpace

<strong>Further analysis helped us identify the following personas with 6 clusters in each group:</strong> 

<strong>Mobile app behaviors:</strong> 
Old World, Nostalgic, Social Light, The Golden Era, Anti-Social Media, Teenage Years and The Baby Boomer Mix.

<strong>Mobile app psychometrics:</strong> 
Uncaring About Tech, Mixed Emotions, Dominating, Old School Edition, Bougie & Uninterested in Tech, Bargain Shoppers.

<strong>Recommendations below are based on insights we identified from personas relating to various clusters:</strong> 
- We would recommend the marketing department to focus on personas that correlate to those who connect with the 'Old World' and 'Nostalgic' patterns. They should create personalized experiences that help brands reconnect to these personas through mobile app development.<br><br>

- Furthermore, data reveals that the demand is high for luxury brands, and therefore we suggest targeting 'Bougie & Uninterested in Tech' & 'Bargain Shoppers' to gain higher revenue from this segment. This can be done by ensuring easier app navigation for the consumers that are not interested in tech to help alleviate the technological advancements that apps might have. Also, when creating promotions, it is recommended to pitch these discounts and sales to this target audience. <br><br>

- Mobile apps related to technological development, updates, news publications, and new devices should also be marketed to those who identify with the Old World and Nostalgic. These groups also have a higher correlation to education which is why they are the perfect target for this type of marketing. <br><br>

- Our last recommendation would be to target those who are in their teenage years. Moreover, these personas are typically iPhone users, which should be observed for specific targeting methods. Additional, focus should be emphasized on those who identify as White or Caucasian, because of the high value count. <br><br>


<strong>Behavioral Question Analysis:</strong><br>
The following survey questions are based on samples having 50% agreeance to the alternatives presented if a * is present: 
 
-	Question 2: Many of our samples from our survey own an iPhone compared to other smartphone devices. * 
-	Question 4: Majority of our samples use the following apps such as music & sound identification, gaming, social networking (i.e. Facebook), and general news (i.e., Yahoo! News). * 
-	Question 11: The answers to this question reflect an even distribution for the number of apps that people have. 
-	Question 12: Of the apps that were free to download, the survey shows an even distribution. 
-	Question 13: This question revealed that 50 % of the mobile users very frequently visit Facebook & YouTube, sometimes Netflix, rarely Twitter and never MySpace.
<br><br>
 
<strong>Psychometric Question Analysis:</strong><br>
The following questions are opinion-based questions that are answered with a scale from strongly agree to strongly disagree. 
-	Question 24  
-	Question 25 
-	Question 26 

<strong>Value Count Analysis of Demographics:</strong><br>
- The value count above show that most people in the survey are in the age group of 18-24, 25-29 and 30-34 years old.

- Moreover, people are mostly college graduates or have some college degree.

- Most survey respondents are married, however a good amount of people are also single in the dataset.

- Many respondents are in the Caucasian racial group, where most do not identify as Hispanic/Latino.

- As we saw in the descriptive statistics that 50 % have the income range from 0 to 59,999 dollars, many of these have specifically the income range of 40,000 - 49,999 dollars.

- Lastly the dataset is quite dispersed between male and female, where female dominates.

# Principal Component Analysis
Below is an analysis of the principal component analysis for mobile behavior and psychometric questions of the survey.

<strong>Mobile Behavioral:</strong><br>
We initially ran a PCA with ‘none’ n_components to determine the location of the elbow in our scree plot. After debriefing <br>and analyzing the location, our team decided to stop at 7 in our plot for behavioral questions. 


#<strong>Mobile App Behavior Scaled Personas - Dictionary:</strong><br>

PC 0 = Old World<br>
Our sample shows that this group utilizes apps for entertainment, television shows and television check-ins. Most of these users have an iPod touch and tablet, with fewer users having an Android product. Additionally, these people use apps like Twitter, Vevo, Last.fm,  AOL Radio, Yahoo Entertainment & Music, and Myspace.  <br><br>
PC 1 = Nostalgic<br>
#This group can be Blackberry, Nokia, and Windows Phone or Mobile device users. They prefer smartphones over tablets. They do not like to use Music and Sound, television shows, and gaming apps. Some of their most frequent apps are Myspace and YouTube. <br><br>
PC 2 = Social Light<br> 
#The majority have iPhones in the sample size. They do not like using gaming and social networking apps like Facebook, in fact they rarely use Facebook. The respondents said that approx. 26 % - 50 % of the apps where free to download. <br><br>
PC 3 = The Golden Era  
#This group of people use Nokia, Windows Phone or HP smartphones and rarely visit IMDB. <br><br>
PC 4 = Anti-social media<br> 
People in this survey’s group prefer using Android phones, and almost all of them do not own BlackBerry. In addition, they do not spend their time using Social Networking Apps (such as: Facebook, and Instagram). They stated that they almost never use Facebook. <br><br>
PC 5 = Teenage Years<br> 
Most of the users in the survey own phones named Nokia and BlackBerry. They love to use Music and Sound Identifications, but they do not prefer using Entertainment Apps (I.e., U2) and TV Show Apps (I.e. Glee). They also do not use Shopping Apps, General News Apps, and Specific Publication News Apps. However, they sometimes listen to Pandora Radio, and they rarely use Yahoo Entertainment and Music. <br><br>
PC 6 = The Baby Boomer Mix<br>  
#The people in this group do not use iPod touch devices. They do not like using Gaming Apps, but they love reading news by using Specific Publication News Apps (such as: New York Times). Furthermore, they use other apps in their spare time. The survey showed that the people in the group rarely watch YouTube, but they very often use LinkedIn. <br><br>


<h3><strong>Mobile Psychometrics PCA:</strong><br></h3>
For our second analysis, we also ran a PCA with ‘none’ n_components to determine the location of the elbow in our scree plot.<br>Based on our findings, our team decided to stop PCA at 5 in our plot for psychometrics questions. 

<strong>Mobile App Psychometrics Personas - Dictionary:</strong>

PC 0 = Uncaring about the world of Tech  
#Our sample has a consistent belief and disagrees with all statements from the survey. They are not tech savvy or knowledgeable, and therefore do not care about apps or devices.<br><br>
PC 1 = Mixed Emotions<br>
#Our sample shows that although people like to stay updated with technology, they try to create a balance between having too much technology in their everyday life. Although they like to have access to technology for information purposes, they still would like to have privacy. Therefore, they prefer not to communicate with friends and family on social media. These people are very active, and, on the go, which is why they do value mobile access.<br><br>
PC 2 = Dominating, Old School Edition<br>
#People agreed with most of the statements from the survey, with a few exceptions. People in this group do not enjoy buying new gadgets and appliances. However, they think that everyday life is filled with a large amount of technology, such as the internet. Additionally, they agree that sites like Facebook provide too much information. From a personal standpoint, they view themselves as an opinion leader. They also prefer to stand out from the crowd and take the initiative when it comes to making decisions. In addition, they enjoy being in control and a risk taker. They think that they are active people who are always on the move, therefore they are always pressed for time.<br><br>
PC3 = Bougie & Uninterested in Tech<br>
The people in this group are more likely not to care about technological development. Therefore, many people do not ask their advice when they are looking to purchase technology or electronic products. They prefer to purchase luxury products and designer brands rather than electronic devices. These people do not like being controlled by technology, therefore their lack of interest. <br><br> 
PC 4 = Bargain Shoppers<br>
Most people in this group love purchasing new gadgets and appliances. They do not think that the internet makes it easier to stay connected with family and friends. In addition, they are the first of their friends and family to try new things and they would rather be told what to do. They are always on the lookout for a bargain, discounts or deals and they derive enjoyment from any kind of shopping. Moreover, they do not buy brands that reflect their style. Moreover, they do not think that it will be worth spending a few extra dollars to get extra App features.  

# Agglomerative Clustering

Below is an analysis of our personas clustered into groups to gain insights and recommendations on the personas mentioned above.
Based on the PCA score after exporting our findings, we created the following names by behavioral personas. 

<strong>Mobile Behavior Persona:</strong><br>
Based on our centroids, our team can interpret how personas stand out based on behavior: 

- <strong>Cluster 1:</strong> Group 0 has mostly ‘Anti-Social Media’ and ‘The Golden Era’ Personas.  

- <strong>Cluster 3:</strong> Group 2 stands out the most because they feature all the personas with a mix of ‘Old World’, ‘Nostalgic’, ‘The Golden Era’, and ‘Teenage Years’.  

- <strong>Cluster 4:</strong> Group 3 has a unique interpretation as they are younger and fall into the ‘Teenage Years, and ‘Social Light’.But they have more interest in social media, however the data is insufficient.  

- <strong>Cluster 5:</strong>  They identify with ‘Old World’ and ‘Nostalgic’ behavioral personas. These personas oppose ‘The Golden Era’.  

- <strong>Cluster 6:</strong> Group 5 is a combination of personas, based on the coefficients showing that they are not in their teenage or baby boomer years by their behavior. However, they are more likely to be in their 30s - 40s as their behavior connects with ‘Nostalgic’ and ‘Social Light’. 

<strong>Mobile Psychometrics Persona:</strong><br>
Based on our centroids, our team can interpret how personas stand out based on their opinions and beliefs: 

- <strong>Cluster 1:</strong> Group 0 aligns more closely with ‘Uncaring About Tech’ persona.  

- <strong>Cluster 2:</strong> Group 1 is filled with mixed persona types based on our results, however, they are not ‘Bargain Shoppers’ as they prefer more luxury brands.  

- <strong>Cluster 3:</strong> Group 2 personal beliefs align more with ‘Bougie & Uninterested in Tech’, but there also ‘Bargain Shoppers’. Therefore, they love to purchase luxury brands at low prices.  

- <strong>Cluster 4:</strong>  Group 3 can be classified are mostly ‘Uncaring About Tech’ and ‘Dominating, Old School Edition’. These people tend to love and imagine the Old School Era because they do not like to be immersed into modern technology developments.  

- <strong>Cluster 5:</strong> Group 4 is very similar to group 3, as they align with the same values and are also ‘Bargain Shoppers’.  

# Boxplot Analysis

<strong>Analysis of Income vs Mixed Emotions</strong><br>
- Cluster 5 which are ‘Old World’ & ‘Nostalgic’ are highlighted most often throughout the boxplot as they have various ranges in income. However, they stand out in the 10,000 to 14,999 dollar group for income. <br><br>

- Those who have ‘Mixed Emotions’ can also be categorized in Cluster 3 who have the traits of being ‘Bougie & Uninterested in Tech’ & ‘Bargain Shoppers’. The dispersion in this group is small. People in this cluster commonly have an income of 20,000 to 29,999 or 60,000 to 69,999 dollars. 

<strong>Analysis of Race vs Teenage Years</strong><br>
- Cluster 3 stands out because it aligns with ‘Teenage Years’ behavioral personas. Most of these groups identify as White races.  

<strong>Analysis of Education vs Old World</strong><br>
- Many of these people identify with Cluster 3 meaning they have a mix of behavioral traits. Additionally, other people in this group who are not a part of cluster 3, are classified into cluster 5 who identify with ‘Old World’ and ‘Nostalgic’ behavioral traits.  
