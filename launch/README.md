## AzureKinect + Rtabmap

### How to launch

##### Make a map
```bash
$ roslaunch azure_kinect_ros_driver slam_rtabmap.launch args:="--delete_db_on_start" cell_size:=0.02
```

##### Localize in a map
```bash
$ roslaunch azure_kinect_ros_driver slam_rtabmap.launch localization:=true rviz:=true cell_size:=0.02
```
