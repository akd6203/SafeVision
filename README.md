# Safevision: AI-Powered Face Mask Detection for Public Health

**Safevision** is an AI-driven project designed to detect and count individuals wearing face masks in real-time video feeds, assisting public health governance during crises like the COVID-19 pandemic. Using computer vision and deep learning, Safevision helps authorities monitor mask compliance in public spaces without compromising privacy.

## Features

- **Real-time Mask Detection**: Accurately identifies people wearing or not wearing masks in live video streams.
- **Automated Monitoring**: Reduces the need for manual mask enforcement and allows efficient resource allocation.
- **Privacy-Focused**: Ensures that no personal identity information is collected or stored—focused only on mask detection.
- **Actionable Data**: Provides real-time statistics on mask compliance for public health authorities to make informed decisions.
- **Scalable and Customizable**: Can be integrated into surveillance systems in public places like hospitals, schools, transportation hubs, and government offices.

## Technologies Used

- **Deep Learning**: Utilizes a fine-tuned VGG16 model for mask detection.
- **Computer Vision**: OpenCV for video stream processing.
- **Python**: Backend code for video stream handling and logic.
- **Keras/TensorFlow**: Frameworks used to train and run the deep learning model.

## Installation

To run Safevision locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/akd6203/Safevision.git
    cd Safevision
    ```

2. Install required Python packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Download the trained model:
   Place the pre-trained `face_mask_fine_tune_model.h5` file in the project directory. You can download the model [here](#).

4. Run the mask detection application:
    ```bash
    python mask_detection_demo.py
    ```

## How It Works

- The system uses a **pre-trained VGG16 model** fine-tuned for mask detection.
- Video frames are captured using **OpenCV** from a webcam or video file.
- Each frame is processed, faces are detected, and the AI model predicts whether a person is wearing a mask or not.
- The video feed is displayed with bounding boxes around faces and mask/no-mask labels, along with real-time counters of masked and unmasked individuals.

## Contributing

Contributions are welcome! If you'd like to contribute to Safevision, please fork the repository and submit a pull request.

1. Fork the repository
2. Create a new branch (`git checkout -b master`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin master`)
5. Open a pull request

---

### Contact

For any inquiries or suggestions, feel free to reach out, Happy Learning!

