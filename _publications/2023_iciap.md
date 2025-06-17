---
title: "LieToMe: An LSTM-Based Method for Deception Detection by Hand Movements"
authors: "Avola, D., Cinque, L., De Marsico, M., Di Mambro, A., Fagioli, A., Foresti, G. L., <b>Lanzino, R.</b>, … Scarcello, F."
collection: publications
category: conferences
permalink: /publication/2023_iciap
# excerpt: none
date: 2023-09-05
venue: 'International Conference on Image Analysis and Processing (ICIAP)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'https://diglib.eg.org/bitstreams/b60aa1b9-6b9d-4ebd-b3d4-120d5ed1058c/download'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Avola, D., Cinque, L., De Marsico, M., Di Mambro, A., Fagioli, A., Foresti, G. L., … Scarcello, F. (2023). LieToMe: An LSTM-Based Method for Deception Detection by Hand Movements. In G. L. Foresti, A. Fusiello, & E. Hancock (Eds.), Image Analysis and Processing -- ICIAP 2023 (pp. 387–398). Cham: Springer Nature Switzerland.'
---
The ability to detect lies is a crucial skill in essential situations like police interrogations and court trials. At present, several devices, such as polygraphs and magnetic resonance, can ease the deception detection task. However, the effectiveness of these tools can be compromised by intentional behavioral changes due to the subject awareness of such appliances, suggesting that alternative ways must be explored to detect lies without using physical devices. In this context, this paper presents an approach focused on the extraction of meaningful features from hand gestures. The latter provide cues on the person’s behavior and are used to address the deception detection task in RGB videos of trials. Specifically, the proposed system extracts hands skeletons from an RGB video sequence and generates novel handcrafted features from the extrapolated keypoints to reflect the subject behavior through hand movements. Then, a long short-term memory (LSTM) neural network is used to classify these features and estimate whether the person is lying or not. Extensive experiments were performed to assess the quality of the derived features on a public collection of famous real-life trials. On this dataset, the proposed system sets new state-of-the-art performance on the unimodal hand-gesture deception detection task, demonstrating the effectiveness of the proposed approach and its handcrafted features.