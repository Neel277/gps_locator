# gps_locator
This program is the best optimum setting which displays all of historical gps data collected by thingspeak cloud and displays it on a web app . I have used the free google api key here which is active only on local server . It won't work on a hosting service. For that you have to purchase api key from google and enable it.  It has the functionality to display :
all of historical data collected on map 
location coordinates , accurate to 9 digits (lat and long)
date 
time 
Also this is a ill attempt , it animates the path between points travelled . Not exact route traced  but the ovrall region covered
The true live tracking is yet to be done as it requires google api key and more accurate sensors 
I used nodemcu , sim800l and neo 6m gps to create the tracker . In developmen to make it more efficient and portable .
You can further refer the details here : 
