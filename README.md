# Hackathon18

This Hackathon focused on diversifying space and place. Our team chose to tackle the problem of wayfinding for the disabled.

# What We Did

Buildings on campus have a lot of WiFi routers. Like... a lot (I found over 150 unique MAC addresses available from half 
of the second floor of the Langford building). These tools are radiating energy at all times of the day, waiting to make
a connection with a device. Our devices are also always monitoring these routers and the signal strength coming from them.
Our idea was to utilize this in a way that allows us to approximate (guess) your location based on the signal strength coming
from each of them.

Over the night, we collected thousands of data points by using NetworkManager and saved them as csv's. This data was used in
a k-means algorithm, provided by SKLearn. By taking the RSS measurements in distinct locations, we were able to estimate a 
location based on the signal coming from each of these routers.

The results were sub optimal. Our binary location finder worked less than 50% of the time. There may be a better learning
algorithm to use for this, or a more efficient way to collect good data.

Regardless, the hackathon was a lot of fun and we all learned new aspects of coding from learning algorithms to app development.
