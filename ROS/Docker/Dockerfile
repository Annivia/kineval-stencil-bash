FROM tiryoh/ros-desktop-vnc:melodic 

RUN apt-get update && apt-get install -y ros-melodic-fetch-gazebo-demo \
    terminator \
    ros-melodic-ros-tutorials

ENTRYPOINT [ "bash", "--init-file", "/opt/ros/melodic/setup.bash" ]
