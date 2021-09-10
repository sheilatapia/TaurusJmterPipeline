# TaurusJmterPipeline
Just to reuse the performanceTest pipeline after executions:
1. Install Taurus with pip
2. Install jenkins

## Run Taurus reading csv data without a jmx file
1. Verify csv path on yml file (taurusCompleteDemoWithout.yml)
2. On jenkinsConf.txt is located the pipeline script
3. Continue the job configuration, check "This execution must parametrized" / "Esta ejecución debe parametrizarse", and select the String Parameter.
4. Add concurrency and Script 
 ![imagen](https://user-images.githubusercontent.com/15008950/132875827-e0349faf-0f38-4fd1-8e2c-2d7c204092e7.png)
5. COnfigure jenkins to github project reading files if is local update the files path.



