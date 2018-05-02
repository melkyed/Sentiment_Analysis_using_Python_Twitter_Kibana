# Sentiment_Analysis_using_Python_Twitter_Kibana
Sentiment Analysis using Twitter, Python and Kibana Dashboard

This project pulls tweets from Twitter about the subject that the user enters and does sentiment analysis.

After doing sentiment analysis the code sends the analyzed data to Elastic Search Cluster.

There, this data is indexed under an index called "logstash-a" which pulls the data from the cluster and Visualizes it on the Kibana Dashboard.

