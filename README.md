AI-POWERED-WEARABLE-ASSISTANT

An intelligent wearable assistant designed for visually impaired individuals, leveraging AI, computer vision, and speech technologies to provide real-time assistance, situational awareness, and enhanced accessibility.

Badges:
Python 3.11 | MIT License | Active Development

________________________________________

📌 Table of Contents
1.	Overview
2.	UI/UX Design
3.	Current Features
4.	Future Features
5.	Technical Architecture
6.	Installation
7.	Usage
8.	Screenshots / GIFs
9.	License

________________________________________

🌟 Overview
AI-POWERED-WEARABLE-ASSISTANT is a fully integrated AI solution designed to empower visually impaired users by providing real-time environmental feedback. The system combines object recognition, color and currency detection, OCR, text-to-speech, and emergency alerts, making daily tasks safer, faster, and more independent.

Core Technologies:
Python, OpenCV, TensorFlow, YOLOv8, EasyOCR, PyTTSx3, gTTS

The system emphasizes instant audio feedback, multi-object awareness, and user-friendly interaction, transforming complex computer vision tasks into intuitive guidance for the visually impaired.

________________________________________

🖥️ UI/UX Design

•	Minimalist and intuitive interface with large buttons and readable text.

•	Real-time camera feed providing live object, color, and currency detection.

•	Audio feedback for every interaction, ensuring accessibility without visual dependency.

•	SOS emergency feature accessible in a single step.

•	Optional visual indicators for partially sighted users.

•	Designed for both wearable integration and desktop usage, supporting hands-free and voice-guided operation.


________________________________________

🚀 Current Features

🆘 SOS Alert

•	Instantly sends emergency alerts to preconfigured contacts.

•	Optional location sharing via messaging services.

•	Audio confirmation ensures user awareness of sent alerts.


🎨 Color Detection

•	Identifies and announces colors of multiple objects in real-time.

•	Highlights detected objects with bounding boxes for partial visual feedback.


💵 Currency Detection

•	Detects Indian currency denominations: ₹10, ₹20, ₹50, ₹100, ₹200, ₹500, ₹2000.

•	Announces the denomination through audio output.

•	Supports detection of multiple notes simultaneously.


📝 OCR + Text-to-Speech

•	Recognizes printed or handwritten text from live or static images.

•	Converts recognized text to speech using PyTTSx3 or gTTS.

•	Useful for reading documents, signs, and product labels.


🏷️ Object Detection

•	Uses YOLOv8 for accurate real-time detection of surrounding objects.

•	Audio alerts guide the user about nearby objects.

•	Multi-object detection ensures comprehensive situational awareness.


________________________________________

🔮 Future Features

•	Real-Time Object Detection & Tracking – Tracks moving objects and alerts users to approaching hazards.

•	Scene Description – Provides a natural language summary of the environment.

•	Voice Commands – Full hands-free operation to control all features.

•	Multi-Language Support – Supports text recognition and speech output in regional languages.

•	Face Recognition – Identifies familiar people and announces their names.

•	Obstacle Distance Estimation – Uses sensors or computer vision to warn about nearby obstacles.

•	Smart Daily Assistance – Offers reminders for medications, appointments, and navigation.

•	Contextual Environment Awareness – Advanced AI to provide situational insights, like crowded areas or moving objects.

•	Adaptive Learning – System learns user preferences and frequently visited locations to improve assistance over time.


________________________________________

🏗️ Technical Architecture

•	Input Layer: Live video feed from camera or wearable device.

•	Processing Layer: YOLOv8 for object detection, EasyOCR for text extraction, and HSV-based color detection.

•	Speech Layer: PyTTSx3/gTTS converts recognized objects, colors, and text into real-time audio.

•	Alert Layer: SOS and hazard alerts with optional location sharing.

•	Future Modules: Voice command processor, scene description engine, and multi-language support.


________________________________________

⚙️ Installation

1.	Clone the repository:

git clone https://github.com/Deepak44x2/aipowered.git

cd AI-POWERED-WEARABLE-ASSISTANT

2.	Create a virtual environment (recommended):

python -m venv venv

source venv/bin/activate   # Linux / Mac

venv\Scripts\activate      # Windows

3.	Install dependencies:
   
pip install -r requirements.txt

4.	Run the main script:

python main.py

Note: Some modules require YOLOv8 weights, microphone access, or webcam permissions.


________________________________________
🎯 Usage

1.	Launch main.py.

2.	Choose a feature: Color Detection, Currency Detection, OCR, Object Detection, or SOS.
   
3.	Follow audio guidance to interact with detected objects.
   
4.	Future voice command support allows fully hands-free operation.
   

________________________________________
📷 Screenshots / GIFs



**SOS PAGE:**

<img width="565" height="971" alt="sos1" src="https://github.com/user-attachments/assets/6a39c339-3bd4-448f-84bb-27fd5396134f" />
<img width="612" height="967" alt="sos2" src="https://github.com/user-attachments/assets/d1e33939-682d-4674-9338-7aabddf9caaf" />
<img width="548" height="972" alt="sos3" src="https://github.com/user-attachments/assets/0b587b32-e8f6-4d91-bce2-387089d5efab" />





**OBJECT DETECTION **




![object detection](https://github.com/user-attachments/assets/7ed89560-deaf-441e-8324-f0e3431fcd2b)
![ob2](https://github.com/user-attachments/assets/3fa85b5a-c417-495d-b903-c462b9e1ef02)



**COLOR DETECTION **



![color 1](https://github.com/user-attachments/assets/6c3aff9d-7b83-4f7f-b09e-6ac592353882)
![color 2](https://github.com/user-attachments/assets/5afae56a-8f54-4ddd-a5f0-9fb649c5b18a)
![color 3](https://github.com/user-attachments/assets/0d723db7-0cc4-491f-9c85-783174bd5f93)

**Optical Character Recognition**

<img width="1581" height="847" alt="image" src="https://github.com/user-attachments/assets/0603ad55-7ca9-47ce-bca0-e7250ac077fa" />
<img width="1575" height="841" alt="image" src="https://github.com/user-attachments/assets/873af816-9ecf-44b0-8bba-4aaae6e6e06f" />




________________________________________

📜 License

This project is licensed under the MIT License – see LICENSE for details.








