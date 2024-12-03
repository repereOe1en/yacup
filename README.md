# yacup
The problem was stated as follows: for each of the tracks in test data 100 other tracks with the highest chance of being covers of the initial one should be found. Train data is divided into "cliques": sets of tracks, that are versions of each other. To be able to process all of the data at the same time in colab data should've been processed (data.ipynb).  
I calculated accuracy on validation as follows: for each track from validation set of 100 closest were found, then I found the intersection between real clique and 100 closest and divided the magnitude of a resulting set by minimum of a hundred and the lengh of the clique. The highest accuracy I was able to obtain was 0.3.  
Link to data: https://disk.yandex.ru/d/RjMQIusMf6_L4w
