#Batch Processing:->
* Historical Card Transactions Dataset has to be loaded from Excel Sheet to Local System, from there to HDFS.Further this data will be moved to RDBMS using Sqoop Export Utility and to Hive HBase table.
* Member Score & Member Details data have been loaded to Hive Tables.
* Card Lookup table is generated with Card Transactions and Member Data.

#Streaming Processing:->
* Data arrives via Kafka Topics and post validating in Kafka based on Business rules ,marked as Fraud/Genuine and posted to card_transactions and card_lookup tables
