## Description

A tutorial describing various techniques for interacting with a graph database,
running graph algorithms, plotting graphs.
We use Natural Language Processing framework to build graph node embeddings.


## Installation
 
#### Database setup
Download and install neo4j desktop: [download](https://neo4j.com/download/)
 
Follow neo4j installation guide on the download page.
 
Once neo4j is installed and configured start its web browser and
create example dataset by running `:play got`. 
Follow the instructions in the neo4j browser.
 
#### Development environment setup
Install the requirements by running:
  
`pip install -r requirements.txt`
 
 
Export neo4j endpoint url with the appropriate username and password:
 
`export NEO4J_URI='http://neo4j:neo@localhost:7474/db/data'`
 
Start notebook:
 
`jupyter notebook`

