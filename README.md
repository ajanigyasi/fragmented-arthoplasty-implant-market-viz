
# **Most U.S Hospitals are Susceptible to a High Markup Potential in the Arthoplasty Surgical Implant Market**
> ###  **Condensing millions of transactions to capture high markup activity in a single plot**

The economics of arthoplasty surgical implant purchases by U.S. hospitals in relation to the high markups imposed by implant manufacturers remains an understudied research area. The arthosplasty implant market is nortoriously opaque with limited pricing transparacy, making it difficult for hospitals to know if they're getting a fair deal. Furthermore, surgical implants often have high markups -- sometimes 300-600% over manufacturing costs. This is due to large medical device companies maintaining [20-30% profit margins](https://www.healthcarevaluehub.org/advocate-resources/publications/medical-devices-worrying-parallels-our-nations-prescription-drug-concerns), with some products commanding even higher margins. The pricing of implants is often based on what the market and reimbursement system will [tolerate](https://starfishmedical.com/resource/margin-matters/), rather than production costs.

Here, I wanted to explore the landscape of the arthoplasty implant market from the perspective of a U.S. hospital. This data-driven analysis of hospital purchasing data from the [Economic Cycle Research Institute (ECRI)](https://www.businesscycle.com/) reveals alarming markup patterns in implant component transactions.


### **Data Summary**
*  Transactions between 2013 - 2019

*  Totaling over 4.5 million transctions

*  1,689 U.S. hospitals

*  97 implant manufacturers

*   Total U.S. hospital spend: \$10,513,927,584.14
*   Total U.S. hospital volume: 8,082,254



### **The Intution Behind Visualzing Trends For Markup Potential**

While examining the relationship between average spend and total quantity might seem like the obvious approach to visualize implant purchasing trends, this analysis can yield counterintuitive results. Moreover, the lack of correlation between these variables reveals complex patterns than initially expected, necessitating a more sophisticated analytical approach.

For example, if hospital one purchased 98,584 implants and their average spend was \$2,218 and hospital two purchased 73,728 implants with an average spend of \$2,291, one could conclude hospital one is less susceptible to a high markup potential than hospital two due to its lower average spend and higher total quantity over a period of time.


[Alt Text](interactive_html/hospital_qty_tot_spend_avg.html)


 Here, I decided to visualize the two variables (average spend vs. quantity total) with each point representing a hospital. The size of the points correspond to the number of implant transactions over the course of 7 years.

After employing OLS regression analysis to test for correlation between average spend and quantity total, we found no significant relationship between these variables. (R<sup>2</sup>=0.002, p=0.089).



### **Characterizing the arthoplasty implant market in a data-driven way**

 What if we took a different approach and compared **ratios or percentages** of total spend and quantity?


Going back to our  example scenario, if hospital one spent a total \$117 million for 98,584 implants and hospital two spent $68 million for 73,728 implants -- this will reveal that hospital one is more susceptible to a higher markup potential with a smaller percentage difference/change between quantity and spend of implants (hospital #1: 1.22% - 1.11% = **+0.11%**; hospital #2:  0.91% - 0.65% = **+0.26%**).

>> ##### **Note: The percentage change between implant quantity and spend is over a 7 year period, which factors in 8,082,254 of total U.S. hospital implant volume and $10,513,927,584.14 of total U.S. hospital spend, respectively.**

[Alt Text](interactive_html/hospital_qty_spend_pct.html)


The above plot recapitulates the hospital market landscape for implants with interpretable patterns and outliers. By characterizing the implant market in a data-driven way, we can reveal that most U.S. hospitals (51.7%) are more susceptible to a high markup potential during negotiations.  


Furthermore, this data-driven approach can also shed light on which implant manufacturers are **less likely** to deploy **high markups** in negotiations with hospitals across implant types.


### **The arthoplasty implant market is fragmented**

In the plot below, I stratified manufacturers into implant types (e.g. hip, knee, etc.) as a function of the percentage change between implant quantity and spend. This allows us to get a 7 year snapshot of the implant market  for more than 1,600 hospitals across 97 manufacturers.


To understand this chart in detail, scroll left to right hover over points for additional information in the tooltips. For example, hover over the knee implant type (the red point) of *Stryker Othopaedics Div Stryker Corp* --  where a majority of U.S. hospitals (n=1,144) were **less susceptible to a high markup potential** (among manufacturer and implant pairs=+1.41%) across more than 1,300 different knee implant components amounting to \$1.3 billion in total spend (tot. quantity=1.1 million), whereas well over 900 of U.S. hospitals were  **more susceptible to a high markup potential** (among manufacturer and implant pairs=-0.68%) during negotiations with *Smith and Nephew Inc Div Smith and Nephew plc* across nearly 1,600 different knee implant components amounting to $551 million in total spend over a 7 year timeframe
 (tot. quantity=369k).

This finding suggests fragmentation in the arthroplasty implant market, where manufacturers with more specialized components may create information asymmetry during negotiations. Consequently, this complexity makes it difficult for hospitals to stay current on all available options, thereby increasing their susceptibility to higher markups.

[Alt Text](interactive_html/mfg_mkt_landscape_by_implant.html)



### **Temporal relationships of susceptibility behavior across implants**

So far, I've visualized years of condensed data showing how hospitals exhibit susceptibility behaviors during negotiations with implant manufacturers. Now the question emerges: can we meaningfully interpret these temporal patterns (Apr 2014 - Dec 2019) of hospital susceptibility behavior across different implant categories?

Visualizing the temporal dynamics of implant market activity reveals compelling patterns. For instance, consider the economic conditions during knee and hip implant negotiations in early 2019.

Data from ECRI's U.S. coincident index suggests the country was experiencing an inflation downswing during this period, potentially enabling hospitals to secure more favorable pricing for hip and knee implants.


>> ##### **Note: "Load Date" represents the date ECRI loaded implant market data into their database and does't reflect the actual date of the transaction. The day of each transction was not provided in this dataset (only the month, year). Using "Load Date" to visualize temporal dynamics was sufficient since there  was a month or two difference from the actual transaction.**   


[Alt Text](interactive_html/annual_mkt_activity_by_implant.html)
