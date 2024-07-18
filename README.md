# Smart_IP_Camera


This project presents a real-time **Face Recognition System** using deep learning techniques. The primary goal of this project is to develop a robust and efficient face recognition model capable of recognizing individuals under various conditions and environments.

**Methodology**
This approach leverages the power of Siamese Networks with triplet loss. The model is trained on a diverse dataset of celebrity faces, which includes varying poses, expressions, and lighting conditions.

**Face Detection:** Utilizes the MediaPipe framework for real-time face detection.
**Facial Recognition:** Employs the trained Siamese network model for recognizing faces.

**Key Features**
High accuracy in recognizing known individuals(84.5% accuracy). 
Effective real-time performance.
Capability to appropriately identify unknown faces.
Incorporation of padding and bounding box adjustments to ensure the detected faces encompass the entire head region, improving accuracy.
