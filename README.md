# YOLOV11-Search-App
# 🔎 YOLO11 Image Search Engine

An AI-powered image search application built with **YOLO11**, **PyTorch**, and **Streamlit**.  
The application detects objects in images and allows users to search for images based on detected object classes.

## 🚀 Overview

The YOLO11 Image Search Engine combines object detection with image retrieval to create a simple and interactive image-search experience.

Instead of manually browsing through hundreds of images, users can enter an object or class name and retrieve images containing that object.

### ✨ Key Features

- 🎯 YOLO11-based object detection
- 🔎 Search images using detected object classes
- 🖼️ Display matching images through an interactive Streamlit interface
- 📊 View detected classes and search results
- ⚙️ Configurable application settings
- 🧩 Modular Python project structure
- 🚀 GPU support for faster inference when available

## 🧠 How It Works

The application follows a simple pipeline:

```text
Input Images
     ↓
YOLO11 Object Detection
     ↓
Extract Detected Objects / Classes
     ↓
Store Image Metadata
     ↓
User Searches for an Object
     ↓
Find Matching Images
     ↓
Display Results in Streamlit
```
🤖 YOLO11 Model

The YOLO11 model weights are not included in this repository.

Download the required YOLO11 weights and place them in the location specified by the project configuration.
