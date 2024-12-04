# 🧠 Stress Level Detection

This project uses machine learning to predict the stress level of individuals based on various heart rate variability features. The model is built using **TensorFlow** and **Keras** with a fully connected neural network.

---

## 🌟 Project Highlights

- **Data Preprocessing**: Cleaned and standardized heart rate features for model training. 🔧
- **Neural Network Model**: Built a neural network to classify stress levels. 🤖
- **Performance**: Achieved high validation accuracy of **95.64%**. 📈
- **Model Saving**: Saved the trained model for deployment. 💾

---

📊 **Data Overview**

The dataset contains heart rate variability features, including:

MEAN_RR, RMSSD, pNN25, pNN50, LF, HF, LF_HF

Target variable: condition (0 = low stress, 1 = high stress)
---

🤖 **Model Details**

Model Type: Fully connected neural network (Dense layers)

Activation Function: ReLU for hidden layers, Softmax for output

Optimizer: Adam

Loss Function: Categorical Crossentropy

🧪 **Model Performance**

Training Accuracy: 95.86%
Validation Accuracy: 95.64%
