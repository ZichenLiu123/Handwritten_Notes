# Handwritten Text Recognition for Physician Notes

## Project Overview  
This project develops a deep learning system to recognize handwritten English words from physician notes using a Convolutional Recurrent Neural Network (CRNN) architecture. Leveraging the IAM Handwriting Database, the pipeline includes preprocessing of grayscale word images, spatial feature extraction via CNN layers, sequence modeling with BiLSTM, and alignment-free transcription using a CTC loss layer.

## Key Features
- **Hybrid CRNN Model**: Combines CNN (spatial feature extraction) + BiLSTM (temporal sequence modeling) + CTC (alignment-free transcription).  
- **Robust Handwriting Handling**: Outperforms rule-based Tesseract OCR on cursive and varied handwriting styles.  
- **Evaluation Metrics**: Word Accuracy, Character Error Rate (CER), Character Accuracy.
