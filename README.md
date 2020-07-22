# Outage_Detection

'India Broadband' is a well established company in the broadband space. Due to immense competition, they are facing a major problem of customer churn and dissatisfaction due to broadband outages. The company has curated a dataset, where it tracks several variables that it believes impact the 'outage_duration'. They have tracked three different 'outage durations': '0' for no outage, '1' for short outages that last between a few minutes and a maximum of 2 hours, and '2' for long outages that can last from 2 hours to sometimes even a couple of days. We use the metrics that the company has tracked to create a machine learning model that will be able to predict the 'outage_duration' using the quantitative and qualitative features.

Predict 'outage_duration' to help the company handle outages better, improve customer satisfaction and thereby reduce customer churn.
Target attribute: "outage_duration", where: 0=no outage, 1=short outages (between a few minutes and a maximum of 2 hours), 2=long outages (from 2 hours to sometimes even a couple of days)

This is a classification problem (3 classes = 0,1,2)

The evaluation metric used is 'F1 Macro Average'
