# Hinglish Chatbot & News Summarizer
- **Hinglish Chatbot** and **News Summarization** implementation.
- The project aims to:
  - Apply concepts learned in the course.
  - Understand the workflow of an encoder-decoder model without relying on pretrained models.
- It includes:
  - Notebooks for **data processing**, **model training**, and **inference**.
  - Tokenizers for **text processing**.
    
The project consists of the following key files:

| **File Name**               | **Description**                                                                 |
|-----------------------------|---------------------------------------------------------------------------------|
| `Hinglish-Chatbot.ipynb`     | Jupyter notebook for training the chatbot model.                               |
| `New-Summarizer.ipynb`       | Notebook dedicated to news summarization tasks.                                |
| `INFER.ipynb`                | Notebook used for running inference with new input data.                       |
| `NLP_Project.pdf`            | Report detailing the methodologies, findings, and analysis of the project.     |
| `chatbot_tokenizer.pkl`      | Tokenizer for processing the chatbot's input and output text.                  |
| `summary_tokenizer.pkl`      | Tokenizer used for processing the news summarization task.                    |


## Requirements

Since the code are in notebook one can run them in colab but make sure to run it in GPU.

## Usage Instructions

To access the models, there is a file named `Models-access.txt`, which contains links to the trained models. You can download the models from there for inference.

To get started with the project, follow the instructions in the Jupyter notebooks:

1. **Open the Jupyter notebooks**: 
   - `Hinglish-Chatbot.ipynb`: Explore the implementation for training and interacting with the Hinglish chatbot.
   - `New-Summarizer.ipynb`: Explore the implementation for the news summarization task.

2. **Load the models and tokenizers**: 
   - In `INFER.ipynb`, load the pre-trained models and their respective tokenizers for both tasks (Hinglish chatbot and news summarization).

3. **Data preprocessing**:
   - Follow the instructions in the notebook to preprocess the data for each task and make it ready for model inference.

4. **Run inference**: 
   - Use the provided functions to interact with the chatbot and generate responses.
   - For news summarization, use the provided functions to generate summaries for the input news articles.

## Future Improvements

- **Training on Larger Datasets**:
  - The models were trained on smaller datasets, leading to less accurate results. Future work will involve training on larger, more diverse datasets to improve the model's generalization and accuracy.

- **Model Upgrades**:
  - Integrating more sophisticated or pretrained models such as **GPT-3**, **BERT**, or other transformer-based architectures will help achieve better performance for both the chatbot and the news summarization tasks.

- **Enhancing Output Quality**:
  - There will be improvements in handling repetitive and irrelevant responses from the chatbot. Additionally, the goal is to generate more coherent, contextually relevant, and meaningful summaries for news articles.

