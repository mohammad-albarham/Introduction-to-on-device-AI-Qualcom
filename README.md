# Introduction to On-Device AI

![Introduction to On-Device AI course banner](course-banner.jpg)

This repository contains the hands-on notebooks and supporting material for [Introduction to On-Device AI](https://www.deeplearning.ai/courses/introduction-to-on-device-ai), a DeepLearning.AI short course taught by **Krishna Sridhar**, Senior Director of Engineering at Qualcomm.

The course introduces the practical techniques used to move machine learning models from the cloud to smartphones and other edge devices. You will work through model compilation, hardware acceleration, profiling, quantization, and deployment using an image-segmentation example.

## What You Will Learn

- Why on-device inference can reduce latency, improve efficiency, and help preserve privacy
- How to prepare PyTorch and TensorFlow models for device deployment
- How to compile models and use CPU, GPU, and NPU compute units
- How to profile on-device performance and validate numerical accuracy
- How post-training quantization can make models smaller and faster
- How to deploy an image-segmentation model to a real smartphone
- The main steps for integrating an optimized model into an Android app

## Course Outline

1. **Deploying segmentation models on-device** - Set up AI Hub and run an FFNet segmentation model on a real device.
2. **Preparing for on-device deployment** - Capture, compile, profile, and run a model using different runtimes and compute units.
3. **Quantizing models** - Prepare a calibration pipeline and compare floating-point and quantized models.
4. **Building the app** - Follow the appendix to integrate the model into an Android application with TensorFlow Lite and Qualcomm QNN delegation.

The official course includes seven video lessons, four code examples, and a graded assignment. The estimated completion time is **1 hour 19 minutes**.

## Repository Contents

| Notebook | Focus |
| --- | --- |
| `L2_Student.ipynb` | Deploying segmentation models on-device |
| `L3_Student.ipynb` | Compiling, profiling, and running models on-device |
| `L4_Student.ipynb` | Post-training quantization |
| `Appendix-Building_the_App.ipynb` | Building a mobile app with TensorFlow Lite and Qualcomm QNN |

## Prerequisites

- Basic Python programming and machine learning experience
- Familiarity with PyTorch or TensorFlow
- A Python environment that can run Jupyter notebooks
- Access to Qualcomm AI Hub for device-in-the-loop jobs
- For the app appendix: Android tooling, the Qualcomm Neural Processing SDK, and a configured Android device or emulator

## Getting Started

1. Open the notebooks in Jupyter or VS Code.
2. Work through the lessons in order, starting with `L2_Student.ipynb`.
3. Run the exercises and compare the performance of different runtimes and compute units.
4. Continue with the appendix when you are ready to package the model in a mobile application.

## Course Link

[Open the course on DeepLearning.AI](https://www.deeplearning.ai/courses/introduction-to-on-device-ai)
