# SQL Associate Certification - Practical Exam

This certification exam (DataCamp) performed various tasks within SQL, particularly exploratory analysis, preprocessing & fixing inconsistencies, & data aggregation. The dataset concerned hotel operations including three unique SQL tables.  
This exam has been taken & completed (or renewed) multiple times: November, 2024 & August, 2026. For clarity, both exams contained the same guidelines & dataset.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Background:** LuxuryStay Hotels is a major, international chain of hotels. They offer hotels for both business and leisure travelers in major cities across the world. The chain prides themselves on the level of customer service that they offer.  
However, the management has been receiving complaints about slow room service in some hotel branches. As these complaints are impacting the customer satisfaction rates, it has become a serious issue. Recent data shows that customer satisfaction has dropped from the 4.5 rating that they expect.

You are working with the Head of Operations to identify possible causes and hotel branches with the worst problems.


### Brief Summary
LuxuryStars Hotels, in the interest of solving the growing decline in customer dissatisfaction due to slow room service, wants to launch an investigation to identify possible causes & hotel branches with the worst problems. This project explored data revolving around the hotel company's procedural & logistical information using three tables: **Services** indicating particular services the hotels perform; **Requests** indicating sent by customers including the corresponding service & branch, the time taken until a response, & the rating of the response; **Branches** indicating details of each branch like the location, total rooms, staff counts, opening date, & types of guests expected to use the hotel. There are four unique services, 100 unique branches, & over 17,500 unique customer requests.

There were four distinct tasks involved in this process.
- **Task 1** explored & cleaned the data in the `branch` table including problems like typos, inconsistent values, missing values, & incorrect data types.
- In **Task 2**, the average & maximum amounts of time taken for customer requests to get responded to were analyzed across the four services & 100 branches.
- In **Task 3**, data was aggregated & then condensed to look at particular services & branch locations specifically Meal & Laundry services in hotels in Europe & Latin America. There are 5,047 such instances.
- In **Task 4**, the lowest performing hotels were obtained based on an average rating of 4.5 (a target set by management) across the different services & branches. There were 215 service-branch pairs of hotels that had an average request rating less than 4.50.
