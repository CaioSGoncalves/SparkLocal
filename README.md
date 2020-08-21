# SparkLocal
Running Apache Spark and Apache Zeppelin locally for tests


./hdfs/transient/purchase
    Upsert case
    Update quantity of the product in purchase -> Keeps last product_quantity by timestamp

./hdfs/transient/transaction_logs
    Upsert solving with event-driven
    New transactions_logs arriving -> Consolidate all logs = balance
