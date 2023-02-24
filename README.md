# team-project-big-boys
## Sprint 20230215

### Vision
#### What is your product (high-level view)?
Gym Equipment Availability Reactivity Sensor or G.E.A.R.S. is a Fitness Software that will remove the need to predict or wait for certain equipment in the gym. Instead, gym memebers will be able to glance at a screen to see available machines and benches. It will take advantage of pressure sensors that are integrated into pads to determine if gym memebers are still using a machine, inbetween sets, or finished with their exercise. These stages will be presented through a "stoplight" color system. Red determining the machine is actively in use, yellow stating a member could be inbetween sets, and green indicating that the machine is available for use.
#### Whom is it for?
G.E.A.R.S. is for gym owners and members.
#### What problem does it solve?
Wasting time in the gym trying to figure out if certain machines are in use.
#### What alternatives are available, who are your competitors?
There are no alternatives on the market, making no competitors.
#### What is novel in your approach, that is "why is this project compelling and worth developing"?
Whether it be finding the time to work out before a day job or fitting in a lift between classes, managing time in the gym is important when it comes to completing a workout. By being able to view a map of gym on an application showing availability of machines, this will cut down on the time wasted wandering around to see what is not in use.
### Software Architecture
G.E.A.R.S will be constructed with a pressure sensor imbedded into gym padding. This pressure sensor will send pressure data to a microcontroller which will analyze the pressure data to see how long the gym equipment has been unused for. From there the microcontroller will send its gym equipment status data to a BLE transceiver. The BLE transceiver will relay the gym equipment status data to another BLE transceiver connected to a PC. Finally, the PC will take in the status data and update an application inside the PC.

### Challenges and Risks
Our team believes one of the most serious challenges we will see in developing this product is working with the pressure sensor to use weight and time to determine the formula we will use to see if the user is still using the machine. We decided the best way to tackle this is simply by trial and error. Going through each of the possible situations so that there are no results our software cannot account for.

___
## Team Meetings
#### Product Manager: Josh Miles

###### Meeting 1
2/24/2023
2:00 PM - 3:00 PM

Group appointed product manager and discussed project scope.  This includes issues that will be faced moving forward as well as weekly meetup times.  Communicated individual responsibilities and plan to possibly create subteams for support where necessary.

Attendance: Josh Miles, Parker Manson, Devyn Strbo, and 
