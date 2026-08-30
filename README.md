# Hi, I'm Maxim! 👋

ML / Computer Vision engineer. I specialize in training neural networks, low-level optimization of CV pipelines, and deploying models to production. Focused on creating fast and efficient commercial systems.

---

## 🛠️ My Stack

![Python](https://img.shields.io/badge/Python-3.14-blue)
![C++](https://img.shields.io/badge/C%2B%2B-v17-blue)
![HTML5](https://img.shields.io/badge/HTML5-E34F26-orange)
![CSS3](https://img.shields.io/badge/CSS3-1572B6-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![OpenCV](https://img.shields.io/badge/OpenCV-v4.10-blue)
![Keras](https://img.shields.io/badge/Keras-v3.0-red)
![NumPy](https://img.shields.io/badge/NumPy-v1.26-blue)
![Pandas](https://img.shields.io/badge/Pandas-v2.2-darkborder)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-v1.4-orange)
![PyTorch](https://img.shields.io/badge/PyTorch-v2.2-orange)
![FastAPI](https://img.shields.io/badge/FastAPI-009688-teal)
![Uvicorn](https://img.shields.io/badge/Uvicorn-499848-green)
![Hugging_Face](https://img.shields.io/badge/Hugging_Face-Spaces-yellow)

---

## 🚀 My Pet Projects

### 🍅 Tomato AI

A web service that detects 10 types of tomato diseases from a leaf photo (trained on the PlantVillage dataset).

* **How it works:** Trained the model on Keras/TensorFlow, wrote the backend using FastAPI, implemented image normalization via NumPy, and connected everything to the frontend using asynchronous requests (Fetch API).
- **Try it yourself:** My deployment lives here — [Hugging Face Spaces](https://huggingface.co/spaces/a21d/tomato-ai)
- **Project code:** [Репозиторий Tomato](https://github.com/Makson-18/Tomato)

### 🦖 Google Dino Bot

An AI bot that plays the "Dino" game by itself in real-time via screen capture. Constantly scores around 890+ points.

- **What's the trick:** Wrote a binary CNN (convolutional neural network). To eliminate bot lagging, I optimized frame loading speeds via the mss library, added .cache() and .prefetch() for the dataloader, and invoke model inference via model(..., training=False). This gave maximum FPS.
- **Project code:** [Репозиторий Dino](https://github.com/Makson-18/dino)

### ⚡ Mathematical Kernels & Optimization (NumPy & C++)

- **Neural Network from Scratch (Pure NumPy)**
    - **What was done:** Implementation of a single-layer neuron (logistic regression) completely from scratch, without using heavy frameworks at all.
    - **Why I did it:** To fully understand the mathematics under the hood. Manually wrote matrix multiplication (np.dot), the Sigmoid function, its derivative, and the Backpropagation algorithm for gradient descent using pure NumPy. The Loss function convergence graph was plotted via Matplotlib.
    - **Project code:** [NumPy-Neiron](https://github.com/Makson-18/numpy)

- **High-Speed Inference (Native C++)**
    - **What was done:** A lightweight forward pass engine for neural network layers in pure C++ without using heavy external libraries (OpenCV).
    - **Why I did it:** For extreme acceleration of Computer Vision pipelines. Optimized data locality (Hardware Cache) through pre-allocation of Contiguous arrays via std::vector::reserve. Implemented virtual 3D-indexing of flat 1D RAM memory under batch-format using the pointer strides formula for fast extraction of color channels.
    - **Project code:** [low-level-computer-vision](https://github.com/Makson-18/low-level-computer-vision)

---

## 📬 Contacts

- 💼 Looking for a paid internship or part-time tasks in **ML / Backend**.
- 😎 Ready to pass a technical interview or complete a coding challenge/test task within a couple of days.
- 💬 **Write to me**: [![Telegram](https://img.shields.io/badge/Telegram-2CA5E0)](https://t.me/maks_planche)
[![Discord](https://img.shields.io/badge/Discord-5865F2)](https://discord.com/users/895895318598656022) 



