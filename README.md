

# Machine Translation Project (English to Hindi)

This project aims to develop a state-of-the-art machine translation system using Long Short-Term Memory (LSTM) networks to translate text from English to Hindi. It is built using an Encoder-Decoder architecture that processes the input sequence in English and generates the output sequence in Hindi.

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Methodology](#methodology)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Future Work](#future-work)
- [Authors](#authors)
- [License](#license)

## Introduction
In this project, we developed a machine translation model capable of translating English text into Hindi using deep learning techniques. The model uses an Encoder-Decoder architecture with LSTM networks to learn the mappings between English and Hindi sentence pairs.

## Project Structure

## Methodology
The machine translation process involves:

1. **Data Collection**: The dataset is collected from Kaggle, consisting of English-Hindi sentence pairs.
2. **Text Preprocessing**: We preprocess the text by normalizing case, removing special characters, and tokenizing the sentences.
3. **Model Training**: The model is trained using an Encoder-Decoder LSTM architecture, which captures the semantic meaning of English sentences and generates corresponding Hindi translations.
4. **Evaluation**: The model is evaluated using BLEU scores to measure translation quality.

## Dataset
We used the `Hindi_English_Truncated_Corpus` dataset from Kaggle, consisting of around 1.2 million English-Hindi sentence pairs. The dataset was preprocessed for optimal performance during model training.

## Model Architecture
- **Encoder-Decoder LSTM**: The encoder processes the English sentence and converts it into a context vector. The decoder uses this vector to generate the Hindi translation word by word.
- **RNN-Based Alternative**: We also experimented with an RNN-based architecture for comparison.

## Evaluation Metrics
- **BLEU Score**: The primary metric used to evaluate the model’s translation accuracy, which compares machine-generated translations to human reference translations.

## Results
- **Training Loss**: The training loss shows a smooth downward trend, indicating effective learning by the model.
- **BLEU Scores**: Achieved satisfactory BLEU scores, demonstrating the ability to generate accurate translations for most sentence pairs.

## Future Work
- Expand the dataset to include more diverse language pairs.
- Experiment with transformers and attention mechanisms to improve translation quality.
- Fine-tune the model for domain-specific translations and real-time applications.

## Authors
- Devshree Jadeja
- Khushi Shah

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Feel free to modify this README as per your project specifics!
