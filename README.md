# The Billionaire Characteristics 
### Project Overview
This working paper introduces a fresh dataset concerning the origins of billionaire wealth and utilizes it to outline shifts in extreme wealth across the United States, Europe, and other developed nations. The dataset categorizes wealth as either self-made or inherited, pinpointing the company and industry from which it arises. Among self-made billionaires, individuals are further classified as company founders, executives, politically-connected, or in finance. Analysis of the data reveals a more dynamic landscape of extreme wealth in the United States compared to Europe. In Europe, just over half of billionaires inherited their wealth, whereas in the United States, one-third did so.

The median age of a European billionaire's company is approximately 20 years older than that of an American billionaire. Traditional sectors predominantly drive the increase in wealth in Europe, while the financial and technology-related sectors largely contribute to the surge in US wealth. There are indications that economic rents are higher in the United States than in Europe, as evidenced by not only the rapid expansion in the number of US billionaires but also the increasing average wealth among them over time, particularly in areas tied to resources, nontradables, or finance.
### Dictionary
- name:	name of individual or family on the billionaires list	(1996-2014	Forbes)
- rank:	rank of individual on the billionaires list, by year	(1996-2014	Forbes)
- citizenship:	billionaire country of citizenship	(1996-2014	Forbes)
- countrycode:	3-digit ISO country code, which corresponds to billionaire's citizenship	(1996–2014)
- networthusbillion:	net worth of billionaire, current US dollars	(1996-2014	Forbes)
- selfmade:	binary variable that is 0 for inherited billionaires and 1 for self-made billionaires	(1996, 2001, 2014	author's calculations)
- typeofwealth:	categorical variable that divides billionaires into inherited, self-made founders, self-made executives, politically connected/resource-related, and self-- made finance	(1996, 2001, 2014	author's calculations)
- gender:	binary variable that is 0 for male billionaires and 1 for female billionaires	(1996, 2001, 2014	author's calculations)
- age:	billionaire age	(2002–14	Forbes)
- industry:	industry labels based on Kaplan and Rauh (2013)	(1996–2014)	
- IndustryAggregates:	broad industry categories  (1996–2014	author's calculations)
- region:	categorical variable that divides billionaires into regions based on country of citizenship	(1996–2014	author's calculations)
- north:	equals 0 for emerging markets and 1 for advanced economies	(1996–2014	author's calculations)
- political: connection	equals 1 where the billionaire is linked to a politician, privatized company, or questionable license (justification given in notes variables)	(1996, 2001, 2014	author's calculations)
- founder:	equals 1 where relationship to company is founder	(1996, 2001, 2014	author's calculations)
- generationofinheriteance:	categorical variable that divides inherited billioniares by generation	(1996, 2001, 2014	author's calculations)
- sector:	sector of billionaire company	(1996, 2001, 2014	author's calculations)
- company:	company primarily associated with billionaire's wealth	(1996, 2001, 2014	author's calculations)
- company type:	indicates whether the company was new, acquired, or privatized when the billionaire or family members were first associated with it	(1996, 2001, 2014	author's calculations)
- relationshiptocompany:	describes the billionaire's relationship to the company primarily responsible for their wealth, such as founder, executive, relation, or shareholder	(1996, 2001, 2014	author's calculations)
- founding date:	founding date of company associated with the billionaire's wealth	(1996, 2001, 2014	author's calculations)
- gdpcurrentus:	by country GDP, current US dollars	(1996-2014	World Bank World Development Indicators)
- sourceofwealth:	Forbes-reported source of billionaire wealth	(2011–14	Forbes)
- notes:	extra information about individual billionaires	(1996, 2001, 2014	author's calculations)
- sources variables (source-source5):	record of web pages used to compile information on individuals	(1996, 2001, 2014	author's calculations)

### Data Source
Billionares: https://www.piie.com/publications/working-papers/origins-superrich-billionaire-characteristics-database?ResearchID=2917
### Tools
- Excel: Data cleaning
- Power BI: Visualization
- Microsoft Office: Report creation
### Tasks
Data Cleaning/Preparation
In the initial data preparation phase, we performed the following tasks:
- Data loading and inspection
- Handling missing values
- Data cleaning and formatting
Exploratory Data Analysis
Report
