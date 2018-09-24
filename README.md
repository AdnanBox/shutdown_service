# shutdown_service
This repository provides a service in ROS to shutdown a linux system.

In case you don't have root access, run the following command in the terminal from root to gain shutdown access:
```
chmod u+s /sbin/shutdown
```

How to:
1. Run the server node using :
```
rosrun shutdown_service server
```
2. Next, run the client node or call the shutdown service using :
```
rosservice call /shutdown
```
