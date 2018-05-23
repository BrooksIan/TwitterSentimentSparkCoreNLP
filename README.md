# TwitterSentimentSparkCoreNLP

 ## Spark Core NLP on Tweets

**Language**: Scala
**Requirements**: 
- [HDP 2.6.X]
- Spark 2.x

**Author**: Ian Brooks
**Follow** [LinkedIn - Ian Brooks PhD] (https://www.linkedin.com/in/ianrbrooksphd/)

Instructions:
1. Please follow this [tutorial](https://community.hortonworks.com/articles/1282/sample-hdfnifi-flow-to-push-tweets-into-solrbanana.html) to build the Solr collection 'tweets'

2. Upload the notebook (JSON File) to Apache Zeppelin

3. Match the version of Spark with the SolrSpark Connector. The version list is included in [here](https://github.com/lucidworks/spark-solr)

4. Review Spark Core NLP's [API](https://github.com/databricks/spark-corenlp) which creates Spark wrapper to the [Stanford CoreNLP](https://stanfordnlp.github.io/CoreNLP/) library 

5. In the Stanford Core NLP download found [here,] (http://nlp.stanford.edu/software/stanford-corenlp-full-2018-02-27.zip) find the stanford-corelop-*-models.jar. the In Zeppelin Spark Interpreters configurations, include the following artifact: /tmp/stanford-corenlp-full-2018-02-27/stanford-corenlp-3.9.1-models.jar	
