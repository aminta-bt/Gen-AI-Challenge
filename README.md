# 🤖 Gen AI Challenge: Prompt. Build. Surprise.
**A 24-hour creative AI sprint hosted by OhCrop and ACM-W BPDC.** 

This repository contains my trails for all three generative AI challenges, showcasing a workflow that blends technical machine learning with creative design.

---

## 🛠️ Tech Stack
* **Languages:** Python
* **Libraries:** TensorFlow, Keras, NumPy, Matplotlib
* **AI Models:** Convolutional Autoencoders, Neural Style Transfer (TF Hub), Generative AI (Nano Banana 2)
* **Design Tools:** Canva (for Challenge 3 refinement)

---

## 🎨 Challenge 1: Image Repair & Style Transformation
### **The Mission**
Take a "broken" image, repair it using a generative model, and apply a completely new artistic style. 

* I utilized the **Fashion-MNIST** dataset to create a consistent pipeline.
* **Methodology:** I injected **Gaussian Noise (factor = 0.2)** to intentionally degrade the structural integrity of the clothing items and built a **Convolutional Autoencoder** using `Conv2D` and `UpSampling2D` layers to denoise the latent space.
* The repaired image was fed into a **Neural Style Transfer** model (via TensorFlow Hub) using Van Gogh's *Starry Night* as the style reference.

---

## 👕 Challenge 2: AI Fashion Designer
### **The Mission**
Train a generative model on fashion data and explore the "latent space" through sampling and interpolation to create new, cohesive designs.

* **Theme:** **Shape-Shifting (Urban Transition)** — Blending a short T-shirt into a long coat.
* **Methodology:** I trained a generative autoencoder on **Fashion-MNIST** to map garments into a **64-dimensional latent space**.
* **The Process:** I performed **Latent Vector Interpolation** between two distinct items (a T-shirt and a coat) to mathematically calculate "in-between" designs.
* **Tools:** Python, Keras, and Matplotlib were used for visualizing the vector arithmetic.

---

## 💧 Challenge 3: AI Poster Designer
### **The Mission**
Use AI as a creative collaborator to design a high-impact poster for a fictional concept.

* **Concept:** **"The Human Recharge"** —  A campaign to encourage myself to drink water.
* **Mood:** **Vibrant Tech-Thirst**. I used "Electric Blue" and "Crisp Cyan" and textures like water droplets to make hydration look like a premium tech feature rather than a chore.
* **Workflow:** I used **Generative AI** to brainstorm surreal metaphors (like water galaxies and glowing auras) and then refined the best output into a cohesive final poster.
