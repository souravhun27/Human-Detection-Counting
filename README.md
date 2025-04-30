🚶‍♂️ Real-Time Human Detection & Counting
A TensorFlow-based application utilizing the Faster R-CNN Inception v2 model to detect and count humans in real-time from images, videos, and live camera feeds. The system provides visual analytics and generates comprehensive crowd reports in PDF format.​

📌 Features
Real-Time Detection: Processes images, videos, and live camera feeds to detect and count humans.

Pre-trained Model: Employs frozen_inference_graph.pb for efficient detection.

User-Friendly GUI: Built with Tkinter for intuitive interaction.

Visual Analytics: Generates Enumeration and Average Accuracy plots.

PDF Reporting: Creates detailed crowd reports summarizing detection statistics.​
GitHub
+3
GitHub
+3
GitHub
+3

🛠️ Requirements
Ensure the following dependencies are installed:

bash
Copy code
python3
tkinter
Pillow
opencv-python
matplotlib
numpy
tensorflow
fpdf
Install them using pip:

bash
Copy code
pip install -r requirements.txt
🚀 Getting Started
Clone the Repository:

bash
Copy code
git clone https://github.com/souravhun27/Real-Time-Human-Detection-Counting.git
cd Real-Time-Human-Detection-Counting
Run the Application:

bash
Copy code
python main.py
🖥️ Usage
Upon launching the application:

Start Screen: Choose between START to begin or EXIT to close the application.

Detection Options:

Image Detection: Select an image file to detect and count humans.

Video Detection: Select a video file for processing.

Camera Detection: Use your device's camera for live detection.

Process Flow:

Select File: Choose the desired media file.

Preview: View the selected media.

Detect: Initiate the detection and counting process.

Results:

Plots: View Enumeration and Average Accuracy plots.

Report: Generate a PDF report detailing detection statistics.​
GitHub
GitHub
+9
GitHub
+9
GitHub
+9

📊 Output
Enumeration Plot: Displays human count over time.

Average Accuracy Plot: Shows detection accuracy trends.

PDF Report: Includes maximum human count, accuracy metrics, and a brief crowd status summary.​

📁 Project Structure
bash
Copy code
├── main.py
├── frozen_inference_graph.pb
├── requirements.txt
├── Screenshots/
├── utils/
├── outputs/
├── README.md
📷 Screenshots
Image Detection
Video Detection
Camera Detection

