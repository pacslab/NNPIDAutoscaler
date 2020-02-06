## Neural Networks PID Auto-Scaler
In this Directory you can find Data Logger and Different controllers used in the research.
More information about how to use these controllers are available in the code comments. 
## Data_Logger
This code can be used for collecting data from cloud application. You can define specific workload patterns and duration of these pattern. All the data will be save in a .csv file. 
## FPID_Controller
Fixed PID controller used as a control theoretical autoscaler for the cloud software system. Details of implementation can be found in the paper.
## Heat_Controller
This is the scaling heat algorithm used as a baseline for comparison in our research. One can find the details of this algorithm [Delivering Elastic Containerized Cloud Applications to Enable DevOps](https://ieeexplore.ieee.org/abstract/document/7968133) .
## NN-PID-Controller
The proposed adaptive control theoretical autoscaling algorithm. The proposed algorithm uses Neural netwroks for modeling the cloud software system. In order to use this section you need to use tensoflow library.
