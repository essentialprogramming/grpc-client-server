### 1. Introduction
[gRPC](https://www.grpc.io/) is a high performance, open source RPC framework initially developed by Google.
It helps in eliminating boilerplate code and helps in connecting polyglot services in and across
data centers.  
You can define how you want the information you’re serializing to be structured by defining protocol
buffer message types in ```.proto``` files. Each protocol buffer message is a small logical record of information, containing a series of name-value pairs.
### 2. Download project using git
Use the following command to clone this repository:

    git clone https://github.com/essentialprogramming/grpc-example.git

Then you can open the project in your favorite IDE.

### 3. Build and run the project  

Navigate to ```grpc-client``` folder at ```pom.xml``` level and execute the following command ```mvn clean install``` in order to:  
* build the project (generate executable uber-jar)
* generate the classes specified in ```.proto``` file

> run the newly generated jar with the following command(from the same path) :  
```java -jar target/grpc-0.0.1-SNAPSHOT-shaded.jar```

Navigate to ```grpc-server``` folder at ```pom.xml``` level and execute the following command ```mvn clean install``` in order to:  
* build the project (generate executable uber-jar)
* generate the classes specified in ```.proto``` file  
> run the newly generated jar with the following command(from the same path) :  
```java -jar target/grpc-0.0.1-SNAPSHOT-shaded.jar```



