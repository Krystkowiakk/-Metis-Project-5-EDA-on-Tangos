# Argentinian Tango Lyrics: Sentiment & Topics NLP
###### METIS Data Science and Machine Learning Bootcamp 2022 by Krystian Krystkowiak
###### project/month(5/7) focus: NATURAL LANGUAGE PROCESSING
#### Code - cleanning [GitHub](https://github.com/Krystkowiakk/Argentinian-Tango-Lyrics-Sentiment-Topics-NLP/blob/main/1.%20Krystkowiak_Krystian_Project_5_Argentinian%20Tango%20Lyrics%20Sentiment%20%26%20Topics%20NLP%20-%20cleaning.ipynb)
#### Code - NLP [GitHub](https://github.com/Krystkowiakk/Argentinian-Tango-Lyrics-Sentiment-Topics-NLP/blob/main/2.%20Krystkowiak_Krystian_Project_5_Argentinian%20Tango%20Lyrics%20Sentiment%20%26%20Topics%20NLP%20-%20NLP.ipynb)
#### Presentation [GitHub](https://github.com/Krystkowiakk/Heart-Disease-Patients-Classification/blob/main/Project%20Presentation/Krystkowiak_Krystian_Project_4_Classification_on-Heart_Disease_Indicators.pdf)
#### Dashboard [Tableau](https://public.tableau.com/views/tango/Dashboard1)
#### <a id="raw-url" href="[https://raw.githubusercontent.com/github-username/project/master/filename](https://github.com/Krystkowiakk/Argentinian-Tango-Lyrics-Sentiment-Topics-NLP/blob/main/lda_vis.html)">Download FILE</a>

ABSTRACT

- Processed 2,400 tango lyrics in Spanish using natural language processing (NLP) techniques, including CountVectorizer and Latent Semantic Analysis, to perform sentiment analysis and distinguish main topics. Tested different models (LSA, NMF, LDA) and used K Means clustering to extract and visualise topical features in an interactive Tableau dashboard.
- The goal of this project was to perform an analysis of topics used by various Golden Age tango poets, in order to help modern orchestras imitate them. The exploration is also useful for other tango proffesionals (music collectors, dj's, dance teachers) and private enthusiasts. The project used a dataset of lyrics from www.el-recodo.com, which was a powerful source of information about Argentinian Tango music for both professionals and hobbyists. After initial cleaning, the Spanish texts were pre-processed to distinguish the topics. The project tested and tuned multiple models, and ultimately decided to use Latent Dirichlet Allocation (LDA). Exploratory Data Analysis was performed and an interactive dashboard was built using Tableau to visualize and communicate the results.

DESIGN

The Golden Age of Tango Music was 1935-1955, when many of the finest poets from Argentina and Uruguay wrote Tango lyrics. The form quickly became one of the richest in popular culture.  As the lyrics improved in quality, great singers also emerged and dominated the Tango scene, particularly with the advent of radio and sound film. However, towards the end of the 60s, Tango lost popularity to rock'n roll and pop music.

In 2022, Tango as a dance is back! We can observe a rise of young orchestras in the last 15 years, many of whom are creating new songs to keep Tango music alive. Analysis of topics used by Golden Age poets can help modern orchestras imitate them and keep the spirit of particular orchestras or periods. Such exploration is also useful for tango specialists and enthusiasts.

DATA

I used a dataset from www.el-recodo.com, which is a powerful source of information about Argentinian Tango music for both professionals and hobbyists. The dataset was scraped and initially cleaned by gefero, who shared it on GitHub: https://github.com/gefero/tango_scrap.

I focused on the period 1920-1960 to include all songs considered as traditional tango. The dataset includes tangos, valses, and milongas, all styles created by the same orchestras and played under similar circumstances.

It contains over 2400 songs in Spanish with an average of 120 words. My focus was on the lyrics (subject of NLP), author, orchestra, singer, and year.

ALGORITHMS

- Filtering and cleaning data, removing capital letters and punctuation, extracting features.
- nltk and spacy were used for removing stopwords and Spanish lemmatization.
- Different models were tested for Dimensionality Reduction and Clustering (LSA, NMF, LDA)
- K-Means clustering and silhouette coefficient suggested 3 topics as optimal.
- PyPI module was used for Spanish sentiment analysis.
- Final EDA was performed on the results of Latent Dirichlet Allocation (LDA). 3 topics were distinguished:

Topic 1: LIFE CHOICES
give, say, life, man, today, old, poor, power, always, time

Topic 2: DRAMATIC LOVE
love, heart, life, pain, power, soul, cry, return, eye, night  

Topic 3: BARRIO MUSIC
tango, love, heart, night, singing, old, neighborhood, flower, song, beautiful

TOOLS

- Python Pandas, Numpy, and re for data processing.
- Python packages for natural language processing (NLTK, spaCy, gensim, scikit-learn, PyPI, pyLDAvis etc.)
- Plotly and WordCloud for data visualization.
- Tableau and Keynote for creating interactive visualizations and presentations.

COMMUNICATION

5-minute live video presentation with visualization and interactive Tableau dashboard at: https://public.tableau.com/views/tango/Dashboard1

![Argentinian Tango Lyrics: Sentiment & Topics NLP](files/cover.jpg)


