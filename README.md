# 제어 2팀 simulation_project

## (우분투 사용자)

1. rosdep install --from-paths src --ignore-src -r -y

## (민트 사용자)

2. rosdep install --from-paths src --ignore-src -r -y --os=ubuntu:focal

## catkin_make 에러 발생 시 설치 한 것들
1) sudo apt install ros-melodic-pid
2) sudo apt install ros-melodic-joy
3) sudo apt install ros-melodic-amcl
4) sudo apt install ros-melodic-map-server
5) sudo apt install ros-melodic-move-base
6) sudo apt install ros-melodic-gazebo-plugins

## Gazebo 맵이 정상적으로 안 뜰때 
https://github.com/osrf/gazebo_models 다운 후 ./gazebo/models에 복사

## URI 태그는 절대경로만 가능해서 각 PC 마다 변경해야 한다.

