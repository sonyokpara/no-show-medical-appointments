# No-show Appointments (Data Exploration)


## Dataset 

The data collects information regarding some 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patients were featured including scheduleDay, AppointmentDay, Age, Gender, Scholarship, Neighbourhood and other characteristics of the patients. The overall goal is to investigate what factor(s) account determine if a patient show up or not for their medical appointment. The full documentation of the dataset can be found on [Kaggle](https://www.google.com/url?q=https://www.kaggle.com/joniarroba/noshowappointments&sa=D&source=editors&ust=1659420750148138&usg=AOvVaw3pqWHH6d7TQ2JGeTRNb14S).

### Questions for Analysis

1. Does any relationship exist between age and showing up?

2. Does prolonged waiting period (time between scheduled day and appointment day) affect patient showing up?

3. Do patients with scholarship show up more for appointment?

I completed this project as part of [Data Analysis Nanodegree](https://eu.udacity.com/course/data-analyst-nanodegree--nd002) program at Udacity. 


## Summary of Findings

In the exploratory analysis, I identified a few issues regarding the quality of the data and hence performed some wrangling to make the clean and fit for purpose. This included dropping some redundant columns like patientID, AppointmentID, Alcoholism, etc., converting data types and feature engineering. This project is **not a full** descriptive statistical analysis of the dataset hence further investigation could be carried out to uncover more insights. However, my research questions led me to uncover the following insights: 

+ Age of patient was a key determinant for showing up for appointment or otherwise.
**Show (decreasing order)**: Adult > Toddlers > Infants > Youth > Kids > Teens  
**No-show (decreasing order)**: Teens > Kids > Youth > Infants > Toddlers > Adults. This shows clearly that adults and infants need more healthcare than other age groups.

+ More patients showed up for appointment on the scheduled day without waiting. However, as waiting days prolonged, the number of patients who showed up for appointment dropped sharply. From this observation, patients are not likely to show up for appointments when they have to wait for too long.

+ Patients without [Bolsa Família](https://www.google.com/url?q=https://en.wikipedia.org/wiki/Bolsa_Fam%25C3%25ADlia&sa=D&source=editors&ust=1659420750149445&usg=AOvVaw297i6HNxSliLC_VGn7MV0a) a.k.a scholarship showed up more for medical appointments. This could mean that healthcare was relatively cheap and affordable.

The complete exploration is documented in this [jupyter notebook] or [HTML]


## Tools
+ Python
+ Pandas
+ Numpy
+ Matplotlib
+ Seaborn


## Further Analysis

+ Explanatory Analysis 
+ Data Visualization
+ Data Wrangling
+ Statistical Analysis
