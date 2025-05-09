# AI-Capstone-Project-with-Deep-Learning-by-IBM

# Crack Detection in Building Walls

This project is designed to automate the detection of cracks in building walls using computer vision. By leveraging deep learning techniques, this model can analyze images of building walls and accurately determine the presence of cracks, which is crucial for building inspection and maintenance.

## 🚀 **Project Overview**

The goal of this project is to build a crack detection system that can be used for monitoring and inspection of building walls. It helps in identifying structural damages that might go unnoticed, allowing for proactive maintenance and safety measures.

## 🔍 **Dataset**

The dataset consists of **40,000 images** of building walls, where:
- **20,000 images** contain cracks.
- **20,000 images** have no cracks.

These images are RGB (colored) and have dimensions of **227x227** pixels.

## 🧠 **Model Architecture**

For this project, we are using the **ResNet50** pretrained model, a deep convolutional neural network that has been fine-tuned for this specific task. The output layer has been modified to classify images into two categories:
- **1**: Crack present.
- **0**: No crack.

The model leverages transfer learning, making it more efficient in detecting cracks with fewer training resources.

## 📊 **Training and Testing**

- **Training Split**: 75% (30,000 images)
- **Testing Split**: 25% (10,000 images)

The images are processed, and the training process uses **cross-entropy loss** for binary classification.

## ⚙️ **Technologies Used**

- **Keras** (with TensorFlow backend) for building and training the deep learning model.
- **ResNet50** pretrained model.
- **Python** for the implementation.
- **TensorFlow** for model deployment and evaluation.

## 🏆 **IBM Certification**

This project was developed as part of my IBM certification in **AI and Machine Learning**. It demonstrates practical experience with deep learning frameworks and computer vision tasks.

## 🤝 **Contributing**

Contributions are welcome! If you find any bugs or have suggestions for improvements, feel free to open an issue or submit a pull request.

## 📜 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Author
**Ridham Garg**  
B.Tech 3rd Year  
Thapar University
