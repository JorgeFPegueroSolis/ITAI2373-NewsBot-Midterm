# ITAI2373-NewsBot-Midterm

This is a Natural Language Processing (NLP) project. In this project, I built a system that can automatically read and understand news articles. 

The NewsBot Intelligence System can: 

✅ Preprocess news articles using advanced text cleaning techniques 

✅ Classify articles into categories (Politics, Sports, Technology, Business, Entertainment, Health) 

✅ Analyze sentiment and emotional tone of news content 

✅ Identify patterns using TF-IDF, POS tagging, and syntax parsing 

✅ Generate insights for media monitoring and business intelligence 

This project was built using: 

spaCy and NLTK: the main libraries for text processing and NLP tasks 

scikit-learn: used to train and evaluate the classification models 

BBC News dataset: a public dataset of 2,225 news articles, used to train and test the system 

Google Colab: the development environment used to write and run the code 

This project follows a modular development approach. Instead of writing all the code in one large file, each function was built and tested separately in its own notebook. Once each function was tested and working correctly, it was exported into its own Python file inside the ‘newsbot/’ folder. Finally, all these functions were imported together into one main notebook, where the complete NewsBot system was built and tested with real news articles. 
