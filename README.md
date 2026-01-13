# Social Media Marketing Analysis

## Key Insights & Findings
High CTR (11.76%) and Engagement Rate (13.56%)
Low Purchase Rate (0.61%) and only 1.3K conversions out of 216K impressions
Strong awareness and engagements:
Target audience: Females between the ages 18 to 32 shows more interest in the ads.
Best ad format: Stories, Image, Carousel, and Video in that particular order.

Jump to Details Insight

Project Objective
The business needs a performance tracking report for advertising campaigns running on Facebook and Instagram. The report will provide visibility into campaign reach, engagement, conversions, and budget utilization.
This will enable the marketing team to:
• Identify the most effective platform (Facebook vs Instagram).
• Track campaign ROI and optimize budget allocation.
• Understand audience engagement patterns.

## Data Overview
This dataset represents Meta Ads Performance Data, covering campaigns, ads, user demographics, and ad interaction events. It is modelled after how Facebook/Instagram (Meta) ad platforms capture data.
The purpose of this dataset is to analyse advertising performance, optimize targeting, and measure ROI (Return on Investment) through KPIs such as:
• Impressions (how often ads are seen)
• Clicks (engagement with ads)
• Purchases (conversions)
• CPM, CPC, CTR, and ROAS (efficiency metrics)
• Audience insights (demographics, location, interests)
This dataset is ideal for building a Power BI Dashboard to evaluate campaign effectiveness, budget utilization, and user engagement patterns.

### Dataset Scope
In Scope:
O Campaigns running on Facebook and Instagram only.
Out of Scope:
o Other platforms (Messenger, Audience Network).
o Organic engagement (only paid ads will be included)

### Key Data Fields
Use of Each Table
Table 1: ad_events
• Stores event-level logs (like impressions, clicks, purchases).
• This is the fact table in the model because all KPIs are derived from events.
• Used to analyze when and how users interact with ads.
Table 2: ads
• Contains details of each ad creative.
• Defines targeting criteria and which campaign an ad belongs to.
• Used for platform-level and creative-type-level analysis (e.g., Facebook Video Ads vs Instagram Image Ads).
Table 3: campaigns
• High-level campaign strategy and budget allocation.
• Provides timeframe and budget for ads.
• Used to calculate cost-based KPIs (CPC, CPM, ROAS).
Table 4: users
• Stores demographic and interest information of users who interact with ads.
• Used for audience segmentation (gender, age, country, location, interests).
• Helps analyze targeting efficiency (are ads reaching the right audience?).

### Relationship Configuration
How the Tables Work Together
• ad_events → ads → Links events to ad details (platform, type, targeting).
• ads → campaigns → Links ads to campaign metadata (budget, duration).
• ad_events → users → Links user engagement events to demographic data.
This creates a star schema:
• Fact Table: ad_events
• Dimension Tables: ads, campaigns, users

Insert dimension table

## Key Insights and Findings

KPI Metrics
• Impressions: 216K: Total times the ads were shown. Good reach.
• Clicks: 25.4K: Number of people who clicked on the ads.
• Shares: 1.3K, Comments: 2.6K: Indicators of organic engagement (beyond paid
reach).
• Purchases (Conversions): 1.3K: Real customer acquisitions from ads.
• Engagements: 29K: Sum of clicks, likes, shares, comments.
• CTR (Click-Through Rate): 11.76%: Strong performance (above industry average
~1-2%). Ads are very attractive.
• Engagement Rate: 13.56%: Very healthy; content resonates with the audience.
• Conversion Rate: 5.21%: Out of all clicks, 5.21% converted into purchases. Good
but could improve with landing page optimization.
• Purchase Rate: 0.61%: Out of impressions, only 0.61% resulted in purchases. Low
conversion funnel efficiency (room to optimize)
Ads are performing strongly in visibility and engagement, but actual purchase
efficiency is weak: need to optimize targeting/landing pages.
• High CTR (11.76%) and Engagement Rate (13.56%) → clearly indicate that the ad
creatives, messaging, and targeting at the top of the funnel are very effective.
People are interested enough to click, like, share, or comment.
• Low Purchase Rate (0.61%) and only 1.3K conversions out of 216K impressions
→ shows a sharp drop-off in the lower funnel. This is a classic case of "awareness
and interest" being strong but "action (purchase)" being weak.

Engagement Breakdown
• By Gender (Donut Chart)
o Female: 13K (43%)
o Male: 6K (22%)
o Other/Not Specified: 10K (35%)
• By Target Age (Bar Chart)
o Peak engagement: 20–30 age group (especially early 20s).
o Drops significantly after 35+.
Primary audience = Young adults
Geographic Distribution
• Top Engaged Countries
o US, India, Brazil, Germany, UK are major contributors..
Insight: Focus campaigns in India & US (high potential, high engagement), and premium
campaigns in Germany/UK (better conversion potential due to higher purchasing power).
Time-Based Trends
• Weekly Engagement Trend (Stacked Bar)
o Fairly consistent across weeks, with no sharp drop.
o Steady engagement shows ads maintain attention.
Hourly Engagement Trend (Line Chart)
o Peaks around late afternoon & evening (~15–20 hours).
o Lowest engagement early morning (~0–5 hours).
Calendar View
• Engagements are mapped to days in June.
• Certain dates (like 19th–21st, 25th–27th) show higher highlights.
Campaign activity peaks on specific days, possibly due to launches/promotions.
Video ads have the highest CTR, CR, ER (best-performing).
Stories ads also perform strongly with higher impressions.
Images/Carousels have decent performance but slightly lower conversions.
Insight: Focus budget more on Video & Story ads for better ROI.
Analysis by Ad Type
Video ads have the highest CTR, CR, ER (best-performing).
Stories ads also perform strongly with higher impressions.
Images/Carousels have decent performance but slightly lower conversions.
Insight: Focus budget more on Video & Story ads for better ROI.

## Recommendations
Ads are performing strongly in visibility and engagement, but actual purchase
efficiency is weak: Schedule ad delivery during afternoons and evenings for maximum impact.
Females engage more than males; campaigns could be tailored toward female
audiences.
For maximum campaign performance and better ROI, campaign should be tailored towards Females aged 18 to 32.
Purchases are higher on weekends and first and last week of the month. Incorporate promotions around these times when purchases are higher.
Ads Timing: Ads that go live in the afternoon do better. It’s best to schedule ads in the afternoon and evening slots.
Focus campaigns on USA and UK, they have better conversion potential due to high purchasing power. Canada and India are also strong target location and can form the secondary campaign target location.
Budget Optimization: Spend more to high performing locations and focus more on using the best ad formats.
Action: Revamp landing pages, design sumptuous offers, and focus them on best target audience to improve purchasing rate.

## Tools and Technologies Used
 - Power BI
 - Power Query
 - DAX

## How This Project Demonstrates My Skills
 - Data cleaning
 - Modelling
 - Analysis


