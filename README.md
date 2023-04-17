# Disease Detection

![Build](https://github.com/MohitGupta121/DiseaseDetection/workflows/Build/badge.svg?branch=main)

[![GitHub license](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![ktlint](https://img.shields.io/badge/code%20style-%E2%9D%A4-FF4081.svg)](https://ktlint.github.io/)
![Twitter Follow](https://img.shields.io/twitter/follow/Mohit_Gupta121?label=Follow&style=social)

**Disease Detection** is a plant disease detecter ✅ Android application 📱 built using Tensorflow Lite, Kaggle and Teachable Machine.

***You can Install and test latest Disease Detection app from below 👇***

[![Disease Detection](https://img.shields.io/badge/DiseaseDetection✅-APK-red.svg?style=for-the-badge&logo=android)](https://github.com/MohitGupta121/DiseaseDetection/suites/6711576160/artifacts/255441035)

## ⚙️ Features
* Take the image from camera and get Plant Disease.
* Also redirect to google for more details.

## 🚀 Technology Used

* Kaggle
* Teachable Machine Model.
* Tensorflow Lite

## 📸 Screenshots

||||
|:----------------------------------------:|:-----------------------------------------:|:-----------------------------------------: |
| ![diseasedetection](https://user-images.githubusercontent.com/76530270/171112927-78ed3aa4-2fdc-42e8-9be4-e842aee7733c.jpg) | ![Screenshot_2022-05-31-12-23-27-332_com android camera](https://user-images.githubusercontent.com/76530270/171113244-c10be32c-c473-49fa-9263-f5f3c613d407.jpg) | ![Screenshot_2022-05-31-12-22-58-343_com example diseasedetection](https://user-images.githubusercontent.com/76530270/171113116-43214846-5c3e-4600-9341-07adfe5644d0.jpg) | 

## 🎥 Demo Screen Recording

https://user-images.githubusercontent.com/76530270/171112532-aa2b4ed7-b36e-4cf6-915a-91a8c216f781.mp4


## Built With 🛠
- [Kotlin](https://kotlinlang.org/) - First class and official programming language for Android development.
- [Android Architecture Components](https://developer.android.com/topic/libraries/architecture) - Collection of libraries that help you design robust, testable, and maintainable apps.
  - [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel) - Stores UI-related data that isn't destroyed on UI changes. 
  - [ViewBinding](https://developer.android.com/topic/libraries/view-binding) - Generates a binding class for each XML layout file present in that module and allows you to more easily write code that interacts with views.
- [Material Components for Android](https://github.com/material-components/material-components-android) - Modular and customizable Material Design UI components for Android.
- [Teachable Machine](https://teachablemachine.withgoogle.com/) - A fast, easy way to create machine learning models for your sites, apps, and more – no expertise or coding required.
- [Kaggle](https://www.kaggle.com/) Kaggle, a subsidiary of Google LLC, is an online community of data scientists and machine learning practitioners.
- [Tensorflow Lite](https://www.tensorflow.org/lite) TensorFlow Lite is a mobile library for deploying models on mobile, microcontrollers and other edge devices. 


# Package Structure
    
    com.example.diseasedetection    # Root Package
    .
    ├── data                # For data handling.
    │   └── repository      # Single source of data.   
    |
    ├── di                  # Dependency Injection             
    |
    ├── ui                  # Activity/View layer
    │   ├── viewmodel       # ViewModels
    │   └── adapter         # Adpaters
    │   └── fragment        # Fragnents
    |
    └── utils               # Utility Classes / Kotlin extensions
   
       
## ⚡ Dependencies Used
```sh
* Tensorflow Lite 0.1.0
```


