# ElasticSearch

three seperate projects included:
1. Finra location vs zip changes 
2. Checkblotter records vs check status 
3. Transaction charts money vs region 


design and implementation:
1. an backend job running to join 7 oracle tables, and port dataset into a flat table
2. and backend job running to clean data in this flat table
3. an elastic script running to import data into Elastic Search Engine
4. an configured Kibana dashboard present the chart
