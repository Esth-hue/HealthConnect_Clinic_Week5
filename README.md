# HealthConnect_Clinic_Week5

## Project Overview

HealthConnect Clinic is an appointment-based healthcare provider seeking to improve patient appointment attendance and the overall patient support experience.

The project explores how data and AI can be used to understand missed appointments, identify attendance patterns, and support better patient engagement.

Week 5 built on the analytical foundation established in Week 4, focusing on extended exploratory analysis, KPI development, Power BI dashboard development, business insights, and recommendations.

## Objectives

•	Investigate factors associated with appointment attendance and no-shows.

•	Develop relevant business KPIs.

•	Build an interactive Power BI dashboard.

•	Identify meaningful business insights.

•	Develop practical recommendations based on the findings.

## Dataset

The dataset contains 5,000 appointment records covering patient characteristics, appointment details, booking behaviour, previous appointment history, reminder activity, distance to the clinic, waiting time, and appointment outcomes.

The validated analytical dataset was saved as:
HealthConnect_Appointment_Data_Cleaned.csv

The original dataset was preserved and not overwritten.

## Key Analysis & Findings

### Appointment Outcomes

•No-Show: 48.46%

•Attended: 46.28%

•Cancelled:5.26%

Almost half of the scheduled appointments were recorded as no-shows, highlighting a significant attendance challenge.

### Booking Lead Time

The average booking lead time was 29.64 days.

•	0–7 days: 27.81% no-show rate

•	8–14 days: 33.55%

•	15–30 days: 43.21%

•	31–45 days: 53.82%

•	46–60 days: 67.69%

No-show rates increased as appointments were booked further in advance.

### Previous No-Shows

Patients with previous no-shows generally had higher current no-show rates, suggesting that previous attendance behaviour may be useful when identifying appointments that require additional attention.

### Reminder Activity

•	No reminder: 51.39% no-show rate

•	Reminder sent: 47.36% no-show rate

•	SMS: 45.75%

•	Email: 48.41%

•	WhatsApp: 49.77%

These findings show an association between reminder activity and appointment outcomes but do not establish causation.

### Appointment Type

Follow-up appointments had the highest observed no-show rate at 51.23%, followed by Diagnostic Tests at 49.75%, Specialist Consultations at 47.44%, and General Consultations at 46.64%.

## Key KPIs

•	Total Appointments: 5,000

•	Attendance Rate: 46.28%

•	No-Show Rate: 48.46%

•	Reminder Coverage Rate: 72.68%

•	Average Booking Lead Time: 29.64 days

### Power BI Dashboard

A three-page interactive Power BI dashboard was developed.

Page 1 — Overview

•	Appointment KPIs

•	Appointment outcome distribution

•	Appointment volume by day

•	Appointment volume by time

•	Appointment volume by appointment type

Page 2 — No-Show Analysis

•	Gender

•	Age group

•	Previous no-shows

•	Appointment time

•	Appointment day

•	Appointment type

Page 3 — Booking & Reminder Analysis

•	Reminder channel

•	Reminder status

•	Booking lead time

•	Average booking lead time by appointment outcome

Slicers were synchronized across the relevant pages to support interactive filtering.

## Key Business Insights

1. No-shows are a major operational issue
   
The clinic recorded a 48.46% no-show rate, meaning almost half of scheduled appointments were missed.

2. Longer booking lead times are strongly associated with no-shows
   
The no-show rate increased from 27.81% for appointments booked 0–7 days ahead to 67.69% for appointments booked 46–60 days ahead.

3. Previous no-show behaviour is an important risk indicator
   
Patients with previous no-shows generally recorded higher current no-show rates.

4. Reminder coverage is incomplete
   
Only 72.68% of appointments received reminders. Appointments with reminders had an observed no-show rate of 47.36%, compared with 51.39% without reminders.

5. Follow-up appointments require attention
   
Follow-up appointments had the highest observed no-show rate at 51.23%.

## Business Recommendations

•	Introduce risk-based attendance monitoring using booking lead time and previous no-show history.

•	Prioritize appointments booked far in advance with additional reminders or confirmation processes.

•	Improve reminder coverage and monitor the effectiveness of different reminder channels.

•	Review follow-up appointment processes to understand the comparatively higher no-show rate.

•	Use the Power BI dashboard for ongoing monitoring of attendance and no-show patterns.

•	Explore predictive modelling using relevant appointment and behavioural features.

## Tools & Technologies

Python | Pandas | NumPy | Jupyter Notebook | Power BI | DAX | Power Query

## Limitations

•	The dataset is fictional and may not fully represent real-world clinic behaviour.

•	Some variables contain missing values.

•	Small subgroups may produce unstable rates.

•	The analysis is observational and does not establish causation.

•	Future predictive models may inherit limitations or biases present in the dataset.

## Project Outcome

Week 5 transformed the analytical foundation established in Week 4 into a deeper business analysis and interactive Power BI solution.

The strongest findings centred on booking lead time, previous no-show history, reminder coverage, and appointment type.

The analysis provides practical direction for improving attendance management and creates a foundation for future predictive modelling and AI-supported interventions.
