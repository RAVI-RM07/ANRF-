This repository presents an AI-driven solution for flood detection and localization in India using satellite imagery and geospatial deep learning. Developed as part of a hackathon challenge, the project focuses on addressing real-world disaster management problems where timely and accurate flood mapping is critical.

Floods affect a significant portion of India’s population, causing damage to infrastructure, agriculture, and human life. However, detecting floods using satellite data is challenging due to factors such as dense cloud cover during monsoons, limited labeled data, and difficulty in distinguishing floodwater from existing water bodies like rivers and lakes.

To tackle these challenges, this project leverages the **Prithvi**, a geospatial foundation model trained on large-scale Earth observation data. The model is fine-tuned using **TerraTorch** with multi-modal inputs, including multispectral and SAR (Synthetic Aperture Radar) imagery. SAR data plays a critical role by enabling reliable observations even under cloud cover.

The solution evolves across two phases: an initial binary segmentation task (flood vs no flood), followed by a more advanced three-class segmentation (no flood, flood, water body). This enhancement enables more realistic and precise flood mapping by reducing misclassification of permanent water bodies.

The pipeline includes data preprocessing, multi-modal data fusion, model fine-tuning, and pixel-wise segmentation. Model performance is evaluated using Intersection over Union (IoU), mean IoU, and pixel-wise accuracy, with emphasis on accurate flood detection.

This project demonstrates how geospatial AI can be effectively applied to build scalable, real-world disaster response systems.
