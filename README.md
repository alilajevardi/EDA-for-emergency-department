# EDA-for-emergency-department in 2009-2010

# Derieved insight
The ages of patients are in the range of 0-15 years, where children between 0 to 5 year old constitute more than 50% of patients.
 ![picture](https://github.com/alilajevardi/EDA-for-emergency-department/blob/main/artifacts/Age_pie.png)
 
 
The average of Triage priority is 3.27 with the average waiting time of 61 minutes. Where around 60% of patients (17915 patients) categorise as the priority level of 3.
 
 
Generally, the triage priority deal with the level of emergency and time response to the case. With increasing the priority level waiting time should increase. The below graph shows the triage priority levels versus average waiting time. The exciting point is that the priority level 5 does not obey the trend.  
Although it is expected to see a high correlation value (close to 1) between triage and waiting time, the level 5  impacts the correlation value.  Since the p-value is  <  0.001, the correlation between Triage Priority and Waiting Time is statistically significant, although the linear relationship isn't strong (~0.24).

![picture](https://github.com/alilajevardi/EDA-for-emergency-department/blob/main/artifacts/Triage_pie.png)

As below graph shows the Depart code of “DNW” is happen in priority level of 2-5. It means that patients with lower priority did not wait for seeing doctor and left the ED. It can explain why level 5 has lower waiting time. 
![picture](https://github.com/alilajevardi/EDA-for-emergency-department/blob/main/artifacts/waiting_depart.png)
 

The three highest number of arrivals to ED occurred in 5, 6 and 7 PM, respectively. While the 8 AM has the lowest waiting time of ~20 minutes opposite to 11-12 PM with highest waiting time of ~88 minutes. The triage priority of 1 received an average waiting time of less than 1 minute.  The waiting time for children in age 8 and triage level of 1 was 0 minute while for children in age 11 there is an average waiting time of 7 minutes.
![picture](https://github.com/alilajevardi/EDA-for-emergency-department/blob/main/artifacts/Waiting_arraival.png)


A person with MRN of 416537 attended ED 68 times during 2009-2010.
