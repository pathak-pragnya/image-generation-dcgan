# **Image Generation using Deep Convolutional GAN (DCGAN)**

## **Overview**
This project demonstrates the implementation of a Deep Convolutional Generative Adversarial Network (DCGAN) to generate high-quality images. The model is trained on a custom dataset of images, focusing on generating realistic outputs by leveraging adversarial training techniques.

---

## **Features**
- **Custom Dataset**:
  - The model is trained on a dataset of .
  - Includes preprocessing steps like resizing, normalization, and augmentation for optimal training.

- **DCGAN Architecture**:
  - Generator and Discriminator networks are built using convolutional layers.
  - Utilizes Batch Normalization, LeakyReLU, and Tanh activation functions.

- **Visualization**:
  - Real-time visualization of training progress.
  - Generates and saves images at regular intervals during training.

- **Hyperparameter Tuning**:
  - Configurable parameters like learning rate, batch size, and number of epochs.

---

## **Technical Details**
### **Generator Architecture**
- Transposed Convolution layers to upscale latent vectors into realistic images.
- Batch Normalization for stabilizing training.
- Tanh activation for the output layer.

### **Discriminator Architecture**
- Convolutional layers to classify real vs. fake images.
- LeakyReLU activation to handle negative values effectively.
- Sigmoid activation for binary classification.

### **Adversarial Training**
- The generator learns to fool the discriminator by generating realistic images.
- The discriminator learns to differentiate between real and generated images.
- Both networks are trained alternately to improve performance.

---

## **Results**
- **Generated Images**:
  - ![image](https://github.com/user-attachments/assets/ab5cd8db-9c0e-4bd3-bcd2-f77787598d05)


- **Training Metrics**:
  - Generator and Discriminator losses are tracked and visualized during training.
  - Gradual improvement in the quality of generated images over epochs.

---

## **How to Run**
### **1. Clone the Repository**
```bash
git clone https://github.com/pathak-pragnya/image-generation-dcgan.git
cd image-generation-dcgan

