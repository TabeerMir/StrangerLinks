![StrangerLinks](https://github.com/TabeerMir/StrangerLinks/assets/134224968/28399939-b78a-49d0-bfbf-07e77f02b333)

This is my project to explore graphs, AI, data science and embeddings using data from the TV show [Stanger Things](https://en.wikipedia.org/wiki/Stranger_Things).

### Data

The orignial data was downloaded from a [repo](https://github.com/jeffreylancaster/stranger-things) and is available in JSON format. 

### Neo4J

I used Neo4J as my graph DB of choice. The data loading cyphers are available under the data_load folder. 

### Node Similarity

One of the reasons for using Neo4J was the Graph Data Science library. I used the FastRP method to calculate embeddings for different characters, and then used K-Nearest Neighbours to find the most similar characters. Here's what the similarity graph look like for the character Eleven (The edges show the similarity score when clicked - it turns out Eleven is most similar to Mike, which is accurate based on the data I have such as common scenes):

![](https://github.com/TabeerMir/StrangerLinks/assets/134224968/173d2f49-9d5d-4dbd-a365-cd60f7116b34)

### Website

The code for the website is included in this repo. It only has a few pages:

![](https://github.com/TabeerMir/StrangerLinks/assets/134224968/24538c5e-ce0f-443d-94bf-9c2c5974d9d4)
![](https://github.com/TabeerMir/StrangerLinks/assets/134224968/dee6c0bc-52eb-483f-a9eb-7dc639b6e6a8")

### NeoDash for Visualisations

I used NeoDash for visualisations, though the cypher queries used are also inlcuded in this repo. Some examples are below:

![](https://github.com/TabeerMir/StrangerLinks/assets/134224968/9e99b6ef-2a51-43d6-8276-11ae64fdfc24")
![](https://github.com/TabeerMir/StrangerLinks/assets/134224968/b92973d7-5075-4a44-8576-d708558829b3")
![](https://github.com/TabeerMir/StrangerLinks/assets/134224968/889e5e76-0d5b-451b-91cb-df16fda8eb54")

### Generative AI for Season Synopsis

The data only included episode summaries, so I used GPT to come up with a season synopsis using these episode summaries:

![](https://github.com/TabeerMir/StrangerLinks/assets/134224968/4a9e5140-a118-4984-996d-7c72f51845ae)


