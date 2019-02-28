# indoor_localization

### ROS Industrial Indoor Positioning System
The objective of this project is to develop an open source generic ROS package for absolute indoor positioning. In order to make the ROS 
package sensor independent, a specific message type called sensor_msgs/AnchorScan that includes the coordinates and TDOA measurements of 
the anchors from which signal received will be defined. At the end of the project, an open source generic ROS package and necessary indoor 
algorithms will be developed for indoor positioning system developers and users. This ROS package will be compatible with other ROS stacks 
and packages like robot_localization, move_base, navigation etc. In addition, in this ROS package, a ROS node will be developed for the 
calculation of KPI parameters.

Maintenance for the package will be supported by Inovasyon Muhendislik Ltd.

### IPS ROS Package Setup

![package_setup](https://user-images.githubusercontent.com/16070067/44731584-2dab3980-aaec-11e8-90ae-d92970aaf144.png)


### Acknowledgement
ROSinPS project is developed by Inovasyon Muhendislik Ltd. (http://www.inovasyonmuhendislik.com)

***
<!-- 
    ROSIN acknowledgement from the ROSIN press kit
    @ https://github.com/rosin-project/press_kit
-->

<a href="http://rosin-project.eu">
  <img src="http://rosin-project.eu/wp-content/uploads/rosin_ack_logo_wide.png" 
       alt="rosin_logo" height="60" >
</a>

Supported by ROSIN - ROS-Industrial Quality-Assured Robot Software Components.  
More information: <a href="http://rosin-project.eu">rosin-project.eu</a>

<img src="http://rosin-project.eu/wp-content/uploads/rosin_eu_flag.jpg" 
     alt="eu_flag" height="45" align="left" >  

This project has received funding from the European Union’s Horizon 2020  
research and innovation programme under grant agreement no. 732287.

