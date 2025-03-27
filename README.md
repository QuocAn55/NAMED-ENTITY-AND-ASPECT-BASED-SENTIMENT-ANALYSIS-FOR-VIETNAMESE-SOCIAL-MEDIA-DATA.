# Named Entity and Aspect based Sentiment analysis for Vietnamese social media data

## Abstract
Aspect-based Sentiment Analysis (ABSA) has advanced significantly over the past decade, yet most research focuses on individual texts rather than dialogues, creating a gap in real-world applications. Extracting entities, aspects, opinions, and sentiments from conversations holds great potential. In this study, we constructed a dataset and trained models on user comments from YouTube videos, utilizing the Extract-Classify-ACOS method combined with transformer models. The best performance was achieved with BERT-base-uncased, reaching 71.27% accuracy, 75.09% precision, and 59.30% recall. Additionally, we conducted error analysis to enhance the dataset.

In this study, the input consists of processed user comments, while the output includes the predicted labels for those comments. The figure below illustrates the input and output of the task.

<p align="center">
  <img width="600" src="https://github.com/QuocAn55/NAMED-ENTITY-AND-ASPECT-BASED-SENTIMENT-ANALYSIS-FOR-VIETNAMESE-SOCIAL-MEDIA-DATA./blob/main/Images/InputOutput.png?raw=true" alt="Input and output">
  <br>
  <em>Figure 1: Example of the input and output of the task.</em>
</p>


## Dataset
We collected user comments from several Vietnamese programs such as "2 Ngày 1 Đêm", "Rap Việt",... and preprocessed them to prepare for model training.


<p align="center">
  <img width="600" src="https://github.com/QuocAn55/NAMED-ENTITY-AND-ASPECT-BASED-SENTIMENT-ANALYSIS-FOR-VIETNAMESE-SOCIAL-MEDIA-DATA./blob/main/Images/Quantity.png?raw=true" alt="Quantity">
  <br>
  <em>Figure 2: Distribution of the number of comments collected from several Vietnamese entertainment programs.</em>
</p>

# System Architecture

<p align="center">
  <img width="600" src="https://github.com/QuocAn55/NAMED-ENTITY-AND-ASPECT-BASED-SENTIMENT-ANALYSIS-FOR-VIETNAMESE-SOCIAL-MEDIA-DATA./blob/main/Images/Architec.png?raw=true" alt="Architecture">
  <br>
  <em>Figure 3: Overall architecture of the task.</em>
</p>

# Model Evaluation

<p align="center">
  <img width="600" src="https://github.com/QuocAn55/NAMED-ENTITY-AND-ASPECT-BASED-SENTIMENT-ANALYSIS-FOR-VIETNAMESE-SOCIAL-MEDIA-DATA./blob/main/Images/Model.png?raw=true" alt="Model">
  <br>
  <em>Figure 4: Training results of the models.</em>
</p>
