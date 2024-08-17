Object Tracking and Counting with YOLOv8 and Norfair
Overview
This project demonstrates the use of the YOLOv8x model combined with Norfair tracking to detect, track, and count cars and motorcycles in a video. The project processes video frames in real-time, identifies vehicles, and tracks their movement to provide an accurate count of each object type.

Features
Real-time Object Detection: Utilizes YOLOv8x for detecting cars and motorcycles with high accuracy.
Object Tracking: Employs Norfair to track objects across frames, ensuring that each object is counted only once.
Video Annotation: Annotates the video with bounding boxes around detected objects and displays the total count of cars and motorcycles.

Code Explanation
YOLOv8 Model: The YOLOv8x model is loaded and used to detect objects in each video frame.
Norfair Tracker: Detections are passed to Norfair's tracker, which assigns unique IDs to each object, allowing accurate counting.
Counting Logic: Objects are counted based on their unique IDs, ensuring that the same object is not counted multiple times.
Video Annotation: The video is annotated with bounding boxes and the current count of cars and motorcycles.
Example Output
The output video shows the detected objects with bounding boxes and displays the total count of cars and motorcycles at the top of the frame.

Contributing
Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.

Acknowledgements
YOLOv8: For providing an exceptional object detection framework.
Norfair: For the powerful and easy-to-use tracking capabilities.
OpenCV: For handling video processing and annotations.
