# Music Genre Classification

For a long time, experts have been attempting to comprehend sound and what distinguishes one music from another. Sound visualisation. What distinguishes one tone from another? We are going to deep dive in this project.

The data:

 - genres original - A collection of 10 genres with 100 audio files each, all having a length of 30 seconds (the famous GTZAN dataset, the MNIST of sounds)

 - images original - A visual representation for each audio file. One way to classify data is through neural networks. Because NNs (like CNN, what we will be using today) usually take in some sort of image representation, the audio files were converted to Mel Spectrograms to make this possible (we'll be talking about this more in depth later)

 - 2 CSV files - Containing features of the audio files. One file has for each song (30 seconds long) a mean and variance computed over multiple features that can be extracted from an audio file (more in depth later). The other file has the same structure, but the songs were split before into 3 seconds audio files (this way increasing 10 times the amount of data we fuel into our classification models). With data, more is always better.
 
We want to understand what is an Audio file. What features we can visualize on this kind of data.
Classification of genres on a 3 second CSV file (we will try multiple models and find which one has better accuracy)
A recommender system: given a song, give me top Y songs most similar.

Credits and Acknowledgements:
Andrada Olteanu
