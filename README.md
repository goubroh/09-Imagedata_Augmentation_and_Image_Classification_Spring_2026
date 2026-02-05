# 09-Imagedata_Augmentation_and_Image_Classification_Spring_2026


Image Data Augmentation and Image Classification (IDEAS TIH Internship Project Spring 2026)

This repository contains a step-by-step implementation of basic **image processing**, **data augmentation**, and **image loading pipelines** using **OpenCV**, **NumPy**, and **PyTorch**.  
The work follows an academic assignment format and demonstrates practical understanding of computer vision and deep learning data preparation.

---

## 📌 Objectives

- Load and manipulate images using OpenCV
- Perform grayscale conversion, shifting, resizing, and rotation
- Download and prepare a real-world image dataset (Cats vs Dogs)
- Apply image augmentation using `torchvision.transforms`
- Create datasets and dataloaders for deep learning models

---

## 🛠️ Technologies Used

- **Python 3**
- **NumPy**
- **OpenCV (cv2)**
- **PyTorch**
- **Torchvision**
- **Google Colab**
- **gdown**
- **Requests**

---

## 📂 Project Structure
- ├── moon-pexels-frank-cone.jpg
- ├── graymoon.jpg
- ├── Cat_Dog_data/
- │ └── Cat_Dog_data/
- │ ├── train/
- │ │ ├── cats/
- │ │ └── dogs/
- │ └── test/
- ├── image_processing_assignment.ipynb
- └── README.md


---

## 🧪 Tasks Performed

### 1. Image Loading
- Imported required libraries (`numpy`, `cv2`)
- Downloaded an image using Google Drive
- Loaded and displayed image shape

### 2. Grayscale Conversion
- Converted RGB image to grayscale
- Verified dimensionality change

### 3. Image Saving
- Saved grayscale image using OpenCV

### 4. Image Shifting
- Applied affine transformation
- Shifted image by 50 pixels right and 100 pixels down

### 5. Image Resizing
- Resized image to **150 × 100**

### 6. Image Rotation
- Rotated image **90° counter-clockwise**
- Verified dimension swap

### 7. Dataset Downloading
- Downloaded Cats vs Dogs dataset
- Extracted and organized files

### 8. Image Transformation Pipeline
- Resized images to **255 × 255**
- Applied random horizontal flip
- Converted images to tensors

### 9. Dataset Creation
- Used `ImageFolder` to load dataset
- Verified total training images

### 10. DataLoader Creation
- Created DataLoader with batch size **64**
- Retrieved and inspected batch shapes

---

## 📊 Sample Output

```text
Image batch shape: torch.Size([64, 3, 255, 255])
Label batch shape: torch.Size([64])
