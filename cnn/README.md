# Cat vs Dog Classifier

A deep learning project to classify images of **cats** and **dogs** using Convolutional Neural Networks (CNN) and MobileNetV2. The trained model achieves high validation accuracy and is saved as an `.h5` file for reuse or deployment.

##  Project Highlights
- Trained using **TensorFlow/Keras**
- Uses **Kaggle’s Dogs vs Cats dataset**
- High accuracy:  ~98% on validation data
- Transfer learning (optional): MobileNetV2 used for lightweight & fast inference
- Includes `.h5` model file for easy testing or reuse

---

##  Dataset

- Dataset used: [Dogs vs Cats | Kaggle](https://www.kaggle.com/c/dogs-vs-cats/data)
- **To download this dataset**, you’ll need a Kaggle account and your `kaggle.json` file.
  
```bash
# Instructions to load Kaggle dataset in Colab:
1. Upload your `kaggle.json` key file.
2. Run:
!mkdir -p ~/.kaggle
!cp kaggle.json ~/.kaggle/
!chmod 600 ~/.kaggle/kaggle.json
!kaggle competitions download -c dogs-vs-cats

