# Airplane-Crashes-and-Fatalities-Since-1908-2009

Air travel has become an integral part of our lives. The air traffic growth is estimated to increase at an annual rate of 5.5%. With such a large system and the number of people opting for this faster mode of transportation, safety concerns become paramount. Most people think of only the aircraft when it comes to travel. But indeed it involves a synergistic and synchronized working of the air operations, air traffic control, crews, airports and weather and security services. To have a closer look at the tragic reality of airplane crashes, the following analysis will provide more insights into the airplane crashed between 1908–2009.

The objectives of this analysis:

Determine the top fatalities by location.
Top fatalities by flight type.
Fatalities by operator.
Comparison between number of passenger aboard and fatalities.
Fatalities by year.
Tool used: Microsoft Excel and Power BI.

Overview of the raw data:

 <img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*4ajpiwzTCJhqiscW1beZ3A.png">

 I started the data cleaning process by removing irrelevant columns in my analysis.

New look of my data:


 <img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*altszASbkYhESUmtRuDH3w.png">

 Separating the generic location from the ‘location’ column by using the ‘split column’ function. Choose ‘,’ as the delimiter to be used.

Before:


 <img src="https://miro.medium.com/v2/resize:fit:446/format:webp/1*D82zIiySl2C5FwAs6HWbUQ.png">

 After;

 


 <img src="https://miro.medium.com/v2/resize:fit:328/format:webp/1*K30R4zzRLXg6rgx5Xb5l0A.png">


The next step is to calculate the necessary parameters for my analysis by using DAX.

Total number of passengers aboard:

 <img src="https://miro.medium.com/v2/resize:fit:640/format:webp/1*IUztGxDgOn37OQ-k21uGeA.png">


Total Fatalities:


 <img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*Aw4XTuOzz9RRTr61mH-Y9A.png">

Average fatalities per year:



 <img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*V_Xj-NMt-uZuBSg19V4HZQ.png">
 

Number of crashes:


 
 <img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*2vheasme2TQJ3nvt6tCJ4A.png">


 
 <img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*mYaPpy7GUwIq6afpdiLwHA.png">

 Insights:

Russia had the highest number of crashes with 4,387. While Brazil took the second with 2,052.

Douglas DC-3 is the airplane type with the highest fatalities with 4,211.

Aeroflot flight operator recorded the highest fatalities with 5,451.

Out of 107k number of passengers aboard, 84k passengers had fatalities.

There was a spike of number of crashes between year 1940 and 2000.

