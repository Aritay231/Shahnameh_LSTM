📜 Shahnameh_LSTM — Persian Poetry Generation with LSTM
This project explores the beauty of Persian epic poetry through the lens of deep learning. Using an LSTM (Long Short-Term Memory) neural network, we train a model on shahnameh.txt—a text version of Ferdowsi’s legendary Shahnameh—to generate new verses that echo its style and rhythm.

🧠 Project Overview
The goal is to generate Persian-style poetry that mimics the structure and tone of the Shahnameh. LSTM networks are particularly suited for this task due to their ability to capture long-term dependencies in sequential data, making them ideal for text generation.

📂 Dataset
- shahnameh.txt: A cleaned and formatted version of Ferdowsi’s Shahnameh, used as the training corpus.

🔧 Model Architecture
- LSTM layers for sequence modeling
- Embedding layer to convert characters or words into dense vectors
- Dense output layer with softmax activation for character prediction

🚀 How It Works
- Preprocessing: Text is cleaned, tokenized, and converted into sequences.
- Training: The LSTM model learns to predict the next character in a sequence.
- Generation: Given a seed phrase, the model generates new lines of poetry in the style of the Shahnameh.

🧙‍♂️ About Ferdowsi and the Shahnameh
Abu al-Qasem Ferdowsi (c. 935–1020 CE) was one of the greatest Persian poets and the author of the Shahnameh—The Book of Kings—a monumental epic that preserves the mythological and historical heritage of ancient Iran. Born near the city of Ṭūs, Ferdowsi spent over three decades composing this masterpiece, driven by a deep love for Persian culture and language during a time of Arab influence.
The Shahnameh is the longest epic poem written by a single author, consisting of nearly 60,000 couplets. It recounts the tales of legendary kings, heroes like Rostam, and mythical creatures, blending history, mythology, and moral lessons. Written in Classical Persian, it played a crucial role in reviving and preserving the Persian language and identity.
Ferdowsi’s work is more than literature—it’s a cultural cornerstone for Iran and the Persian-speaking world. His poetic legacy continues to inspire generations, and your project taps into that timeless spirit by using AI to generate new verses in his style.
