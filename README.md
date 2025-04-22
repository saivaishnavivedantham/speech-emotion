## 🎙️ Speech Emotion Recognition
**📍 Institution:** UTA  

Developed a machine learning pipeline to detect emotions from speech using audio features and classical ML models.

### ✨ Highlights
- Used **librosa** to extract **MFCC** features from the **TESS** (Toronto Emotional Speech Set) dataset.
- Applied **PCA** to retain 99% variance and **SMOTE** for class balancing.
- Trained multiple classifiers (SVM, Random Forest, KNN, Logistic Regression).
- Enabled real-time emotion inference for affective computing use cases.

### 🧠 Workflow
1. **Audio Processing** → MFCC extraction (librosa)  
2. **Dimensionality Reduction** → PCA  
3. **Balancing** → SMOTE  
4. **Modeling** → SVM, RF, KNN, LR  
5. **Deployment Readiness** → Real-time Inference Pipeline  

### 📂 Dataset
- 📥 [Toronto Emotional Speech Set (TESS) – Kaggle](https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess)

### 🛠️ Tech Stack
`Python`, `librosa`, `scikit-learn`, `Pandas`, `Seaborn`

### 📊 Results
- 🎯 Achieved 91% test accuracy using SVM  
- 🎧 Built for real-time audio-based emotion detection
