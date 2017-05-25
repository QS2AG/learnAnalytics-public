---
layout: default
---

# Skills measured in Exam 70-773: [Analyzing Big Data with Microsoft R Server](https://www.microsoft.com/en-us/learning/exam-70-773.aspx)

This exam measures your ability to accomplish the technical tasks listed below. You can watch video tutorials about the [variety of question types](https://www.microsoft.com/en-us/learning/certification-exams.aspx?types=true) on Microsoft exams. The majority of the resources we point to here are in one of the following locations:

 - [Microsoft R on MSDN](https://msdn.microsoft.com/en-us/microsoft-r) 
 - [Analyzing big data with Microsoft R (edX)](https://www.edx.org/course/analyzing-big-data-microsoft-r-server-microsoft-dat213x)
 - [Analyzing Big Data with Microsoft R](https://jonsan21.gitbooks.io/analyzing-big-data-with-microsoft-r/content/)
 - [Scalable Machine Learning and Data Science with Microsoft R Server and Spark](https://bookdown.org/alizaidi/mrs-spark-ml/).

**Please note that the questions may test on, but will not be limited to, the topics described in the bulleted text. Also note that this guide is not an official curriculum but rather should be viewed as a community resource.**

Do you have feedback about the relevance of the skills measured on this exam? Please [send Microsoft your comments](mailto:mslcd@microsoft.com?subject=Skills%20measured%20feedback). All feedback will be reviewed and incorporated as appropriate while still maintaining the validity and reliability of the certification process. Note that Microsoft will not respond directly to your feedback. We appreciate your input in ensuring the quality of the Microsoft Certification program.

If you have concerns about specific questions on this exam, please submit an [exam challenge](https://www.microsoft.com/en-us/learning/certification-exam-policies.aspx?challenge=true).

If you have other questions or feedback about Microsoft Certification exams or about the certification program, registration, or promotions, please contact your [Regional Service Center](https://www.microsoft.com/en-us/learning/help.aspx).

### [Read and explore big data](https://www.microsoft.com/en-us/learning/exam-70-773.aspx#syllabus-1)

- Read data with R Server
  
  - Read supported data file formats, such as [text files, SAS, and SPSS](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-data-import); convert data to XDF format; identify [trade-offs between XDF and flat text files](https://smott.gitbooks.io/introduction-to-microsoft-r-server/content/12c-xdf-vs-csv.html); read data through [Open Database Connectivity (ODBC) data sources](https://msdn.microsoft.com/en-us/microsoft-r/scaler-odbc); read in files from [ther file systems](https://msdn.microsoft.com/en-us/microsoft-r/microsoft-r-get-started-node); use an [internal data frame as a data source](https://msdn.microsoft.com/en-us/microsoft-r/scaler/rximport); process data from sources that cannot be read natively by R Server.

- Summarize data
  
  - Compute [cross-tabulations](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-crosstabs) and [univariate statistics](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-data-summaries), choose when to use [`rxCrossTabs` versus `rxCube`](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-crosstabs), integrate with open source technologies by using packages such as [`dplyrXdf`](https://github.com/RevolutionAnalytics/dplyrXdf), use [`group_by` functionality](https://github.com/RevolutionAnalytics/dplyrXdf/blob/master/vignettes/dplyrXdf_user.Rmd), create [complex formulas](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-transform-functions) to perform multiple tasks in one pass through the data, extract quantiles by using [`rxQuantile`](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-data-transform)

- Visualize data
  
  - [Visualize in-memory data with base plotting functions and ggplot2](https://smott.gitbooks.io/introduction-to-microsoft-r-server/content/21d-examining-outliers.html); create [custom visualizations with `rxSummary` and `rxCube`](https://smott.gitbooks.io/introduction-to-microsoft-r-server/content/22a-reordering-neighborhoods.html); visualize data with [`rxHistogram`](https://msdn.microsoft.com/en-us/microsoft-r/scaler-getting-started) and [`rxLinePlot`](https://msdn.microsoft.com/en-us/microsoft-r/scaler-distributed-computing), including faceted plots

### [Process big data](https://www.microsoft.com/en-us/learning/exam-70-773.aspx#syllabus-2)

- Process data with  `rxDataStep`

  - [Subset rows of data](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-data-transform); modify and create columns by using the [`Transforms`](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-data-transform) argument; choose when to use [on-the-fly transformations versus in-data transform](https://smott.gitbooks.io/introduction-to-microsoft-r-server/content/13b-a-simple-transformation.html); handle missing values through [filtering](https://smott.gitbooks.io/introduction-to-microsoft-r-server/content/21g-filtering-by-manhattan.html) or [replacement](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-data-transform); generate [a data frame or an XDF file](https://msdn.microsoft.com/en-us/microsoft-r/scaler/rxdatastep); [process dates](https://msdn.microsoft.com/en-us/microsoft-r/scaler/rximport) (`POSIXct`, `POSIXlt`)

- Perform complex transforms that use transform functions

  - Define a [transform function](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-transform-functions); reshape data by using a transform function; use open source packages, [such as lubridate](https://smott.gitbooks.io/introduction-to-microsoft-r-server/content/13c-complex-transformations.html); pass in values by [using `transformFunc` and `transformObjects`](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-transform-functions); use [internal `.rx` variables and functions](https://msdn.microsoft.com/en-us/microsoft-r/scaler/rxtransform) for tasks, including cross-chunk communication

- Manage data sets

  - [Sort data](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-data-transform) in various orders, such as ascending and descending; use  `rxSort ` deduplication to [remove duplicate values](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-data-transform); merge data sources using [`rxMerge`](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-data-transform) and its merge options and types; identify when alternatives to `rxSort` and `rxMerge` should be used

- Process text using 

packages
  
  - Create features using MicrosoftML functions, such as [`featurizeText`](https://github.com/Azure/mr4ds/blob/master/Student-Resources/rmarkdown/6-MML-for-NLP.rmd);  create indicator variables and arrays using MicrosoftML functions, such as `categorical` and `categoricalHash`; perform feature selection using MicrosoftML functions

### [Build predictive models with `RevoScaleR`](https://www.microsoft.com/en-us/learning/exam-70-773.aspx#syllabus-3)

- Estimate linear models
  -Use [`rxLinMod`](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-linear-model), [`rxGlm`](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-generalized-linear-model) and [`rxLogit`](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-logistic-regression) to estimate linear models; set the family for a generalized linear model by using functions such as [`rxTweedie`](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-generalized-linear-model); process data on the fly by using the appropriate arguments and functions, such as the [`F` function](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-data-summaries) and [the `transforms` argument](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-data-summaries); weight observations through [frequency or probability weights](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-linear-model); choose between [different types of automatic variable selections](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-linear-model), such as greedy searches, repeated scoring, and byproduct of training; identify the impact of missing values during automatic variable selection

- Build and use partitioning models
  
  - Use [`rxDTree`](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-decision-tree), [`rxDForest`](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-decision-forest), and [`rxBTrees`](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-boosting) to build partitioning models; [adjust the weighting of false positives and misses by using loss](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-decision-forest); select [parameters that affect bias and variance, such as pruning, learning rate, and tree depth](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-decision-tree); use `as.rpart` [to interact with open source ecosystems](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-pmml)

- Generate predictions and residuals
  
  - Use [`rxPredict`](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-linear-model) to generate predictions; perform parallel scoring using  `rxExec` ; generate different types of predictions, such as link and response scores for GLM, response, prob, and vote for `rxDForest`; generate different types of residuals, such as Usual, Pearson, and DBM

- Evaluate models and tuning parameters
  
  - [Summarize estimated models](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-linear-model); run arbitrary code out of process, such as parallel parameter tuning by using [`rxExec`](https://msdn.microsoft.com/en-us/microsoft-r/scaler-distributed-computing); [evaluate tree models by using `RevoTreeView` and `rxVarImpPlot`](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-decision-tree); [calculate model evaluation metrics](https://msdn.microsoft.com/en-us/microsoft-r/scaler-user-guide-logistic-regression) by using built-in functions; calculate model [evaluation metrics and visualizations by using custom code](https://smott.gitbooks.io/introduction-to-microsoft-r-server/content/32g-judging-predictive-performance.html), such as mean absolute percentage error and precision recall curves

- Create additional models using MicrosoftML packages
  
  - Build and use a One-Class Support Vector Machine, build and use [linear and logistic regressions that use L1 and L2 regularization](https://github.com/Azure/mr4ds/blob/master/Student-Resources/rmarkdown/6-MML-for-NLP.rmd), build and use [a decision tree by using `FastTree`](https://github.com/Azure/mr4ds/blob/master/Student-Resources/rmarkdown/6-MML-for-NLP.rmd), use `FastTree` as a recommender with ranking loss (NDCG), build and use a simple three-layer feed-forward [neural network](https://github.com/Azure/mr4ds/blob/master/Student-Resources/rmarkdown/6-MML-for-NLP.rmd)

### [Use R Server in different environments](https://www.microsoft.com/en-us/learning/exam-70-773.aspx#syllabus-4)

- Use different compute contexts to run R Server effectively
  
  - [Change the compute context](https://msdn.microsoft.com/en-us/microsoft-r/scaler-distributed-computing) using `rxHadoopMR`,`rxSpark`,`rxLocalseq`, and `rxLocalParallel`; identify [which compute context to use for different tasks](https://msdn.microsoft.com/en-us/microsoft-r/scaler-distributed-computing); use [different data source objects, depending on the context](https://msdn.microsoft.com/en-us/microsoft-r/scaler-distributed-computing) (`RxOdbcData` and `RxTextData`); identify and use [appropriate data sources for different data sources and compute contexts (HDFS and SQL Server)](https://msdn.microsoft.com/en-us/microsoft-r/scaler-distributed-computing); [debug processes across different compute contexts](https://msdn.microsoft.com/en-us/microsoft-r/scaler-distributed-computing); identify use cases for [`RevoPemaR`](https://msdn.microsoft.com/en-us/microsoft-r/pemar-getting-started)

- Optimize tasks by using local compute contexts
  
  - Identify and execute tasks that can be run only in the local compute context; identify tasks that are more efficient to run in the local compute context; choose between [`rxLocalseq` and `rxLocalParallel`](https://msdn.microsoft.com/en-us/microsoft-r/scaler-distributed-computing), [profile across different compute contexts](https://msdn.microsoft.com/en-us/microsoft-r/scaler-distributed-computing)

- Perform in-database analytics by using SQL Server
  
  - Choose [when to perform in-database versus out-of-database computations](https://smott.gitbooks.io/introduction-to-microsoft-r-server/content/41c-deploying-to-sql-server-demo.html); identify [limitations of in-database computations](https://smott.gitbooks.io/introduction-to-microsoft-r-server/content/41c-deploying-to-sql-server-demo.html); use in-database versus out-of-database compute contexts appropriately; use [stored procedures for data processing steps](https://msdn.microsoft.com/en-us/library/mt683483.aspx); [serialize objects and write back to binary fields in a table](https://smott.gitbooks.io/introduction-to-microsoft-r-server/content/41c-deploying-to-sql-server-demo.html), [write to SQL tables](https://msdn.microsoft.com/en-us/library/mt634286.aspx), [configure R to optimize SQL Server (`chunksize`, `numtasks`, and `computecontext`)](https://msdn.microsoft.com/en-us/library/mt723571.aspx), [effectively communicate performance properties to SQL administrators and architects](https://msdn.microsoft.com/en-us/library/mt723574.aspx) (SQL Server Profiler)

- Implement analysis workflows in the Hadoop ecosystem and Spark
  
  - Use appropriate [R Server functions in Spark](https://msdn.microsoft.com/en-us/microsoft-r/scaler-spark-getting-started); [integrate with Hive, Pig, and Hadoop MapReduce](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-r-server-get-started#accessing-data-in-hive-and-parquet); [integrate with the Spark ecosystem of tools, such as SparklyR and SparkR](https://bookdown.org/alizaidi/mrs-spark-ml/apache-spark-1.html#mllib); [profile and tune across different compute contexts](https://msdn.microsoft.com/en-us/microsoft-r/scaler-distributed-computing); use [`doRSR` for parallelizing code that was written using the open source `foreach` package](https://msdn.microsoft.com/en-us/microsoft-r/scaler-distributed-computing)

- Deploy predictive models to SQL Server and Azure Machine Learning
  
  - [Deploy predictive models to SQL Server as a stored procedure](https://msdn.microsoft.com/en-us/library/mt634292.aspx), deploy an arbitrary function to Azure Machine Learning by using the [AzureML R package](https://cran.r-project.org/web/packages/AzureML/vignettes/getting_started.html), identify [when to use DeployR](https://msdn.microsoft.com/en-us/microsoft-r/deployr-about)
