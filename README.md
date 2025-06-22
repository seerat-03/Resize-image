# 🖼  Resize 100 Images to 50% Using OpenCV

This project uses OpenCV to reduce the size of 100 images by 50% and save them in a separate folder. It's simple, efficient, and runs perfectly on Google Colab or your local system.

---

## 🚀 Features

- 🔹 Automatically resizes all images to 50%
- 🔹 Supports .jpg, .png, .jpeg, .bmp
- 🔹 Outputs images into a zip file for easy download

---

## 🧰 Tech Stack

- Python 3
- OpenCV (cv2)
- Google Colab

---

## 📦 How to Use

### 📌 Upload a ZIP file of 100 images

```python
from google.colab import files
uploaded = files.upload()
