# Computer Vision & Deep Learning Collection 🚀

A comprehensive collection of Computer Vision projects, ranging from classic CNNs to modern Transformers and Multimodal models (CLIP). Each project is self-contained and includes its own documentation.

## 📚 What's Inside?

### 1. [ViT Transformer](./vit-fine-tuning)
- **Tech:** Vision Transformer (ViT), Hugging Face, PyTorch.
- **Concept:** Fine-tuning a pre-trained Transformer model on a custom subset of the Food101 dataset. Optimized for CPU training.

### 2. [CLIP Search & Explainable AI](./clip-spatial-service)
- **Tech:** OpenAI CLIP, ChromaDB (Vector Search), FastAPI, OpenCV.
- **Concept:** A semantic image search engine. Includes **Spatial Reasoning** (finding object position) and **Attention Maps** to visualize model decisions.

### 3. [U-Net Brain Tumor Segmentation](./unet-brain-tumor-segmentation)
- **Tech:** U-Net Architecture, PyTorch.
- **Concept:** Medical image segmentation for identifying brain tumors. Demonstrates pixel-level classification capabilities.

### 4. [CNN Image Classification](./cnn-facial-keypoints-regression)
- **Tech:** Convolutional Neural Networks, PyTorch/TensorFlow.
- **Concept:** The fundamentals of computer vision. Classic approach to image classification with data augmentation and performance metrics.

### 5. [YOLO Smart Parking Slot Detector](./yolo-parking-slot-detector)
- **Tech:** YOLO11, OpenCV, Python, Pickle.
- **Concept:** Real-time parking occupancy monitoring. Features a custom UI for manual slot marking (ROI) and automated detection using geometric point-in-polygon validation.

### 6. [YOLO People Counter & Tracker](./yolo-people-tracker)
- **Tech:** YOLO11 Tracking API, OpenCV, Deep Learning.
- **Concept:** A tripwire-based counting system. It uses unique ID tracking to monitor movements and counts individuals crossing a virtual boundary in both directions.

### 7. [Stable Diffusion Experiments](./stable-diffusion)
- **Tech:** Stable Diffusion v1.5, ControlNet (Canny), LoRA Adapters, Hugging Face Diffusers, PyTorch.
- **Concept:** Exploration of generative AI pipelines. Features text-to-image synthesis, structural control via edge detection, and style injection using lightweight adapter fine-tuning.

### 8. [Camera Ego-Motion Compensation & Trajectory Prediction](./slam)
- **Tech:** YOLO11, BYTETracker, OpenCV (Lucas-Kanade Optical Flow), NumPy.
- **Concept:** Advanced tracking system that filters out camera movements using optical flow. Calculates the true absolute velocity of targets to predict and plot their trajectory vectors 30 frames into the future.

---

## 🛠️ Global Setup

All projects share a common environment. To get started:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/misharysh/computer-vision-collection.git
   cd computer-vision-collectiom
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## 🗂️ Structure
- Each folder contains a standalone `README.md` with specific details for that model.
- Shared datasets and weights are excluded via `.gitignore` to keep the repo lightweight.
