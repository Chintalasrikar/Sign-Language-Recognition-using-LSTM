# Sign-Language-Recognition-using-LSTM

This project aims to bridge the communication gap between the hearing and speech-impaired communities and others by recognizing hand gestures and translating them into text or speech. We use an LSTM-based deep learning model, which excels at processing sequential data like hand movements in sign language. Keypoints are extracted from video frames using tools like MediaPipe or OpenCV, allowing the system to focus on essential features for accurate recognition. Python and TensorFlow power the backend, ensuring efficiency and scalability, while real-time video processing with OpenCV makes the model practical for live use. Together, these technologies create an inclusive and accessible solution for seamless communicatio

**About the Project**\n
We trained the model to recognize 10 common gestures:
Hello, Thanks, How are you, Fine, Good, Yes, Name, No, Happy, and House.
These gestures are interpreted from sequences of keypoints extracted from videos/images, making it an efficient tool for recognizing temporal patterns in sign language.

Here’s how the model works:

Input: Hand gesture video or image.
Processing: Keypoints are extracted using MediaPipe.
Output: The recognized gesture is displayed in text.

**Demo**
![hello](https://github.com/user-attachments/assets/e4376cb4-1588-48f4-8779-ba1145583816)

Figure: The model recognizing the "Hello" gesture.

![Screenshot 2024-09-11 122250](https://github.com/user-attachments/assets/9b275b8f-0f3e-41b8-be4e-a9f584b3b9d4)

Figure: The model recognizing the "Name" gesture.

**Features**
Recognition of 10 commonly used gestures.
Real-time gesture recognition capability.
High accuracy and efficient processing of sequential data.

**Getting Started**
1. Clone the Repository
git clone https://github.com/yourusername/sign-language-recognition.git
cd sign-language-recognition

2. Install Dependencies
pip install -r requirements.txt

**Technologies Used**
TensorFlow/Keras: For building and training the LSTM model.
OpenCV & MediaPipe: For video and keypoint extraction.
Python: Core programming language.
Matplotlib: For visualizing model performance

**License**
This project is licensed under the MIT License.
