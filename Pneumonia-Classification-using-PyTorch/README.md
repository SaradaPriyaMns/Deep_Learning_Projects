This directory will contain the project files for the Pneumonia Classification using Pytorch Project.


# Pneumonia Classification using PyTorch

This project involves classifying pneumonia from chest X-ray images using a deep learning model implemented in **PyTorch**. The model is trained on a dataset of chest X-rays, and the project aims to demonstrate the effectiveness of deep learning in medical image analysis.

## Project Structure:

1. **`chest_xray_data/`**: Contains the dataset (X-ray images).
   - **Note**: Due to the large size of the dataset, it is **not hosted on GitHub**.
   - You can download the dataset from the following Kaggle link:
     - [Download Chest X-ray Pneumonia Dataset on Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
   - After downloading, extract the dataset and place the `chest_xray_data` folder in the project directory.

2. **`helper.py`**: Contains functions for image transformations, data loading, and model saving.

3. **`Pneumonia_Classification.ipynb`**: The main notebook for performing pneumonia classification and running the model.


4. **`results/`**: Contains output from training, including plots and saved models.
   - **`training_plots/`**: Folder for storing plots of training accuracy and loss.
   - **`final_model.pth`**: The final trained model file.

## How to Run the Project:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Pneumonia-Classification-using-PyTorch.git
   cd Pneumonia-Classification-using-PyTorch

