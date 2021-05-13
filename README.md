# elasticsearch_guide
# A basic elasticsearch guide in python for beginners.

## I - Setting up the environment:

  #### Download the elasticsearch zip from https://www.elastic.co/downloads/elasticsearch
  #### Start the executable in your local machine (Make sure java is installed in your machine.)
  #### Hit http://localhost:9200, it should return output present in elastic.json(file has been uploaded)
  
  
## II - Connecting to the cluster created at 9200 port through jupyter/researchcollab
  
  #### !python -m pip install elasticsearch
  #### from elasticsearch import Elasticsearch
  #### es = Elasticsearch([{'host': 'localhost', 'port': 9200}])
  
## III - Congratulations, now you are free to explore elasticsearch!!!

  #### Refer to elastic_search.py for just the input commands.
  #### Refer to elastic_search.pynb for input as well as output. (My file downloaded from research collab)

