# Enhanced-Cell-Tracking-Techniques
Codes for journal publication for the paper: Enhanced Cell Tracking in Dense Tissues via Deep Learning: Improving Contrast, Noise Reduction, and Segmentation Accuracy
Authors: Rejeti Kartik, Vanipenta Pavan Kumar Reddy, Peta Sandeep, Tripty Singh, Afnaan K.

# Overview
# Dataset
The original dataset is the Rat Astrocyte cells dataset taken from the 3DHISTECH scanner in Budapest, Hungary with 1200 images along with their positions. The original link is https://bbbc.broadinstitute.org/BBBC042. The images are in 8-bit TIF format and positions are in text format.

# Models
SegNet architecture
![SegNet-architecture](https://github.com/user-attachments/assets/62b350f6-935c-4c6b-bbea-505c2123a628)

HRNet architecture
![The-architecture-of-the-used-high-resolution-network-HRNet-for-singing-voice-separation](https://github.com/user-attachments/assets/ee91fd7e-fb64-4223-ab65-35346b2611ac)

UNet3+ architecture
![download](https://github.com/user-attachments/assets/6b1f16d9-bc88-44ca-91b8-bd10eb381379)

# Training
Each model undergoes the through 100 epochs but with early stopping parameter and binary cross entropy loss function hence giving the best values for segmentation followed by the cell tracking methods.

# Execution
Execute all the segmentation notebooks with the methods along with the location of the dataset and its position in local desktop or Google Colab.
Then run the HRNet and UNet3+ tracking algorithms.ipynb and the SegNet tracking algorithms.ipynb files for the same dataset location.
