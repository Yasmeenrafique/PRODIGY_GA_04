# 🖼️ Task-04: Image-to-Image Translation using Pix2Pix (cGAN)

This project implements an **Image-to-Image Translation system** using a **Conditional Generative Adversarial Network (cGAN)** known as **Pix2Pix**.  
The model learns to transform one type of image into another, for example converting **edge maps into realistic photographs**.

This task demonstrates a real-world application of **deep learning, computer vision, and generative AI**.

---
## 🚀 Objective

To build a Pix2Pix model that learns a mapping between:
- **Input Image (Edges)**
- **Target Image (Real Photo)**

The trained model can generate realistic images from structured inputs such as sketches or edges.
---

## 🧠 What is Pix2Pix?

Pix2Pix is a **conditional GAN** that learns a mapping from:

It uses:
- **Generator** (U-Net) to create images
- **Discriminator** (PatchGAN) to judge image realism

Both networks compete during training to produce high-quality outputs.

---
## ⚙️ Technologies Used

- Python  
- TensorFlow  
- NumPy  
- Matplotlib  
- OpenCV  
- Google Colab (GPU)

---

## 🔧 Project Workflow

1. Download Pix2Pix dataset  
2. Preprocess images (split input & target)  
3. Normalize and resize images  
4. Build Generator (U-Net)  
5. Build Discriminator (PatchGAN)  
6. Define GAN and L1 loss  
7. Train Pix2Pix model  
8. Generate translated images  
9. Visualize input, generated, and real images  

---

## 🏗 Model Architecture

### Generator
- U-Net based CNN
- Produces translated image

### Discriminator
- PatchGAN
- Evaluates realism of generated images

---

## 📉 Loss Functions

- **GAN Loss** – to fool the discriminator  
- **L1 Loss** – to ensure pixel-level accuracy  

Final Loss generator:
---

## 🧪 Training Strategy

To reduce training time and resource usage, a subset of **400 image pairs** was used instead of the full dataset.

This is sufficient to demonstrate:
- GAN training
- Image translation
- Visual output quality

---
## 🎯 Real-World Applications

Pix2Pix is used in:
- Medical image translation
- Satellite to map conversion
- Photo enhancement
- Sketch to photo generation
- UI design automation

---

## ✅ Conclusion

This project demonstrates how **conditional GANs** can be used to perform **image-to-image translation**, a powerful technique in modern AI-driven design, vision, and automation systems.

---

Author: Yasmeen Rafique






