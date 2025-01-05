## Ping-Pong-Game 

### Overview
This project demonstrates a Hand Gesture Controlled Ping Pong Game, where players use their hand movements as a paddle to control the game in real-time. Built using Digital Image Processing techniques, this game is a fun and interactive application of computer vision.

### Features
1. **Hand Gesture Recognition**:
   - Uses webcam input to detect and track hand movements.
2. **Real-Time Interaction**:
   - Smooth and responsive paddle control for an immersive gaming experience.
3. **Digital Image Processing**:
   -Implements techniques such as contour detection, color segmentation, and motion tracking to recognize gestures.
4. **Customizable Gameplay**:
   - Modify game settings like speed, difficulty, and paddle sensitivity.

### Tools and Technologies
**Programming Language**: Python

**Libraries Used**:
1. OpenCV: For image processing and hand detection.
2. NumPy: For efficient numerical computations.

### How It Works
1. The webcam captures real-time video input.
2. Hand gestures are detected using contour-based image segmentation.
3. Paddle movements in the game are controlled based on the detected hand position.
4. The game logic manages the ball, paddle collision, and scoring.
