# Web-Traffic-Analysis

## Summary
* Analysed Google Analytics data to identify the key drivers behind decreasing web traffic and its impact on sales for a client.
* Recommended focusing marketing efforts on primary traffic source and valuable customer segments. Developed a cross-selling engine in R to increase average transaction value.
* Including snippets of code in this ReadMe file instead of the code file as parts of the code contains confidential information.


## Methodology
* This was a real-life consulting project, a group work which we met up with the CEO and staff to understand how their business operates and the exisiting challenges they were facing. After a series of research and analysis using data on Google Analytics which we were authorised access to, we discovered that there was a decreasing trend of web traffic and conversion and hence decided that it would be an insightful scope to look into their ecommerce platform.
* From there, we tried to make sense of the data, understand the reasons behind declining web traffic and ecommerce sales to provide some suggestions of improvement. Research on other market competitors that has an ecommerce page was also taken into consideration before recommendations were formulated.
* Unless otherwise mentioned, all of the data used in this markdown file was extracted from Google Analytics across the period from 1 Aug 2021 to 31 July 2022.
* Data was cleaned and wrangled in R and ggplot2 package is mainly used to create the visualisations.
* The parts which I was mainly in charge of is highlighted below.


## Project Highlights

### Analysis of Main Traffic Sources

From this chart, we can see that the channels that brought the most users are:
  * Social
    * The social media platforms that they have been using has been effective in bringing potential customers to the website.
  * Direct
    * This is pretty concerning as direct channel usually refers to unknown sources, implying that data might not have been complete.
  * Paid Search
    * This could suggest that the keywords bidded were effective
   
 
<img width="825" alt="image" src="https://github.com/tltxyyy/Web-Traffic-Analysis/assets/69724535/828e69ea-c3a9-429c-b31e-7ca8c74585d8">

If we looking into the user mix by source, we observe that Facebook, paid search and organic search are the most valuable sources which bring people into the website.

<img width="645" alt="image" src="https://github.com/tltxyyy/Web-Traffic-Analysis/assets/69724535/5e219de4-4950-4cd9-b925-0791815fe0fe">
   
### Web Traffic Trend

From the chart, we observe a decreasing trend of users visiting the website across the past year.
<img width="850" alt="image" src="https://github.com/tltxyyy/Web-Traffic-Analysis/assets/69724535/d5959ecf-f55a-40e9-8a65-ededf264ee51">

#### Deep Diving into the Trend of each Channel
If we look into the trends of each channel, it can be observed that the channels causing the decreasing trend were three channels: Paid search, Organic search and Social. After investigating into the random spikes in April and June 2022 caused by the “Referral” channel, it was discovered that they were glitches in system. This further defines the declining trend if we remove the erroneous data points of these random spikes.
<img width="863" alt="image" src="https://github.com/tltxyyy/Web-Traffic-Analysis/assets/69724535/eae777e6-401f-4fa9-bc5e-18c11131038e">

Zooming into the three channels identified to be causing the decreasing trend, we can see that paid and organic search has been gradually decreasing and users that came from social channels from periodical updates do not spike as high anymore.
<img width="836" alt="image" src="https://github.com/tltxyyy/Web-Traffic-Analysis/assets/69724535/4aac9d0b-03ee-4469-bf1f-6828216ebed0">


### Customer Conversion Analysis
Recalling that Facebook is the top source that brings users into the website, the conversion however is not living up to the potential customers it brings in relative to paid and organic search.

<img width="510" alt="image" src="https://github.com/tltxyyy/Web-Traffic-Analysis/assets/69724535/c789ca5b-3a04-4681-bca8-96f8dc6e86e6">

<img width="722" alt="image" src="https://github.com/tltxyyy/Web-Traffic-Analysis/assets/69724535/6a8e262f-c1d3-4fb2-a2e8-5222370890da">


#### Understanding Users from Facebook
To understand the role of Facebook in this ecommerce business, we also looked into the top transaction conversion paths shown in GA, whereby we only spot “social network” in the 35th most common conversion paths. This explains the insight that we have found previously where although the social channel brings in the highest volume of users, it does not bring in high transactions. Rather, it acts as an assisting role in the user’s conversion path. As we see here, this path means that the user came in from social network, exit then came in again from referral channel and made a purchase. Its inherent value is therefore in bringing in high traffic, build brand awareness and in assisting users to convert to customers.

<img width="210" alt="image" src="https://github.com/tltxyyy/Web-Traffic-Analysis/assets/69724535/3d320bb7-5388-4e96-b54c-da4a769f1190">


Hence, the solution we formulated to tackle the problem of decreasing traffic in Social channel is to create a facebook exclusive promo code. On top of the fact that it manifests great potential in assisting conversions of users to customers, Facebook has the highest concentration of users which are classified as “deal seekers” as shown in the chart below.

<img width="450" alt="image" src="https://github.com/tltxyyy/Web-Traffic-Analysis/assets/69724535/13c317e3-d33b-4a15-a183-babc11b87013">

With exlcusive discount codes only on Facebook, it will incentivise customers to find the coupon code on Facebook page, indirectly drive traffic to Meatlovers’ Facebook site. Moreover, customers will feel like they are earning an exclusive discount of great value, encouraging customers from Facebook to make a purchase.


### Cross-selling engine

engine that is intuitive and easily usable by the company even after the project
