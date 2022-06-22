# CheckPoint Bridge

Based on the MQTT messaging protocol, CyberStalker Bridge facilitates the connection between remote locations requiring minimal code footprint and/or network bandwidth. Thanks to the wide range of various parameters and options, CyberStalker Bridge provides an exquisite opportunity for high volumes of sensor messages transferring within a specific infrastructure, e.g. Hitachi, Lenovo, HP, etc.
Its simplicity in implementation, zero (or near zero) administration and continuous session awareness features make CyberStalker Bridge a versatile and mighty tool for developers to use it regarding the infrastructures of a different type and scale.

CheckPoint Bridge is based on the MQTT machine-to-machine connectivity protocol. IT is useful for connections with remote locations where a small code footprint is required and/or network bandwidth is at a premium. Thanks to MQTT, users have an excellent way to send high volumes of sensor messages (as is common in such applications) to Hitachi platforms and everything in between.
As a result, the designers made a number of key choices which have come to characterize it:
- Simple to implement;
- Publish/subscribe messaging;
- Zero administration (or near-zero administration);
- Minimal on-the-wire footprint;
- Expect and cater for frequent network disruption;
- Continuous session awareness;
- Expect that client applications may have very limited processing resources available;
- Provide traditional messaging qualities of service where the environment allows;
- Flexible and data agnostic.

CheckPoint Bridge pulls in all your time series data (metrics and events) from Hitachi infrastructure making it easy for your developers to use. This data can be used for monitoring your applications and infrastructure as well as enhancing your applications by being queried in a real-time visualization in your application — a single source of truth for all your time series data.
CheckPoint Bridge reads from specified MQTT topics and adds messages to Pixel Central Station. Messages are in the CheckPoint Agent’s Drivers input data formats for post-processing.
