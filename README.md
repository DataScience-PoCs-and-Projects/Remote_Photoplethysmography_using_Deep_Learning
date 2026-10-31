This repository contains a complete deep learning pipeline for estimating heart rate and vital signs directly from facial video streams using Remote Photoplethysmography (rPPG).

The project leverages Computer Vision (for facial mesh tracking and region-of-interest extraction) and Deep Learning (1D-CNNs, GRU, and DualTL) to analyze subtle color variations in the human face and predict the underlying pulse.
It also features live webcam inference and Explainable AI (XAI) techniques, such as Grad-CAM and occlusion mapping, to visualize exactly how the models interpret facial regions to detect heart rate.
