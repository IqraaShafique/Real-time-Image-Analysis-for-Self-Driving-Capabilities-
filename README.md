# Real-time-Image-Analysis-for-Self-Driving-Capabilities-
This project explores the development of a real-time visual navigation system for self-driving cars 
using traditional image processing techniques on a resource-constrained platform, specifically 
the Raspberry Pi 5. The system is designed to perform functions lane detection, obstacle 
detection, and directional decision-making without the use of deep learning, demonstrating that 
reliable autonomy can be both efficient and cost-effective for embedded systems. The pipeline 
begins with preprocessing frames to isolate yellow lane markings using HSV color segmentation 
and histogram equalization. Lane lines are then detected using Canny edge detection and the 
Hough Transform. Based on these lane lines, a region-of-interest mask is generated to focus 
obstacle detection efforts. Obstacle identification is performed using edge-based contour 
analysis, applying geometric filtering to distinguish valid objects. A decision-making module 
evaluates obstacle positions to suggest whether the vehicle should stop, move forward, or turn. 
Real-time performance is ensured through efficient frame processing and FPS calculation, with 
visual feedback provided for debugging and system analysis.  
