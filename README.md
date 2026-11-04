# Hi, I'm Suryansh 👋

**Computer Vision engineer** focused on object detection, model deployment, and generative models.
B.Tech in Electronics & Communication Engineering (Data Science specialization), [SRMIST](https://www.srmist.edu.in/), 2025.

I like building things from scratch to understand them, then measuring them honestly.

📍 Open to Computer Vision / AI engineer roles (Bangalore, Gurugram, Delhi, or remote)

---

## Featured projects

### 🚁 [Drone Object Detection: YOLOv8n vs YOLO26n](https://github.com/suryansh-sinha/YOLO-VisDrone)
Trained and benchmarked two nano detectors on VisDrone (small-object aerial detection) at 640 and 960 px, then exported to ONNX and TensorRT and re-measured accuracy after every conversion.

- Higher resolution improved test mAP50-95 by about 5 points, reaching 20.2 (YOLOv8n) and 19.3 (YOLO26n).
- TensorRT FP16 cut per-image latency 2.1-3.3x versus PyTorch (0.73-1.29 ms at batch 1 on an RTX 5070 Ti), with at most ~0.2 mAP points lost in export.
- YOLO26n's NMS-free head cut postprocessing from 0.33 to 0.07 ms, making it 11-17% faster in TensorRT at a cost of 0.4-0.9 mAP points.

`Python` `PyTorch` `Ultralytics` `ONNX Runtime` `TensorRT` `Weights & Biases`

### 🔍 [DDPM From Scratch: Generation and Anomaly Detection](https://github.com/suryansh-sinha/ddpm-transistor)
A Denoising Diffusion Probabilistic Model written in PyTorch without diffusion libraries (U-Net with residual blocks, GroupNorm and self-attention, noise scheduler, EMA ancestral sampler), trained on 213 defect-free MVTec AD transistor images.

- Turned it into an unsupervised defect detector using noise-denoise reconstruction and a 1-SSIM anomaly map: **0.94 image-level AUROC** and 0.77 pixel-level AUROC on the MVTec test set.
- Evaluated across noise levels, scoring methods, and defect types, and documented the limitations (test-set tuning, single seed, no baseline).
- Checked that the model was not memorizing its training data.

`Python` `PyTorch` `scikit-learn` `Weights & Biases`

---

## Tech

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Weights & Biases](https://img.shields.io/badge/Weights_&_Biases-FFBE00?style=for-the-badge&logo=weightsandbiases&logoColor=black)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## What I'm up to

- 🎯 Looking for a junior Computer Vision / AI engineer role where I can ship detection and deployment work
- 🌱 Studying 3D computer vision on the side
- 💬 Happy to talk about object detection, TensorRT/ONNX deployment, diffusion models, and anomaly detection

## Reach me

📧 [suryanshsinha01@gmail.com](mailto:suryanshsinha01@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/suryanshsinha/)
