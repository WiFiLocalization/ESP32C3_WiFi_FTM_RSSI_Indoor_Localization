# Wi-Fi FTM RSSI Localization dataset

![Alt text](https://ieee-dataport.org/sites/default/files/DatasetB-1.png)



Wi-Fi Fine Time Measurement for positioning / Indoor Localization in 3 different locations and using 8 different APs

Custom APs using ESP32C3 and Raw FTM is measured in nanoseconds

Data is only measured at the Router Side

Data is not measured at client side

Has 4 datasets inside the zip folder with over 100,000 data points

Contains processed Wi-Fi FTM packets from various routers in:  
1. University of Victoria, Engineering Office Wing (EOW) 3rd Floor
2. University of Victoria, Engineering Office Wing (EOW) 5th Floor
3. University of Victoria, Engineering and Computer Science (ECS) 1st Floor

Each folder contains a training dataset and a testing dataset that is independent in time and space

Router Time is synchronized using chrony

 
# Dataset is in CSV format

Relative Time (seconds) | X Position (meters) | Y Position (meters) | Feature 1 | Feature 2 | Feature 3 .....
 
Time resets at every new position and position accuracy is a few centimeters using LIDAR and RGBD camera
 
Map is in ROS2 PGM format that can read by ROS2 programs

Data for the paper
 
Wi-Fi and Bluetooth Contact Tracing Without User Intervention
https://ieeexplore.ieee.org/document/9866766
