# Masked LLM vs. BERT Models

Welcome to the **Masked LLM vs. BERT Models** project repository! This project compares different approaches for masked language modeling using a dataset of Twitch chat data. The primary goal is to assess the performance of a custom masked LLM implementation in comparison to a default BERT model and a fine-tuned BERT model.

## Project Overview

- **Custom Masked LLM (my_model.ipynb)**: This Jupyter Notebook contains the implementation of a custom masked Language Model for text generation. The model's performance is evaluated on masked sequences of text using Twitch chat data. As expected, the custom implementation may perform differently from pre-trained models due to its unique architecture and training data.

- **BERT Model (BERT_pretrained.ipynb)**: This Jupyter Notebook uses the default BERT model and evaluates its performance on the masked dataset. BERT is a widely used pre-trained model for various natural language understanding tasks.

- **Fine-Tuned BERT Model (BERT_pretrained_finetuned.ipynb)**: This Jupyter Notebook contains a BERT model that has been fine-tuned using the specific task of masked language modeling. It is then evaluated on the same masked dataset to determine if fine-tuning improves performance.

## Dataset

The project utilizes a dataset comprised of Twitch chat data, which presents unique challenges due to the informal and diverse nature of the language used.

## Project Context

This project was developed as part of the final assignment for CSCE 421 at Texas A&M University. The objective was to explore and experiment with different approaches to custom word generation for masked sequences of text, which is a valuable skill in various natural language processing tasks.

## Evaluation and Results

The performance of each model should be discussed in detail within the respective Jupyter Notebooks. Cosine similarity was used as the basis of accuracy.

## Limitations

The project involved the Twitch Dataset which contained numerous unknown words for standard vectorizers. As such many words would simply be classified as unknown leading to misleading results. 

## Possible Improvements

While the project provides valuable insights into masked language modeling, there are several avenues for improvement, including:

- Custom Vectorizer: Exploring the use of a custom word embedding vectorizer that aligns better with the Twitch chat data, capturing its unique linguistic characteristics.

- Handling Unknown Words: Developing a more robust method for classifying unknown words into embeddings to improve the generation of unseen or rare words.

## Contributing

If you would like to contribute to this project by enhancing the models, conducting further experiments, or addressing possible improvements, please fork this repository, make your changes, and submit a pull request. Your contributions are highly welcome!

## Contact

If you have any questions, suggestions, or feedback regarding this project or its findings, please don't hesitate to reach out.

Anish Karthik
