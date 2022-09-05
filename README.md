# No Show Appointment (Investigate a Dataset)
## by Oluwatosin Durodola


## Dataset

This dataset consist of over 110,000 medical appointments collected in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row including age, gender and other patients info. The dataset and its features documentation are available [here](https://www.kaggle.com/datasets/joniarroba/noshowappointments)

Additional 3 features was added; waited_days, days (appointment days of the week), and
age_group. Six data points were removed from the analysis due to inconsistencies or
missing information.


## Summary of Findings

In this analysis, I found out that patients with closer appointment dates show up
more unlike patients with longer waiting days. Also patients who received sms
are very small compare to those who didn't receive at all, so proportional,
patients who received sms and didn't turn up begin to increase as the number of sms received increased.

I aslo found out that days of the week might not be the factor of not showing up
for appointment but despite appointment fix for saturday are fews, the percentage
of not showing up is high compare to others. It turns out that Teens, Youths
and Children have the highest rate of not showing up for their appointment.


## Key Insights for Presentation

For the presentation, I focused on showing the relationships between dependent variable (no show) and independent variables.

I used pandas to programmatic view the data and clean it up then use matplotlib
visualize the independent variables one by one, and then went ahead to further show
how they are connected to patients showing up for their appointments.