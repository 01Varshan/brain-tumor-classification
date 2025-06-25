# 🧠 Brain Tumor Classification using Deep Learning

This project uses Convolutional Neural Networks (CNNs) to classify brain MRI images into four categories:

- Glioma Tumor  
- Meningioma Tumor  
- Pituitary Tumor  
- No Tumor  

Built with TensorFlow and trained on a publicly available Kaggle dataset, the goal is to assist in medical image understanding using accessible AI tools.

---

## 📁 Dataset

- **Source:** [Kaggle - Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
- MRI scans organized into folders by tumor type
- Training and Testing sets provided

---

## 🧠 Model Summary

- Custom CNN with 3 convolutional layers
- Dropout regularization for generalization
- Softmax output for 4-way classification

Technologies used:
- TensorFlow / Keras  
- NumPy & Matplotlib  
- Scikit-learn for evaluation

---

## 📈 Performance Highlights

- Achieved **~XX% training accuracy** and **~XX% validation accuracy**  
- Evaluated with a **confusion matrix** and **classification report**
- Supports real-time prediction on new MRI images

> 🔁 Model is saved as `brain_tumor_model.h5` for reuse or deployment

---

## 🧪 How to Use

1. Open the notebook (`brain_tumor_classification.ipynb`) in [Google Colab](https://colab.research.google.com/)
2. Upload your Kaggle API token to fetch the dataset
3. Run all cells to:
   - Preprocess MRI images
   - Train and validate the CNN
   - Test with new uploaded MRI images

---

## 👨‍💻 Author

**Varshan Chaubey**  
Electronics & Communications | Shiv Nadar University  
Passionate about deep learning, education & open research.

---

## 📄 License

This project is open-source under the MIT License.

