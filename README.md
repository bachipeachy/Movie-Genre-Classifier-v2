# Movie-Genre-Classifier-v2
Completed version if multi label classifier for movie genre
## Dataset
You will need CMU Movie Summary Corpus open dataset. You can download the dataset directly from 
http://www.cs.cmu.edu/~ark/personas/data/MovieSummaries.tar.gz
This dataset contains multiple files, but you need only two of them:
movie.metadata.tsv: Metadata for 81,741 movies, extracted from the November 4, 2012 dump of Freebase. The movie genre tags are available in this file
plot_summaries.txt: Plot summaries of 42,306 movies extracted from the November 2, 2012 dump of English-language Wikipedia. Each line contains the Wikipedia movie ID (which indexes into movie.metadata.tsv) followed by the plot summary
## Running the script
First run data jupyter notebook that creates a clean, merged dataset stored at ./data/
Then run the model notebook that reloads the dataset created by the data notebook
The model was run for 5 epochs that started to overfit at 2.5 epoch point.
