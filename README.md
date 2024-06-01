# Changing-World-Order

This project focuses on a comprehensive comparative analysis between the United States and China across multiple key metrics over several decades. The goal is to predict a future point where the overall scores of these two countries might intersect, indicating a potential shift in global standings.

## Categories and Subcategories

The analysis encompasses five major categories, each containing specific subcategories that provide a granular view of various aspects of national performance:

### 1. Economics
- **GDP per Capita**: A measure of the average economic output per person.
- **Infrastructure**: Evaluation of the physical and organizational structures needed for the operation of a society.
- **GINI Index**: Assessment of income inequality within the population.
- **Purchasing Power Parity (PPP)**: Comparison of economic productivity and standards of living between countries.
- **Labor Productivity**: Measurement of economic output per labor hour.

### 2. Education
- **Graduates**: The number of individuals completing tertiary education.
- **Higher Education Enrollment**: The rate at which individuals are enrolling in higher education institutions.
- **Innovation Index**: Evaluation of a country's capacity for innovation and development.

### 3. Wellbeing
- **Life Expectancy**: Average lifespan of individuals in the country.
- **Voter Turnout**: The percentage of eligible voters who participate in elections.

### 4. Rule of Law
- **Control of Corruption**: The extent to which public power is exercised for private gain.
- **Homicide Rate**: The number of homicides per 100,000 inhabitants.

### 5. Global Thinking
- **Globalization Index**: The degree of economic, social, and political globalization.
- **FDI Outflow**: The investment outflows from a country to the rest of the world.
- **FDI Inflow**: The investment inflows into a country from the rest of the world.
- **Tourism**: The number of international tourists and their economic impact.
- **Internet Access**: The percentage of the population with access to the internet.

## Project Goals

By analyzing these diverse metrics, this project aims to:
- Understand the historical trends and trajectories of the United States and China in these key areas.
- Identify patterns and correlations that could predict future shifts in national standings.
- Provide a data-driven prediction of if and when China might reach parity with or surpass the United States in terms of overall performance across these categories.

This analysis will be valuable for policymakers, economists, and researchers interested in the evolving dynamics of global power and development.

## Data Collection Challenges and Solutions

Originally, this project included many more subcategories and two additional categories. However, changes were made for several reasons.

Throughout this process, many datasets were removed because their values were ratios. Additionally, some datasets lacked sufficient legitimate data to perform linear regression and create future datasets. 

This issue was particularly pronounced with data from China, where many metrics were either completely omitted or had significantly different ratings compared to non-government sources.

The datasets ultimately used in this analysis were those that were the most cross-verifiable and the best fit our criteria for weighting.

The data currently utilized in this analysis is organized by set values that vary by year and are not represented as ratios. Future data were inferred based on existing data using linear regression. 

These extrapolated datasets were normalized using z-score method around the mean of the data for each dataset.


## Approach by Weightage

<b>A quick disclaimer.</b> The main fault with my project is in this section. Not the weightage system itself, but purely how based off opinion it was. I decided what sections were important, and I decided how important each of those were. It is without doubt that others will disagree on how important each of these categories are, or if they should even be categories. However, it is what I, and many prominent Geopoliticists and Economists consider the core of nation building so it is what I chose.

The reason I decided to use weightage for this project was because of necessity. I think it's impossible to rank where a nation actually is purely on the basis of one factor like Economicsor Military, which is what I often see. Country's need to be ranked by various factors that aren't neccesarily directly influencing each other in order to give us a macro view of what's actually happening.

This in turn leads to the weightage. Obviously not every category is going to be weighted the same, despite all of them being important. Economics is still by far the biggest section here, for obvious reasons. However, its weight is equivalent to the rest of the categories added up, balancing it out significantly. 

The weightage is out of 100. Weightage for each category is given below

- Economics - 50/100 

- Rule of Law - 10/90

- Education - 10/90

- Global Thinking - 15/90

- Wellbeing - 15/100



### Economic Weightage Breakdown

- GDP/C - (15/50)  

- Infrastructure - (5/50) 

- GINI (Wealth Inequality Indexy) - (10/50) 

- PPP (Purchasing Power Parity) Growth - (15/50) 

- Labor Productivity - (5/50)  

### Rule of Law Breakdown

- Control of Corruption - (5/10)

- Homicide Growth - (5 /10)

### Education

- Graduates - (4/10)

- Higher Education Enrollment - (4/10)

- Innovation Index - (2/10)

### Global Thinking

- Globalization Index (3/15)

- FDI Outflow (4/15)

- FDI Inflow (4/15)

- Tourism (1/15)

- Internet Access (3/15)

### Wellbeing

- Life Expectancy (10/15)

- Voter Turnout (5/15)



