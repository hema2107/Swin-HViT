# Swin-HViT: A Hybrid Transformer Approach for Accurate Early-Stage Crop Disease Diagnosis

## Summary

Agriculture plays a pivotal role in global economic growth, yet it faces significant challenges from pests and crop diseases. 
Early detection is crucial for preventing large-scale crop losses and ensuring food security. 
This study introduces a hybrid transformer model, Swin-HViT, which integrates the strengths of Vision Transformer (ViT) and Swin Transformer to accurately predict crop diseases. 
While ViT captures global image features, Swin Transformer excels at extracting fine-grained local details. 
Evaluated on two benchmark datasets, Corn and PlantDoc, our model achieved accuracies of 98.81% and 81.81%, respectively, surpassing recent works. 
Here, we demonstrate the effectiveness of combining complementary transformer architectures to enhance disease identification in diverse agricultural settings.

## Dataset 
The dataset used in this research can be downloaded from the following links:                                                                                                    
Corn Dataset: https://www.kaggle.com/datasets/smaranjitghose/corn-or-maize-leaf-disease-dataset                                                                                  
PlantDoc Dataset: https://www.kaggle.com/datasets/abdulhasibuddin/plant-doc-dataset

## Architecture
The proposed Hybrid Architecture is given below:
<img width="940" height="644" alt="image" src="https://github.com/user-attachments/assets/f4faa9c6-ceee-4fed-9571-0473771e1bd0" />

## Reproducing Results & Figures
This repository provides a script 'Hybrid Swin-ViT model.py' to facilitate the reproduction of key results from the paper, including model training, figure generation, and inference.

## Using Pip
``` !pip install -q git+https://github.com/huggingface/transformers ```

https://doi.org/10.5281/zenodo.18182700                                                                                                                                  
This code is related to the manuscript that is under preview, it is available at https://doi.org/10.21203/rs.3.rs-8588269/v1


