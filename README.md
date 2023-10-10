# data-512-homework_1

Data 512  

Homework 1: Professionalism & Reproducibility  

Goal  
The goal of this assignment is to construct, analyze, and publish a dataset of monthly article traffic for a select set of pages from English Wikipedia from July 1, 2015 through September 30, 2023. Your notebook(s) and your data files will be uploaded to a repository of your choosing. You will submit a  link to your repository to enable grading of this assignment. The purpose of the assignment is to develop and follow best practices for open scientific research.     

Source data licenses   
The source data is distributed under the Creative Commons Attribution-ShareAlike 3.0 Unported License which states:   

You are free to:   
Share — copy and redistribute the material in any medium or format  
Adapt — remix, transform, and build upon the material for any purpose, even commercially  
Under the following terms:  
Attribution — You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use  
ShareAlike - If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.   
Additionally, you may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.   
[Wikimedia Foundation REST API Terms of Use](https://foundation.wikimedia.org/wiki/Policy:Terms_of_Use)

References to API   

Outputs    
These are the JSON files that are in the output:
1. Monthly mobile access - The API separates mobile access types into two separate requests, you will need to sum these to make one count for all mobile pageviews. You should store the mobile access data in a file called: academy_monthly_mobile_<startYYYYMM>-<endYYYYMM>.json   

3. Monthly desktop access - Monthly desktop page traffic is based on one single request. You should store the desktop access data in a file called:
academy_monthly_desktop_<startYYYYMM>-<endYYYYMM>.json  
4. Monthly cumulative - Monthly cumulative data is the sum of all mobile, and all desktop traffic per article. You should store the monthly cumulative data in a file called: academy_monthly_cumulative_<startYYYYMM>-<endYYYYMM>.json  







