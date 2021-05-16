# UnemploymentForecasting

Responding to an unprecedented surge in unemployment claims, I worked closely with the Michigan Unemployment Insurance Agency to build innovative forecasting models to ensure an accurate and timely response to applicants. As a part of this work, I implemented a backend scraper that retrieved the latest unemployment data on a weekly basis from the Bureau of Labor Statistics to ensure a short collection lag. I also built a forecasting model using SPSS Modeler and SAP Analytics Cloud to predict the amount of requests for a given period. Process workflow data showed that we could reduce the average length of phone calls and hold times. In order to accomplish this goal, our team implemented an interactive voice recognition system and virtual agent to address the 45% of callers who could have their queries solved without a live agent. By building data-driven prediction models, my team discerned the most effective technological solutions to improve workflow by 33%. In just one month, we were able to provide monetary relief to over 1.3 million people who lost their jobs due to the pandemic.

#### Data Specification 

<li>Title:               Initial Claims</li>

<li>Series ID:           ICSA </li>

<li>Source:              U.S. Employment and Training Administration</li>

<li>Release:             Unemployment Insurance Weekly Claims Report</li>

<li>Seasonal Adjustment: Seasonally Adjusted</li>

<li>Frequency:           Weekly, Ending Saturday</li>

<li>Units:               Number</li>

<li>Time Series Range:   Until 2021-04-24</li>

<li>Last Updated:        2021-04-29 7:33 AM CDT</li>

<p>


Notes:               An initial claim is a claim filed by an unemployed individual after a
                     separation from an employer. The claim requests a determination of
                     basic eligibility for the Unemployment Insurance program.

Citations: U.S. Employment and Training Administration, Initial Claims [ICSA].



#### Analysis Methods

<ul>
 <li>Exploratory data analysis.</li>  
 <li>Time series analysis.</li>  
 <li>Regression on time series using tslm function.</li>  
 <li>Tests of significance - Hypothesis testing.</li>  
</ul>
