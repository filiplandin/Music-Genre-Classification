# Music-Genre-Classification
Music Genre Classification on the GTZAN Dataset using spectrograms and a Resnet18 architecture.

Download the data here:
https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification

Content
* genres original - A collection of 10 genres with 100 audio files each, all having a length of 30 seconds (the famous GTZAN dataset, the MNIST of sounds)
* images original - A visual representation for each audio file. One way to classify data is through neural networks. Because NNs usually take in some sort of image representation, the audio files were converted to Mel Spectrograms to make this possible.
* 2 CSV files - Containing features of the audio files. One file has for each song (30 seconds long) a mean and variance computed over multiple features that can be extracted from an audio file. The other file has the same structure, but the songs were split before into 3 seconds audio files (this way increasing 10 times the amount of data we fuel into our classification models).
