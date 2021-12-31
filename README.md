# Covid-cases-hunter
## This is an in-class kaggle competition. We are given features x of several countries (such as population, area, etc.), and want to predict y, the log of the number positive cases of a given country. We use the mean squared loss (MSE) of the test data as the evaluation metric (lower is better). Here, I tried several regression models, including linear regression models, logistic regression models, kernel models, random forest, lightgbm and Xgboost. And Xgboost turns to be the best models with the lowest test MSE.

# Dataset description
## Dataset splits
We have three partitions of the dataset: a training set, a validation set and a test set. They have 91, 31, and 61 data points, respectively. We provide both features x and labels y for the training set and validation set, while we only provide features x for the test set.

## Feature description
Region: Part of the world this country is from. The options are: 0. 'OCEANIA'; 1. 'NORTHERN AFRICA'; 2. 'BALTICS'; 3. 'NORTHERN AMERICA'; 4. 'ASIA (EX. NEAR EAST)'; 5. 'SUB-SAHARAN AFRICA'; 6. 'C.W. OF IND. STATES'; 7. 'LATIN AMER. & CARIB'; 8. 'WESTERN EUROPE'; 9. 'EASTERN EUROPE'; 10. 'NEAR EAST'

Population: Total population of country.

Area (sq. mi.): Area in square miles.

Pop. Density (per sq. mi.): Population density, calculated per square mile.

Coastline (coast/area ratio): Ratio of coastline per area, in miles.

Net migration: Net migration rate, calculated as the difference between the number of immigrants (people coming into an area) and the number of emigrants (people leaving an area) throughout the year.

Infant mortality (per 1000 births): The number of deaths of infant before his or her first birthday, per 1000.

GDP ($ per capita): Gross domestic product, calculated as the total monetary or market value of all the finished goods and services produced within a country's borders.

Literacy (%): Literacy rate of the country, calculated as the percentage of population aged 15 years and over who can both read and write with understanding a short simple statement on his/her everyday life.

Phones (per 1000): Number of phone owners per 1000 people.

Arable (%): Percentage of arable land, defined as land under temporary crops, temporary meadows for mowing or for pasture, land under market or kitchen gardens, and land temporarily fallow.

Crops (%): Percentage of land used for agriculture, defined as the share of land area that is arable, under permanent crops, and under permanent pastures.

Other (%): Percentage of land used for other purposes (not arable or for crops).

Birthrate: The number of live births per thousand of population per year.

Deathrate: The ratio of deaths to the population of a particular area or during a particular period of time, usually calculated as the number of deaths per one thousand people per year.

Agriculture: GDP sector contribution attributed to agriculture.

Industry: GDP sector contribution attributed to industry.

Service: GDP sector contribution attributed to service.

Handwashing Facilities: Share of the population with basic handwashing facilities on premises, most recent year available

Extreme poverty: Share of the population living in extreme poverty, most recent year available since 2010

Median age: Median age of the population, UN projection for 2020

Life expectancy: Life expectancy at birth in 2019

Human development index: A composite index measuring average achievement in three basic dimensions of human development—a long and healthy life, knowledge and a decent standard of living.
