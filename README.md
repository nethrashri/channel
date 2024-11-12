# chennel


Weekdays (Monday to Friday, 9 AM - 6 PM): Higher proportion of "Software", with fewer entries for "Social Media" and "Streaming".
Weekday Evenings and Nights: Higher proportion of "Gaming" and "Streaming".
Friday Evenings: Increased "Shopping" entries.
Weekends: More entries from "Shopping", "Streaming", and "Gaming".


I’ve created a mock dataset with a variety of meaningful features related to QoS for WiFi prioritization, which includes patterns specifically for prioritizing an office meeting device in a home network. Here’s an overview of the features included and the patterns embedded to support both exploratory data analysis and building a recommendation system:
Dataset Features
Device_ID: Unique identifier for each device connected to the WiFi network.
Device_Type: Type of device (e.g., Laptop, Smartphone, Smart TV, Tablet) to understand different bandwidth needs.
Application_Type: Type of application running on each device, like "Video Conference" for meetings or streaming applications such as YouTube or Netflix.
Signal_Strength_RSSI: Received signal strength indicator for each device, measured in dBm.
Latency_ms: Latency experienced by each device, which is critical for real-time applications.
Jitter_ms: Variation in packet arrival times, which can affect video/audio quality.
Packet_Loss_Rate: Percentage of packets lost in transmission, relevant for real-time QoS.
Bandwidth_Usage_MBps: Current bandwidth usage by each device.
Priority_Score: Hypothetical priority level of each device’s connection based on user or network policy.
Time_of_Day: Time period during which the connection is active (e.g., Morning, Afternoon, Evening, Night).
Traffic_Spike: Indicates whether a traffic spike was observed, which may affect bandwidth distribution.
Buffer_Occupancy: Percentage of buffer usage, useful for identifying high-traffic situations.
Patterns in the Data
Devices used for Video Conferencing (e.g., Device_ID 1) have lower latency, lower jitter, and higher priority scores.
Streaming applications like YouTube and Netflix have higher bandwidth usage but are given lower priority scores to maintain quality for real-time meetings.
Time of Day influences traffic, with evening hours showing a higher frequency of streaming activity, which can add congestion.
Traffic Spikes and Buffer Occupancy increase during streaming periods, influencing real-time QoS adjustments.


This dataset structure allows for meaningful analysis and can be used to develop a machine learning model that recommends optimal QoS settings


This dataset includes features like Signal Strength (RSSI), Latency, Jitter, Bandwidth Usage, and Priority Score among others, and introduces patterns such as:
Lower latency, jitter, and packet loss for video conferencing applications (to simulate higher QoS needs for meetings).
Higher bandwidth usage for streaming applications like YouTube and Netflix.
Priority scoring to differentiate traffic types and prioritize office meeting connections.
This dataset is structured to allow for exploratory data analysis and model building, ideal for developing a recommendation system to manage bandwidth prioritization based on application type and device requirements.



