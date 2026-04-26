# Plant Growth Stage Detection (YOLOv8)

This repository contains a PyTorch model (`best.pt`) trained to detect and classify various stages of plant development. This can be used for automated crop monitoring, smart greenhouses, or phenotyping research.

## Classes & Characteristics
The model is trained on the following 5 stages of plant growth:

1. **Germination**: The moment the embryo breaks the seed coat (0-2cm).
2. **Seedling**: Young plants with developing root systems and true leaves (2-10cm).
3. **Flowering**: The reproductive phase where the plant produces buds/flowers (~2x seedling height).
4. **Fruiting**: The development of fruit from the pollinated flowers.
5. **Ripening**: The final stage where fruit reaches maturity and changes color/texture.

## Model Details
- **Framework**: PyTorch / YOLOv8
- **Format**: `.pt` (PyTorch Weights)
- **Primary Use**: Object detection for agricultural automation.

## Performance
