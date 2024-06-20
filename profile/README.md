# ASING! - Capstone Project Bangkit Team C241-PS157

## Overview

This project aims to address the issue of stunting in Indonesia by developing a machine learning model capable of classifying food into categories of 'worthy' or 'unworthy' for consumption by pregnant women. The classification will be achieved using Convolutional Neural Network (CNN) architecture, specifically leveraging a pre-trained MobileNet V2 model, implemented with TensorFlow and related libraries.

![Mockups](https://storage.googleapis.com/asing-frost/Introduction%F0%9F%8C%9B.png)


## Motivation

Stunting is a significant public health concern in Indonesia, affecting the physical and cognitive development of children. By ensuring that pregnant women have access to nutritious and suitable food, we aim to contribute to reducing the stunting rates. Our model will assist in identifying whether a given food item is recommended for consumption by pregnant women based on its nutritional content.

## Project Scope

The primary objective of this project is to develop a food classification system with the following features:
- Image Classification: The model will classify food items as either 'worthy' or 'unworthy' of consumption for pregnant women.
- Recommendation System: If the food item is not present in the dataset, it will be classified as 'unworthy' by default.
- Nutritional Education: The system will provide educational information about why certain foods are recommended or not.
- Valuable Articles/Tips: The application will offer valuable articles and tips related to nutrition, health, and well-being for pregnant women.

## Technology Stack

### Machine Learning
- Framework: TensorFlow
- Architecture: Convolutional Neural Networks (CNN), using a pre-trained MobileNet V2 model
- Programming Language: Python
- Development Environment: Google Colab

### Android Development
- Design Tool: Figma
- Programming Language: Kotlin
- Networking: Retrofit, OkHttp

### Cloud
- Cloud Provider: Google Cloud Platform
- Prgramming Language: NodeJS
- Backend Support: Integrating backend services using Google Cloud Platform for data storage, processing and deployment

## Dataset

The dataset used for training the model is sourced from a public URL on our Google Cloud Platform: [Dataset](https://storage.googleapis.com/dataset-dragon-frost/New_Asing_Classification.zip). 

## Implementation

The implementation involves developing a system that captures images of food items, processes these images through the trained CNN model, and provides a recommendation on whether the food is suitable for pregnant women. The Android application will interface with the backend supported by Google Cloud to deliver real-time recommendations and updates.

## Future Enhancements

Future enhancements may include:
- Integrated Healthcare Services: Providing a platform that integrates various healthcare services for pregnant women.
- AI Chatbot Consultation: Implementing an AI chatbot to offer real-time consultation and support.
- Expansion of Indonesian Food Dataset: Increasing the variety and volume of Indonesian food items in the dataset.
- Real-time Meal Reminder Notifications: Sending notifications to remind users about meal times and suitable food choices.
- Lifestyle Recommendations: Offering personalized lifestyle recommendations based on dietary habits and health data.

## Team Members

| ID           | Name                            | Institution                           | Role                                | Status  |
|--------------|---------------------------------|--------------------------------------|-------------------------------------|---------|
| M518D4KY2101 | Rifialdi Faturrochman           | Politeknik Enjinering Indorama       | Project Manager & Machine Learning  | Active  |
| M299D4KX2004 | Reisa Aulia Sodikin             | Universitas Pendidikan Indonesia     | Machine Learning                    | Active  |
| M299D4KY1393 | Muhammad Fadhillah Nursyawal    | Universitas Pendidikan Indonesia     | Machine Learning                    | Active  |
| C291D4KY0251 | Muhamad Lanang Abid Kusuma      | Universitas Pasundan                 | Cloud Computing                     | Active  |
| C518D4KY0469 | Fadli Nurhidayat                | Politeknik Enjinering Indorama       | Cloud Computing                     | Active  |
| A299D4KY4259 | Rachman Faiz Maulana            | Universitas Pendidikan Indonesia     | Mobile Development                  | Active  |
| A518D4KY4599 | Muhammad Daris Hafizh Permana   | Politeknik Enjinering Indorama       | Mobile Development                  | Active  |

## Conclusion

This project is a significant step towards leveraging machine learning to tackle the issue of stunting in Indonesia. By providing clear recommendations on food suitability for pregnant women, we hope to contribute to healthier pregnancies and better developmental outcomes for children.

## Contact

For more information, please contact:
- [Rifialdi Faturrochman](m518d4ky2101@bangkit.academy)
