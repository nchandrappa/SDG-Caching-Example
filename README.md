# SDG-Caching-Example
This project provides a sample implementation of spring caching abstraction using Pivotal Gemfire.

### STEP 1: Start a Gemfire Cluster

For Convenience, scripts are provided to Start a Gemfire Cluster. Navigate to **Grid** folder and update the environment variables in gf.config file.

Start the locator by running **startLocator.sh** and Start the cache servers by running **startServer.sh**


### STEP 2: Run the Demo

```
mvn spring-boot:run
```
