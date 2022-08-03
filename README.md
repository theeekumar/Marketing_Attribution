##### Analyze Data with SQL - Code Academy 
# Project Assignment: Marketing Attribution

[Link to Google Slides presentation](https://docs.google.com/presentation/d/177hfmA2fJo9tM9HU_Mg1L1TtqHbMqSeXTRuuMiDJj_0/edit?usp=sharing)
## Overview
CoolTShirts, an innovative apparel shop, is running a bunch of marketing campaigns. CoolTShirts sells shirts of all kinds, as long as they are T-shaped and cool. Recently, CTS started a few marketing camapigns to increase website visits and purchases. By using touch attribution, CTS would like to map their customer's journey: from initial visit to purchase.

In this project, you'll be helping them answer these questions about their campaigns:

**1. Get familiar with the company.**
- How many campaigns and sources does CoolTShirts use and how are they related?
- What pages are on their website?

**2. What is the user journey?**
- How many first touches is each campaign responsible for?
- How many last touches is each campaign responsible for?
- How many visitors make a purchase?
- How many last touches on the purchase page is each campaign responsible for?
- What is the typical user journey?

**3. Optimize the campaign budget.**
- CoolTShirts can re-invest in 5 campaigns. Which should they pick and why?

The dataset for this project consists of one SQL table, page_visits, which features five different columns:
- user_id: A unique identifier for each visitor to a page
- timestamp: The time at which the visitor came to the page
- page_name: The title of the section of the page that was visited
- utm_source: Identifies which site sent the traffic (i.e., google, newsletter, or facebook_ad)
- utm_campaign: Identifies the specific ad or email blast (i.e., june-21-newsletter or memorial-day-sale)
