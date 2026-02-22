### **KARAMOJA CROP PRODUCTION DATA ANALYSIS**

<img width="490" height="300" alt="image" src="https://github.com/user-attachments/assets/df6cff8a-e66e-423d-8bdc-86dc2d4a82a3" />

#### **Overview**
Karamoja is the most food-insecure region of Uganda, primarily due to low crop productivity caused by intense droughts, pest outbreaks, and disease epidemics. Multiple NGOs provide technical support and farm inputs to farmers experiencing extremely low yields, but they lack visibility into the overall state of the region and often rely on local sources of information to prioritize their activities.
#### **Business Problem**
Dalberg Data Insights (DDI) has been tasked with developing a food security monitoring tool to support NGO decision-making in Karamoja. This project creates an interactive visualization dashboard using satellite-derived crop yield data for the 2017 season, serving as a mockup for the full Food Security Monitoring tool. 
#### **Objectives**
* At least one map in the dashboard 

* Ability to visualise results by district and subcounty levels (two administrative levels used by the NGO) 

* Interactive functionality for decision support
#### **Key Business Questions**
1. Which sub-counties have the highest crop yields? 

2. Which district produces the most total food? 

3. Where should we deploy resources first? 

4. Which crops are performing better in which areas? 

5. Which areas show potential for rapid improvement?
#### **Deliverables**
* Cleaned and enriched datasets from two sources: Uganda district crop yield population and Uganda subcounty crop yield population      

* Data visualisation illustrating the trend of maize and sorghum by district and subcounty  

* Features with the strongest positive and negative correlations. 

* A well-documented Jupyter notebook with data cleaning, exploratory data, visualisations, and interpretations.
#### **Final Goal**
To analyse maize and sorghum production in the Karamoja region of Uganda at both district and subcounty levels. The analysis explores production patterns, population influence, land use efficiency, and yield distribution to support data-driven decision-making for agricultural planning and resource allocation. 
#### **Finding**
##### **District Distribution**
* KAABONG: 15 sub-counties 

* KOTIDO: 10 sub-counties 

* NAKAPIRIPIRIT: 8 sub-counties 

* ABIM: 7 sub-counties 

* AMUDAT: 5 sub-counties

* MOROTO: 4 sub-counties 

* NAPAK: 3 sub-counties

#### **Production Patterns**
1. Maize Dominance: Maize production exceeds sorghum in all districts 

2. District Performance: Kotido leads in sorghum production; Moroto shows the lowest overall agricultural activity 

3. Subcounty Distribution: 52 subcounties across 7 districts with varying productivity levels

 <img width="652" height="400" alt="image" src="https://github.com/user-attachments/assets/68db1078-0b52-438d-9563-5788a2834d57" />

#### **Yield Characteristics**
Maize shows a slight negative skew (most sub-counties have relatively high yields); Sorghum shows a slight positive skew (some very high productivity areas). 

<img width="767" height="396" alt="image" src="https://github.com/user-attachments/assets/2afd1d78-8045-4071-8046-bc9c2ed673a4" />

#### **Land Use Efficiency**
* Area-Yield Relationship: Weak correlation between cultivation area and yield 

* Key Insight: Productivity depends more on inputs (rainfall, soil quality, farming practices) than land size
 
<img width="610" height="400" alt="image" src="https://github.com/user-attachments/assets/f1d04129-c803-4d7a-880d-8546257aefb4" />

#### **Conclusion**
Based on the analysis, here are three concrete recommendations for the NGO; 

1. **Targeted Interventions in Critical Sub-counties**

**Finding**: Several sub-counties show extremely low yields (<150 kg/ha) for both maize and sorghum, indicating critical food security risk. 

**Action**:  

* Prioritise 10-15 sub-counties with the lowest yields for immediate intervention 

* Deploy an agricultural expert to these areas to offer training and help them connect to markets  

* Provide drought-resistant seed varieties and basic inputs

**Expected Impact**: 30-50% yield improvement in targeted sub-counties within 2 seasons 

2. **District-Level Resource Allocation Based on Production Gaps** 

**Finding**: Kotido district has the highest production but also the highest population, while Moroto shows consistently low production across all metrics. The correlation between area and yield is weak, suggesting productivity factors matter more than land size. 

**Action**: 

* For high-potential districts (Kotido, Kaabong), offer training to add more knowledge for maximum impact. 

* For medium-performance districts (Abim, Nakapiripirit), fix their main problems, i.e. water availability 

* For low-performance districts (Moroto, Napak, Amudat), they need more support in offering drought-resistant seeds and creating water systems  

* Focus on productivity-enhancing inputs rather than land expansion
**Expected Impact**: Balanced regional development with 20% overall production increase 

3. **Crop-Specific Support Based on Yield Patterns** 

**Finding**: Maize yields show negative skew (most subcounties perform relatively well), while sorghum yields show positive skew (some exceptional performers but many underperformers). This suggests different intervention strategies for each crop. 

**Action**: 

* Maize: Focus on maintaining good performance through pest/disease management and drought mitigation 

* Introduce improved different sorghum varieties in sub-counties that can withstand different weather conditions  

* Sorghum: Identify top-performing sub-counties as learning centers; study their practices and replicate in low-performing
#### **Future Enhancements**
* Multi-year analysis - Add time dimension to track trends 

* Weather data integration - Correlate yields with rainfall patterns 

* Predictive modeling - Forecast food security risks 

**Tableau Dashboard**
https://public.tableau.com/views/karamojadashboard/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
 


