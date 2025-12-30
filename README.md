# CoOp: Context Optimization for Oxford-IIIT Pets (Colab Version)

This repository contains a Google Colab implementation of **CoOp (Context Optimization)** for Vision-Language Models. It demonstrates how to train prompt learners for the Oxford-IIIT Pets dataset using the Dassl framework and CLIP.

## 🚀 Project Overview
- **Method:** CoOp (Context Optimization)
- **Backbone:** CLIP (ViT-B/16 or ResNet)
- **Dataset:** Oxford-IIIT Pets (37 classes)
- **Experiments:** 1-shot, 4-shot, and 16-shot learning scenarios.
- **Environment:** Designed to run smoothly on Google Colab (Tesla T4 GPU).

## 📊 Features
- Automated environment setup (Dassl, CoOp, PyTorch).
- Automatic dataset downloading and preprocessing.
- Training pipeline for few-shot learning.
- Visualization of training results and accuracy metrics.
- Saves models directly to Google Drive.

## 🔧 Usage
You can run this project directly in your browser using Google Colab. No local setup is required.

<a href="https://colab.research.google.com/github/A-ABBAS-H/oOp-OxfordPets-Implementation/blob/main/CoOp_OxfordPets_Trainer.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>


## 📚 References
This project is based on the following works:
- [CoOp: Learning to Prompt for Vision-Language Models](https://github.com/KaiyangZhou/CoOp)
- [Dassl.pytorch](https://github.com/KaiyangZhou/Dassl.pytorch)

## 📄 License
This project follows the MIT License as per the original CoOp implementation.
