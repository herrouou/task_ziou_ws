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

Some code formatting and linting tools:

```
sudo apt-get install clang-format
sudo apt-get install python3-autopep8
sudo apt-get install python3-ament-pycodestyle
```

## Compile

Firstly, clone the repository and go into the workspace:

```
git clone https://github.com/herrouou/task_ws.git
cd task_ws
```

**Build and Test**
The `build_and_test.sh` run the both the build and test(for all packages and test files):

```
. build_and_test.sh
```

If you want to execute build and test separately, please follow:
**Build**:

```
source /opt/ros/humble/setup.bash
unset GTK_PATH
colcon build
```

and source the setup.bash file:

```
source install/setup.bash
```

**Test**:

Run the test for C++ version sine_wave_cpp:
```
colcon test --packages-select sine_wave_cpp
```
Run the test for Python version sine_wave_python:
```
colcon test --packages-select sine_wave_py
```

To see the test result, run:
```
colcon test-result --verbose
```



