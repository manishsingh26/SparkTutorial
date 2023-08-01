

Hadoop V/S Spark

| Parameter       | Hadoop                                                                                        | Spark                                                                                                         |
|-----------------|-----------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| Performance     | Hadoop is slower then spark. it writes data back to the disk and read again from to in-memory | Spark is faster then hadoop because spark do all the the computation in memory.                               |
| Batch/Streaming | Build for batch data processing.                                                              | Build for batch as well as streaming data processing.                                                         |
| Ease Of Use     | Difficult to write code in hadoop. Hive was built to make it easier                           | Easy to write and debug code. Interactive shell to develop and test. Spark provides high and low level API's. |
| Security        | Use kerberos Authentication and ACL autirization. (YARN)                                      | Don't have solid security. (HDFS->ACL)(YARN->kerberos).                                                       |
| Fault Talerance | It has block of data (128 MB) and replication factor to handle the failure.                   | Use DAG to provide fault talerance.                                                                           |