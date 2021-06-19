From in class assignment

--SELECT  FROM `bads-customer-analytics.supermarket_class.supermarket` LIMIT 1000

CREATE MODEL`bads-customer-analytics.supermarket_class.clustering_2`
OPTIONS( MODEL_TYPE='KMEANS',NUM_CLUSTERS=5,KMEANS_INIT_METHOD='RANDOM') AS 
SELECT*FROM`bads-customer-analytics.supermarket_class.supermarket`
