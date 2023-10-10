# data-512-homework_1

Data 512  

Homework 1: Professionalism & Reproducibility  

**Goal**  
The goal of this project is to obtain monthly article traffic data, conduct a thorough analysis, and present the findings in a verifiable manner.

**Licenses**         
Source Data - https://creativecommons.org/licenses/by/4.0/   
Wikimedia Foundation REST API Terms of Use - https://www.mediawiki.org/wiki/API:REST_API#Terms_and_conditions   
REST API Documentation -https://wikimedia.org/api/rest_v1/#/Pageviews_data/get_metrics_pageviews_aggregate_project_access_agent_granularity_start_end 
Pageviews API Documentation - https://wikitech.wikimedia.org/wiki/Analytics/AQS/Pageviews    

**Replication**   

Outputs    
These are the JSON files that are in the output:
1. Monthly mobile access - The API separates mobile access types into two separate requests, you will need to sum these to make one count for all mobile pageviews. You should store the mobile access data in a file called: academy_monthly_mobile_<startYYYYMM>-<endYYYYMM>.json   

3. Monthly desktop access - Monthly desktop page traffic is based on one single request. You should store the desktop access data in a file called:
academy_monthly_desktop_<startYYYYMM>-<endYYYYMM>.json  
4. Monthly cumulative - Monthly cumulative data is the sum of all mobile, and all desktop traffic per article. You should store the monthly cumulative data in a file called: academy_monthly_cumulative_<startYYYYMM>-<endYYYYMM>.json  







