# gobike ford Data Exploration

## Dataset
gobike ford dataset from ford company .
The data consists of information regarding 174952 bike with the following attributes.

 - Trip Duration (in seconds)
 - Start Time and Date
 - End Time and Date
 - Start Station ID
 - Start Station Name
 - Start Station Latitude
 - Start Station Longitude
 - End Station ID
 - End Station Name
 - End Station Latitude
 - End Station Longitude
 - Bike ID
 - User Type (Subscriber or Customer - "Subscriber" = Member or "Customer" = Casual)
 - Member Year of Birth
 - Member Gender

Summary of Findings
Univariate Exploration: in the section I have tried to see the counts of some types in my dataset like  gender and duration and i have found that 

1-the average of duration is about 400 second.
2- gender has no effect on duration as we see in all top 15 end stations.
3- young people ride bikes more than old people and longer.
4- other genders ride longer than females and females ride longer than males.
5- for all top 5 start stations we can see that the average time of rides is about 600 seconds.
6- customers is riding longer than subscribers with almost  twice in all top 15 end stations.


Key Insights for Presentation
In my representation I will focus on duration in general ....the effect of being customer or subscriber ..... and how the gender has no effect  in the duration 
..the effect of age on the duration and  the distribution of sharable bikes.

Tech Stack
These are the following packages I used throughout this project.

import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sb