---
title: "Projects"
showToc: false
---

My other projects span **multimodal AI, computer vision, and intelligent system applications**, with an emphasis on connecting perception, reasoning, and real-world deployment.

## Selected Projects

### Modular Real-Time Image Captioning for Visually Impaired Users  
*Outstanding Undergraduate Thesis*

- Designed a **lightweight image captioning architecture** optimized for real-time inference and mobile deployment.  
- Addressed limitations of existing captioning models such as high computational cost and slow inference.  
- Developed a **modular caption generation pipeline** suitable for assistive applications for visually impaired users.  
- On the Flickr30K dataset, the proposed model achieved **+8% CIDEr and +6% BLEU-1 improvement** compared with the SmallCap (CVPR 2023) baseline while maintaining low latency.

---

### EEG–Speech Multimodal Deep Fusion for Early Depression Screening  
*National College Statistical Modeling Competition — First Prize (Top 5%, Rank 62 / 1226)*

- Proposed a **Vision Transformer (ViT)-based multimodal fusion framework** for early depression detection.  
- Designed a **dual-channel ViT-SE encoder** to extract features from EEG time-frequency maps (128 channels) and speech Mel-spectrograms.  
- Implemented **adaptive cross-modal fusion** using learnable gating weights and optimized with contrastive loss.  
- Achieved **92% accuracy and 0.80 AUC on the MODMA dataset**, improving F1 score by **18.6% over single-modality baselines**.

---

### Unsupervised and Content-based Lead Frame Design Retrieval System

- Developed an **unsupervised image retrieval system** for semiconductor lead frame design diagrams.  
- Implemented feature detection and robust matching strategies for complex engineering drawings.  
- Designed a semantic retrieval pipeline based on **embedding representations and vector similarity search**.  
- Enabled **structure-aware “image-to-image” retrieval** for efficient design reuse and similarity analysis.

---

### Video-based Identity Recognition System

- Developed a **multimodal identity recognition system** combining **face recognition and person re-identification**.  
- Built on the **ReFace framework**, integrating real-time camera capture with a fine-tuned **YOLOv7 detection model** for human localization and cropping.  
- Fused facial features and full-body re-identification embeddings to improve identity inference accuracy, achieving **98% recognition accuracy in real-world scenarios**.  
- Implemented additional modules including **standing-state detection and restricted check-in area control** to improve reliability and reduce false recognition.  
- Integrated into a **multimodal big-data-driven research productivity analysis platform** as an automated attendance module.

---

### Parking Recommendation with Neural Collaborative Filtering  
*Undergraduate Research Project — Project Leader*

- Proposed **TransGAT-CF**, a neural collaborative filtering framework integrating **local graph attention and global Transformer encoding**.  
  - Designed a dual-path GNN architecture: **Inner-GNN** for dynamic neighbor weighting via self-attention, and **Cross-GNN** for heterogeneous interaction modeling.  
  - Introduced a Transformer encoder with **learnable positional embeddings** to capture global preference patterns.  
  - Achieved **+2.47% AUC improvement** over the GMCF baseline (SIGIR 2021, CCF-A) on the parking recommendation dataset.

- Proposed **GMCF-Pool**, a graph-based collaborative filtering model with **multi-strategy pooling and GRU-based sequential feature fusion**.  
  - Combined **global attention pooling and Set2Set pooling** with dynamic weighting mechanisms.  
  - Incorporated **GRU-based sequence modeling** to enhance user–item interaction representation.  
  - Achieved **+2.16% AUC improvement** over the GMCF baseline while maintaining computational efficiency.

- **Project Lead**: defined research direction, coordinated literature review and implementation, and led the development of TransGAT-CF. Responsible for the final project report and presentation.