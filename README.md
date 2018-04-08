# Map-Reduce
This repo is to execute a Map-Reduce in Windows (not using HDFS) from the local IDE(InteliJ). This will help you to quickly test your 
Map-Reduce logic so that you can then move to a stand alone cluster or a full cluster to run the jar or what ever.
The way I do it is as follows.
1. First set up a local Map-Reduce job and test your assumptions
Once you are satisfied with your results - use Cloudera - CDH to run this in a stand alone cluster
You can then add multiple nodes and test the same and if needed finetune the Map-Reduce job
