
# 🏞️ Tourist Spot Image Caption Generator

Automatically generate descriptive captions for tourist spot images using deep learning models (VGG16 + LSTM).

## 📌 Abstract

This project proposes a deep learning-based image captioning system for tourist attractions. It uses **VGG16** (CNN) for feature extraction and **LSTM** (RNN) for generating natural language descriptions. The system is trained on a dataset of tourist spot images, each annotated with four captions.

> 📝 **BLEU Score Achieved:** 6 (baseline performance)

Despite the modest BLEU score, the model shows promise and can be enhanced further with improved data and techniques such as attention mechanisms.

---

## 📷 Sample Output

| Input Image | Generated Caption |
|-------------|--------------------|
| 🏰 Landmark Image | "A historic monument surrounded by greenery" |
| 🏞️ Nature Scene | "A river flowing through the forest landscape" |

---

## 🎯 Objectives

- Develop a model that describes tourist spots accurately.
- Ensure captions are **semantic**, **contextual**, and **informative**.
- Evaluate the model using metrics like BLEU, coherence, and user satisfaction.

---

## 📚 Literature Survey

| Title | Authors | Year | Methods |
|-------|---------|------|---------|
| New CNN-RNN framework | Genc Hoxha et al. | 2020 | CNN + Encoder-decoder |
| Caption based on target detection | Yan Wang et al. | 2023 | ResNet-50 + SSD |
| Object + color recognition | Nimra et al. | 2023 | Transformer-decoder |
| Deep neural network | Sudhakar et al. | 2022 | LSTM + VGG16 |
| ResNet-50 and LSTM | Satish Kumar et al. | 2023 | LSTM + ResNet-50 |

---

## 🧠 Architecture

- **Feature Extraction**: VGG16
- **Caption Generation**: LSTM
- **Vector Size**: 4096 (image), 256 (word embeddings)
- **Output Layer**: Softmax (707 vocabulary size)

---

## 📂 Dataset

- **Images**: 434 tourist spot images  
- **Captions**: 1736 (4 per image)  
- **Format**: Image file + Caption file  

---

## 🛠 Requirements

### Software
- Python
- TensorFlow / Keras or PyTorch
- Google Colab (recommended)

### Hardware
- 16GB RAM, 500GB SSD
- NVIDIA GTX 1080 Ti (or higher)

---

## 🧪 Test Cases

| Test Scenario | Input | Expected Output |
|---------------|-------|-----------------|
| Basic Functionality | Single Image | One accurate caption |
| Diverse Images | Different scenes | Descriptive captions |
| Varying Resolution | High/low res images | Consistent captions |
| Noisy Images | Blurred/noisy input | Robust captioning |

---

## 💡 Conclusion

This project successfully integrates CNNs and RNNs for image captioning, particularly in the tourism domain. With further improvements (e.g., attention mechanism, dataset expansion), the system can become a robust tool for travel apps, education, and tourism boards.

---

## 🚀 Future Scope

- Integrate **attention mechanisms**
- Use **transformer-based models**
- Deploy as a web app with **Streamlit**

---

## 📑 References

1. Genc Hoxha et al., IEEE Xplore, 2020  
2. Yan Wang et al., IEEE Xplore, 2023  
3. Nimra et al., IEEE Xplore, 2023  
4. Sudhakar et al., IEEE Xplore, 2022  
5. Satish Kumar et al., IEEE Xplore, 2023

---

## 🖥️ Deployment (Optional)

To run locally or in Google Colab:




