iibench-mongodb
===============

iiBench Benchmark for MongoDB and TokuMX


Requirements
=====================

* Java 1.6 or 1.7
* Maven 3.0 or above

* This example assumes that you already have a MongoDB or TokuMX server running on the same machine as the iiBench client application.
* You can connect a different server or port by editing the run.simple.bash script. 


Running the benchmark
=====================

In the default configuration the benchmark will run for 1 hour, or 100 million inserts, whichever comes first.

```bash
git clone https://github.com/teoincontatto/iibench-mongodb.git
cd iibench-mongodb
```

*[optionally edit run.mvn.bash to modify the benchmark behavior]*

```bash
./run.mvn.bash <host> <port> <dbname>
```
