
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

## 🧠 Architecture

- **Feature Extraction**: VGG16
- **Caption Generation**: LSTM
<img width="1672" height="809" alt="image" src="https://github.com/user-attachments/assets/0f2d92ad-d19c-4881-ba16-ad6dde928df3" />

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

## 💡 Conclusion

This project successfully integrates CNNs and RNNs for image captioning, particularly in the tourism domain. With further improvements (e.g., attention mechanism, dataset expansion), the system can become a robust tool for travel apps, education, and tourism boards.

---

## 🚀 Future Scope

- Integrate **attention mechanisms**
- Use **transformer-based models**
- Deploy as a web app with **Streamlit**

---

## 🖥️ Deployment (Optional)

To run locally or in Google Colab:




