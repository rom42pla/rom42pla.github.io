---
title: "Multi-Stream 1D CNN for EEG Motor Imagery Classification of Limbs Activation"
authors: "Avola, D., Cinque, L., Di Mambro, A., <b>Lanzino, R.</b>, Pannone, D., & Scarcello, F."
collection: publications
category: manuscripts
permalink: /publication/2024_access
# excerpt: none
date: 2024-06-11
venue: 'IEEE Access'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10552846'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Avola, D., Cinque, L., Di Mambro, A., <b>Lanzino, R.</b>, Pannone, D., & Scarcello, F. (2024). Multi-Stream 1D CNN for EEG Motor Imagery Classification of Limbs Activation. IEEE Access, 12, 83940–83951. doi:10.1109/ACCESS.2024.3412710'
---
Determining the motor intentions of an individual through the analysis of electroencephalograms (EEGs) is a challenging task that concurrently holds considerable potential in aiding subjects with motor dysfunctions. Moreover, thanks to the recent advances in artificial intelligence models and EEG acquisition devices, such analyses can be carried out with ever higher accuracy. The latter aspect covers great importance, since the EEG analysis of subjects whose mental efforts are focused on moving limbs is frequently used for crucial tasks, including the control of interactive interfaces and prosthetic devices. In this paper, a novel multi-stream 1D Convolutional Neural Network (CNN) architecture is proposed. The input EEG signal is processed by four convolutional streams, which differ in the size of convolutional kernels, thus allowing the extraction of information at different time scales. The resulting 1D feature maps are then fused together and provided to a dense classifier to identify which limb the subject intended to move. Comprehensive experiments conducted on PhysioNet EEG motor movement/imagery dataset, which remains the reference collection of data in this application context, have demonstrated that the proposed model surpasses the key works in the current state-of-the-art in both cross-subject and intra-subject settings.