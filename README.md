# STM_gesture

**Project Name: Gesture-Based Zooming System**

**Description:**
This project aims to develop a gesture-based zooming system where users can perform specific gestures to zoom in or out on a display. The system detects gestures using a sensor and recognizes them to trigger the zooming function accordingly. For zooming in, users are required to rotate their fingers clockwise, while for zooming out, the gesture involves rotating the finger anti-clockwise.

**Setup and Requirements:**
- **Hardware Requirements:**
  - Sensor capable of detecting rotational motion (e.g., gyroscope, accelerometer)
  - Display device
  - Microcontroller board (e.g., STM32 ,MEMS)
  
- **Software Requirements:**
  - Firmware development environment (e.g., STM32CubeIDE)
  - Gesture recognition algorithm implementation
  
**Usage:**
1. **Initialization:**
   - Connect the sensor and display device to the microcontroller board.
   - Upload the firmware containing the gesture recognition algorithm to the microcontroller.

2. **Operation:**
   - Start the system by powering on the microcontroller board.
   - Place the sensor in a position where it can detect finger rotation comfortably.
   - Display the content that needs to be zoomed in or out on the connected display device.

3. **Gesture Recognition:**
   - Perform a clockwise rotation gesture with your finger to trigger zooming in.
   - Perform an anti-clockwise rotation gesture with your finger to trigger zooming out.

4. **Zooming:**
   - Upon successfully recognizing the gesture, the system will zoom in or out accordingly.
   - The zooming effect will be visible on the connected display device.

**Example:**
- To zoom in on an image displayed on the screen, rotate your finger clockwise.
- To zoom out from the same image, rotate your finger in an anti-clockwise direction.

**Note:**
- Ensure that the sensor is positioned correctly and calibrated to detect rotational gestures accurately.
- Fine-tuning of the gesture recognition algorithm may be necessary to achieve optimal performance.


