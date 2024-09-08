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
---

## How Safevision Meets the GovHack2024 AI in Governance Challenge Criteria

**Safevision** is designed as a practical solution for public health governance, leveraging AI to detect and count individuals with and without masks in real-time video feeds. Here's how it meets the key criteria of the **GovHack2024 AI in Governance Challenge**:

### 1. Operational Efficiency
Safevision automates the detection of mask compliance in public spaces, reducing the need for manual intervention. By analyzing video feeds in real-time, it provides immediate feedback on mask usage, helping authorities quickly allocate resources to areas where intervention is needed. This makes enforcement more efficient and frees up personnel for other critical tasks.

### 2. Privacy and Security
Privacy is at the core of Safevision. The system does not store or process any personal identification data—its sole focus is on detecting whether individuals are wearing masks. No video footage or personal information is saved, ensuring compliance with privacy regulations like GDPR. Data is minimized and encrypted when necessary to maintain secure communication between systems.

### 3. Transparency and Accountability
Safevision enhances transparency by generating anonymized reports on mask compliance, which can be shared with the public. This allows communities to see how well guidelines are being followed and provides accountability in the enforcement of public health measures. The open-source nature of the project allows for scrutiny and improvement by anyone.

### 4. Ethical Use of AI
Ethical AI principles are embedded in Safevision’s design. The system has been trained on a diverse dataset to ensure fairness across different demographic groups, reducing bias. It provides clear and simple predictions (with or without mask), ensuring transparency in how decisions are made. Safevision promotes fairness, transparency, and accountability, aligning with ethical AI standards.

### 5. Building Public Trust
By ensuring transparency and protecting privacy, Safevision helps build trust between the government and the public. Citizens can access anonymized compliance data, fostering a sense of collective responsibility in public health efforts. The emphasis on privacy reassures the public that their identities are not being tracked or stored.

### 6. Scalability and Future Adaptations
Safevision is designed to scale effortlessly—whether deployed in small government offices or large public spaces, it handles varying loads without sacrificing performance. Its adaptable architecture allows for integration with other public health monitoring needs, such as detecting social distancing or other health measures in future emergencies. Safevision can evolve with emerging AI technologies to continue serving public interests effectively.

---

### Conclusion
**Safevision** not only improves the efficiency of public health governance but does so ethically and transparently, ensuring privacy and building public trust. It's a scalable, adaptable solution for governments looking to leverage AI in real-time compliance monitoring.

---

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

