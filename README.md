# Analysis-and-Visualization-of-Baywheels-bike


## Introduction
This project is about analysis and visualization of the Bay Wheels bike dataset, you can find original data  lyft website: https://s3.amazonaws.com/baywheels-data/index.html
In the original dataset ,ther are more than 150,000 entries and 13 features.
The features can be classified as three categories:     

***trip duration info***: start_at,ended_at,  
***station info***: start_station_name, start_station_id, end_station_name, end_station_id, start_lat,start_lng,end_lat,end_lat   
***member info***: ride_id, rideable_type(bike type), member_casual(user type)

## Data Preprocessing
This section includes fixing data type,droping rows that have extreme values,creating new features such as duration_in_min,hour of the day and day of the week for the trip starting time by extracting information from start_at.

## Data Visualization
performed univariate visualization, bivariate visualization and multivariate visualization using heatmap,histogram,count plot,bar chart,point point,etc.

## Convertion

After the visualization was done,I converted the jupyter notebook into a slide deck presentaion that can be played on the browser and blocked the code during presentation.  

## Summary of findings

During my investigation of the relationships in this part,we didn't observed features that strengthened each other in terms of looking features to my interest.Howerev,I did find some interesting business insights that might be useful.
1. Saturday has the largest bike use count regardless of bike type.However, Saturday afternoon has the largest number of casual users while monday afternoon has the largest number of member users.
2. The number of casual users is larger than that of the member users almost every hour of the day and the number of eletric bikes is larger than the number of the docked bikes every  hour of the day.
3. Longest bike use duration of the day usually takes place in the afternoon.
4. The bike use duration at weekends is longer than duration on the weekdays.
5. The bike use duration for casual users is longer than that of the member users for almost every start hour of the day and everyday of the week.   
6. The bike use duration for docked bike is longer than that of the electric bikes for almost every start hour of the day and everyday of the week.
7. The difference in bike use duration between casual users and member users is the largest during the start hour in the afternoon.
8. The difference in bike use duration between the casual users and members is larger at weekends compared to weekdays.

## About the presentation

In this presentation,I presented univariate visualization, bivariate visualization and multivariate visualization.In the univariate visualization, I presented the histogram of the duration_in_min and the logged form of duration_in_min, the count plot for the trip starting hour and trip starting day.Al last, I presented the proportion of user type and bike type in pie chart.In the bivariate visualization section,I showed the interactions between user type, bike type,trip starting day of the week and trip starting hour of the day.Then in the heatmap,I visualized the count by trip starting hour of the day and trip strating day of the week.In the multivariate visualization, I explored the relations between bike use duration(in min) with user type ,bike type, trip starting hour of the day and trip starting day of the week.

## Links
The original data is here:https://github.com/LeiZhang0919/Analysis-and-Visualization-of-Baywheels-bike/blob/master/202008-baywheels-tripdata.csv.zip

The analysis and visualization process here:https://github.com/LeiZhang0919/Analysis-and-Visualization-of-Baywheels-bike/blob/master/Analysis_and_visualization_of_Baywheels_Project.ipynb    

This code was used to bloke the visualization code during presentation:https://github.com/LeiZhang0919/Analysis-and-Visualization-of-Baywheels-bike/blob/master/output-toggle.tpl

 The slides in html format:https://github.com/LeiZhang0919/Analysis-and-Visualization-of-Baywheels-bike/blob/master/Analysis_and_visualization_of_Baywheels_Project.slides.html, you can download and play it on your browser.


