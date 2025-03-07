**GPS BASED LOCATION MONITORING SYSTEM WITH GEOFENCING CAPABILITIES FOR MENTALLY RETARDED PERSONS**
             Mentally impaired individuals often face challenges in navigating their environmental safety, which can lead to situations where they unintentionally 
	     wander away from safer zones, putting themselves at risk. The development of advanced electronics has brought revolutionary changes in these fields. To 
             address this issue, this project proposes Geo-Fencing based location tracking system, utilizing Global Positioning System and Global System for Mobile 
	     Communications to ensure the safety and well-being of mentally retarded individuals. A comprehensive location tracking solution, built around Global 
             Positioning System technology, combines satellite-based communication tools to provide precise latitude and longitude coordinates of a wandering person. When a 
             monitored person exists predefined zones, the system automatically triggers an alert via Global System for Mobile Communication module to the caregivers. This 
             reliable and efficient system that enables caregivers to monitor the whereabouts of mentally retarded individuals in real-time, ensuring their safety and preventing 
             potential risks. With its scalable architecture and adaptable design, safe guard can be easily customized to meet the unique needs of different user groups.

WORKING PRINCIPLE
             The overall working principle of the proposed GPS location tracking system is to continuously monitor the location of a mentally retarded person in the 
Rehabilitation Homes. The system relies on a network of satellites orbiting the Earth that continuously send signals. Trilateration is a mathematical technique 
used to determine the location of a point in 3D space by measuring its distance from multiple known reference points. In GPS, trilateration is used to calculate the
position of a GPS receiver by measuring its distance from three GPS satellites. Using three distances, trilateration can pinpoint a precise location. Each satellite is 
at the centre of a sphere and where they all intersect is the position of the GPS receiver. As the position of the GPS receiver moves, the radius of each circle will 
also change.The ESP8266 Microcontroller continuously gets signals from the GPS receiver and progress it. It has been checked whether the individual go out of the 
region. The safe distance boundary can be measured by using Haversine Formula. A Geo-fence is a defined area in a virtual setting that corresponds to a real-world 
geographic area. Circular Geo-fence has to be created such that radius is depends on the dimensions and constructions of Homes. Centre of the circular fence is 
defined, while the location of individual may move from one place to another, and it noted by the GPS receiver. Distance between centre of circular fence and the 
pointed location of an individual is measured by well known Haversine Formula Technique. The system designed with GSM module constitutes for sending alert 
messages at the time of their wandering. Then the officials will take required action to save them. IP address for webserver is also visible in the serial monitor of 
Arduino IDE. The address can be traced to locate the individual location in web browser. In web server, link can be followed to view the location in google maps under real time conditioning. So, it can be concluded that by getting the closest 
distance between the patient and the caregiver, it can speed up the caregiver in handling the patient beyond the Geo-fencing area boundary and increasing patient 
safety.
