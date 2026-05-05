# 2025-Yuumi-Purrformance
A dive into Yuumi's 2025 metrics, from top-tier enchanter support to niche pick, this Tableau Dash examines win rates, ban rates, and the shifting itemization landscape during the season!

# Goals: 
To visualize my favorite champion’s performance throughout the year, manually collecting data across all tiers using Op.GG’s website. I peaked Emerald 2 duoing! Since I was playing so much ranked at the time, I had figured I’d record general champion stats to see how all other Yuumi players were doing as well!  

# Finished Project: 
Explore and see Yuumi’s performance on my Tableau Public Dashboard [here]! 
<br> 
<br>
**Deliverables** 
- A Tableau Public Dashboard 
- A dataset of Yuumi’s performance throughout the year 

# Programs Used: 
- Excel for data collection 
- Tableau for Visualization 
- Copilot 
    - Used primarily to troubleshoot errors. 

# Analysis Questions and Findings: 
- What build sees the highest win rate throughout the year? 
    - **All builds have a very close win rate percentage but Moonstone -> Ardent Censer -> Redemption is the highest average win rate.**  
- What Champion consistently has a high win rate against Yuumi? 
    - **Zoe has the highest win rate against Yuumi. I believe it's that hard cc that makes playing against Zoe devastating to Yuumi or the ADC she’s riding!**  
- How do the pick/ban/win rates change over the course of the season? 
    - **Pick, ban, and win rates all experience similar rates of rise and fall at the same time, which I thought was particularly interesting! Seeing Yuumi’s win-rate steadily rise —and in response ban rates and pick rates spiking at the same time— only to have all 3 taper off later in the season (after a brutal series of repeated nerfs), may demonstrate player base reaction to perceived strength of Yuumi as well as a dislike of seeing her in their games.**
- What outside influences may have impacted these events?
    - **Yuumi did recieve multiple nerfs alongside a redemption nerf late in the season. These nerfs likely contributed to her declining win and pick rate.**  

# Data Collection and Disclosures: 
I manually went to OP.GG every 15 days or so and after filtering by “All Tiers”, recorded the specific Yuumi stats I was interested in. This gave each patch a bit of breathing room and time to build up accurate statistics. Up until patch 15.10 where I found myself “behind” and recorded 3 patches in a row (15.1 -> 15.12).  After this mid-way mark, my recordings were not as consistent as I would have preferred. It doesn’t necessarily mean any of the collected data is inaccurate or wrong; it just has varying sample sizes and impacts based on patch release. If I were to do this again, I would have recorded the sample size at the time of each recording.  

# Dash Progress Photos and Design concepts 
Where we at on end of Day 1:
<img width="980" height="635" alt="image" src="https://github.com/user-attachments/assets/8a0c8cca-e58d-40cd-bac0-b4f72c810105" />
<br>
## Notes at the time: 
- Frustrated that I cannot do 3 measures on 1 graph. 
- Normalized metrics and managed to get 3 lines on a graph, didn't like how they looked and how unliteral it was.  
- Implemented a 3-chart system, reoriented containers to be more left->right reading friendly.
- I liked using win rate as a color mark to indicate the spikes in it on both pick and ban
<img width="1055" height="595" alt="image" src="https://github.com/user-attachments/assets/85dcf739-c095-4d93-9175-4612d7b8c7d9" />
I adjusted the layout to be more left to right friendly, especially with the patch navigational filter, and leaving the top-heavy chart on the bottom. I made the line graphs thicker since when they were thin they looked kinda too thin. I was still figuring this out.
<br>
<img width="1056" height="732" alt="image" src="https://github.com/user-attachments/assets/435b18eb-121b-4f8f-a267-19deab60a05f" />
Drafting some visual concepts and placements in Word, very handy for that!

# Color Palette assignment: 
<img width="687" height="96" alt="image" src="https://github.com/user-attachments/assets/cf741f17-7c43-4b73-88cc-8f059221109c" />
Originally had this color palette above in mind. Taking the warm brown tones from the splash background, I struggled to make the brown look good on the eye. So, I leaned into the purple-y tones and her whimsical golden yellow magical vibes using this palette: 
<img width="1051" height="52" alt="image" src="https://github.com/user-attachments/assets/128273b7-9795-414b-aef9-f0d43a96a066" />
<br>

Assigned to the following roles:
- Background: #1a1b36
- Chart containers: #2e2e58
- Chart marks & key labels: #fbe335
- Chart titles & Axis labels: #bbc9e5
- Highlights and accents: #CB9FC1

Pre-desktop polish: 
<img width="1057" height="651" alt="image" src="https://github.com/user-attachments/assets/d4edfaee-f077-4817-a64a-66b76b930b02" />
My biggest roadblock here was not being able to get the item builds shapes to highlight when you select a patch. It seems Tableau doesn’t support that many to one style relationship in it’s highlighting actions.  
<br>
I also added the pie charts using [this tutorial](https://www.thedataschool.co.uk/rosh-khan/combining-bar-and-pie-charts-in-tableau-a-cleaner-way-to-show-totals-and-percentages/). I found for items and summoners it added important context to say these are the highest win rate options, but this is what gets played the most across the whole year. I also implemented dynamic tool tips using a variety of calculated fields which I was very proud of. Especially on the line charts as they involved some calculating variations across patches and ensuring that the first instance didn’t show patch variation (since there was no last recorded patch).  

# Reflection:  
I enjoyed the theming of this dashboard while still implementing a lot of interesting and valuable data. It’s especially fun to visualize so “cleanly” not a lot of statistics or clutter, but if you hover/dig deeper, a lot of that data is available for the user to explore on their own. The line chart is definitely something I could see being implemented into a business setting as well. Especially the change from last patch could be represented in quarter or other time metrics with sales data instead of League of Legends data haha. The color scheme work is really really good on this dash too, and color schemes are something I particularly struggle to feel confident about. I’m really finding my footing in Tableau, and I’m really pleased to see how I’m progressing.  
