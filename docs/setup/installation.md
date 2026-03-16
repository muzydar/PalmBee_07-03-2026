# Installation

To install the PalmBee package, follow these steps:

---

## 1. Install and setup ROS2 Humble First:

```bash
using this documentation
https://docs.ros.org/en/humble/Installation.html
```

---

## 2. Install and setup this specific Zed SDK:

```bash
[git clone https://github.com/ep51lon/PalmBee.git](https://www.stereolabs.com/en-id/developers/release/4.2
note : this repository is based on wrapper 4.2.5 and tested on ZED SDK for JetPack 6.1 and 6.2 (L4T 36.4))
```

---

## 3. Create the workspace directory:

```bash
mkdir -p palmbee_ws/src
cd palmbee_ws/src
```

---

## 4. Clone the repository:

```bash
git clone https://github.com/ep51lon/PalmBee.git
```

---

## 5. Install dependencies:

```bash
git clone https://github.com/ep51lon/PalmBee.git
```
or build specific package (for example, pb_perception) using
```bash
colcon build --packages-select pb_perception
```

---

## 6. Build the package:

```bash
colcon build
or build specific package (for example, pb_perception) using
colcon build --packages-select pb_perception
```

---

## 7. Source the setup file:

```bash
source install/setup.bash
```
or set it up on ~/.bashrc using the source command
```bash
note : for yolo_ws / u can also build it on different workspace and build it too ( but u must install / set yolo first and any package that yolo needed )
```
