# Video Forgery Detection

## Objective
**Video Forgery Detection** is an AI-powered system designed to identify fake and manipulated videos (deepfakes).  
The system leverages deep learning, computer vision, and NLP-based techniques to analyze facial movements, audio-visual synchronization, and pixel-level inconsistencies, ensuring accurate detection of video authenticity.  

## Features
- Detects and classifies **fake vs. real videos**.  
- Extracts and analyzes frames for forgery artifacts.  
- Detects facial inconsistencies, lip-sync mismatches, and blending artifacts.  
- Supports preprocessing of video data (frame extraction, resizing, noise reduction).  
- Tracks performance and experiments with MLflow.  
- Provides a user-friendly web interface for real-time video verification.  

## Technologies Used
- **Programming Languages:**  
  - Python  

- **Frameworks and Libraries:**  
  - TensorFlow / PyTorch  
  - OpenCV (video preprocessing & frame extraction)  
  - MediaPipe / Dlib (facial landmark detection)  
  - Hugging Face Transformers (for vision-language models)  
  - Scikit-learn  

- **Datasets:**  
  - Deepfake Detection Challenge (DFDC)  
  - FaceForensics++  
  - Celeb-DF  
  - Custom datasets for fine-tuning  

## Future Improvements
- Real-time detection during live video streams.  
- Multi-modal detection combining **video + audio forgery analysis**.  
- Model optimization for deployment on mobile and edge devices.  
