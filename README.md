# 📩 SMS Spam Detection using TensorFlow & NLP

## 📌 **Overview**
This project builds a machine learning model to classify SMS messages as **spam or ham** (not spam). Using **TensorFlow, Keras, and NLP techniques**, the model learns to detect spam messages based on a dataset of labeled SMS texts.

## 🚀 **Features**
✅ Text preprocessing & tokenization using Keras
✅ Converts text into sequences for model input
✅ Uses **Embedding, Global Average Pooling & Dense layers**
✅ Trained using **Adam optimizer & Binary Cross-Entropy Loss**
✅ Predicts if an SMS is **spam or ham**

---

## 📊 **Technologies Used**
- Python
- TensorFlow & Keras
- Natural Language Processing (NLP)
- Pandas & NumPy
- Matplotlib (for visualizations)

---

## 📂 **Dataset**
The model is trained on a dataset of SMS messages labeled as "ham" (not spam) or "spam". The dataset is fetched from freeCodeCamp's project files.

---

## 🛠 **Installation & Setup**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/sms-spam-detection.git
   cd sms-spam-detection
   ```
2. Install dependencies:
   ```bash
   pip install tensorflow pandas numpy matplotlib
   ```
3. Run the script:
   ```bash
   python spam_detection.py
   ```

---

## 📌 **Usage**
### **Training the Model**
The model is trained using:
```python
history = model.fit(X_train, y_train, epochs=10, batch_size=512, validation_data=(X_test, y_test), verbose=1)
```
### **Making Predictions**
Use the function to predict if a message is spam:
```python
predict_message("Congratulations! You have won a prize. Call now!")
```
Example output:
```
[0.9823, 'spam']
```

---

## 🧩 **Project Structure**
```
├── train-data.tsv          # Training dataset
├── valid-data.tsv          # Validation dataset
├── spam_detection.py       # Main script
├── README.md               # Documentation
```

---

## 👥 **Contributing**
Feel free to contribute by submitting pull requests or reporting issues. Suggestions and improvements are always welcome!

---

## 📜 **License**
This project is open-source and available under the **MIT License**.

