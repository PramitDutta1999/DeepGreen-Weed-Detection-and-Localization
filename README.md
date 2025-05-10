# DeepGreen Weed Detection and Localization

**Weed and Crop Detection and Localization via Deep Learning in Agri-Imagery**

## Overview

**DeepGreen** is a machine vision project developed for the **ENGG*6100 Machine Vision** course at the University of Guelph. It aims to detect and localize weeds and crops in agricultural field images using a modified YOLOv10 model. The project addresses dataset imbalance, noisy field conditions, and real-world deployment considerations.

## Key Features

- Modified YOLOv10 with Ghost Convolutions  
- Class-aware data augmentation to handle imbalance  
- CLAHE and sharpening-based image preprocessing  
- Designed with edge device compatibility in mind (e.g., Jetson Nano, Raspberry Pi 5)


## Notes

- Change all file paths in scripts to match your local directory structure.
- The training configuration (batch size, image size, epochs, etc.) may need to be modified based on hardware and training needs.
- All preprocessing is done after augmentation to improve visual clarity for model learning.
- The model was trained and evaluated using freely available Google Colab GPU resources.
- Please refer to the project report for detailed implementation, performance, specifications and compatibility.
## License

This project is licensed under the MIT License. See `LICENSE` for details.

## Acknowledgments
This project was completed as part of the UNIV*6100: Machine Vision course at the University of Guelph under the guidance of Professor Medhat Moussa. Thanks to the AI Enabled Medical Imaging Analysis Lab for their support and resources throughout this work.
