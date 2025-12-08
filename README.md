# Vehicle Detection using YOLOv8m

This project uses the Ultralytics YOLOv8m model to detect vehicles (cars, bikes, buses, trucks) from images and videos. The model is trained in Google Colab using a Kaggle dataset.

Dataset link:
https://www.kaggle.com/datasets/ashfakyeafi/road-vehicle-images-dataset

--------------------------------------------------------------------------------

## Project Features
- YOLOv8m vehicle detection
- Kaggle API dataset download
- Image detection
- Video detection
- Exportable trained weights 
- Google Colab training notebook

--------------------------------------------------------------------------------

## Dataset
Name: Road Vehicle Images Dataset  
Source: Kaggle  
Link: https://www.kaggle.com/datasets/ashfakyeafi/road-vehicle-images-dataset

You must use your own Kaggle API key (kaggle.json).  
If you do not know how to get it, follow these steps:

1. Go to Kaggle → Profile → Account  
2. Find the API section  
3. Click "Create New API Token"  
4. This downloads kaggle.json  
5. Upload it in Step 2

--------------------------------------------------------------------------------

Results

Add your result images and videos in the results/ folder:

results/
├── image_result.jpg

--------------------------------------------------------------------------------


Files in This Repository

Vehicle_detection.ipynb
README.md
results/
best.pt (optional)

--------------------------------------------------------------------------------

Future Improvements

Add Streamlit interface

Add webcam live detection

Export ONNX/TFLite models

--------------------------------------------------------------------------------

Credits

Dataset by Ashfak Yeafi (Kaggle)

Model: Ultralytics YOLOv8
