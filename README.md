# deep-learning-fashion-image-classification
Deep Learning practical for fashion image classification using TensorFlow/Keras and Fashion MNIST, with a business application for automated product categorization in e-commerce.
# Deep Learning Fashion Image Classification

This repository contains a practical implementation of **Deep Learning for Fashion Image Classification** using Python, TensorFlow/Keras, and the Fashion MNIST dataset.

The practical is designed for BBA AI/ML students and connects Deep Learning concepts with a real-world **e-commerce business application**.

## 📌 Business Scenario

An e-commerce company receives thousands of product images every day.

Instead of manually identifying and categorizing every product, a Deep Learning model can automatically classify images into categories such as:

- T-shirt/Top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle Boot

The model takes a product image as input and predicts its product category.

## 🎯 Learning Objectives

This practical demonstrates how to:

- Use images as input for Deep Learning.
- Build a simple Artificial Neural Network.
- Understand input, hidden, and output layers.
- Train a model using labelled product images.
- Evaluate model accuracy.
- Predict product categories from images.
- Connect Deep Learning outputs with a business use case.

## 🧠 Deep Learning Approach

The practical uses a simple **Artificial Neural Network (ANN)**.

### Model Structure

```text
Product Image
      ↓
   Flatten
      ↓
Dense Hidden Layer
   64 Neurons
      ↓
     ReLU
      ↓
Output Layer
  10 Classes
      ↓
   Softmax
      ↓
Predicted Product Category
