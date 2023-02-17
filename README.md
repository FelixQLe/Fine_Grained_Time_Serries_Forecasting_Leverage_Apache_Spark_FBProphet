Intructions on this Repo
Heap size error run this command line before run jupyter notebook on command line
export PYSPARK_SUBMIT_ARGS=' --conf spark.sql.shuffle.partitions=700 --conf spark.default.parallelism=700 --driver-memory 30g --driver-cores 6 --executor-memory 30g --executor-cores 6 pyspark-shell'

ERROR PythonRunner: Python worker exited unexpectedly (crashed) java.net.SocketException: Connection reset
Try to run several times

# Fine_Grained_Time_Serries_Forecasting_Leverage_Apache_Spark_FBProphet

Retailers are utilizing the advancements in time series forecasting to generate more dependable demand forecasts. However, the main challenge lies in producing these forecasts promptly and with enough detail to enable precise adjustments to product inventories. By using Apache Spark and Facebook Prophet, numerous businesses facing such challenges are able to surpass the scalability and accuracy constraints of past solutions. 

In this Repo I emphasizes the significance of time series forecasting, provides visual representations of sample time series data, and presents a basic model to illustrate the use of Facebook Prophet. Once a single basic model has been constructed, A more complex combining Facebook Prophet with the capabilities of Spark allows allows hundreds of models to be trained at once, resulting in accurate forecasts for each individual product-store combination, an unprecedented level of granularity.

### Why is improving the speed and accuracy of time series analyses to forecast the demand for their products and services important?

The success of retailers depends on improving the speed and accuracy of time series analyses to forecast the demand for their products and services. If too much product is stocked in a store, it can strain shelf and storeroom space, and result in expired products. This can also tie up financial resources in inventory, preventing retailers from taking advantage of new opportunities or shifting consumer patterns. On the other hand, if too little product is stocked, customers may not find what they need, leading to lost sales and customer frustration. These forecast errors can immediately cause a loss of revenue for the retailer, and over time may drive customers to competitors. Therefore, it is critical for retailers to accurately forecast demand to ensure that the appropriate amount of product is stocked in each store at the right time.

Copyright: This notebook followed the instruction in big-book-of-machine-learning-use-cases-2nd-edition - published by DataBricks websites, by authors Bilal Obeidat, Bryan Smith and Brenner Heintz. 
