## Testing

**TODO**

To use the PalmBee package, follow these steps:

## 1. Launch camera (for example using Realsense):
```bash
ros2 launch pb_perception rs_slam_launch.py
```

## 2. Launch AprilTag Detector:
```bash
ros2 launch pb_perception rs_apriltag_launch.py
```

## 3. Get annotated image and coordinates:
```bash
ros2 run pb_perception get_markers.py
```

## 4. Open your favorite image viewer to display the anotated image:
```bash
ros2 run rqt_image_view rqt_image_view
```
and select the image topic to display.
