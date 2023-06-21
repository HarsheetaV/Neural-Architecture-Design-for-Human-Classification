# Neural-Architecture-Design-for-Human-Classification
Machine learning and Data Science project mentored by Amazon Lab 126

This project contains confidential materials and code. Therefore, I have uploaded a poster in PDF format that provides an overview and understanding of the project's objectives and activities.

Amazon Lab126, a research and computer hardware company owned by Amazon, is undertaking a project focused on developing a deep neural network for human classification. The objective is to build a network with the highest possible accuracy in classifying humans,
leveraging the capabilities of deep neural networks trained on the ImageNet dataset, which encompasses over 1000 classes. However, this project specifically concentrates on human classification, narrowing down the scope of classification tasks.

Step by Step approach of the project:

1) Finetuning Mobile Net V2 for Human Classification:
The initial phase involved collecting a diverse dataset of human images labeled with their corresponding classes. The
dataset was then prepared through tasks such as image resizing, cropping, and normalization. The pre-trained MobileNetV2model was fine-tuned using an appropriate optimizer, loss function, and evaluation metric to achieve optimal performance in human classification.

2) Improved Model and Preliminary Edge Device Implementation:
The focus of this phase was to evaluate the model's performance on a validation dataset using various metrics, including accuracy, precision, recall, confusion matrix, and F1-score. Hyperparametersand architecture were optimized to enhance the model's accuracy. Basic
models were implemented and tested using both TensorFlow and PyTorch frameworks. The primary goal was to achieve a 95% accuracy rate.

3) Model Compression and Continued Edge Device Implementation:
TensorFlow Lite was compiled for the Raspberry Pi's processor architecture and installed on the device. The deep learning model underwent compression techniques while ensuring a minimal impact on accuracy, aiming to maintain a 95%+ accuracy level.

4) Full Edge Device Implementation:
The deep learning model was converted from its original format to TensorFlow Lite format usingthe TensorFlow Lite
converter. On the Raspberry Pi, extensive model inference was conducted to ensure real-time
processing and compliance withthe device's memory constraints.

5) Exploration of Compression and Quantization Techniques:
A variety of compression and quantization techniques were explored, considering different model types.
Quantization was performed, and research was conducted on Quantization-Aware Training (QAT) to further enhance model efficiency. Sensitivity analysis was carried out to gain deeper insights into the MobileNetV2 architecture and fine-tuning. In any available time, additional research was conducted on topics such as Fused IBN and Neural Architecture Search toexpand knowledge and potential
improvements.

The project schedule provided a clear roadmap for the team's activities, ensuring a systematic approach to model development, optimization, and deployment on edge devices. The completed milestones and tasks demonstrated steady progresstowards achieving the project's objectives.
