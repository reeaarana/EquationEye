# 


# EquationEye – Handwritten Math Expression Recognition  

EquationEye is an AI-powered OCR model designed to recognize handwritten mathematical expressions with high accuracy. Using deep learning techniques, it processes images of equations and extracts mathematical symbols for further computation.  

## 📌 Features  
- **Dataset**: Uses the [Handwritten Math Expressions Dataset](https://www.kaggle.com/datasets/govindaramsriram/handwritten-math-expressions-dataset).  
- **Preprocessing**:  
  - Converts images to grayscale  
  - Resizes to 128×128 pixels  
  - Normalizes pixel values  
- **Model Architecture**:  
  - **CNN layers** for feature extraction  
  - **LSTM layers** for sequence modeling  
  - Fully connected dense layers for classification  
- **Training & Evaluation**:  
  - Model is trained with Adam optimizer  
  - Categorical cross-entropy loss function  
  - Accuracy & loss tracking over epochs  
  - Confusion matrix for performance evaluation  

## 📂 Dataset  
The dataset consists of handwritten mathematical expressions with corresponding labels. It includes expressions like:  
```
3 + 4 → 7
(8 - 5) → 3
9 ÷ 3 → 3
```

## 🚀 Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/EquationEye.git
   cd EquationEye
   ```  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
3. Download the dataset from Kaggle and extract it.  

## 🔧 Usage  
Run the preprocessing script:  
```bash
python preprocess.py
```  
Train the model:  
```bash
python train.py
```  
Evaluate the model:  
```bash
python evaluate.py
```  

## 📊 Results  
- Model performance evaluated on validation and test datasets  
- Training and validation accuracy/loss plots  
- Confusion matrix for error analysis  

## 🔮 Future Improvements  
- Improve accuracy with Transformer-based OCR models  
- Enhance dataset with more variations  
- Implement real-time handwritten math expression recognition  

## 📜 License  
This project is open-source and available under the MIT License.  

---

Let me know if you'd like any modifications! 🚀👀
