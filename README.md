# Review Text Mining & Topic Modeling Project  

This project explores customer reviews from Amazon, Netflix, and movie datasets using text mining and topic modeling techniques to extract insights, detect key entities, and understand customer sentiment trends.  

## Project Overview  
The goal of this project was to clean, process, and analyze review text data, perform Named Entity Recognition (NER) to extract brands and product names, and use Latent Dirichlet Allocation (LDA) topic modeling to group reviews into meaningful themes. The project visualizes results using word clouds and topic distributions to provide actionable insights for improving customer experience.  

## Project Components  

### Amazon Review NER Analysis  
- Cleaned and preprocessed Amazon product reviews.  
- Performed language detection to filter multilingual reviews.  
- Applied **Named Entity Recognition (NER)** to extract product names, brands, and relevant entities.  
- Generated word clouds and frequency distributions for extracted entities.  

### Movie & Netflix Review Analysis  
- Preprocessed and cleaned review text (lowercasing, tokenization, stopword removal).  
- Generated **word clouds** and **sentiment analysis** to identify overall audience sentiment.  
- Identified top positive and negative terms, highlighting common themes in reviews.  

### LDA Topic Modeling & Clustering  
- Built **LDA (Latent Dirichlet Allocation)** topic models on review datasets.  
- Tuned number of topics using **coherence score** and **perplexity** metrics.  
- Visualized topic distributions using **pyLDAvis**.  
- Compared LDA results with alternative clustering approaches (K-Means/EM).  

## Technologies Used  
- **Languages & Libraries:** Python, Pandas, Numpy, NLTK, SpaCy, Gensim, pyLDAvis, Scikit-learn, Langdetect, Langid  
- **Techniques:** Text Cleaning, Tokenization, NER, Topic Modeling (LDA), Clustering, Sentiment Analysis  
- **Visualization:** Matplotlib, WordCloud, pyLDAvis  
   ```bash
