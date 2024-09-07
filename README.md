# Deep Learning for Automatic Pneumonia Detection

Pneumonia is the leading cause of death among young children and one of the top mortality causes worldwide. The pneumonia detection is usually performed through examine of chest X-Ray radiograph by highly trained specialists. This process is tedious and often leads to a disagreement between radiologists. Computer-aided diagnosis systems showed potential for improving the diagnostic accuracy. In this work, we develop the computational approach for pneumonia regions detection based on single-shot detectors, squeeze-and-extinction deep convolution neural networks, augmentations and multi-task learning.

## Tech Stack
- Backend: MongoDB, Express, Node.js
- Frontend: React, Next.js
- Server: NGINX web server
- Deployment: Hosted on DigitalOcean

## Web Application Features
- User Authentication: Only logged-in users can make predictions.
- Image Upload and Prediction: Users can upload X-ray images, and the app predicts whether the image depicts pneumonia or not.
- Fast Inferences: Inference speed is nearly instant, with high confidence values (e.g., 99% probability of pneumonia).
