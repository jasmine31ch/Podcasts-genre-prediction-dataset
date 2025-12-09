# Podcasts-genre-prediction-dataset
We constructed our dataset using Spotify’s genre-specific Top 30 rankings. For each of the six target genres, we selected five channels by prioritizing shows labeled exclusively with that genre, and when necessary, those listing the genre as their primary category. From these, three channels per genre were assigned to the training set, while one channel each was reserved for validation and testing. 

For the training dataset (3 shows), each show has 6 episodes. (180 snippets)

For the test/validation dataset (1 show each dataset), each has 4 episodes. (40 snippets)

Each snippet has 40s. The snippet is selected randomly from the episodes and they don’t overlap with each other.

