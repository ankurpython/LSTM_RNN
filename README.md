# LSTM_RNN

**Next-Word Prediction Checker**

A simple next-word prediction tool based on LSTM (and possibly GRU) networks, with a Streamlit interface for interactive testing.

---

## Project Structure

- **app.py**  
  A Streamlit-based web application for entering text and getting next-word predictions.
  
- **lstm_experiment.ipynb**  
  A Jupyter notebook showcasing LSTM model training and experimentation.

- **next_word_lstm.h5**  
  The trained LSTM model saved in HDF5 format.

- **tokenizer.pickle**  
  The tokenizer object used for preprocessing input text.

- **hamlet.txt**  
  A text dataset (likely Shakespeare’s *Hamlet*) used for training purposes.

- **requirements.txt**  
  A list of required Python libraries and dependencies.

---

## Demo

Visit the live demo of the application here:  
[lstmandgru-ankur.streamlit.app](https://lstmandgru-ankur.streamlit.app/) :contentReference[oaicite:0]{index=0}

---

## Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ankurpython/LSTM_RNN.git
   cd LSTM_RNN
