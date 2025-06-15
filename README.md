# Age-and-Gender-Detector
This project uses pre-trained deep learning models to perform real-time age and gender prediction from images or webcam input, built with OpenCV’s DNN module.

## 🚀 Features

- Detects gender: Male or Female
- Estimates age range (e.g., 25–32)
- Uses OpenCV's DNN module and pre-trained Caffe models
- Real-time webcam support or image-based detection

## 📁 Project Structure

Age_Gender_Detector/
├── age_deploy.prototxt
├── age_net.caffemodel
├── gender_deploy.prototxt
├── gender_net.caffemodel
├── example.jpg
├── detect.py
└── README.md


## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Age_Gender_Detector.git
   cd Age_Gender_Detector
   
#Install required packages:
pip install opencv-python numpy

🖼️ Usage
Detect age and gender from an image:
python detect.py --image example.jpg

For real-time detection using your webcam:
python detect.py --webcam

📊 Example Output
Detected: Female, Age: 25-32

🧠 Models Used
Age Detection: age_net.caffemodel (trained on Adience dataset)
Gender Detection: gender_net.caffemodel

📌 Dependencies
Python 3.x
OpenCV
NumPy

📝 License
This project is licensed under the MIT License.

🙋‍♂️ Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

### ✅ Next Steps:

1. Extract your zip
2. Add the `README.md` above
3. Run:

```bash
git init
git add .
git commit -m "Initial commit with age & gender detector"
git remote add origin https://github.com/yourusername/Age_Gender_Detector.git
git push -u origin main
