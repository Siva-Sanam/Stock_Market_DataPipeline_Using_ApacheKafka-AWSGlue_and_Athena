## Stock_Market_DataPipeline_Using_ApacheKafka-AWSGlue_and_Athena
This data engineering project focuses on real-time stock market data processing. Apache Kafka is used to ingest live stock price feeds from various sources. The streaming data is then stored in Amazon S3, where AWS Glue processes and transforms it into a structured format. AWS Glue Catalog organizes the data for efficient querying, and Amazon Athena enables analysts to perform ad-hoc queries and derive insights, such as price trends, volatility analysis, and trading volume patterns. The pipeline ensures scalable, real-time analytics for informed decision-making.

## Architecture 
<img src="ProjectArchitecture.jpg">

## Technology Used
- Programming Language - Python
- Apache Kafka
- Amazon Web Service (AWS)
1. S3 (Simple Storage Service)
2. Athena
3. Glue Crawler
4. Glue Catalog
5. EC2



## Dataset Used
You can use any dataset, we are mainly interested in operation side of Data Engineering (building data pipeline) 

Here is the dataset used in the video - https://github.com/darshilparmar/stock-market-kafka-data-engineering-project/blob/main/indexProcessed.csv









