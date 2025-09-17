# Automated Re-Identification of Densely Crowded Holstein-Friesian Cattle

## Authors
Phoenix Yu (Junjie Yu); Tilo Burghardt; Andrew Dowsey, Neill Campbell

## Overview
Holstein-Friesian detection and re-identification capture individuals well when targets are scattered. However, the existing pipelines become exhaustive and error-prone when cows cluster together due to their unique biological patterns. Additionally, the low portability of the contemporary models results in customised, long-term retraining and configuration in new environments. To boost efficiency and transferability, we propose a pipeline that combines the off-the-shelf OWLv2 detector with SAM2 for re-identifying cows under challenging conditions. With 9 days of data collection from cameras, we compared our two-step model against pre-trained oriented bounding box and SAM-only detectors as a quality comparison. We witnessed a rise in species identification accuracy of 47.52% with the oriented bounding box detector and 27.13% with the SAM-only pipeline. Then, we used an unsupervised contrastive learning framework for the re-identification performance. The average result of 94.82% accuracy shows that our OWL–SAM pipeline can produce competitive-quality masks for crowded scenes with strong global feature consistency. We demonstrate the pipeline’s potential for scalable, automated dataset creation with minimal manual intervention, and its applicability to downstream re-identification tasks. The GitHub repository for our individual cow identifiers is also available at [https://github.com/Phoenix4582/TOBEADDED](https://github.com/Phoenix4582/TOBEADDED). 

## Citations
```
TO BE ADDED
```

## Acknowledgements
We thank Dr Neill Campbell and Dr Tilo Burghardt for their tireless efforts in supervising the PhD research project from scratch. We thank Andrew Drowsey for his continuous support for hardware management and occasional checkups for the progress of PhD students. We acknowledge the support from Axel Montout and Jing Gao for providing and storage of the video data for the project. We thank the members of the John Oldacre Centre AI meeting for their lasting passion for innovations and interdisciplinary communication. We thank the University of Bristol for the many aspects of opportunity, the School of Computer Science for professional knowledge and the Veterinary School for providing a healthy testing farm. We thank all the loved ones who provided us with support from many aspects within our group. 
