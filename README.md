# realtime-face-emotion-analysis

*italicized text*## Project Title: Real-time Face Detection and Emotion Analysis System

### Project Summary:
Developed and implemented a real-time computer vision system in Google Colab for robust face detection and emotion recognition from live webcam feeds, demonstrating expertise in deep learning model integration and front-end interaction for dynamic data capture.

### Key Technical Contributions:

*   **Architected** a seamless webcam integration using a custom JavaScript-Python interface within Google Colab, enabling real-time image acquisition and processing.
*   **Implemented** dual-approach face detection using:
    *   **OpenCV's Deep Neural Network (DNN) module** with a pre-trained Caffe model (`res10_300x300_ssd_iter_140000.caffemodel`) for high-accuracy bounding box generation and confidence scoring.
    *   The **`face_recognition` library** (built on `dlib`) for alternative robust facial feature localization.
*   **Integrated** the **`DeepFace` library** to perform advanced emotion analysis on detected faces, classifying sentiments (e.g., happiness, sadness, anger) directly from the visual input.
*   **Managed** comprehensive environment setup and dependency resolution, including `tensorflow`, `opencv-python-headless`, `dlib`, `face_recognition`, `DeepFace`, and `matplotlib`, ensuring functional stability within the Colab ecosystem.
*   **Optimized** computational resource allocation by explicitly configuring TensorFlow for CPU-only execution, enhancing portability and demonstrating adaptability across different hardware configurations.
*   **Utilized** `cv2_imshow` and `matplotlib.pyplot` for dynamic visualization of processed images, displaying detected faces with overlaid bounding boxes, confidence scores, and predicted emotions.

### Technologies & Libraries:
`Python`, `OpenCV (cv2)`, `imutils`, `tensorflow`, `numpy`, `dlib`, `face_recognition`, `DeepFace`, `matplotlib`, `Google Colab (JavaScript integration)`
