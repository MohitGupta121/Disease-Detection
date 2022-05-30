# Disease Detection

![Build](https://github.com/MohitGupta121/DiseaseDetection/workflows/Build/badge.svg?branch=main)

[![GitHub license](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![ktlint](https://img.shields.io/badge/code%20style-%E2%9D%A4-FF4081.svg)](https://ktlint.github.io/)
![Twitter Follow](https://img.shields.io/twitter/follow/Mohit_Gupta121?label=Follow&style=social)

**Disease Detection** is a plant disease detecter ✅ Android application 📱 built using Tensorflow Lite, Kaggle and Teachable Machine.

***You can Install and test latest Disease Detection app from below 👇***

[![Disease Detection](https://img.shields.io/badge/DiseaseDetection✅-APK-red.svg?style=for-the-badge&logo=android)](https://github.com/hellosagar/AssigmentHub/releases/download/v1.2/app-release.apk)

## ⚙️ Features
* Take the image from camera and show Plant Disease.
* Also redirect to google for more details.

## 🚀 Technology Used

* Disease Detection built using Kotlin
* Kaggle
* Teachable Machine Model.
* Tensorflow Lite

## 📸 Screenshots

||||
|:----------------------------------------:|:-----------------------------------------:|:-----------------------------------------: |
<!-- | ![Imgur](https://user-images.githubusercontent.com/76530270/170965228-515111bc-e02c-49cf-878c-eed593ec8a85.png) | ![image](https://user-images.githubusercontent.com/76530270/170965417-b0a9e49a-a7bd-461a-bccd-5c73904f79ae.png) | ![image](https://user-images.githubusercontent.com/76530270/170965814-60209f61-6323-41d4-9978-70c52f788879.png) |
| ![image](https://user-images.githubusercontent.com/76530270/170965993-3942c71b-bd06-4307-acf5-56adbd4723b9.png) | ![image](https://user-images.githubusercontent.com/76530270/170966073-00ea3afa-f094-48a0-875c-264c83742c8c.png) | ![image](https://user-images.githubusercontent.com/76530270/170966221-b91ecc1f-0047-4c14-9b2f-fd92bb934b94.png) -->

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
    
    dev.hellosagar.assigmenthub    # Root Package
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

## License
```
MIT License

Copyright (c) 2022 Mohit Gupta

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
