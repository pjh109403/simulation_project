# 제어 2팀 simulation_project

(우분투 사용자)
rosdep install --from-paths src --ignore-src -r -y
(민트 사용자)
rosdep install --from-paths src --ignore-src -r -y --os=ubuntu:focal

에러 발생 시
sudo apt install ros-melodic-pid
sudo apt install ros-melodic-joy
sudo apt install ros-melodic-amcl
sudo apt install ros-melodic-map-server
sudo apt install ros-melodic-move-base
sudo apt install ros-melodic-gazebo-plugins

Gazebo 맵이 정상적으로 안 뜰때 
https://github.com/osrf/gazebo_models 다운 후 ./gazebo/models에 복사

URI 태그는 절대경로만 가능해서 각 PC 마다 변경해야 한다.
uri absoulte path
