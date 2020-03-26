# Disaster Recovery Plan (Karachi)

## 1. Introduction
Karachi is the largest city of Pakistan and the most populated, which makes
it extremely difficult to manage in a crisis situation.

Because it has been growing rapidly, it does not have an actual center
which makes co-ordination a challenge. 

This document would serve as a guideline for disaster recovery for COVID-19
and would cater various aspects. 

## 2. Demographics

In this section, we will not cover the general demographics, but in the light 
of COVID-19 disaster and how should one look at Karachi when solving for this catastrophe

Karachi should be divided into 3 parts 
1) Main Karachi 
2) Edge Karachi
3) Crisis Karachi

or simply ***MEC (Main, Edge, Crisis)***.

#### 2.1. Pictorial Representation of Division
![Alt text](../images/khi-div.png?raw=true "Title")

#### 2.2. Pictorial Representation of Sub Division
![Alt text](../images/div-exp.png?raw=true "Title")

#### 2.3. Explanation of the Division and Sub Division
#### 2.3.1. Crisis Karachi
All the area that is between Geo Shinwari and Bahria Town 
located on motorway M-9 is considered to be a part of crisis Karachi.
The main road artery joining rest of Karachi with this part is M-9 
Motorway. It should cover the 30km length and 2km width area
along the M-9 motorway.

![Alt text](../images/crisis-khi.png?raw=true "Title")

##### 2.3.1.1. Explanation
1. Least densely populated
2. Surrounded with empty plots and restaurants
3. Mega projects in the vicinity like Bahria Town
4. Connected with rest of Karachi and Pakistan via M-9 motorway
5. Road infrastructure is extremely optimal for large transportation as well

##### 2.3.1.2. Areas of interest in the vicinity

- ***Sajjad Restaurant***
- ***Al Habib Restaurant***
- ***Shaheen Shinwari Restaurant***
- ***Metro Highway Restaurant***
- ***Bahria Town***
- ***Sabzi Mandi***

![Alt text](../images/crisis-aoi.PNG?raw=true "Title")

#### 2.3.2. Edge Karachi
All the areas that are between ***Naya Nazimabad*** and ***Geo Shinwari*** via
the road artery shown in the drawing below. It should cover 
the 30km length and 200m width area along the M-9 motorway. 

****NOTE: THIS COVERS ONE ROUTE ONLY. CONSIDER ALTERNATIVE ROUTES AS WELL****

![Alt text](../images/edge-khi.png?raw=true "Title")

##### 2.3.2.1. Explanation
1. Moderately populated
2. Surrounded with empty event halls and restaurants
3. Connected with main road arteries of the city
4. Bridge between **Crisis** and **Main** Karachi

##### 2.3.2.2. Areas of interest in the vicinity

- ***Naya Nazimabad***
- ***Afroz Textile***
- ***Sakhi Hassan Graveyard***
- ***Friends Football Stadium***
- ***Bahria Town***
- ***Geo Shinwari***

![Alt text](../images/edge-aoi.PNG?raw=true "Title")

#### 2.3.3. Main Karachi
All remaining areas that are not covered in the above section 
should be considered in **Main Karachi**. 

##### 2.3.3.1. Explanation
1. More than 95% of the area/population
2. Connected with between **Edge** Karachi

##### 2.3.3.2. Areas of interest in the vicinity
- Too many to list.

#### 4. Main Road Arteries
These are the main road arteries connecting different areas of 
Karachi with all the three divisions (Main, Edge, Crisis)
and are critical for this disaster recovery plan.

![Alt text](../images/main-road-arteries.PNG?raw=true "Title")

## 3. Strategy
#### 3.1. Severity Levels
There should be four severity levels in this system
1) ***Sev 0*** (Highlighted in Red) - ![#FF0000](https://placehold.it/15/FF0000/000000?text=+)
2) ***Sev 1*** (Highlighted in Orange) - ![#FFA500](https://placehold.it/15/FFA500/000000?text=+)
3) ***Sev 2*** (Highlighted in Yellow) - ![#FFFF00](https://placehold.it/15/FFFF00/000000?text=+)
4) ***Sev 3*** (Highlighted in Green) - ![#00FF00](https://placehold.it/15/00FF00/000000?text=+)

- **SEV 0 => Critically ill**
- **SEV 1 => Seriously ill**
- **SEV 2 => Moderately ill**
- **SEV 3 => Mildly ill or no symptoms**

The transition between severity levels is shown in the diagram below:

![Alt text](../images/sev-level-transition.png?raw=true "Title")

#### 3.2. Ambulance queuing mechanism
##### 3.2.1 District Level Distribution
1) Each district would have a dedicated pool.
2) Each district would have dedicated queues (can be multiple)
3) Each district should have operators dedicated to the same area users
4) All operators should be able to contact centralized dispatcher
5) Centralized dispatcher
   1) Dispatches ambulances to users from queues
   2) Contact central pool if district pool becomes small
   3) Direct ambulances from pool to queues
   
![Alt text](../images/amb-district.png?raw=true "Title")

##### 3.2.2 Overall distribution
1) Total 5 district pools and 1 central pool
2) Central pool has a team in contact with dispatchers from districts
3) Central team dispatches ambulances from central to district pools

![Alt text](../images/pool-dist.png?raw=true "Title")

##### 3.2.3 Central Pool
1) Central pool is filled by three different levels
   1) Level 1 (Welfare Organizations + Government)
   2) Level 2 (Ride-share Organizations)
   3) Level 3 (Hospitals)
2) Central pool should be filled by the levels in ascending order.
(Hospitals should be the last resort).
3) A higher level (level 2) should only be contacted if a lower level
(level 1) is out of capacity
4) Centralized dispatch team should be able to contact representatives
from each level.
![Alt text](../images/central-pool.png?raw=true "Title")

##### 3.2.4 Penalty on misuse of dispatcher service by user.
1) 1 million PKR **OR**
2) 6 months in jail **OR**
3) Both (depending on the severity)

#### 3.3. COVID Testing mechanism
##### 3.3.1 Online Diagnosis
1) Online platform like ***doctHERs*** to be used by people for diagnostics
2) If patient has severity
   - ***SEV 0*** -> Call district dispatcher with highest priority for ambulance
   - ***SEV 1*** -> Call district dispatcher for ambulance
   - ***SEV 2*** -> Allow user to directly initiate and appointment for test
   - ***SEV 3*** -> Allow user to directly initiate and appointment for test
3) For ***SEV 2 & 3***, user would initiate the appointment if needed, and each
appointment goes in a queue.
4) The queue is read by dedicated district hospitals which contact users
for performing tests
5) For ***SEV 1 & 2***, the dispatcher is called directly by the online 
doctor. 
   - ***SEV 1*** -> Contact another district immediately if ambulance not available
   - ***SEV 2*** -> Contact another district after certain threshold has passed if 
   ambulance not available
6) ***SEV 1 & 2*** are taken directly to the hospital for treatment.  
   
![Alt text](../images/dist-testing.png?raw=true "Title")

##### 3.3.2 Hospital Distribution
1) After initial treatment, if possible, patient must be transferred
to the respective section of Karachi
   - ***SEV 0*** -> Directly to ***Crisis Karachi*** hospitals
   - ***SEV 1*** -> Directly to ***Edge Karachi*** hospitals after preliminary tests 
   - ***SEV 2*** -> 
     - If old, directly to ***Edge Karachi*** hospitals
     - If young, isolate at district hospital IF case is deteriorating 
   - ***SEV 3*** -> Isolate temporarily if needed for short period, or preliminary 
   treatment and discharge. 
   
![Alt text](../images/hospital-dist.png?raw=true "Title")

#### 3.3. Law Enforcement Positioning
Consider three metrics with respect to areas (can be added if possible)
- COVID outbreak (label = **v**, weight = **0.5**)
- Slums (label = **s**, weight = **0.3**)
- Crime (label = **c**, weight = **0.2**)

Calculate weight for all areas: 
- ****W(area) = (v * cases) + (s * slums) + (c * crimes)****

Calculate weight for all districts: 
- ****W(dist) = Sum(W(areas))****

Divide force with respect to:
1) Districts
2) Areas

Areas with high weights should have more **Rangers** than normal. An 
example of data spread on a map for slums and COVID infections 
is given below (hypothetical data) : 

![Alt text](../images/covid-slums-overlap.png?raw=true "Title")

![Alt text](../images/crime-distribution.PNG?raw=true "Title")



   


   









