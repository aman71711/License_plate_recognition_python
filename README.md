License plate recognition system using Python. This system uses machine learning to detect license plates from images, videos, and webcams. The prerequisites for this system are Windows or Linux, an internet connection, and Python 3.8.0+. 

Here are the steps to install the system:

Clone the repository to your directory using this command:
git clone https://github.com/aman71711/License_plate_recognition_python.git

Navigate to the LPR directory using this command: 
cd LPR

Install the required packages using this command:
pip install -r requirements.txt

After the installation is complete, you can use the system as follows:

For webcam:
python number_plate.py
Save the image using 's'. The images will be saved in "\runs\detect\cam". Run the OCR notebook to extract text from the saved images.

For any image:
python predict.py model='best.pt' source="path of image"

For any video:
python predict.py model='best.pt' source="path of Video"



