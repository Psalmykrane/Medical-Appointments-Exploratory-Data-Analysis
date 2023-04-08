
# Medical Appointments Exploratory Data Analysis

This project is aimed to understand why people who receive treatment instructions do not show up at the next appointment time. In other words, what are the contributing factors for missing appointments?


## Project Objectives

- What is the ratio of people who miss appointments to those who don’t?

- Who don’t show up more often — men or women?
- What is the most popular month/day/hour for not showing up?
- What is the age distribution of patients?

This list is not complete — you can extend it with additional questions that come to your mind during the analysis

## Features
| Column  | Description |
| ------------- | ------------- |
| PatientID  | a unique identifier of a patient  |
| AppointmentID | a unique identifier of an appointment |
| Gender |  |
| ScheduledDay | a day when an appointment is planned to occur |
| AppointmentDay | a real date of an appointment |
| Age | a patient’s age|
| Neighborhood | a neighborhood of each patient |
| Scholarship | Does the patient receive a scholarship? |
| Hypertension | Does the patient have hypertension? |
| Diabetes | |
| Alcoholism | |
| Handicap | |
| SMS_received | Has the patient received an SMS reminder? |
| No_show | Has the patient decided not to show up? |

## Workspace Setup

```python
import numpy as np #linear algebra
import pandas as pd #data processing
import matplotlib.pyplot as plt
%matplotlib inline
import plotly.graph_objs as go
import seaborn as sns
```

## Reading in the data
```
no_df = pd.read_csv("KaggleV2-May-2016.csv", parse_dates=["ScheduledDay", "AppointmentDay"])
```
## Documentation

[Dataset souce](https://www.kaggle.com/joniarroba/noshowappointments)

[Project source](https://medium.com/towards-data-science/exploratory-analysis-python-kaggle-data-b0afb6ec1788)


## Screenshots

#### Interquartile Ranges of Age for Patients Who Showed Up and Did Not Show Up
![Interquartile Ranges of Age for Patients Who Showed Up and Did Not Show Up](https://github.com/Psalmykrane/Medical-Appointments-Exploratory-Data-Analysis/blob/main/Medical%20health%20file/images/Web%20capture_8-4-2023_195320_localhost.jpeg)


#### Percentage of Patients Attendance on Appointment Date
![Percentage of Patients Attendance on Appointment Date](https://github.com/Psalmykrane/Medical-Appointments-Exploratory-Data-Analysis/blob/main/Medical%20health%20file/images/Web%20capture_8-4-2023_195444_localhost.jpeg)


#### Percentage of Patients by Gender
![Percentage of Patients by Gender](https://github.com/Psalmykrane/Medical-Appointments-Exploratory-Data-Analysis/blob/main/Medical%20health%20file/images/Web%20capture_8-4-2023_19546_localhost.jpeg)


#### Number of Times Patients were Absent (Weekdays)
![Number of Times Patients were Absent (Weekdays)](https://github.com/Psalmykrane/Medical-Appointments-Exploratory-Data-Analysis/blob/main/Medical%20health%20file/images/Web%20capture_8-4-2023_22826_localhost.jpeg)


## 🛠 Skills
* Data cleaning (pandas)
* Data exploration (pandas, numpy, matplotlib, seaborn)
* Data visualization (matplotlib, seaborn)
* Data Manipulation (pandas, numpy)
* Critical thinking
* Python


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## Authors

- [@Psalmykrane](https://www.github.com/Psalmykrane)

