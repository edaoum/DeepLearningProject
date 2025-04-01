## 💻 How to run the project

### Step 1: clone the repository
```bash
git clone https://github.com/your_username/TP1-RNN-Sentiment-Analysis.git
cd TP1-RNN-Sentiment-Analysis

### Step 2 : set up a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

### Step 3: install dependencies
pip install -r requirements.txt

Step 4: run the notebook
jupyter notebook

📊 Results
The trained model achieves around 88% accuracy on the validation set.
A detailed confusion matrix provides insight into the performance.

📈 Future Improvements
Experiment with different architectures (GRU, CNN+RNN).
Hyperparameter tuning (embedding dimensions, LSTM units, regularization).
