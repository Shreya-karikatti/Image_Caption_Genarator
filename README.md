# Image_Caption_Genarator
**ABSTRACT**
This project presents a novel approach to generating descriptive captions for images of tourist spots using a combination of deep learning models: VGG16 for feature extraction and Long Short-Term Memory (LSTM) networks for sequence generation. The VGG16 model, a pre-trained Convolutional Neural Network (CNN), is employed to extract high-level features from the input images, effectively capturing the visual content. These features are then fed into an LSTM network, a type of Recurrent Neural Network (RNN), to generate coherent and contextually relevant captions.
The model was trained and evaluated on a diverse dataset of tourist spot images, each annotated with multiple descriptive captions. The evaluation of the generated captions was performed using the BLEU (Bilingual Evaluation Understudy) score, a widely used metric for assessing the quality of machine-generated text by comparing it with reference captions. The model achieved a BLEU score of 6 indicating a baseline performance with significant room for improvement. 
Despite the modest BLEU score, the results demonstrate the potential of integrating CNNs and RNNs for automated image captioning in the domain of tourism. The project highlights key areas for future enhancement, including dataset augmentation, model architecture refinement, and the incorporation of attention mechanisms

**PROBLEM DEFINITION**
Image caption generation for tourist spots involves the development of a model that can automatically generate descriptive and informative captions for images depicting various tourist attractions, landmarks, or scenic views. 
Problem Statement: Given a dataset of images showcasing different tourist spots, the task is to develop a deep learning model that can generate accurate and contextually relevant captions describing the contents of these images.
Input: 
Dataset of tourist spot images (e.g., images of landmarks, natural landscapes, historical sites).
Ground truth captions corresponding to each image, providing accurate descriptions of the depicted scene.
Output:
Automatically generated captions for each input image, describing the contents of the image in a descriptive and informative manner

**ARCHITECTURE DIAGRAM**
<img width="1672" height="809" alt="image" src="https://github.com/user-attachments/assets/cbc3980d-b591-484a-ab67-5a68dca015d6" />

**FLOW DIAGRAM**
<img width="2023" height="1045" alt="image" src="https://github.com/user-attachments/assets/2303fcd5-e449-4513-af2f-cb4513264039" />


