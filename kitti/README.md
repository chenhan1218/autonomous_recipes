## demo of Google Cartographer on kitti dataset

This demo have been verified on 
* Environment 1
  * osrf/ros:kinetic-desktop-full-xenial docker image running on Ubuntu 16.04, with cartographer_ros installed
  * dataset 2011_09_26_drive_0117 (2.6 GB)
    * transfer to kitti_2011_09_26_drive_0117_synced.bag with kitti2bag

TODO:
* Confirm commit id of googlecartographer/cartographer_ros

### Demo
```
roslaunch demo.launch bag_filename:=/mnt/dataset/kitti/kitti_2011_09_26_drive_0117_synced.bag
```
