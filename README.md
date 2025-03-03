# Task_Ziou

This is a workspace of the task done by Ziou. It contains a ROS2 workspace which has 2 packages.


## Prerequisites

### 1.1 Ubuntu and ROS

Ubuntu 64-bit 22.04. [ROS Humble](https://docs.ros.org/en/humble/Installation.html).

## 1.2 Extra packages

These are the extra packages to run the program:

```
sudo apt-get update
sudo apt-get install libcanberra-gtk-module
sudo apt-get install libcanberra-gtk3-module
sudo apt-get install ros-humble-plotjuggler-ros
sudo apt-get install ros-humble-generate-parameter-library
sudo apt-get install ros-humble-cv-bridge
sudo apt-get install python3-colcon-common-extensions
```

For the code formatting and linting, if you need:

```
sudo apt-get install clang-format
sudo apt-get install python3-autopep8
sudo apt-get install python3-ament-pycodestyle
```

RUN apt-get update && apt-get install -y \
    libcanberra-gtk-module \
    libcanberra-gtk3-module \
    python3-autopep8 \
    python3-ament-pycodestyle \
    clang-format \
    ros-humble-plotjuggler-ros \
    ros-humble-generate-parameter-library \
    ros-humble-ament-clang-format \
    ros-humble-cv-bridge \
    python3-colcon-common-extensions \
    build-essential \
    && rm -rf /var/lib/apt/lists/*
```

The file explorer is accessible using the button in left corner of the navigation bar. You can create a new file by clicking the **New file** button in the file explorer. You can also create folders by clicking the **New folder** button.

## Switch to another file

All your files and folders are presented as a tree in the file explorer. You can switch from one to another by clicking a file in the tree.

## Rename a file

You can rename the current file by clicking the file name in the navigation bar or by clicking the **Rename** button in the file explorer.

## Delete a file

You can delete the current file by clicking the **Remove** button in the file explorer. The file will be moved into the **Trash** folder and automatically deleted after 7 days of inactivity.
