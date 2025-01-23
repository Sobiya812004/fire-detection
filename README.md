
# AI-Based Fire Detection 🚒🔥

This project demonstrates an **AI-based fire detection system** that uses **Convolutional Neural Networks (CNNs)** for detecting fire in images or video frames. The model is trained on a dataset of fire and non-fire images and deployed to help in early fire detection, minimizing damage and saving lives.

## Features
- **Fire Detection**: Detects fire from video streams or images in real time.
- **Deep Learning Model**: Built using CNNs for accurate classification.
- **Live Feed Monitoring**: Integrates with a live video feed to detect fire as it happens.
- **Alerts**: Sends notifications or triggers alarms upon fire detection.
- **Scalability**: Can be integrated with IoT systems or surveillance cameras.

## Tools and Technologies
- **Python** for backend development.
- **OpenCV** for image processing.
- **TensorFlow/Keras** for building and training the CNN model.
- **Flask** or **FastAPI** for deploying the model as a web application.
- **MySQL** or **SQLite** for storing logs of detected incidents.
- **GitHub Actions** for CI/CD workflows (optional).

## Steps Included
1. **Data Collection and Preprocessing**:
   - Dataset of fire and non-fire images was collected from open-source repositories.
   - Data augmentation techniques were applied for improving model robustness.

2. **Model Training**:
   - A Convolutional Neural Network (CNN) was designed and trained using TensorFlow/Keras.
   - Hyperparameter tuning and optimization were performed to improve accuracy.

3. **Deployment**:
   - The model was wrapped in a REST API using Flask/FastAPI.
   - Integrated the API with a web interface for ease of use.

4. **Testing and Monitoring**:
   - The system was tested on various live streams and video footage for validation.
   - Logs of detected events are stored in the database for later analysis.

## Challenges Faced
- Ensuring real-time detection with minimal latency.
- Avoiding false positives from similar fire-like patterns (e.g., sunset, reflections).
- Balancing model accuracy and computational efficiency.

## Future Enhancements
- Add smoke detection capabilities for early warnings.
- Integrate with IoT sensors for enhanced fire monitoring.
- Deploy the system on edge devices for better scalability.
