# bikesharing

## Overview

The objective of this challenge was to clean, visualize and analyze the bikesharing data of citibike in N.Y City. Firstly the "tripduration" column had to be modified to have a datatype of "datetime" instead of an integer. This helped create cleaner and standarized visualisations in Tableau. Once the data was cleaned and saved in a csv file, visualizations with Taleau were created. Finally, a Tableau story was created to show and demonstrate all the graphs.

During this challenge I refreashed the knowledge of Pandas to clean the data. I also learned to use Tableau and create different visualization being filtered with specific fields.

## Results

During the analysis 5 graphs

### Checkout by Hour

![CheckOut by Hour](https://user-images.githubusercontent.com/95836718/162648903-1c2951cb-ff6f-459c-941a-b5d645c68aeb.png)

**Note:** This graph clearly states that most trips last less that one hour with a mode of 5 minutes. We can infer that most people use the citibike service to travel small distances, and uses it as a mode of transportation and not of exercise or recreational.

### Checkout by Hour filtered by Gender

![CheckOut by Hour](https://user-images.githubusercontent.com/95836718/162649212-57b4d5be-2e43-466a-b009-4a57e35ed7f7.png)

**Note:** This may be considered an upgrade of the previous visualization, only that it filters the data by gender. There service is more popular among men than women, by seeing the difference in line lengths.

### Trips by Weekday

![Trips by Weekday](https://user-images.githubusercontent.com/95836718/162649412-acf86a6d-7ce6-4cf4-b352-f6132d718471.png)

**Note:** This heatmap shows the hours and days of the week the service has more activity. The most popular hours are 8 am and 5/6 pm during the week, this adds up on our theory of infering that the service is use mostly as a mode of transportation to work and from work.

### Trips by Weekday Filtered by Gender

![Weekday by Gender](https://user-images.githubusercontent.com/95836718/162649645-6eaa7b2b-15d4-42d0-9cf3-ec7c7d7e573e.png)

**Note:** This visualization adds up on our past assumptions, and confirms past trends. We still see that male represent most of the users and the same hours and days are still the most popular in both genders.

### Trip by Gender by Weekday

![Trip by Gender by Weekday](https://user-images.githubusercontent.com/95836718/162650095-c9e1b202-b6de-4b1d-bdde-39c772fe548f.png)

**Note:** This visualization shows how most of the rides are made by subscribes during the weekdays, but another trend is made clear. Non-users tend to use the service during the weekend.

## Summary

Seeing the trends we can determine that the main target  has to be workmen that seeks to travel to their work and to their home. 

Two more visualizations that can be made are:
- See the more popular stations to identify possible trends and where are they close to.
- Check in what stations more people check-in and check-out to identify and determine the supply of bikes to each station.

Tableau URL:

[link to dashboard](https://public.tableau.com/views/citibike_16493937268290/Historia1?:language=es-ES&publish=yes&:display_count=n&:origin=viz_share_link)
