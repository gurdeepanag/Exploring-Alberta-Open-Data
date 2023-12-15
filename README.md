# Navigating-Alberta-s-Multidimensional-Data

## **Introduction**

Embarking on this comprehensive project, our primary goal is to delve into Alberta's open data, extracting insights that hold significance for both established residents and newcomers. Our exploration encompasses three key sectors: Housing, Health/Environment, and Business/Economy. Recognizing the importance of a data-centric approach, we are committed to empowering informed decision-making, catalyzing positive change, and shedding light on various aspects of Alberta.

This initiative serves to enable current and potential Albertan citizens and promote a stronger collective understanding of its municipalities. After establishing a common ground of Alberta's recent events (i.e. housing crisis (Calgary City Council to Hold Special Meeting to Address ‘Housing Crisis'., (2023).), transportation projects (Alberta NDP calls on Province to Fully Commit to Calgary's Green Line Funding., (2023).), and wildfires (Wildfires in Alberta Could Burn All Winter: Official., (2023).)), we gained a newfound interest in gaining a better understanding of these sectors relating to Alberta specifically over the past decade. The diverse perspectives within our team, including both newcomers and long-term residents, add depth to our understanding of Alberta's nuances.

In the housing sector, our research seeks answers to compelling questions, unraveling the unique characteristics of Alberta's priciest housing municipalities, tracking the evolution of rent rates over time, and identifying areas with the highest concentration of family-style homes.

Shifting focus to Health/Environment, our inquiries delve into how municipalities compare in terms of air quality and population growth, aiming to paint a historical picture of the environmental landscape and demographic trends in Alberta.

In the realm of Business/Economy, our research aims to untangle the intricate relationship between taxes and business creation. Additionally, we seek to reveal the impact of government project funding on the proliferation of businesses within the province. By addressing these critical questions, our project aims to offer nuanced insights that can guide strategic decisions and contribute to the sustainable development of Alberta.

Gurdeep had worked primarily on the Health/Environment sector, Harjot had worked primarily on the Housing sector and Shabbir and Lukas collectively worked on Business/Economy.

## **Individual Datasets**

We've chosen datasets by exploring the Government of Alberta's open data portal, for CSV files with matching primary keys (municipality and year). After sorting these datasets into three categories – Housing, Health/Environment, and Business/Economy – we proceeded with data analysis, in accordance with the Alberta Open Government License.

Working with these datasets has been a journey of discovery and skill improvement. Spending hands-on time with SQL and within our shared database was productive in learning how to clean, organize, and combine our raw datasets into meaningful tables. This process highlights the challenges of inconsistent data, like missing values or info placed in the wrong columns. We've noticed patterns in how often certain data was collected, the lack thereof in data collection for smaller municipalities, and the sheer amount of government data that had been compiled for certain datasets (i.e. population census). We carefully filter rows to best answer our guiding questions and joined relevant datasets by municipality and year.

In the realm of the housing industry, our discerning eye fell upon datasets such as Average Rent by Municipality, Percent Single Family Houses by Municipality, and Property Assessments by Municipality. These choices were motivated by a strategic focus on factors deemed vital to newcomers in Alberta. Understanding the trends in these metrics over time is pivotal for those unable to outright purchase a home, aiding them in discerning affordability across municipalities. Moreover, insights into the percentage of single-family homes cater to the diverse needs of moving families, contrasting the preferences of families with young children against those of single professionals. 

Transitioning to the health and environment domain, our chosen datasets encompassed Air Quality by Municipality, Births and Deaths by Municipality, and Population by Municipality. Ensuring that residents and newcomers are aware of trends in air quality, especially given the recent severity of wildfires that have adversely affected the health of many Albertans, will be incredibly informative for those seeking a data-driven balanced perspective of what has really happened over time. Delving into population dynamics, our datasets provided the foundation for calculating the birth rate per 100 people as well as the domestic net growth for each municipality, to illustrate how the growth rates of municipalities have changed over time. 

In the business and economy sphere, our scrutiny extended to Tax Rates by Municipality, Business Incorporations by Municipality, Number of Businesses by Municipality, and Major Projects by Municipality. The emphasis here was on unraveling the economic fabric of each municipality. Tax rates and business incorporations were deemed pivotal, acting as catalysts for creating opportunities and jobs, thereby stimulating local economies. The dataset on major projects further enriched our insights, offering a window into the commitment of each municipality to growth and community betterment, factors highly influential for those contemplating a move.

## **Discussion**

Our project took a close look at three important areas in Alberta: housing, health, and business. We discovered interesting details that help us understand the region better. In the Health and Environment category, we found that air quality is consistently good, especially in rural areas. The population is growing slowly or, in some cases, decreasing a bit, but cities like Calgary and Edmonton lead in births. Turning to housing, we noticed a strong connection between property values and rent rates, giving us a clue about future housing trends. In the Business and Economy field, government projects play a big role in business growth, especially in Calgary and Edmonton. Surprisingly, higher taxes don't always mean fewer businesses, challenging what we might expect.

Now, let's think about what we've learned and how we can do better in future projects. This experience really helped us improve our skills in using SQL. We focused on making our queries run faster, showing our commitment to doing great work. Using Tableau to visualize data became one of our strong points, making complex ideas easy to understand. Looking ahead, we're excited to learn more, especially about other database systems like MongoDB and Redis. Real-world situations are the best way to use what we know and learn even more. We're also interested in trying out other tools like Power BI to make our projects even better. Having a variety of skills makes us ready for anything in the world of data analysis.

In a nutshell, this project was more than just looking at Alberta's sectors. It helped us grow personally and as a team, improving our skills, questioning what we thought we knew, and making us eager to learn more. As we think about what's next, we're ready to use our skills and insights to achieve even more in the world of data analysis and exploration.

## **Conclusion**

During this project, we carefully studied data from Alberta and its various municipalities. We worked with relational CSV datasets, looking at important factors in Housing, Health/Environment, and Business/Economy. Our main goal was to learn how to use advanced tools like SQL and Tableau to organize and query the data, so we could find answers to our research questions. We also focused on creating clear and varied visualizations to show how different areas in Alberta perform across chosen metrics. Our findings are useful for both long-time residents and those thinking about moving to Alberta. For residents, it's a helpful resource to find areas for improvement or where the province might need to step in. Prospective residents can use this info to understand which places might be a good fit for them. In a nutshell, our project gives a modern view of Alberta's recent years, highlighting areas that could use attention or improvement. To sum up our learning journey, our skills in SQL, along with tools like SQL Workbench and Python connectors, helped us make sense of the data. Creating interactive Tableau dashboards showed our commitment to making the data easy to explore.

In the end, our mission was successful. We didn't just dive into the details of municipality data – we went the extra mile to present it in a way that's easy to understand. Our project shows our dedication to giving valuable information to Alberta residents and potential newcomers, so they can make well-informed decisions in the ever-changing province.

## **References**

Alberta NDP calls on Province to Fully Commit to Calgary's Green Line Funding. (2023).CTV News. https://calgary.ctvnews.ca/alberta-ndp-calls-on-province-to-fully-commit-to-calgary-s-green-line-funding-1.6479706

Air Quality Index by Municipality. (2023). Government of Alberta. https://www.alberta.ca/open-government-program

Average Rent by Municipality. (2023). Government of Alberta. https://www.alberta.ca/open-government-program/average-rents-by-municipality

Births and Deaths by Municipality. (2023). Government of Alberta. https://www.alberta.ca/open-government-program

Businesses by Municipality. (2023). Government of Alberta. https://open.alberta.ca/opendata/businesses-by-municipality 

Calgary City Council to Hold Special Meeting to Address ‘Housing Crisis'. (2023). CBC News. https://www.cbc.ca/news/canada/calgary/housing-needs-assessment-report-calgary-housing-crisis-1.6958518

Census employment by Municipality. (2023). Government of Alberta. https://open.alberta.ca/opendata/census-employment-by-municipality

Incorporations by Municipality. (2023). Government of Alberta. https://open.alberta.ca/opendata/incorporations-by-municipality

Major projects by Municipality. (2023). Government of Alberta. https://www.alberta.ca/open-government-program/major-projects-by-municipality

Median income by Municipality. (2023). Government of Alberta. https://open.alberta.ca/opendata/median-income-by-municipality

Municipal Tax Rates by Municipality. (2023). Government of Alberta. https://open.alberta.ca/opendata/municipal-tax-rate-by-municipality

Open Government Program. (2023). Government of Alberta. https://www.alberta.ca/open-government-program

Percent Single Family Houses by Municipality. (2023). Government of Alberta. https://www.alberta.ca/open-government-program/percent-single-family-houses-by-municipality

Property Assessments by Municipality. (2023). Government of Alberta. https://www.alberta.ca/open-government-program/total-equalized-assessment-by-municipality

Population by Municipality. (2023). Government of Alberta. https://www.alberta.ca/open-government-program

Wildfires in Alberta Could Burn All Winter: Official. (2023). Global News. https://globalnews.ca/news/10014200/alberta-wildfires-burning-season-ending/
