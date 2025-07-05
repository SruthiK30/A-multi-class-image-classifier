# A-multi-class-image-classifier
Obj : To train a ResNet-18-based multi-class image classifier in two phases: first using labeled data, then applying semi-supervised learning with unlabeled data to improve performance. Generated test set predictions and documented the complete pipeline in a clean, modular Colab notebook.
This project is my submission for the internship assignment. I built a multi-class image classifier using ResNet-18, first training only on labeled data, then improving the model with semi-supervised learning by adding unlabeled data.
Phase 1: Trained on labeled images and generated predictions for the test set.
Phase 2: Used both labeled and unlabeled images to improve the model and made new predictions on the same test set.
The predictions are saved in:
phase1_predictions.csv
phase2_predictions.csv
All code and training steps are documented in the Colab notebook included in this repository. The dataset used follows the provided folder structure, and no external data was used.
