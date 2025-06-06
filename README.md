# image_encryption1


# 🔐 SIRDS-Based Image Encryption Demo

This is a concept project built during my 6th semester while studying Computer Vision. It explores the idea of using **SIRDS (Single Image Random Dot Stereograms)** for **image encryption and secure transmission**.

## 💡 Concept

Instead of traditional encryption, this project demonstrates how an image can be securely encoded into **multiple stereograms** and only be reconstructed by combining specific ones.

### 🧠 How It Works
1. **User inputs an image**
2. The system generates **3 random depth maps**
3. Each depth map is converted into a **SIRD (Single Image Random Dot Stereogram)**
4. Any **2 SIRDs can be combined** to reconstruct the original image
5. The third SIRD acts as an additional "key" or noise layer

> ⚠️ This is a proof-of-concept project — it doesn't implement actual file transfer or encryption but illustrates the idea of **visual encoding and partial decryption** through stereograms.

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Backend/Logic**: Python (for generating depth maps and SIRDS)

---
## 🔗 Live Demo

Check out the deployed project here:  
[![Live Site](https://img.shields.io/badge/Live-Demo-green?style=for-the-badge&logo=render)](https://image-encryption-5snc.onrender.com)


## 🚀 Getting Started

### 1. Clone the Repo
```bash
git clone https://github.com/AnandOjha2407/Image-Encryption.git
cd Image-Encryption




