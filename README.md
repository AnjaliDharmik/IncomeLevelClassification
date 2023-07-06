# Income Level Classification using census bureau database

The main goal is to perform binary classification analysis to predict whether a person income level over 50K a year or not using census bureau database.

### Census Bureau Current Population Survey (CPS) Overview - Business Understanding
1. The Current Population Survey (CPS) is the source of the official Government statistics on employment and unemployment. The CPS has been conducted monthly for over 50 years. Currently, CPS interviews about 54,000 households monthly, scientifically selected on the basis of area of residence to represent the nation as a whole, individual states, and other specified areas. Each household is interviewed once a month for four consecutive months one year, and again for the corresponding time period a year later. This technique enables CPS to obtain month-to-month and year-to-year comparisons at a reasonable cost while minimizing the inconvenience to any one household. 
2. purpose of the survey: Although the main purpose of the survey is to collect information on the employment situation, a very important secondary purpose is to collect information on the demographic status of the population, information such as age, sex, race, marital status, educational attainment, and family structure. 
3. From time-to-time additional questions are included on such important subjects as health, education, income, and previous work experience. 
4. The statistics resulting from these questions serve to update similar information collected once every 10 years through the decennial census and are used by government policymakers and legislators as important indicators of our nations economic situation and for planning and evaluating many government programs. 
5. The CPS provides current estimates of the economic status and activities of the population of the United States. Because it is not possible to develop one or two overall figures (such as the number of unemployed) that would adequately describe the labor market, the CPS is designed to provide a large amount of detailed and supplementary data. Such data are made available to meet a wide variety of needs on the part of users of labor market information.
6. The CPS sample is based on the civilian noninstitutional population of the United States. The sample is in approximately 826 sample areas comprising 1,328 counties and independent cities with coverage in every State and in the District of Columbia. In all, some 70,000 housing units or other living quarters are assigned for interview each month; about 50,000 of them containing approximately 100,000 persons 15 years old and over are interviewed. CPS survey included demographic data for approximately 22,000 children 0- 14 years old and 400 Armed Forces members living with civilians either on or off base within these households. 
7. The remainder of the assigned housing units are found to be vacant, converted to non-residential use, contain persons with residence elsewhere, or are not interviewed because the residents are not found at home after repeated calls, are temporarily absent, or are unavailable for other reasons.
8. Approximately 20,000 non-interview households are present each month. The resulting file size is approximately 142,000 records. Each year in the ASEC supplement, data are collected for armed forces members residing with their families in civilian housing units or on a military base. The armed forces members, however, are not asked the monthly labor force questions. 
9. In addition, the ASEC is supplemented with a sample of Hispanic households identified the previous November. This results in the addition of about 6,000 households (4,500 interviewed). The inclusion of the additional sample of Hispanic households began in 1976. 

### Data Understanding
1. Data is collected in 2019 - Current Population Survey in Annual Social and Economic (ASEC) Supplement conducted by the Bureau of the Census for the Bureau of Labor Statistics in Washington USA.
2. The Dataset included the civilian noninstitutional population of the United States living in housing units and members of the Armed Forces living in civilian housing units on a military base or in a household not on a military base. 
3. This Annual Social and Economic (ASEC) Supplement provides the usual monthly labor force data, but in addition, provides supplemental data on work experience, income, noncash benefits, and migration. 
4. Survey covers all States, regions and divisions are identified in their entirety. Within confidentiality restrictions, indicators are provided for 260 selected core-based statistical areas (CBSA), 44 selected combined statistical areas (CSA), 280 counties, and 40 central cities in multi-central city core-based statistical areas or combined statistical areas. Also within confidentiality restrictions, indicators are provided for metropolitan/nonmetropolitan, central city/balance metropolitan, and CBSA size.
5. The client leads the countrys Federal Statistical System; its primary responsibility is to collect demographic and economic data about America to help inform strategic initiatives.

### Project Flow
![image](https://github.com/AnjaliDharmik/IncomeLevelClassification/assets/25155794/fca7b17b-b3d7-415d-ab92-65d37185d2cb)

### Data Collection
Sample Data
provided a sample dataset from the US Census archive containing detailed, but anonymized, information for ~300,000 individuals: 
1. census_income_learn.csv (data for model training). 
2. census_income_test.csv (data for model testing). 
3. census_income_metadata.txt (metadata for both datasets). 
4. census_income_additional_info.pdf (supplemental information).
The learning data has 199523 number of instances in Learning and 99762 instances in test dataset with 42 number of features. Where 12 numeric and 29 categorical features.

### Model Performance Result
![image](https://github.com/AnjaliDharmik/IncomeLevelClassification/assets/25155794/6a5fa50d-c74e-4723-8881-9d2a33cb5fbf)





