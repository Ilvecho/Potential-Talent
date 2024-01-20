This project helps talent sourcing and managing company to automate the process of matching ideal candidates for technology companies.
● Poposed several approaches to rank individuals based on their LinkedIn job title and location similarity with the ideal candidate’s information.
● After the Exploratory Data Analysis, preprocessed the job titles with tokenization, stop words removal, acronym expansion and lemmization, implemented with the nltk python library;
● Ranked the strings based on Fuzzy Matching implemented with TheFuzz python library; 
● Ranked the strings based on Bag Of Words, N-grams and TF-IDF similarities using sklearn python library;
● Further processed the job titles based on POS tags and semantic dependencies, then ranked the strings based on the pre-trained word2vec similarity implemented by SpaCy python library.

Curious for more? Check out the Notebook in the repo
