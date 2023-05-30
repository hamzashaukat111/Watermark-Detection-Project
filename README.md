# Watermark-Detection-Project


This web application allows users to upload an image and detects whether it contains a watermark or not. The image is sent to Azure's Custom Vision service,  which uses a custom vision model I made and trained on a large dataset of watermark and non-watermark images.

## Features
- Upload an image to be processed by the watermark detection model.
- Utilize a custom vision model trained on a large dataset of watermark and non-watermark images.
- Display the prediction result with the probability of containing a watermark or not.
- Show a visual representation of the prediction result using a percentage bar.
- Ensure the model's accuracy by training on a diverse and extensive dataset.
<img width="1178" alt="dippp" src="https://github.com/hamzashaukat111/Watermark-Detection-Project/assets/75229817/2ff128e4-64c1-4667-8184-940d77686c47">

<img width="1200" alt="dipAppHam" src="https://github.com/hamzashaukat111/Watermark-Detection-Project/assets/75229817/db8bc458-e835-4483-af7c-16f15228252d">

## Technologies Used

- HTML
- CSS (Bootstrap 5)
- JavaScript (jQuery)
- Azure Custom Vision (Cognitive Services)

## Usage

1. Clone the repository: `git clone https://github.com/your-username/your-repository.git`
2. Open `index.html` in a web browser.
3. Click the "Choose File" button to select an image file.
4. Click the "Check Image" button to process the image and display the result.

## Configuration

To configure the application to work with your Azure Custom Vision model, update the following details in the `script.js` file:

- **Endpoint**: Replace `<YOUR_CUSTOM_VISION_ENDPOINT>` with your Azure Custom Vision endpoint URL.
- **Prediction-Key**: Replace `<YOUR_PREDICTION_KEY>` with your Azure Custom Vision prediction key.
