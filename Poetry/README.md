# 📝 Persian Poetry Text Generation with RNN

This project trains a **character-level RNN (GRU)** model using TensorFlow to generate **Persian poetry** inspired by the works of **Khayyam** and **Molana**.  
The model learns the style and structure of Persian text and produces new lines of poetry from a given starting phrase.

---

## 📘 Project Overview
- Loads and encodes Persian text from `khayyammolana.txt`
- Builds a character vocabulary and integer mapping
- Prepares input and target sequences for training
- Defines and trains a **GRU-based RNN model** with:
  - Embedding layer
  - GRU layer (1024 units)
  - Dense output layer
- Generates new Persian text character by character

---

## 🛠️ Key Technologies
- Python  
- TensorFlow / Keras  
- NumPy  

---

## 📈 Example Generated Text
