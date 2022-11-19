# Search-Engine

### Back End:

Employs different ranking algorithms such as the word based statistical  TFIDF, token based matching Jaccard Index, sequence based Ratcliff-Obershelp algorithms to return relevant documents based on a query. 


Users can upload documents from their computer to the website and select a specific algorithm or choose to run the best algorithm selector. 


Utilizes the Levenshtein Distance algorithm which widens the scope of a query to account for minor errors in spelling and grammar. Creates multiple queries, similar to the one entered by the user. 


An Artificial Neural Network, trained using the Gradient Descent and the doc2vec similarity algorithm, determines the ideal ranking algorithm based on the length of the query, reducing search latency by 60%.

### Front End:

Created a Flask backend for processing requests and queries to the ranking algorithm and a RESTful API, which serves data in a JSON format.


Accompanied by a basic React.js and Tailwind CSS page with a text box for entering the query and an endpoint to upload documents to the website. The most relevant documents are then displayed in a list format.


**Libraries Used: NLTK, spaCy, NumPy, pandas**