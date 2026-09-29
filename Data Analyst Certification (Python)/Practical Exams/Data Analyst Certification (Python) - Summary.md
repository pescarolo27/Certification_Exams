# Data Analyst Certification (Python) - Practical Exam

This certification exam (_DataCamp_) performed various tasks within Python, particularly exploratory analysis, preprocessing & fixing inconsistencies, data aggregation, statistical analyses, the development of new variables, & recommendations. Making & recording a presentation was also required as part of the exam process (the former of which can also be found in this repository; the recording, unfortunately, was too large a file for GitHub). The dataset revolved around a fictional business that provides high-quality office products to large organizations & includes techniques the business has been employing to sell their products along with additional sales information. This exam has been taken & completed in: November, 2025.

----------------------------------------------------------------------------------------------------------------------------------------------------------

**Background:** _Pens and Printers_ is a trusted provider of high quality office products to large organizations. We've built long-lasting relationships with our customers and they trust us to provide them with the best products for them. As the way in which consumers buy products is changing, our sales tactics have to change too. Launching a new product line is expensive and we need to make sure we are using the best techniques to sell the new products effectively. The best approach may vary for each new product so we need to learn quickly what works and what doesn't.

Six weeks ago, we launched a new line of office stationery. Despite the world becoming increasingly digital, there is still demand for notebooks, pens and sticky notes. Our focus has been on selling products to enable our customers to be more creative, focused on tools for brainstorming. We have tested three different sales strategies for this: targeted email and phone calls, as well as combining the two.  
- **Email:** Customers in this group received an email when the product line was launched, and a further email three weeks later. This required very little work for the team.
- **Call:** Customers in this group were called by a member of the sales team. On average, members of the team were on the phone for around thirty minutes per customer.
- **Email & call:** Customers in this group were first sent the product information email then called a week later by the sales team to talk about their needs and how this new product may support their work. The email required little work from the team—the call was around ten minutes per customer.

In discussions between the sales & analytical teams, the former has requested responses to five distinct inquiries.
- _How many customers were there for each approach?_
- _What does the spread of the revenue look like overall? And for each method?_
- _Was there any difference in revenue over time for each of the methods?_
- _Based on the data, which method would you recommend we (the sales team) continue to use? Some of these methods take more time from the team so they may not be the best for us to use if the results are similar._
- _We don't really know if there are other differences between the customers in each group, so anything you can tell us would be really helpful to give some context to what went well._



### Brief Summary
Following some standard preprocessing of the dataset, which included fixing inconsistencies & data types plus imputing missing values, each of the five aforementioned inquiries was evaluated. A more in-depth breakdown of each can be found within the project file.

To start, the proportions of customers contacted by each sales approach were determined. Generally, for every six customers, three of them were contacted via email, two via phone, & one via both email & phone.

When evaluated in terms of revenue generated, there were striking differences across the three sales methods. In short, only contacting people via phone was the least effective method by far, whereas utilizing both methods (email & phone) saw the greatest returns in terms of revenue generated.  
Over time, all three sales methods saw a considerable increase in typical revenue on a per-customer basis. The email method saw the smallest increase in generated revenue over the six-week period, whereas the phone method saw the greatest increase.

Additional variables were analyzed according to the three sales methods, but the only variable that appeared to have a meaningful relationship was the number of products purchased by customers. More specifically, customers who were contacted via email _&_ phone typically bought two more products (in quantity) than a customer who was contacted via email _or_ phone.

Following these initial analyses, the main analysis, having to do with providing recommendations regarding which methods to use (see section **Analysis IV** in the project), was conducted. Given that the sales team has limited amounts of time to employ these sales methods, multiple factors needed to be considered in this process. To assist with the quantitative analyses, a new metric was established to help quantify the effectiveness of each sales method based on the total revenue obtained & the effort/time typically utilized advertising to a customer. As part of this, base estimates regarding how much time a sales team member generally spent communicating with a customer needed to also be defined, as described below.
- _Phone Call only_: Team members were on the phone for around 30 minutes on average per customer.
- _Email only_:      It is estimated that constructing & sending an email took no more than three minutes on average.
- _Email + Call_:    Customers were sent an email & called about a week later. These phone calls were around ten minutes on average per customer.

With these estimates, the ratio of the typical revenue per customer & the typical amount of time spent on each customer can be obtained for each sales method. Generally, the value of this metric increased over the six-week period. In the most recent week of data, the three sales methods had the following typical revenue efficiencies.
- _Phone Call only_: About \$132 per hour.
- _Email only_:      About \$2,597 per hour.
- _Email + Call_:    About \$1,047 per hour.

Not only can this metric assess how the relative effectiveness of each sales method has evolved, but it can also be used to project revenue efficiencies in the near future & provide recommendations regarding how the sales team's time spent advertising can be optimized.


### Recommendations
In contextualizing the findings from the revenue efficiency metric with those of previous analyses, it is clear that only calling customers was the least productive sales strategy by far in terms of both outright revenue as well as revenue efficiency. Ideally, this technique, given how much less profitable it has been in comparison to the other two methods, should be utilized at a minimum; however, this is not to say that talking to customers directly over the phone does not have some value. Moreover, with how much time the sales team typically spends on these phone calls—about 30 minutes per customer, which is the most of any of the three methods—it would be more productive for them to spend most of their time emailing customers & occasionally calling some people about a week after emailing them.

Utilizing both sales techniques resulted in the most revenue per customer, but this method hasn't been quite as efficient as only emailing customers. Therefore, emailing customers should continue to be the primary sales method, which hasn't been the case in the most recent two weeks of data.

On another note, it is important that the company continues to monitor this metric (& any others they have used or found useful) because customer purchasing habits can change easily. Allowing for flexibility is essential if, for example, customers were to suddenly become considerably more enamored by the products via phone call & less so by email. Moreover, if total revenue were to stop increasing or decline, new strategies or plans may need to be considered or conceived so that the company doesn't become uncompetitive or unprofitable.

> In summary, an optimal strategy moving forward would involve mostly emailing customers & occasionally calling some people about a week after emailing them (the "Email" & "Email + Call" sales methods). Calling people who have not been emailed (the "Call" method) should be used at a minimum.

With this information in mind, it would be useful for the sales team to have a more defined plan as to how to optimize their time across the three sales methods. Since emails have the greatest revenue efficiency per customer & they require the least amount of time of the three sales methods, the revenue would theoretically be maximized if all of the sales team's time was allotted to this method alone; however, having some diversity in advertising approaches is more ideal to help keep the business competitive, relevant, & flexible.

As such, the balance between the amount of time spent on each sales method depends on how much the company values revenue versus diversity in their advertising approaches. A few examples were created (see the **Analysis IV** section) that lay out estimates of revenue & other quantities based on how much of an employee's time per week is spent advertising across each of the three sales methods. They all follow the same general strategy discussed previously—little time is spent only phoning customers, & most is spent sending emails out. Although relying more on emails alone will likely yield more revenue, these examples serve to provide an illustration of how the sales team can fiddle with the time they allot to each sales method to obtain a desirable (theoretical) revenue.
