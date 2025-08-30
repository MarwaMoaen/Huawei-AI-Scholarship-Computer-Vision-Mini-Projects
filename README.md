Perfect 🚀 — let’s make your repo look like a **mini-portfolio of Huawei AI scholarship tasks**.
Here’s a `README.md` draft that combines **Task 1 (Edges vs Harris)** and **Task 2 (OpenCV vs skimage)** into one clean project:

---

# 🎓 Huawei AI Scholarship – Computer Vision Mini Projects

This repository contains Jupyter Notebooks I developed as part of my **Huawei AI Scholarship** journey.
Each notebook explores a key concept in computer vision, with theory, code, and visual results.

---

## 📂 Contents

### 🔍 Task 1 – Edge Detection vs Harris Corner Detection

* **Goal:** Compare edges (object outlines) vs corners (interest points).
* **Notebooks:**

  * `Edge_vs_Harris_Lena.ipynb` → classic Lena test image (for fundamentals).
  * `Edge_vs_Harris_Buildings.ipynb` → real-world photo (for practical demo).
* **Key Insight:**

  * **Edges** = outlines, big picture.
  * **Corners** = stable anchor points for matching & tracking.

---

### ⚡ Task 2 – Comparing OpenCV vs scikit-image

* **Goal:** Run the same operations with two different Python libraries:

  * Grayscale conversion
  * Edge detection (Canny vs Sobel)
  * Thresholding (Binary vs Otsu)
* **Notebook:** `OpenCV_vs_skimage.ipynb`
* **Key Insight:**

  * **OpenCV** = fast, industry-grade, great for real-time.
  * **scikit-image** = clean, NumPy-based, perfect for research & prototyping.

---

## 📊 Results Preview

### Task 1

| Original                          | Canny Edges                    | Harris Corners                  |
| --------------------------------- | ------------------------------ | ------------------------------- |
| ![](images/original_building.jpg) | ![](images/canny_building.jpg) | ![](images/harris_building.jpg) |

### Task 2

| OpenCV Canny                 | skimage Sobel                 |
| ---------------------------- | ----------------------------- |
| ![](images/opencv_edges.jpg) | ![](images/skimage_edges.jpg) |

---

## 🚀 How to Run

1. Clone this repo:

   ```bash
   git clone https://github.com/YourUsername/huawei-ai-vision-tasks.git
   cd huawei-ai-vision-tasks
   ```

2. Install requirements:

   ```bash
   pip install opencv-python matplotlib scikit-image numpy
   ```

3. Open notebooks:

   * `Edge_vs_Harris_Lena.ipynb`
   * `Edge_vs_Harris_Buildings.ipynb`
   * `OpenCV_vs_skimage.ipynb`

---

## 🌍 About

These notebooks are part of my **Huawei AI Scholarship crash course**.
I’m sharing them here to document my learning and to contribute back to the AI/Computer Vision community.

📬 Feedback, suggestions, or collaborations are always welcome!

\#ComputerVision #AI #OpenCV #scikitimage #Huawei #Scholarship

