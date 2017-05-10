# 26.6
1 Static vs dynamic partitioning
Classification of partitioning
• Static partitioning
• Dynamic Partitioning
When to use static partitioning
• Static partitioning needs to be applied when we know data (supposed to be inserted)
belongs to which partition.
When to use dynamic partitioning
• In static partitioning, every partitioning needs to be backed with individual hive
statement which is not feasible for large number of partitions as it will require writing of
lot of hive statements.
• In that scenario dynamic partitioning is suggested as we can create as many number of
partitions with single hive statement.
