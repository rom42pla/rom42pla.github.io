---
title: "Towards Multi-View Hand Pose Recognition Using a Fusion of Image Embeddings and Leap 2 Landmarks"
authors: "Esteban-Romero, S., <b>Lanzino, R.</b>, Marini, M. R., & Gil-Martín, M."
collection: publications
category: conferences
permalink: /publication/2025_icaart
# excerpt: none
date: 2025-01-01
venue: 'International Conference on Agents and Artificial Intelligence (ICAART)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'https://diglib.eg.org/bitstreams/b60aa1b9-6b9d-4ebd-b3d4-120d5ed1058c/download'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Esteban-Romero, S., Lanzino, R., Marini, M. R., & Gil-Martín, M. (2025). Towards Multi-View Hand Pose Recognition Using a Fusion of Image Embeddings and Leap 2 Landmarks. Proceedings of the 17th International Conference on Agents and Artificial Intelligence - Volume 3: ICAART, 918–925. doi:10.5220/0013234300003890'
---
This paper presents a novel approach for multi-view hand pose recognition through image embeddings and hand landmarks. The method integrates raw image data with structural hand landmarks derived from the Leap Motion Controller 2. A Vision Transformer (ViT) pretrained model was used to extract visual features from dual-view grayscale images, which were fused with the corresponding Leap 2 hand landmarks, creating a multimodal representation that encapsulates both visual and landmark data for each sample. These fused embeddings were then classified using a multi-layer perceptron to distinguish among 17 distinct hand poses from the Multi-view Leap2 Hand Pose Dataset, which includes data from 21 subjects. Using a Leave-OneSubject-Out Cross-Validation (LOSO-CV) strategy, we demonstrate that this fusion approach offers a robust recognition performance (F1 Score of 79.33 ± 0.09 %), particularly in scenarios where hand occlusions or challenging angles may limit the utility of single-modality data. 