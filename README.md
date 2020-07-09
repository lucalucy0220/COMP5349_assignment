# Environment Setup
Follow week 10 tutorial to start a new EMR cluster. To run the application smoothly without encountering exceeding memory errors, it is advisible to use m5.2xlarge for both Master and two Core nodes in Step2 Hardware Configuration. 
If you have configured the software correctly by following Week 10 tutorial to include four components (Hadoop, Spark, Livy, Tenserflow), you can just get started with the notebook from here. 

# Running the Application
In order to run our application, it is required to download MNLI data from https://gluebenchmark.com/tasks. In this assignment, we will only be using five datasets: `dev_matched.tsv`, `dev_mismatched.tsv`, `test_matched.tev`, `test_mismatched.tsv`, and `training.tev`. Depends on where you store the MNLI datasets, you might want to change the file path near the beginning of the notebook. Before start running the cells, set the kernel to `Pyspark` if it is currently not. 