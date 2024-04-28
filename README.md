# Web-Traffic-Analysis

## Summary
* Analysed Google Analytics data to identify the key drivers behind decreasing web traffic and its impact on sales for a client.
* Recommended focusing marketing efforts on primary traffic source and valuable customer segments. Developed a cross-selling engine in R to increase average transaction value.
* Including snippets of code in this ReadMe file instead of the code file as parts of the code contains confidential information.


## Methodology
* This was a real-life consulting project, a group work which we met up with the CEO and staff to understand how their business operates and the exisiting challenges they were facing. After a series of research and analysis using data on Google Analytics which we were authorised access to, we discovered that there was a decreasing trend of web traffic and conversion and hence decided that it would be an insightful scope to look into their ecommerce platform.
* From there, we tried to make sense of the data, understand the reasons behind declining web traffic and ecommerce sales to provide some suggestions of improvement. Research on other market competitors that has an ecommerce page was also taken into consideration before recommendations were formulated.
* Unless otherwise mentioned, all of the data used in this markdown file was extracted from Google Analytics across the period from 1 Aug 2021 to 31 July 2022.
* The parts which I was mainly in charge of is highlighted below.


## Project Highlights

### Analysis of Main Traffic Sources

<img width="373" alt="image" src="https://github.com/tltxyyy/Web-Traffic-Analysis/assets/69724535/51156d97-efd3-4050-87a9-e1a0c778d154">

From this chart, we can see that the channels that brought the most users are:
  * Social
    * The social media platforms that they have been using has been effective in bringing potential customers to the website.
  * Direct
    * This is pretty concerning as direct channel usually refers to unknown sources, implying that data might not have been complete.
  * Paid Search
    * This could suggest that the keywords bidded were effective

If we looking into the user mix by source, we observe that Facebook, paid search and organic search are the most valuable sources which bring people into the website.
<img width="527" alt="image" src="https://github.com/tltxyyy/Web-Traffic-Analysis/assets/69724535/0470ce9f-9e2e-4ad0-983c-29f4e86c68be">
   
### Decreasing Web Traffic Trend

<img width="845" alt="image" src="https://github.com/tltxyyy/Web-Traffic-Analysis/assets/69724535/35b40756-9b21-409c-9fc0-dc9b1c911ca7">

#### Deep Diving into the Trend of each Channel
From this chart, we can observed that the channels causing the decreasing trend were these three channels: Paid search, Organic search and Social. After investigating into the random spikes in April and June 2022 caused by the “Referral” channel, it was discovered that they were glitches in system. This further pronounces the declining trend if we remove the erroneous data points of these random spikes.
<img width="585" alt="image" src="https://github.com/tltxyyy/Web-Traffic-Analysis/assets/69724535/c12ea81b-0fdf-45fe-82c4-458a3a2cfe15">

Zooming into the three channels identified to be causing the decreasing trend, we can see that paid and organic search has been gradually decreasing and users that came from social channels from periodical updates do not spike as high anymore.
<img width="679" alt="image" src="https://github.com/tltxyyy/Web-Traffic-Analysis/assets/69724535/4a3e92a3-6f49-4b74-b501-54be3974237e">


### Customer Conversion Analysis
Recalling that Facebook is the top source that brings users into the website, the conversion however is not living up to the potential customers it brings in relative to paid and organic search.
<img width="544" alt="image" src="https://github.com/tltxyyy/Web-Traffic-Analysis/assets/69724535/8b00faa3-eae0-4afd-a175-a1f87f1708e5">

#### Understanding Users from Facebook
This reasoning is further supported by the top transaction conversion paths shown in GA, whereby we only spot “social network” in the 35th most common conversion paths. 
This shows that social channel does not bring in high transactions. Rather, it acts as an assisting role in the user’s conversion path. As we see here, this path means that the user came in from social network, exit then came in again from referral channel and made a purchase.
So its inherent value is in bringing in high traffic, build brand awareness and in assisting users to convert to customers.

<img width="207" alt="image" src="https://github.com/tltxyyy/Web-Traffic-Analysis/assets/69724535/4bf8f3e5-b33a-403b-8423-5ab8131f0098">


<img width="931" alt="image" src="https://github.com/tltxyyy/Web-Traffic-Analysis/assets/69724535/13c317e3-d33b-4a15-a183-babc11b87013">

