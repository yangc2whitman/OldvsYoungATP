# OldvsYoungATP
Cameron Yang | Seha Park
Analyze longevity of players in more recent years compared to past years

### **Introduction**

It is said that the average peak age for world-class athletics is from 25 to 27 years old. In our project we plan to debunk this claim on our analysis of professional tennis players throughout the years. The dataset for our study includes over 64,000 matches from ATP tennis tournaments spanning multiple years, providing information on yearly player rankings, and age.

**Questions to Address:**

1. Are players reaching the top of the rankings in the ATP Tour getting older or younger?  
2. What possible reasons are there for this?

**Approach:**

* Data preparation involves cleaning and formatting to extract relevant information such as the year, player ages, and player rankings  
* Provide analysis and visualizations to support our claim

---

### **Methods & Results**

#### **Data Preparation**

1. **Filtering Criteria**: ATP players were filtered to include only those ranked in the Top 10 and aged above 28 years, isolating the dataset relevant to the research question.  
     
2. **Categorization of Players**: Players were grouped based on the year they played. Older players were categorized as those from 1990 to 1997, while younger players were categorized as those from 1998 to 2019\.  
   

**Issues and Concerns:**

* Some entries may have missing values, particularly in the `Age` or `Ranking` columns, which could affect the filtering process.   
* The dataset spans 1990 to 2019, limiting analysis of historical trends. Including data from the 1980s would provide a more accurate view of player longevity over time.

**Analysis:**
{% include_relative plot_visualization.html %}
**Age and Rankings Correlation**

* Visualized age trends of players who reached career-high rankings (Top 10\) over the age of 28\.  
* Graph (Figure 1): Tracks individual player ranking trajectories with age. Highlights players like Federer and Agassi maintaining high performance beyond 30\.  
* Older players are shown in the navy lines and younger players are shown in sky blue lines

**Age Distribution of Top Players by Decade**

* Analyzed yearly counts of players aged 28+ in the ATP Top 10\.  
* Graph (Figure 2): Shows a clear increase in older players in Top 10 rankings in recent years, peaking in 2015-2019.

---

#### 

**Conclusion**

**Answers to the research questions**

* Players reaching the top 10 ATP rankings are indeed older in recent years  
* This trend suggests a shift in athletic peak age for tennis players, extending into their 30s  
* Advance in injury prevention and sports science  
* Improvements in nutrition and recovery techniques  
* Changes in playing styles favoring longevity

**Limitations**

* Dataset focuses on ATP and excludes women's tennis (WTA).  
* Age inaccuracies in early data could skew trends.  
* Lack of granular data on factors like injuries or workload.  
* Lack of data from before 1980 which could help benefit showing more of the older era

**Further Study**

* Explore WTA trends to compare them with men’s trends and check whether the trend we find is specific to the ATP or applies to tennis as a whole.  
* Investigate the role of playing surfaces in career longevity  
* Study correlation between career length and injury rates.

**Group Assessment**

50% Cameron Yang 50% Seha Park

**References:**

Moopoo, Mimoopoo. “ATP Tennis Rankings (1990 to 2019).” *Kaggle*, 7 Dec. 2024, 

[https://www.kaggle.com/datasets/mimoopoo/atp-tennis-rankings-1990-to-2019](https://www.kaggle.com/datasets/mimoopoo/atp-tennis-rankings-1990-to-2019).
