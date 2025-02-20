# Multi-Language Text Generation and Classification with RNNs

## Overview
This project implements a Recurrent Neural Network (RNN) for text generation and language classification. The objective is to generate text based on a given dataset and classify languages from text samples. The tasks are divided into two parts:  
1. **Text Generation** - Train an RNN to generate text similar to the dataset.  
2. **Language Classification** - Use an RNN to classify text samples into different languages.

## Prerequisites
Before running the code, ensure you have the following installed:  
- Python  
- NumPy  
- PyTorch  
- Matplotlib  
- Torchvision  

## Dataset
- The dataset for text generation consists of the complete works of Shakespeare.
- The dataset for language classification contains Bible translations in 20 different languages.
- You can also use a custom dataset for Part 2 of the project.

## Running the Code
1. Install the required dependencies.
2. Set up the dataset by running the provided script:
   ```sh
   ./download_language.sh
3. Run MP4_generation.ipynb and MP4_classification.ipynb
