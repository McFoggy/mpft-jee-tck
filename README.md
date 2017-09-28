# Eclipse Microprofile Fault Tolerant TCK runner for JEE platforms
 
## Run TCK

- run all the tck on default platform: 
```
mvn integration-test
```

- filter TCK tests using failsafe: 
```
mvn integration-test -Dit.test=RetryTest
```
