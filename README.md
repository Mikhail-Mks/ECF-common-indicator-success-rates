# ECF common indicator success rates

In this project, I analysed the success of projects funded by the European Social Fund (ESF) and the Youth Employment Initiative (YEI) based on common indicators such as year, priority, and department. I used Python and Power BI to perform data transformation and visualisation. The data source was transformed using Power Query.

## Key findings:
Some of the key findings from my analysis are:

* Most of the projects are accepted and completed successfully.
* The number of projects peaked in 2015 and then declined gradually until 2021, when it dropped to almost zero due to the COVID-19 pandemic.
* The majority of the projects (97.7%) are funded by ESF, while only a small fraction (2.3%) are funded by YEI.
* The most common priority for the projects is 9i - Active inclusion, including with a view to promoting equal opportunities and active participation, and improving employability. This priority accounts for 28.6% of all projects.
* The second most common priority is 8i - Access to employment for job seekers and inactive people, including the long term unemployed and people far from the labour market, also through local employment initiatives and support for labour mobility. This priority accounts for 23.4% of all projects.
* The least common priority is 10iv - Improving the labour market relevance of education and training systems facilitating the transition from education to work, and strengthening vocational education and training systems and their quality, including through mechanisms for skills anticipation, adaptation of curricula and the establishment and development of work based learning systems, including dual learning systems and apprenticeship schemes. This priority accounts for only 11.7% of all projects.
* The majority of the projects are led by the Employment, Social Affairs and Inclusion department, which is responsible for 75.8% of all projects.
* The countries that participated in the projects were grouped into four categories based on their average performance across all metrics: high performers, above average performers, below average performers, and low performers.
* Current dataset contains only operational programmes. Technical Assistance Programme is not included in this list.
* The data indicates that the investment in job search was at its highest level of effectiveness between 2019 and 2020, with a significant drop in 2021.
* Spain appears to have the most effective investment in this area, followed by Germany and Poland.
* For education and training, the picture is different: Irish and Estonian projects also have significant rates along with Germany.
* Investment in gaining a qualification is as effective as investment in job search. Spain has the same value in both indicators, and Germany also has a highly significant level in both.
* Poland has strong positions in investment in employment, both at the time of leaving the programme and six months after leaving.
* Overall for all four indicators, Spain is leading by a margin, followed by Germany and Poland, having best results in 2018 and 2021.
* Italy is leading in effectiveness of investment in employment six months after leaving the programme, followed by Poland and France.
* There is a significant strong effect of investments into gaining a qualification across all indicators, meaning that this type of investment has a positive impact on various outcomes for participants.
* There is also a significant strong effect of investments into employment, but with more variation across indicators and countries.

Additionally, I performed a deeper analysis on four specific indicators: investment in job search, investment in education and training, investment in gaining a qualification, and investment in employment. I used regression models to measure the effectiveness of these investments on different outcomes such as employment rate, income level, job satisfaction, and social inclusion.

You can find more details about my analysis and the code I used in this repository.

#### Data source: https://data.europa.eu/data/datasets/6dsf-6m94?locale=en
#### Description: https://ec.europa.eu/sfc/sites/default/files/QG%20pdf/CCI_0.pdf
