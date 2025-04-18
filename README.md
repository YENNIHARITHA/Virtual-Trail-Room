# Virtual Fitting Room
## Overview
The Virtual Fitting Room is an AI and Augmented Reality (AR) based application that allows users to try on clothes virtually using their webcam. This eliminates the need for physical trials, making online shopping more interactive and efficient. Users can select multiple clothing items for both men and women and see how they would look in real time.

## Features
Real-time virtual try-on using webcam

Clothing selection interface (for men and women)

Multi-person try-on capability

AR-based clothing overlay

Pose estimation for realistic fitting

Support for multiple body types and sizes

Interactive UI with "Try On" functionality

## Technologies Used
Frontend: React.js (Web UI)

Backend: Flask (Python)

Database: MongoDB (Database name: user_db, collection: users)

## Machine Learning / AI:

Human Pose Estimation: MediaPipe / OpenPose

Clothing Overlay: CP-VTON or similar

Image Segmentation: U-Net or DeepLabV3+

Augmented Reality: OpenCV with webcam stream

Languages: Python, JavaScript, HTML, CSS

## How to Use
Launch the web interface.

Log in or sign up to access the dashboard.

Select clothing items from the home page.

Click on the "Try On" button.

Stand in front of the webcam to see the selected clothes applied to your body.

Try out different styles and outfits in real time.

## Installation
Backend (Flask)

## Clone the repository:

git clone https://github.com/yourusername/virtual-fitting-room.git
cd virtual-fitting-room/backend

## Create a virtual environment and install dependencies:

python -m venv venv
source venv/bin/activate  # On Windows use venv\Scripts\activate
pip install -r requirements.txt

## Run the Flask server:

python app.py
Frontend (React)

## Navigate to the frontend directory:

cd ../frontend

## Install dependencies:

npm install

## Start the development server:

npm start
Database
Ensure MongoDB is installed and running. Use the user_db database and users collection for storing user data.

## Future Enhancements

More advanced garment fitting and cloth simulation

Mobile camera support

Fashion recommendation system using AI

Integration with e-commerce platforms

Save and share outfit previews

## OutputScreens

## Index Page
![Alt text](https://github.com/YENNIHARITHA/Virtual-Trail-Room/blob/8f61a189adc312c92acf43c5ad0a99954377a428/OutputScreens/index.png)

## View Selected Clothes
![Alt text](https://github.com/YENNIHARITHA/Virtual-Trail-Room/blob/8f61a189adc312c92acf43c5ad0a99954377a428/OutputScreens/view-selected-clothes.png
)

## Multiple User Tryon
![Alt text](https://github.com/YENNIHARITHA/Virtual-Trail-Room/blob/8f61a189adc312c92acf43c5ad0a99954377a428/OutputScreens/multiple-users-tryon.jpg)


