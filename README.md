# Flint_Water_Crisis- Predictive Analysis to target areas with high Lead Risk.

# Introduction to Flint Water Crisis:
The Flint water crisis began in April 2014 when the drinking water source for the city of Flint, Michigan was changed from Lake Huron to the Flint River. The Water from Flint river was more corrosive than thought which led to insufficient water treatment. Flint water Infrastructure has lead pipes treated with protective layers. Flint’s corrosive water began to erode these protective layers causing lead from aging pipes to leach into the water supply, leading to extremely elevated levels of the heavy metal neurotoxin. As a result, there was a series of problems that culminated with lead contamination, creating a serious public health danger. Over 100,000 residents were potentially exposed to high levels of lead in the drinking water. In Flint, between 6,000 and 12,000 children have been exposed to drinking water with high levels of lead and they may experience a range of serious health problems.1 Due to the change in water source, the percentage of Flint children with elevated blood-lead levels may have risen from about 2.5% in 2014 to as much as 5% in 2015.2

# Purpose of this Project:
The project goal is to predict whether a given home/parcel of land is likely to have high levels of lead. The EPA action level for a dangerous level of lead is 15 parts per billion (PPB). So, our goal is to predict, for each sample in a test set, whether a lead test result is above 15 PPB or not.

# Dataset:
The dataset consists of 10,469 records of data comprising 37 parameters. The parameters describe various aspects of the parcel like the location of the parcel, area of the parcel, year in which the parcel was built, style of the parcel, use of the parcel etc. The sampling parameters included are date of the water sample submitted, the time of the sampling etc.

The parameters include “Lead content in ppb” parameter representing the lead content in the samples. The lead content permissible for the drinking water is 15 ppb. Implying that any water sample containing lead content below or equal to 15 ppb is safe to use and water sample above 15 ppb is not advisable.

The objective of the study is to accurately predict if the new house within Flint region would have lead content above 15 ppb. Thus, suggesting the government officials to check the service lines of those houses on priority. Thus, the Lead content parameter is value-labeled as “Yes” if the Lead content is more than 15 ppb and “No” if it is less than or equal to 15 ppb.

Complete list of parameters for the Flint Water Crisis Data:\n
● sample_id - unique identifier for each water test
● Lead_(ppb) - lead concentration in water (parts per billion)
● parcel_id - unique identifier for each property/home
● Date_Submitted - date and time of test submission
● google_add - address of the parcel
● Latitude - latitude of the parcel
● Longitude - longitude of the parcel
● Owner_Type - parcel usage type
● Land_Value - parcel value
● Land_Improvements_Value - value of improvements on the parcel
● Residential_Building_Value - value of parcel (residential only)
● Residential_Building_Style - category of residential parcel
● Commercial_Building_Value - value of parcel (commercial only)
● Building_Storeys - height of parcel in stories
● Parcel_Acres - size of parcel's lot
● Rental - whether or not the parcel is a rental
● Use_Type - parcel usage type
● Prop_Class - type of residential/commercial usage
● Year_Built - year the parcel was built
● USPS_Vacancy - whether or not the parcel is vacant
● Zoning - zoning type of the lot
● Future_Landuse - lot is planned for use in the future
● DRAFT_Zone - future assigned zoning
● Housing_Condition_2012 - condition of parcel during 2012 survey
● Housing_Condition_2014 - condition of parcel during 2014 survey
● Commercial_Condition_2013 - condition of commercial parcels
● Hydrant_Type - type of nearest fire hydrant
● Ward - division of the city
● PRECINCT - voting precinct
● CENTRACT - census area
● CENBLOCK - census block
● SL_Type - service line type
● SL_Type2 - service line secondary type
● SL_Lead - whether or not the service line contains lead
● Homestead - Whether or not the parcel is a homestead
● Homestead_Percent - Fraction of homestead
● HomeSEV - State Equalized Value

Snapshot of the dataset:

