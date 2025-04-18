# 🖼️ Image Caption Generator using CNN + LSTM

This project uses deep learning to generate natural language captions for images. It combines a CNN (InceptionV3) for image feature extraction with an LSTM for text generation.

---

## 🚀 How It Works

1. **Pre-trained InceptionV3** extracts image features.
2. Captions are preprocessed and tokenized.
3. Image features + sequence tokens are fed into an LSTM to predict the next word.
4. Training is evaluated using BLEU score.

---

## 🧪 Dataset

- **Flickr8k** Dataset: [Download Here](https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip)
- Captions: [Flickr8k_text.zip](https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip)

---

## 📊 Sample Output

| Image | Generated Caption |
|-------|-------------------|
| ![dog](images/dog.jpg) | "a dog is running through the grass" |
| ![football](images/football.jpg) | "several men are playing soccer" |

---

## 🛠️ Installation

```bash
pip install -r requirements.txt
