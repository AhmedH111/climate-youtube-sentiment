# climate-youtube-sentiment
Code and datasets used in dissertation

# Comparative Climate Change Sentiment Analysis using Machine Learning.

The project trains a BERT + CNN sentiment classifier, optimises CNN heads with MTNAS, tests DAPT on YouTube comments, and applies the final model to climate-related YouTube comments from US and EU news channels (2010–2025).

# Notebooks

- `APIYoutube.ipynb` – Collect climate-related YouTube comments via the YouTube Data API v3  
- `ParqToExcel.ipynb` – Convert collected Parquet files into yearly Excel tables  
- `Initial_DatasetB.ipynb` – Baseline training on a Kaggle YouTube sentiment dataset  
- `MTNAS.ipynb` – Multitask Neural Architecture Search (MTNAS) for CNN heads  
- `DAPTtest.ipynb` – Fine-tuning and Domain-Adaptive Pre-Training (DAPT) experiments  
- `ClimateDataAnalysis.ipynb` – Descriptive analysis of labelled climate comment data  

# Datasets (Kaggle)

The following public datasets were used for training and evaluation (The first four are the A-D datasets and the 5th dataset was used only for DAPT):

- Sentiment140 (Twitter) – https://www.kaggle.com/datasets/krishbaisoya/tweets-sentiment-analysis 
- 100K YouTube Comments – https://www.kaggle.com/datasets/surajbhandari527/100k-youtube-comments-youtube-sentiment-dataset 
- YouTube Comments Dataset – https://www.kaggle.com/datasets/hamzaedit/youtube-comments-dataset 
- Twitter Climate Change Sentiment – https://www.kaggle.com/datasets/edqian/twitter-climate-change-sentiment-dataset/data
- YouTube Comments Sentiment Dataset – https://www.kaggle.com/datasets/amaanpoonawala/youtube-comments-sentiment-dataset

The collected climate-related YouTube comment data are not included in this repository due to platform terms and privacy considerations.
