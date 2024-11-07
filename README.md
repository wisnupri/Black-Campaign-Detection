# Combination K-Means and LSTM for Social Media Black Campaign Detection

This project implements a machine learning pipeline combining **K-Means** clustering and **LSTM** (Long Short-Term Memory) for detecting black campaigns related to the **2024 Indonesia Presidential Candidates** on social media. The system aims to identify and categorize campaign-related posts for further analysis and monitoring.

## Paper Reference

This project is based on the paper:

> **Combination K-Means and LSTM for Social Media Black Campaign Detection of Indonesia Presidential Candidates 2024**  
> Published in **Jurnal Teknik Informatika (JUTIF), Vol. 5, No. 2, April 2024**  
> DOI: [10.52436/1.jutif.2024.5.2.1635](https://doi.org/10.52436/1.jutif.2024.5.2.1635)

You can read the full paper here:  
- [Article Link](https://jutif.if.unsoed.ac.id/index.php/jurnal/article/view/1635) ✍️
- [PDF Download](https://jutif.if.unsoed.ac.id/index.php/jurnal/article/view/1635/475) 📄

## Features

- **Data Preprocessing**: Clean and prepare text data for analysis.
- **K-Means Clustering**: Group similar social media posts into clusters.
- **LSTM Model**: Classify the posts to detect black campaign content.
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score.

## Project Structure

```plaintext
📂 data/           # Dataset
🪐 K_means_pre_pro_Anies.ipynb
🪐 K_means_pre_pro_Ganjar.ipynb
🪐 K_means_pre_pro_Prabowo.ipynb
🪐 LSTM_Model_Detection.ipynb
📄 README.md       # Project documentation
