# Unsupervised Machine Translation System

This repository contains code for an unsupervised machine translation system that leverages parallel corpora to translate between English, Hindi, and French. The system uses pre-trained Helsinki NLP models and evaluates performance using BLEU, METEOR, and TER scores.

## Features
- Translate between **English** and **French** using `NLP2_en_fr.ipynb`.
- Translate from **English** to **Hindi** using `en_to_hi.ipynb`.
- Translate from **Hindi** to **English** using `hi_to_en(1).ipynb`.
- Test and evaluate the trained models using BLEU, METEOR, and TER metrics via `test.ipynb`.

## Prerequisites
1. Python 3.7+
2. Libraries:
   - Transformers
   - Torch
   - NumPy
   - SacreBLEU
   - METEOR
   - TERCOM

Ensure all dependencies are installed. You can install the required packages using:
```bash
pip install -r requirements.txt
```

## Files in the Repository
1. **NLP2_en_fr.ipynb**: Translates between English and French.
2. **en_to_hi.ipynb**: Translates from English to Hindi.
3. **hi_to_en(1).ipynb**: Translates from Hindi to English.
4. **test.ipynb**: Tests the trained models on a given file and calculates BLEU, METEOR, and TER scores.

## Instructions
### 1. Training Models
Each `.ipynb` file corresponds to a specific language pair. Open the desired file in Jupyter Notebook and follow the instructions to train the model.

### 2. Testing and Evaluation
To test the trained models:
1. Open `test.ipynb`.
2. Provide the path to the file containing sentences to be translated.
3. Run the notebook to compute the evaluation metrics (BLEU, METEOR, TER).

### 3. Pre-trained Helsinki NLP Models
This system uses pre-trained models from Helsinki NLP as the base for translation. You can load these models directly in the notebooks.

## Example
Here’s how to translate between English and French:
1. Open `NLP2_en_fr.ipynb` in Jupyter Notebook.
2. Load the pre-trained Helsinki model.
3. Provide the source text and run the cells to generate the translation.

## Evaluation Metrics
The test notebook calculates the following metrics to evaluate translation performance:
- **BLEU**: Bilingual Evaluation Understudy Score.
- **METEOR**: Metric for Evaluation of Translation with Explicit ORdering.
- **TER**: Translation Edit Rate.

## License
This project is open-source and distributed under the MIT License. Feel free to use and modify the code as per your needs.

---

### Note:
For more details or troubleshooting, please refer to the documentation in each notebook or raise an issue in the repository.

## Contributions
Contributions and suggestions are welcome! Feel free to fork this repository and create a pull request.

---

Happy Translating!


