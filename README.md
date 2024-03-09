![StrangerLinks](https://github.com/TabeerMir/StrangerLinks/assets/134224968/28399939-b78a-49d0-bfbf-07e77f02b333)

This is my project to explore graphs, AI, data science and embeddings using data from the TV show [Stanger Things](https://en.wikipedia.org/wiki/Stranger_Things).

### Data

The orignial data was download from a [repo](https://github.com/jeffreylancaster/stranger-things) and is available in JSON format. 

### Neo4J

I used Neo4J as my graph DB of choice. The data loading cyphers are available under the data_load folder. 

### Node Similarity

One of the reasons for using Neo4J was the Graph Data Science library. I used the FastRP method to calculate embeddings for different characters, and then used K-Nearest Neighbours to find the most similar characters. Here's what the similarity graph look like for the character Eleven:

![](https://github.com/TabeerMir/StrangerLinks/assets/134224968/173d2f49-9d5d-4dbd-a365-cd60f7116b34)
