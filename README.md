
# Potato Disease Classification using CNN

### Overview
This project aims to classify potato diseases using Convolutional Neural Networks (CNN). It utilizes TensorFlow for deep learning, FastAPI for building the API, and additional libraries for image processing and visualization.

### Target Audience
This project is designed for Machine Learning developers interested in potato disease classification and leveraging CNNs for image classification tasks.

### Datasets

https://www.kaggle.com/arjuntejaswi/plant-village

### Technologies Used
- TensorFlow 2.5.0
- FastAPI
- Uvicorn
- Python-Multipart
- Pillow
- TensorFlow Serving API 2.5.0
- Matplotlib
- NumPy

### Installation
To use this project, make sure you have Python installed. Then, install the required dependencies using the following command:
```pip install -r requirements.txt```

### Usage

Navigate to the **api** folder.
Run the **main.py** file.

```
cd api
python main.py
```
1. Test the project using Postman or your preferred API testing tool.


### API Endpoints
**/predict:**  POST endpoint for classifying potato disease. Send an image file in the request.

### Example Usage
1. Start the server as mentioned in the "Usage" section.
2. Open Postman and send a POST request to http://localhost:8000/predict.
3. Attach an image file in the request.
4. Receive the classification result in the response.
