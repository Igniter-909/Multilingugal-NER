# Multilingual Named Entity Recognition (NER)

This project demonstrates a Named Entity Recognition (NER) system using multilingual models. The system implements **Zero-Shot Transfer Learning** to recognize entities in various languages without direct training on those languages.

## Project Overview

Named Entity Recognition (NER) is the process of identifying and classifying entities in text into predefined categories such as **person names**, **organizations**, **locations**, and more. This notebook provides a multilingual NER solution, focusing on the use of transfer learning techniques.

### Zero-Shot Transfer Learning
Zero-shot transfer or zero-shot learning refers to the task of training a model on one set of labels and evaluating it on a different set of labels or tasks. In this context, we apply transformers to perform NER across different languages, even when the model has not been fine-tuned on the specific language.

## Requirements

To run this notebook and implement the NER system, ensure the following dependencies are installed:

- Python 3.6+
- Jupyter Notebook
- Hugging Face Transformers
- Torch
- Tokenizers

You can install the required packages using the following:

```bash
pip install torch transformers tokenizers
```

## How to Run

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/multilingual-ner.git
    ```

2. Navigate to the project directory and open the Jupyter notebook:
    ```bash
    cd multilingual-ner
    jupyter notebook Multilingual_NER.ipynb
    ```

3. Follow the steps in the notebook to train and evaluate the multilingual NER model.

## File Structure

- `Multilingual_NER.ipynb`: The main notebook file implementing the NER system.
- `data/`: Directory for any sample datasets (if applicable).
- `models/`: Directory for saving trained models.

## Acknowledgements

This project makes use of pre-trained models from Hugging Face's [Transformers](https://huggingface.co/transformers) library.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
