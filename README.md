# DATA 512 HW1

## Goal of HW1

The goal of this homework is to analyze Wikipedia pageview data for a collection of articles, focusing on access types, popularity, and data completeness. This involves retrieving pageview data using the Wikimedia Foundation REST API, processing and analyzing the data, and generating insights through visualizations.

# Sources and Licenses

## Data Sources

- **English Wikipedia Data**: The source data comes from English Wikipedia, and the text is licensed under the "Creative Commons Attribution Share-Alike license" ([CC BY-SA 3.0 License](https://en.wikipedia.org/wiki/Wikipedia:Text_of_the_Creative_Commons_Attribution-ShareAlike_3.0_Unported_License)).

- **Wikimedia Foundation REST API**: We leverage the Wikimedia Foundation REST API to retrieve additional data. Please refer to the Wikimedia Foundation REST API's terms of use for more information ([Terms and Conditions](https://www.mediawiki.org/wiki/REST_API#Terms_and_conditions)).

## Code Attribution

- **Code Developed by Dr. David W. McDonald**: We make use of code developed by Dr. David W. McDonald for Data 512, which is provided under the [Creative Commons CC-BY license](https://creativecommons.org/licenses/by/4.0/). You can find more information about Creative Commons licensing [here](https://creativecommons.org/).

## List of Academy Award Winning Articles

- **List of Academy Award Winning Articles**: We will be using a list of Academy Award-winning article titles provided by Dr. McDonald. The list can be found [here](https://drive.google.com/drive/folders/1lPJF73GX5Vyu2uAvT5VpAY-xGwP2fCCx).


## Data Files

- **Input Data:**
  - `thank_the_academy.AUG.2023.csv`: A CSV file containing movie-related data, used to fetch pageview data for movies. Can be found here: https://drive.google.com/file/d/1p7pfcakjI5YQpw0JI2HX9Lff318TBPmz/view?usp=sharing      
    
- **Output Data:**
  - `academy_monthly_mobile_<start201507>-<end202309>.json`: JSON file containing monthly mobile access pageview data.
  - `academy_monthly_desktop_<start201507>-<end202309>.zip`: JSON file containing monthly desktop access pageview data. This was added as a zip file due to size constraints.
  - `academy_monthly_cumulative_<start201507>-<end202309>.json`: JSON file containing monthly cumulative pageview data.

## Data Retrieval and Processing   

- Data retrieval is done using the Wikimedia Foundation REST API.
- The retrieved data is processed and organized into Pandas DataFrames.
- The homework focuses on mobile, desktop, and cumulative access types.

## Known Issues   

- The code includes rate-limiting to avoid exceeding API limits.
- The JSON file for desktop has been added as a zip file, due to size constraints.
