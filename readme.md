# Giới thiệu
Project này điều khiển robot vi sai (diff robot) bằng navigation stack với local planner là [teb_local_planner](http://wiki.ros.org/teb_local_planner).

Tăng cường khả năng tránh vật cản trong môi trường động cho teb_local_planner bằng cách kết hợp với nhận dạng đối tượng bằng [darknet_ros](https://github.com/leggedrobotics/darknet_ros).

# Sử dụng
---
**Lưu ý:**

Đã kiểm tra trên ubuntu 18.04 LTS.

---
- Bước 1: Tạo catkin workspace
```
$ mkdir -p ~/catkin_ws/src
$ cd ~/catkin_ws/
$ catkin_make
```
- Bước 2: clone darknet_ros và build
```
$ cd ~/catkin_ws/src
$ git clone --recursive https://github.com/leggedrobotics/darknet_ros.git
$ cd ../
$ catkin_make -DCMAKE_BUILD_TYPE=Release
```
- Bước 3: clone project này
```
$
```
