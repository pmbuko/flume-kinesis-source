
# Amazon Kinesis Source and Sink for Apache Flume service
Originally comes from: https://github.com/pdeyhim/flume-kinesis
Fixes added, tested and works.

## To Do 
Copy prebuilt JAR found in *target* folder to *$FLUME_HOME/lib*

## Rerefence material
Refer to the configuration samples in *flume-kinesis/conf* on how to configure Amazon Kinesis Sink and Source

## Building the JAR (if rebuild needed)
1. git clone https://github.com/bkovari/flume-kinesis
2. cd flume-kinesis
3. mvn clean compile assembly:single

