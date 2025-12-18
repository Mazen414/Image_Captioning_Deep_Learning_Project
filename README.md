# Automatic Image Captioning using Deep Learning (CNN-LSTM)
**Group:** 23
**Course:** LEEN364 - Deep Learning and Classification Techniques

## 📂 Project Structure
* **`01_Experimental_Validation.ipynb`**: Scientific validation using an 80/20 split to calculate BLEU scores.
* **`02_Production_Training_Pipeline.ipynb`**: The main training pipeline run on Google Colab (T4 GPU) for 20 Epochs on the full dataset.
* **`03_Live_Demo_Interface.ipynb`**: The inference script that loads the trained model to caption new images.

## 🧠 Model Artifacts
* **`tokenizer.json`**: Included in this repository (Dictionary mapping).
* **`best_model.h5`**: [Download the Trained Model Here](https://drive.google.com/file/d/1uDH1eBI44JXmYfZQaqm-qGel1ogO15FE/view?usp=drive_link)
  *(Note: The model file is hosted on Google Drive due to GitHub file size limits.)*

## 🚀 How to Run
1. Download the `Flickr8k` dataset and place it in the project directory.
2. Download `best_model.h5` from the link above.
3. Run `03_Live_Demo_Interface.ipynb` to launch the caption generator.
