### Marketing-Analysis-w-R
**Introduction of data set:**<br>
- This data set is prepared for analyzing the impact of an automotive brand competitors' keyword bidding strategy. In order to focus on the competition performance, this data includes the segment, make, and model of the competitve vehicle, the geographic (region and market) for each observation, competitor's vehicle sales, price, incentives and their other marketing strategy spending.
  
**Business Questions:**<br>
1. In general, does bidding on competitive keywords help our sales or damage competitors' sales?
2. In which regions/segments, does bidding on competitive keywords have the greatest negative impact on the competition’s sales?
3. For the regions/segments that bidding has a negative impact, which segments/regions should we focus?
4. For a particular region/segments, against which competitor do we have the greatest opportunity to impact sales negatively? 

**Analysis Strategies:**<br>
1. Based on the following reasons: first, both our and competitors' sales varies from different segments, regions, and time periods, second, the spend on this month may have greater effect on next month or next two month's sales, I use the gap between our and competitors' next month (next two month) sales as dependent variable.
2. For the segment perspective, I separate the data into 14 different segments and try to find the "most fitted" model for each segment. From these different models, I can observe the impact of keyword bidding on the gap of sales. I assume the error terms for these models may correlate across each others so that seemingly unrelated regressions can be applied for this analysis. However, I don't have equal observations among the segments, for now, I treat them as separate data sets.
*Updated*: After ran through the analysis for each segment, I found that for some segments, I don't have enough data (ex. no sales at all or only few cost greater than 0), therefore, I ignored these segments.<br>

3. I do have equal amount of observations for each region, so I'll do the same approaches as segment part but using full data set instead.

**Take a look of data:**<br>
![alt text](https://github.com/lucute/Marketing-Analysis-w-R/blob/master/Sales%20over%20time.png) <br>
![alt text](https://github.com/lucute/Marketing-Analysis-w-R/blob/master/Sales_over_time_by_month_eachyear.png) <br>
![alt text](https://github.com/lucute/Marketing-Analysis-w-R/blob/master/Sales_over_time_firstsegments.png) <br>

**Results:**<br>
![alt text](https://github.com/lucute/Marketing-Analysis-w-R/blob/master/Segment_results.png) <br>
![alt text](https://github.com/lucute/Marketing-Analysis-w-R/blob/master/Region_results1.png) <br>
![alt text](https://github.com/lucute/Marketing-Analysis-w-R/blob/master/Region_results2.png) <br>

**Findings and Suggestions** 
![alt text](https://github.com/lucute/Marketing-Analysis-w-R/blob/master/Suggestions.png) <br>
![alt text](https://github.com/lucute/Marketing-Analysis-w-R/blob/master/Segment1.png) <br>
![alt text](https://github.com/lucute/Marketing-Analysis-w-R/blob/master/Segment2.png) <br>
![alt text](https://github.com/lucute/Marketing-Analysis-w-R/blob/master/Region6.png) <br>
![alt text](https://github.com/lucute/Marketing-Analysis-w-R/blob/master/Region7.png) 

