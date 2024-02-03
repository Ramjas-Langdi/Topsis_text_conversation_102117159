# Topsis_text_conversation_102117159
# Hugging Face Pretrained Models Comparison
This project compares the performance of five pretrained models from Hugging Face using TOPSIS. The models are evaluated based on four parameters: coherence, engagement, relevance, and understandability. The evaluation is conducted on a sample text conversation to determine which model performs best in generating embeddings for text data.
  
Comparison process involves the following steps:
  
Data Preparation: A sample text conversation is used as input data for evaluating the pretrained models.
  
Model Evaluation: The pretrained models are loaded using the Hugging Face library and their embeddings are generated for the text conversation. The embeddings are then evaluated based on the specified parameters using the TOPSIS method.
  
Result Analysis: The evaluation results are saved to a CSV file (102117159model_comparison_results.csv) containing the scores and ranks for each model.
    
Visualization: A bar graph is generated to visually compare the performance of the models based on the evaluation parameters.
  
The following pretrained models from Hugging Face are used in this project:
  BERT (bert-base-uncased, bert-base-cased)
  RoBERTa (roberta-base)
  DistilBERT (distilbert-base-uncased)
  XLNet (xlnet-base-cased)  
The models are evaluated based on the following parameters:
  Coherence
  Engagement
  Relevance
  Understandability  
The bar graph visualizes the performance of the pretrained models based on the evaluation parameters. Each bar represents a pretrained model and the height of the bar indicates the score for each parameter.
