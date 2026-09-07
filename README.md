🤖 Sarcasm Detector

Sarcasm Detector is a Flutter application built with Dart that uses an ONNX machine learning model to analyze user-provided text and classify whether it contains sarcastic content. The application performs AI inference directly on the device, providing real-time predictions without requiring a backend or external API.

✨ Key Features

* 🤖 Sarcasm detection using an ONNX ML model
* 📝 User-provided text analysis
* 🧠 On-device AI inference
* 📊 Text classification and prediction
* ⚡ Real-time prediction results
* 🔒 Offline processing without a backend
* 🧹 Text preprocessing for model inference
* 📱 Cross-platform Flutter implementation

🏗️ Architecture & Workflow

The Flutter UI collects text input from the user and preprocesses it before passing the data to the ONNX inference layer. The machine learning model processes the text directly on the device and returns a prediction indicating whether the content is sarcastic, which is then displayed through the Flutter interface.

🛠️ Tech Stack

Flutter • Dart • ONNX • Machine Learning • Text Classification • On-Device AI

🎯 Project Purpose

This project demonstrates how ONNX machine learning models can be integrated into Flutter applications for offline text classification. It provides practical experience with model inference, text preprocessing, AI integration, and real-time predictions while keeping the entire workflow on the device.
