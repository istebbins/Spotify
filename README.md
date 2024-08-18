# Spotify Pre-Wrapped & "Nostalgia Engine"
### Data Science with My Personal Spotify Data:

* Used my personal Spotify data to create top song and top artist data visualizations before the end of year wrapped data was produced to the app.

* Scraped data from Lyric Website Genius using [lyricsgenius](https://lyricsgenius.readthedocs.io/en/master/) (Python client for Genius API).

* Utilized [Gensims](https://radimrehurek.com/gensim/models/doc2vec.html) Doc2Vec model to calculate lyric embeddings based on Quoc Le and Tomas Mikolov's: [“Distributed Representations of Sentences and Documents"](https://arxiv.org/pdf/1405.4053v2.pdf) Paragraph Vector model.

* Identified top similar songs to an input based on the Doc2Vec models lyrical word embeddings. Gave successful suggestions from both the same artist and other artists.

* One potential use case of a model like this would be for streaming platforms to give "nostalgic" recommendations similar to the song you are currently listening to. I.E. songs that are in the individual users' listening history that they have heard before and are similar, but may not have listened to recently.
