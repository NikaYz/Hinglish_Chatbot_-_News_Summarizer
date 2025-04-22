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

To get started with the project, follow the instructions in the Jupyter notebooks:

1. **Open the Jupyter notebooks**: `Hinglish-Chatbot.ipynb`, `New-Summarizer.ipynb` to explore the implementation.
   
2. **Load the models and tokenizers** in `INFER.ipynb`: 

3. **Data preprocessing**: 
   - Preprocess the data as per the notebook instructions to prepare it for the model.

4. **Run inference**: 
   - Use the provided functions to interact with the chatbot and generate responses.
   - For the news summarization task, use the provided functions to generate summaries for news articles.
     
## Future Improvements

- **Training on Larger Datasets**:
  - The models were trained on smaller datasets, leading to less accurate results. Future work will involve training on larger, more diverse datasets to improve the model's generalization and accuracy.

- **Model Upgrades**:
  - Integrating more sophisticated or pretrained models such as **GPT-3**, **BERT**, or other transformer-based architectures will help achieve better performance for both the chatbot and the news summarization tasks.

- **Enhancing Output Quality**:
  - There will be improvements in handling repetitive and irrelevant responses from the chatbot. Additionally, the goal is to generate more coherent, contextually relevant, and meaningful summaries for news articles.

