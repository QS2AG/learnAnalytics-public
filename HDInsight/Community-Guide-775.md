# Perform Data Engineering on Microsoft Azure HDInsight Community Guide

## Administer and Provision HDInsight Clusters

1. **Deploy HDInsight Clusters**

	- [Connecting HDInsight Clusters with Virtual Networks](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-extend-hadoop-virtual-network)
	- [Using the Azure Portal to Create Customized HDInsight Clusters](https://blogs.msdn.microsoft.com/cindygross/2015/02/26/create-hdinsight-cluster-in-azure-portal/)
	- [Configure Domain-joined HDInsight clusters](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-domain-joined-configure)
	- [Customize Linux-based HDInsight clusters using Script Action](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-customize-cluster-linux)
	- [Azure Resource Manager Quickstart Templates](Customize Linux-based HDInsight clusters using Script Action)

2. **Deploy Secure Multi-User HDInsight Clusters**

	-  [Configure Domain-Joined HDInsight Clusters](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-domain-joined-configure)
	-  [Manage Domain-joined HDInsight clusters](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-domain-joined-manage)
	-  [Configure Hive policies in Domain-joined HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-domain-joined-run-hive)
	-  [Configure Domain-joined HDInsight clusters (Preview) using Azure PowerShell](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-domain-joined-configure-use-powershell)
	-  [Video - Configure AAD, and create HDInsight cluster](https://www.youtube.com/watch?v=D1_pGdTiicY)
	-  [Powershell Script for Domain-Joining HDInsight clusters](https://github.com/HDInsight/DomainJoinedHDInsight)
	-  [Video - Ignite 2016: Secure your Enterprise Hadoop environments on Azure](https://myignite.microsoft.com/videos/3102)

3. **Ingest data for batch and interactive processing**

	-  [Collecting and loading data into HDInsight](https://msdn.microsoft.com/en-us/library/dn749794.aspx)
	-  [Upload Data Using Command Line Tools](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-upload-data)
	-  [Using Sqoop with HDInsight through SSH](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-use-sqoop-mac-linux)
	-  [Use Oozie with Hadoop to Define and Run a Workflow](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-use-oozie-linux-mac)

4. **Configure HDInsight Clusters**

	-  [Customize HDInsight Clusters with Bootstrap Configurations](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-customize-cluster-bootstrap)
	-  [Monitoring HDInsight with Ambari API](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-monitor-use-ambari-api)
	-  [Manage HDInsight Using Azure CLI](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-administer-use-command-line)

5. **Manage and Debug HDInsight Jobs**

	-  [Manage Hadoop Clusters in HDInsight with the Ambari Portal](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-administer-use-portal-linux)
	-  [Manage HDInsight Clusters wtih the Ambari Web UI](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-manage-ambari)
	- [Video: Manage and Troubleshoot Infrastructure with Operations Management Suite](https://www.youtube.com/watch?v=n9RBu02fnmk)
	- [GitHub Scripts to Monitor HBase Clusters with OMS](https://github.com/Azure/hbase-utils)

## Implement Big Data Batch Processing Solutions

1. **Implement batch solutions with Hive and Apache Pig**

	- [Use Hive and Hive QL to Query Data in Azure](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-use-hive)
	- [Use Pig with HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-use-pig)
	- [Use Python with Hive and Pig in HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-python)
	- [HDInsight Tools for Visual Studio](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-visual-studio-tools-get-started)

2. **Design Batch ETL Solutions for Big Data with Spark**

	- [Spark SQL with Azure HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-apache-spark-jupyter-spark-sql)
	- [Integrating Hive and BI Tools with Spark](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-apache-spark-use-bi-tools)

3. **Operationalize Hadoop and Spark**

	- [Hive Activity in Azure Data Factory](https://docs.microsoft.com/en-us/azure/data-factory/data-factory-hive-activity)
	- [Pig Activity in Azure Data Factory](https://docs.microsoft.com/en-us/azure/data-factory/data-factory-pig-activity)
	- [MapReduce Activity for Azure Data Factory](https://docs.microsoft.com/en-us/azure/data-factory/data-factory-map-reduce)
	- [HDInsight Activities in Azure Data Factory](https://docs.microsoft.com/en-us/azure/data-factory/data-factory-data-transformation-activities)
	- [Spark Activities for Azure Data Factory](https://docs.microsoft.com/en-us/azure/data-factory/data-factory-spark)

## Implement Big Data Interactive Processing Solutions

1. **Implement interactive queries for big data with Spark SQL**

	- [Spark SQL with Azure HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-apache-spark-jupyter-spark-sql)
	- [Integrating Hive and BI Tools with Spark](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-apache-spark-use-bi-tools)
2. **Perform exploratory data analysis by using Spark SQL**
	- [Use Livy to Submit Spark Jobs Remotely](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-apache-spark-livy-rest-interface)
	- [Use Zeppelin Notebooks with HDInsight Spark Clusters](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-apache-spark-zeppelin-notebook)
	- [Use Jupyter Notbeooks with HDInsight Spark Clusters](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-apache-spark-jupyter-notebook-kernels)
	- [Adding External Packages to Jupyter Notebooks in HDInsight Spark Clusters](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-apache-spark-jupyter-notebook-use-external-packages)
3. **Implement interactive queries for big data with Interactive Hive**
	- [Use Interactive Hive in HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-use-interactive-hive)
4. **Perform interactive processing by using Apache Phoenix on HBase**
	- [Use Phoenix with HBase Clusters](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-hbase-phoenix-squirrel-linux)


## Implement Big Data Real-Time Processing Solutions

1. **Create Spark streaming applications using DStream API**

	- [Spark Streaming: Process events from Azure Event Hubs with Apache Spark cluster on HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-apache-spark-eventhub-streaming)
	- [Understanding and Using HDInsight Spark Streaming](https://blogs.msdn.microsoft.com/shanyu/2015/09/18/understanding-and-using-hdinsight-spark-streaming/)
	- [GitHub Repo for EventHubs Receiver for Spark Streaming](https://github.com/hdinsight/spark-eventhubs)

2. **Create Spark structured streaming applications**


3. **Develop big data real-time processing solutions with Apache Storm**

	- [Real-Time Analytics with Storm on HDInsight Clusters](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-storm-overview)
	- [Storm Starter Samples on HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-apache-storm-tutorial-get-started)
	- [Process Events from EventHubs with Storm on HDInsight with C# Topologies](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-storm-develop-csharp-event-hub-topology)
	- [Develop C# Topologies for Storm with HDInsight Tools for Visual Studio](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-storm-develop-csharp-visual-studio-topology)
	- [GitHub Repo for HDInsight Storm Examples](https://github.com/hdinsight/hdinsight-storm-examples)

4. **Build solutions that use Kafka**

	- [Use Kafka with Storm on HDInsight](https://azure.microsoft.com/en-us/resources/samples/hdinsight-storm-java-kafka/)
	- [Replicate Topics from One Kafka Cluster to Another Using MirrorMake](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-apache-kafka-mirroring)
	- [Use Spark with Kafka on HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-apache-spark-with-kafka)
	- [Video: Introducing Apache Kafka on Azure HDInsight](https://channel9.msdn.com/Shows/Azure-Friday/Introducing-Apache-Kafka-on-Azure-HDInsight)
	- [GitHub Repo for HDInsight Kafka Tools](https://github.com/hdinsight/hdinsight-kafka-tools)


5. **Build solutions that use HBase**

	- [Getting Started with HBase on HDInsight](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-hbase-tutorial-get-started)
	- [Adding HBase to Azure Virtual Network](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-hbase-provision-vnet)
	- [Configuring HBase Replication](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-hbase-replication)
	- [Real Time Processing with HBase](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-hbase-analyze-twitter-sentiment)