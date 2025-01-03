
# Emojify

Emojify is a project from the Coursera Deep Learning Specialization that enhances emoji lookup functionality by leveraging word vectors and neural networks. This project explores the use of vector representations to associate words with emojis, even when those associations aren't explicitly present in the training data.

## 📝 Project Overview

Many emoji interfaces require users to remember specific keywords to find emojis. For example, typing "love" might not return ❤️ because it’s mapped to "heart." Emojify creates a smarter emoji interface using word vectors, enabling the model to generalize and associate related words with emojis effectively.

### Key Features
1. **Word Vector Integration**:
   - Use word vectors to generalize associations between words and emojis.
2. **Baseline Model (Emojify-V1)**:
   - A simple classifier leveraging word embeddings.
3. **Advanced Model (Emojify-V2)**:
   - Incorporates LSTM layers for improved performance and generalization.

### What You'll Learn:
- Creating an embedding layer in Keras with pre-trained word vectors.
- Advantages and disadvantages of the GloVe algorithm.
- Building and training sentiment classifiers using word embeddings.
- Developing an advanced sentiment classifier with LSTMs.

## 🛠️ Tech Stack
- **Programming Language**: Python
- **Libraries**: 
  - NumPy
  - Matplotlib
  - Keras (with TensorFlow backend)

## 🚀 Installation and Usage

### Prerequisites
- Python 3.x
- Required Python libraries:
  ```bash
  pip install numpy matplotlib tensorflow
  ```

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/emojify.git
   ```
2. Navigate to the project directory:
   ```bash
   cd emojify
   ```
3. Run the notebook or Python script:
   ```bash
   jupyter notebook Emojify.ipynb
   ```

### Usage
1. Input a sentence into the Emojify model.
2. The model will output the most relevant emojis based on word vector associations.

## 📚 Project Details

This project builds two models:
1. **Emojify-V1**:
   - Baseline model using word embeddings for classification.
2. **Emojify-V2**:
   - Advanced model incorporating LSTMs for improved accuracy and generalization.

## 🌟 Project Status
This project is in **maintenance mode** and is available for educational purposes. 

## 📧 Contact
For questions, feedback, or contributions, please contact:
**Gabriel Meredith**  
Email: [Gabriel.b.meredith@gmail.com](mailto:Gabriel.b.meredith@gmail.com)

## 🙏 Acknowledgments
This project was developed as part of the Coursera Deep Learning Specialization by Andrew Ng. Special thanks to the creators and contributors of the GloVe word vector algorithm.

---
