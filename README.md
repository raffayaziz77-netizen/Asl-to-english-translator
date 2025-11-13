**ASL-to-English Translator**

\*\*ASL-to-English Translator\*\* is an AI-powered computer vision tool that uses \*\*Convolutional Neural Networks (CNNs)\*\* to translate basic \*\*American Sign Language (ASL)\*\* alphabets and digits into English text helping bridge the communication gap between the deaf and hearing communities.

\---

**Overview**

This project demonstrates how deep learning and computer vision can be combined to interpret sign language gestures from images and convert them into readable English text.    
It was trained on a \*\*public dataset\*\* containing ASL alphabets and digits.

\---

**Tech Stack**

\- \*\*Python 3.x\*\*  
\- \*\*PyTorch\*\* – model creation and training    
\- \*\*Torchvision\*\* – data transformations    
\- \*\*OpenCV\*\* – image handling and preprocessing    
\- \*\*PIL (Pillow)\*\* – image processing    
\- \*\*Matplotlib\*\* – visualization  

\---

**Project Structure**

ASL-to-English-Translator/  
│  
├── model/  
│ └── model link
│  
├── src/  
│ ├── train.py \# Model training script  
│ ├── test.py \# Model testing / prediction  
│ └── ASL-to-English Translator.txt \# Notes & example outputs  
│  
├── data/  
│ └── test\_images/ \# Sample ASL images for testing  
│  
├── requirements.txt  
├── .gitignore  
└── README.md

**How to Run**

1\. \*\*Clone this repository\*\*  
   git clone https://github.com/raffayaziz77-netizen/Asl-to-english-translator.git
   cd ASL-to-English-Translator

**Install dependencies**  
pip install \-r requirements.txt

**Run the model**  
python src/test.py  
✅ Works on both CPU and GPU

**Model Information**

Model Type: CNN (Convolutional Neural Network)  
Framework: PyTorch  
Dataset: Public ASL dataset (alphabets & digits)  
Input: Image of hand gesture  
Output: Predicted English letter or digit

**Training & test details included in:**  
📄 src/ASL-to-English Translator.txt

**Example Results**  
Example test results and explanations are included in the text file:  
src/ASL-to-English Translator.txt

**Future Enhancements**  
Add real-time webcam recognition  
Extend to ASL words and phrases  
Build a web interface (Streamlit/Flask) for live translation  
Include audio output for spoken English translation

**Author**  
Muhammad Raffay Aziz  
📧 raffayaziz77@gmail.com

**🪪 License**  
This project is released for educational and non-commercial use only.  
