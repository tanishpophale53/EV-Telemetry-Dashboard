# EV Telemetry System

As of now, electric vehicles manufacturers are creating their own telematics dashboard to show the parameters like vehicle speed, temperature, latitude, longitude, vibration, battery stat, etc. Let say if a person having a Bajaj electric vehicle will have a different looking dashboard compared with his friend B having an ola electric vehicle.

Consider a scenario where person A needs to drive the ola electric vehicle of his friend B, then person A may find some difficulty in understanding the ola electric vehicle dashboard. To address the above problem, we built a real time standard EV Telematics dashboard for all electric vehicles so that any person can easily understand the functionalities of the dashboard in a simple way.

To the above problem statement, we won 1st prize in India's biggest EV competition named ICreate.

The standard EV Telematics dashboard is built using Thingsboard - An open source IoT platform. Initially various sensors like temperature, gyro, vibration, speed were attached to a controlled system named as aries and this aries hardware system was connected to raspberry PI and raspberry PI was connected to thingsboard server. So if the latitude or longitude of a vehicle changes or temperature changes immediately it will update in realtime on the IoT dashboard.Similarly, if a battery status of a vehicle changes immediately it will get updated in the dashboard.

## Glimpse of IoT Dashboard

![WhatsApp Image 2024-03-25 at 8 20 13 PM](https://github.com/tanishpophale53/EV-Telemetry-System/assets/71888416/08e37594-80c1-4467-b362-49324aa3e3d5)


On each device click from the entities table for ex - TestEV_1 from the above image, the individual device dashboard will open detailing its parameters like Temperature, BatteryStat, Gyro, Vibration, vehicle Speed, Latitude and Longitude.


![WhatsApp Image 2024-03-25 at 8 15 54 PM](https://github.com/tanishpophale53/EV-Telemetry-System/assets/71888416/20bbb276-ccc0-43dc-99db-f72656d0cf64)


