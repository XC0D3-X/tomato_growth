# Plant Growth Stage Detection (YOLOv8)

This repository contains a high-accuracy computer vision model (`best.pt`) trained to detect and classify five distinct stages of plant development. This is ideal for smart agriculture, automated greenhouse monitoring, and phenotyping research.

## 📊 Model Performance
The model was trained for **50 epochs** and shows strong reliability across all stages.

| Class | Precision (P) | Recall (R) | mAP50 |
| :--- | :--- | :--- | :--- |
| **All Classes** | **0.893** | **0.867** | **0.910** |
| Germination | 0.823 | 0.768 | 0.814 |
| Seeding | 0.927 | 0.844 | 0.910 |
| Vegetative | 0.932 | 0.969 | 0.989 |
| Flowering | 0.877 | 0.842 | 0.895 |
| Fruit & Ripening | 0.903 | 0.914 | 0.942 |

## 🌱 Growth Stage Descriptions
Below are the physical characteristics and average heights used for each class in this model:

1. **Germination (0–1.5 cm)**: The initial breaking of the seed coat and the emergence of the radical or plumule.
2. **Seeding (1.5–5 cm)**: The early establishment phase after the sprout breaks the soil surface.
3. **Vegetative (5–30 cm)**: The primary growth stage where the plant develops its main stem and foliage.
4. **Flowering (20–60 cm)**: The reproductive stage marked by the appearance of flower buds and blossoms.
5. **Fruit & Ripening (30–100+ cm)**: The combined final stage covering fruit development through to full maturity and harvest readiness.

## 🛠️ Technical Specifications
- **Framework:** PyTorch / Ultralytics YOLOv8
- **Format:** `.pt` (PyTorch Weights)
- **Parameters:** 3,006,623
- **Inference Speed:** 2.5ms (on Tesla T4)
- **GFLOPs:** 8.1

## 📦 How to Use
To run inference with this model, ensure you have `ultralytics` installed:

```bash
pip install ultralytics
