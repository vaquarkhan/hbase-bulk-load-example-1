# HBase Bulk Load Example

This project should be a template for HBase Bulk Load Jobs using MapReduce.

It will _not_ work out of the box. One reason for this is that the business logic in the mapper is not implemented and the Driver doesn't set an InputFormat or any input data.

It is coded against the HBase 1.4.1 API.

*Note*: I have not tested the Secure Bulk Load 

## Template vs. Example

There are two sets of classes in here. One ending in `Template` will _not_ run out of the box. You'll need to customize it to your needs.

The other - ending in `Example` - should run. It treats all input files as text files.


- https://blog.cloudera.com/how-to-use-hbase-bulk-loading-and-why/
- https://medium.com/hashmapinc/3-steps-for-bulk-loading-1m-records-in-20-seconds-into-apache-phoenix-99b77ad87387
- https://github.com/vaquarkhan/HBase-Bulk-Load-Example
- https://github.com/zeyuanxy/spark-hbase-bulk-loading/blob/master/HBaseBulkload.scala
