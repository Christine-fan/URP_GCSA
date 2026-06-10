This repository contains datasets for the paper titled "Exact and hybrid heuristic methods for the Unmanned Aerial Vehicle Routing Problem Considering Ground Control Station Allocation".
The test instances are divided into three groups: Group A, Group B, and Group C.
Group A is an instance set designed for short-range scenarios, where the UAV's maximum flight duration is set to 100 minutes, with an average service time of 2 minutes per customer.
Group B is an instance set designed for medium-range scenarios, where the UAV's maximum flight duration is extended to 300 minutes, with an average service time of 4 minutes per customer.
Group C is an instance set designed for large-scale scenarios, where the UAV's maximum flight duration is also 300 minutes, with an average service time of 4 minutes per customer. The number of customer points ranges from 50 to 100.
Each test instance ID consists of four parts, in the order of: number of GCSs, number of UAVs, number of customers, and instance index. 
Each instance contains three suffixes of data files and the meanings of each column in the table are as follows:
Customer: Index of the customer node
XC: x-coordinate of the customer node
YC: y-coordinate of the customer node
demand: Resource demand at the customer node
serviceTime: Service time at the customer node
fleet_size: Number of UAVs
fleet_capacity: Maximum payload capacity of each UAV
fleet_start_x_coord: x-coordinate of the airport
fleet_start_y_coord: y-coordinate of the airport
fleet_max_working_time: Maximum flight endurance of each UAV
S: Number of ground control stations (GCSs)
S_location: Position coordinates of GCSs
RS: Maximum control radius of each GCS
d: Average time interval between consecutive monitoring tasks
