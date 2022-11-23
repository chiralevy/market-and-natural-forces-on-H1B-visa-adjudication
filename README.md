# Market and Natural Forces on H1B Visa Adjudication

## Introduction

In this project, I investigate trends and patterns in the H1B Visa adjudication process. The H1B Visa is a non-immigrant work visa that allows U.S. employers to hire foreign workers for specialty jobs that require a bachelor's degree or equivalent. This visa is particularly relevant today as it is the most common visa status applied for and held by international students once they complete college. Additionally, the receipt of an H1B visa as an immigrant is predictive of long term personal and career health. 

The first of three questions I investigate in this project is as follows: **What is the relationship between wait time and the month of case submission and how has COVID-19 affected this relationship?** My rationale for analyzing this relationship stems from the fact that wait times for H1B visas can be very unpredictable at times and that an understanding of what influences wait times can help immigrants better coordinate potential employment start-dates, travel dates, and navigate their work and life with less uncertainty. Additionally, with the Coronavirus still impacting business and governmental operations, it is useful to see how the "COVID era" may have changed the wait-times for H1B visas.

For my second question, I ask **How has the acceptance rate of tech professional roles changed over time?** Often times, immigrants base their career choices off of what would best position them to live a safe life and allow them to provide their family with fair opportunities. Thus, data on what job categories have high acceptance rates and how those rates change over time are particularly useful for the foreign worker community as well as the broader public. As this is a data science class, I chose to specifically investigate the acceptance rates for tech professional roles.

Lastly, I investigate **the differences in salary between certified and denied applications**. It is known that an employer's offered salary plays a big role in how an H1B application is evaluated, for it must be enough for the foreign employee to sustain themselves and any dependents they live with. That said, salaries vary widely from job category to city to employer, and this minimum salary let alone any trend is not visible at first glance at the data. I conduct this simple analysis just to see if there exists any significant difference in salary between certified and denied applications. This information would surely be of use to prospective H1B visa applicants.


## Data Source

My data were downloaded from the U.S. Department of Labor website, particularly the Office of Foreign Labor Certification's case management system which collected the data. Within each dataset, each row represents an applicant's H1B petition and each column represents a certain component of the application, e.g. case number, employer, salary (or prevailing wage), case_status, case_submission date, etc. All together, I used 9 data sets: five from the fiscal years 2014 to 2019 and four from the fiscal quarters of 2020. In spite of this being structured data , significant cleaning was required to ensure types and columns were consistent across the tables so that they could be properly joined. My dataset, after tidying, cleaning and joining, had 2,929,073 rows and 8 columns.

## Data Ethics

An ethical harm associated with working with this data is the breach of privacy and security. In spite of this data being anonymized, there exists many adjacent personal identifiers, such as country of origin, employer, city of employment, employment start and end date, etc. Another potential harm surrounding this data lies in how it could further exacerbate existing inequities and systems of oppression if used to train an automated H1B visa adjudicator. It's not yet known what biases are absorbed in this data, so any predictive tool or analysis depending on it should be used with caution and integrity.
