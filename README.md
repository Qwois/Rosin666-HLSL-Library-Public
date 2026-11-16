# 🎨 Rosin666 HLSL Library

A curated collection of custom **HLSL shaders (`.usf`)** designed for Unreal Engine Material Custom Nodes and post-processing pipelines.

---

## 📑 Table of Contents
- [Shaders](#-shaders)
  - [CRT Bicubic Interpolation (`crt_bicubic_interpolation.usf`)](#1-crt-bicubic-interpolation)
- [How to Use](#-how-to-use)
- [License](#-license)

---

## 🧩 Shaders

### 1. CRT Bicubic Interpolation
**File:** `crt_bicubic_interpolation.usf`

A high-quality **bicubic texture filtering** shader combined with a **CRT screen emulation** effect. Designed to upscale low-resolution pixel art or retro textures smoothly without standard bilinear blur, while adding authentic scanlines and subpixel curvature.

#### 🎥 Preview
https://github.com/user-attachments/assets/e4329ca1-616f-46a0-a0db-4d90dce198f4

#### 🔌 Node Inputs & Graph Setup
<p align="center">
  <img width="1254" height="859" alt="Node Inputs Setup" src="https://github.com/user-attachments/assets/d1542e9f-7f92-4451-9af6-342c6153e4ec" />
</p>

*(Note: Ensure your Custom Node inputs match the exact naming and data types shown in the screenshot above).*

---
## 📄 License

This repository is distributed under a **Non-Commercial License**. 
- ✅ **Allowed:** Personal projects, educational purposes, research, and non-commercial prototypes.
- ❌ **Prohibited:** Commercial use, redistribution for profit, or integration into commercial games/software without explicit permission from the author.
