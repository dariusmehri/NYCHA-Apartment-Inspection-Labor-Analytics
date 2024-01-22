### NYCHA Apartment Inspections

#### Background and Objectives
The objective of this project is to identify and investigate bad actors who undermine the apartment inspection process. The purpose of NYCHA apartment inspections is to identify and address maintenance and repair issues. This includes identifying problems such as leaks, structural issues, electrical problems, and other issues that may affect the safety and habitability of the apartments. By rooting out bad actors and identifying repair issues early, NYCHA can take steps to ensure that residents have safe and well-maintained living spaces. 

#### Process and Approach
Labor transaction data, such as time to complete an inspection, the proportion of components in the unit that receive a satisfactory rating and access to the unit are used as measures to determine whether the inspection was completed properly.

#### Data and Methods
1. A direct connect to the NYCHA database to pull the data was established.
2. Data is cleaned, merged and quality checked in Python.
3. Visualizations were created in Tableau to explore patterns in bad behavior.
4. A bad actor list is created using key performance measures.

#### Results
##### Bad Actor List
The average inspection time is 39 minutes, during that time the inspector must answer 142 questions about the condition of apartment using a handheld device. The average satisfactory rate for an apartment that is inspected is 93%. The Bad Actor list includes inspectors with a low average inspection time and high satisfactory rates. 

A bad actor is defined as having an average inspection time of 20 minutes or less and a satisfactory rate of 97 percent or higher.

![Bad Actor List](https://github.com/dariusmehri/NYCHA-Apartment-Inspections-Labor-Analytics/assets/11237613/2937e042-2264-498e-be38-44f56af4ecc2)


#### Daily Work Time Analytics

A visualization of the daily work was also produced. For this inspector, the daily average number of minutes per inspection is far lower than the average of 39 minutes:

![Work Time](https://github.com/dariusmehri/NYCHA-Apartment-Inspections-Labor-Analytics/assets/11237613/be5d55be-8b11-4439-898e-886a0c17f19b)


#### Inspector Drill Down

A visualization was also created to drill down into the daily activity of the inspectors.

![Employee Drill Down](https://github.com/dariusmehri/NYCHA-Apartment-Inspections-Labor-Analytics/assets/11237613/d720e5eb-f7ab-43e5-beb3-c185eb829724)











