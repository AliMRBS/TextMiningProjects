# 🧠 Persian Text Generation with RNN (Khayyam & Molana)

This project trains a **character-level RNN (GRU)** model using TensorFlow to generate Persian poetry inspired by **Khayyam** and **Molana**.  
The model learns the structure and style of Persian text and produces new lines of poetry based on an input phrase.

---

## 📘 Project Overview
- Reads and encodes Persian text from `khayyammolana.txt`
- Builds a character vocabulary and integer mapping  
- Creates input and target sequences for training  
- Defines and trains an RNN model with:
  - **Embedding layer**
  - **GRU layer (1024 units)**
  - **Dense output layer**
- Generates new Persian text character-by-character after training

---

## 🛠️ Tech Stack
- Python  
- TensorFlow / Keras  
- NumPy  

---

## 🚀 How to Run
1. Place `khayyammolana.txt` in the project directory.  
2. Run the Python file to train the model:
   ```bash
   python main.py
