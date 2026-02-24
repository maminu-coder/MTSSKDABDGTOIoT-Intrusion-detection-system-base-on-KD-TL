# MTSSKDABDGTO IoT-Intrusion-detection-system-base-on-KD-TL
The paper tackles a critical challenge in IoT security: developing efficient malware detection systems for rcIoT devices. 
-Traditional deep learning approaches for malware detection are too computationally intensive for IoT devices, yet the proliferation of IoT devices has created new attack surfaces for sophisticated malware threats.

## Multi-Teacher Ensemble Network (MTENet) 

### A teacher model composed of:
- InceptionCNN (for spatial feature extraction)
- InceptionGRU (for temporal feature extraction)
- Hybrid InceptionCGRU (combining both approaches)

### eCGRU Student Model 
- A lightweight student model (efficient Convolutional Gated Recurrent Unit) trained via knowledge distillation from the MTENet teacher models.

### ABC-GTO Feature Optimization - A hybrid feature selection method combining:
- Artificial Bee Colony (ABC) algorithm
- Gorilla Troop Optimization (GTO) algorithm

## This is an ongoing project. 
