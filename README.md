# No-show Appointments

## Dataset

The data used for this analysis contains 110,527 medical appointments from April to June, 2016 in Brazil, including Age, AppointmentDay, Neighbourhood, Gender, etc. The dataset can be gotten using this [link](https://www.kaggle.com/joniarroba/noshowappointments.)

### Objective

* To understand the steps involved in a data analysis process.

* To generate insights from the exploratory data analysis.

#### Dataset summary

* There are 110,527 rows in this dataset.

* There are 14 features (columns) in this dataset.

* Some column names are not descriptive.

* There are no missing and duplicate values.

* There are 9 numeric variables (continuous and discrete) and 5 categorical variables.

* There is a mismatch of records in the No_show column.

#### Preliminary Data Wrangling

* Inconsistencies in the age column were replaced with mean age.

* The erroneous data types of some variables were changed to their correct datatype.

* New variables, Scheduled_day, Scheduled_month, Scheduled_year, Appointment_day, Appointment_month, Appointment_year, Scheduledtime_hour, Scheduledtime_min, Scheduledtime_sec and Age_groups were engineered to aid the analysis.

## Summary of Findings

#### Questions asked from the dataset

1. Which days of the week and months are patients more likely to show up?
Observation: Patients showed up more on Thursday and in the month of June from the plots although their proportions with the other days of the week and months were very close.

2. Does sending reminder messages make patients show up for their appointments?
Observation: Sending reminder messages does not affect the rate at which people show up for their appointments. The patients that didn't receive the reminder messages showed up for their appointments more than the patients that received the reminder messages.

3. Which hospital do patients frequent the most for their appointments?
Observation: Patients visit the hospital in Jardim Camburi and Maria Ortiz neighbourhood the most for their appointments from the plot shown above.

4. Which day of the week do scholarship patients show up the least for their appointments?
Observation: Scholarship students show up least for their appointments on Saturday and Thursday from the plot.

5. Which age category showed up for their appointments the most?
Observation: The elderly age group which is 55 years and above showed up the most with a percentage of 27.2 while the least was the Teens age group with 23.0%.

6. Which patients (gender) show up for their appointments the least?
Observation: The female patients showed up the least although the percentages of both genders are every close from the plot above.

7. What percentage of patients scheduled and showed up for their appointments on the same day?
Observation: A large percentage of patients scheduled and showed up for their appointments on the same day.

#### Conclusion

1. The hospital in JARDIM CAMBURI neighbourhood had the highest number of patients and the reminder messages did not affect the rate at which patients showed up for their appointments. 

2. There were 4 age groups which includes teens, adults, youth, and elderly and the elderly patients were the ones that visited the hospitals the most.

3. 88% of Patients whose appointment and schedule days were on the same day showed up for their appointments.

4. Patients showed up on all the days of the week except Sundays and the month (April, May, June) proportions were also close.
