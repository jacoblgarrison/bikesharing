# bikesharing

## NYC Citibikes Tableau Link
[link to dashboard] (https://public.tableau.com/app/profile/jacob.garrison8472/viz/NYC_Citibikes_16483239974280/Story2?publish=yes)

## Overview

Using Tableau, our goal was to analyze bike sharing data in NYC and see if it is a viable business in Des Moine, Iowa. We analyzed a csv file in Tableau to breakdown data even further and help us visualize what our data tells us. Some of the key data types we brokedown: gender, trip duration, and how often the bikes were utilized. 

## Results

AVERAGE TRIP DURATION:

![Mod-14 Avg Trip Duration](https://user-images.githubusercontent.com/95515322/162112796-831a1098-9ae7-4357-9100-07214e498772.png)

This visualization helps us breakdown how long our users ride for the duration of one trip. As we can see, the graph tells us the younger someone is, typically we see a much longer trip. 

BIKE UTILIZATION: 

![Mod-14 NYC Bike Utilization](https://user-images.githubusercontent.com/95515322/162113067-e3691476-9b4d-4d6a-8dbf-4cf3102b5f1f.png)

With this graphic, we can see which specific bikes have been utilized the most. An example from one of the larger data plots on the graph, Bikeid: 17,551 has a trip duration of 3,381,357, and is one of the most utililzed bikes in the city.

CHECKOUT TIMES FOR USERS:

![Mod-14 Checkout Times for Users](https://user-images.githubusercontent.com/95515322/162113307-92835ae8-5ef6-4420-b173-1435f4ccda04.png)

This graph shows us the number of bikes on the Y-axis, and on the X-axis the duration of the rides where we see how long each ride lasted by the minute within each hour of the trip. The majority of riders (146,752 to be exact) only lasted around 5 minutes per ride. After 5 minutes we see a sharp decline for the duration of trips. Because of this sharp decline, there wasn't any reason to look past the 2 hour mark since the graph levels out.

CHECKOUT TIMES BY GENDER:

![Mod-14 Checkout Times by Gender](https://user-images.githubusercontent.com/95515322/162114069-17af48a6-50ed-4dc6-a265-669588d2a226.png)

This graph is the same as before, however we broke it down by gender. Males dominated in the amount of bike riders, peaking at 108,057. Despite more men riding bikes, we see the same sharp decline between both genders around the 5 minute mark. The only difference is that female riders seemed to not decline so sharply after 5 minutes like the men do.

TRIPS BY WEEKDAY FOR EACH HOUR: 

![Mod-14 Trips by Weekday for each Hour](https://user-images.githubusercontent.com/95515322/162114441-ddefda6f-b1d4-4455-be2c-a3fb0be8fd55.png)

We're breaking what time our users started their bike rides on each day of the week. As we can see, not many users started their bike ride until between 7AM - 9AM for Monday - Friday. The heaviest concentration of start times for Monday - Friday looks to be beginning at 5PM and 6PM, except for Wednesday. On Wednesday it appears there are more users starting their bike rides at 8AM than 5PM which is interesting. For Saturday we see the heaviest concentration of a start time at 12PM. This makes sense since more people have the weekend off. Sunday there seems to be less users compared to Saturday, showing us that Saturday is a much more popular day to ride a bike.

TRIPS BY GENDER:

![Mod-14 Trips by Gender](https://user-images.githubusercontent.com/95515322/162114983-5dc210a6-2968-42fe-84b6-5cc8a3454270.png)

Similar to the graphic before, except this time we are breaking down by gender. Like our earlier graphs suggested, we see a heavier concentration of males riding bikes than females. The pattern seems to be the exact same for males and females as far as start times, suggesting there isn't a difference between the genders on a preferred start time. 

USER TRIPS BY GENDER BY WEEKDAY: 

![Mod-14 User Trips by Gender by Weekday](https://user-images.githubusercontent.com/95515322/162115201-49b52f5d-f7c5-4d9c-a0e5-ceb5376bdb1e.png)

Lastly, this graphic displays customers vs subscribers of our bikes and they are broken down by their gender. Just like earlier, we see more males as subscribers. We also can see what our past graphics have already told us, which is that most users prefer to ride a bike on Thursday and Friday. Something interesting, more male subscribers ride their bikes on Monday and Tuesday compared to Saturday but this is not the case for female subscribers. More female subscribers ride a bike on Saturday than Monday and also Tuesday. 

## Summary

To summarize our findings: you're more likely to subscribe to a bike if you are male, likely to rider your bike for longer if your younger as opposed to being older, the majority of users only use the bikes for around 5 minutes before a sharp decline, the majority of users begin their bike rides at 5PM or 6PM during the weekday, Saturday bike riders typically begin their ride around 12PM, and males are much more likely to subscribe than females.

One visualization I would have liked to see is comparing the start station latitude/longitude with the end station latitude/longitude and break that down by gender. Having this visualization would be interesting to compare the trips between males and females.

Another visualization would be the same concept as before, looking at the start station latitude/longitude with the end station latitude/longitude, and breaking down by birth year instead of gender. 
