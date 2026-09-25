# Python Data Associate Certification - Practical Exam

This certification exam (DataCamp) performed various tasks within Python, particularly exploratory analysis, preprocessing & fixing inconsistencies, data aggregation, & statistical analyses. The dataset concerned paint products.
This exam has been taken & completed (or renewed) multiple times: November, 2024 & August, 2026. For clarity, both exams contained the same guidelines & dataset.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Background:** _Spectrum Shades LLC_ is a prominent supplier of concrete color solutions, offering a wide range of pigments and coloring systems used in various concrete applications, including decorative concrete, precast concrete, and concrete pavers. The company prides itself on delivering high-quality colorants that meet the unique needs of its diverse clientele, including contractors, architects, and construction companies.

The company has recently observed a growing number of customer complaints regarding inconsistent color quality in their products. The discrepancies have led to a decline in customer satisfaction and a potential increase in product returns.
By identifying and mitigating the factors causing color variations, the company can enhance product reliability, reduce customer complaints, and minimize return rates.

You are part of the data analysis team tasked with providing actionable insights to help _Spectrum Shades LLC_ address the issues of inconsistent color quality and improve customer satisfaction.


### Brief Summary
_Spectrum Shades_, in the interest of solving the issue of a growing number of complaints regarding inconsistent color quality in their products, wants to evaluate factors causing color variations & how they relate to product quality scores (a.k.a. customer satisfaction levels). This project explored data revolving around the production of the company's colorants & concrete color solutions including variables like production date, material supplier, pigment type, pigment quantity, mixing time, mixing speed, & product quality score. In particular, it explored & examined the relationship between pigment quantity & product quality score. There were 2,000 batches that comprised this dataset.  
There were four distinct tasks involved in this process.

Following some straightforward preprocessing of the data, these two main variables of interest were aggregated across the two raw-material suppliers which were either national or international (each had 700+ batches). For both variables, the differences in the averages between the two groups of suppliers was quite striking.
- Products made from materials from a national supplier contained about 10 more kilograms of pigment on average than those from international suppliers.
- Products made from materials from a national supplier saw an average product-quality score that was more than two points greater than those from international suppliers.
- Compared to the overall averages, pigment quantities & quality scores of products from national suppliers were considerably above average, whereas those from international suppliers were noticeably below average.
As such, it is clear that products of national suppliers are rated more highly than those of international suppliers.

Next, the data was filtered to look more closely at colorants built using materials from international suppliers that had more than 35 kilograms of pigment. Once more, aggregate metrics were analyzed. Despite the data being biased towards heavier quantities of pigment, these 619 batches had the same average product quality score (~5.97) as that of the 1,300 batches made from materials of international suppliers even though the filtered batches had an average pigment quantity about four kilograms greater. As such, it could be indicative that there is no or a weak relationship between pigment quantity & product quality-score specifically for international suppliers.

The final section analyzed the pigment-quantity & product-quality-score variables more directly by evaluating their distributions & their correlation. From these analyses, it seems that when more pigment is included in the business' colorants, customers are generally happier with the product. More specifically, a scatter plot was made, which illustrated a clear, linear relationship between these two variables. This relationship possessed a weak-to-moderate, positive correlation of about 0.49. In other words, the more pigment that is put into the company's products, customers are typically more satisfied with it & indicate this through a higher product quality score. To clarify, this metric does not indicate causation, but merely that the two variables change in relation to one another.


### Recommendations
As such, the scattter plot in the final section & the associated analyses offer an immediate solution for the company towards fixing their dilemma in the rising number of complaints with their products. By introducing more pigment into their products, _Spectrum Shades_ is likely to see a rise in the quality scores of their products which should be accompanied by less complaints. Such an undertaking will hopefully begin to resolve the problem with low customer satisfaction.

When it comes to the problem of inconsistent color quality, a higher pigment concentration typically produces a brighter, more vivid result in colorants. It is unclear as to what exactly the problem of "inconsistent color quality" is, but products lacking a clear, rich, vibrant hue may be one aspect. If so, adding pigment could not only aid in the problem of low customer satisfaction but also that of inconsistent color quality.  
If this problem does not have to do with the concentration of the business' colorants, then other factors will need to be analyzed. Perhaps such quality problems are arising due to pigment type, mixing time, mixing speed, material supplier, or the amount of time between production & usage. Such variables, which are available in this dataset, could be evaluated against the product quality scores to determine if there is any relationship. Even if there is not a meaningful relationship, the information is still valuable in that it can rule out such factors. Beyond these variables, other aspects of the production process could be analyzed such as the equipment utilized, the elements in which the material may be exposed to (i.e. air, metals), how it is stored, etc.
