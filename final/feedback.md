# Feedback on your final

**Final Score: 54/60**

The grading rubric for the final can be found in GitHub: https://github.com/paulboal/hds5210-2023/blob/main/final/final-instructions.pdf

**Functional Requirements**
* 5 points - Uses data from at least two different sources: local file, internet, web service, relational database, AWS S3, etc; and formats: CSV, JSON, database, XML, Excel, etc
* 5 points - Data from multiple sources has to be joined together at least twice
* 5 points - Data is aggregated or pivoted at least twice during the program
* 5 points - Some kind of field-level transformation is performed at least 5 times
* 5 points - The program creates 3 or more data visualizations 
* 5 points - The program serves a theoretical purpose described in documentation, that could potentially do something in healthcare or another industry of interest

**Modularity / Style**
* 15 points - The code is broken up into various functions or classes to make testing and reuse easier

**Documentation and Professionalism**
* 15 points - All functions are documented and notebook cells include annotations and explanations.


**Note that Snowflake is one word with a lowercase "f".  You had it correct most of the time except in one header.  It's an important sign of respect to get company and people names exactly correct.**

**(-1) Using a variable name like `snowflakedata` isn't very helpful.  Sure, it came from Snowflake, but what is the purpose of the data?  That's what the variable name should be.  The name `data_2` is even less informative.**

**(-2) Your "data transformation" steps just select specific columns, but that doesn't meet the requirement for "field level transformations".  You do some "fillna" and data type conversions, so I'll give partial credit for this requirement.**

**(-2) When you merge your data, you haven't specified how the merge should happen.  It's unclear to me as a reader how those data will join.  Maybe it's unclear to you, too, because you don't specify what fields are used for the join.  The fact that you ended up with 84,084 rows in the `final_data` makes me think something is going wrong in the join and duplicating data.**

**(-1) Your Display Order / Data Value plot isn't readable and doesn't really give you any useful information.  What meaning is there in "display order"?**


**I think you met most of the technical requirements for the project, but your analysis steps didn't always make sense and sometimes felt they were just there to fulfill a technical requirement rather than to try to answer a real question about the data.  Your programming was solid.**