# Demo webapp.

Start the demo server with custom contactpoints:

java -Ddemo.cassandra.contactPoint=localhost -Ddemo.cassandra.speculativeRetry=false -Ddemo.cassandra.allowRemoteHosts=false -Ddemo.cassandra.dc1=datacenter1 -Ddemo.cassandra.cl=LOCAL_QUORUM -jar ./target/demo-webapp-0.1.0.jar

java -Ddemo.cassandra.contactPoint=xxxxx -Ddemo.cassandra.speculativeRetry=false -Ddemo.cassandra.allowRemoteHosts=false -Ddemo.cassandra.dc1=dc1 -Ddemo.cassandra.dc2=dc2 -Ddemo.cassandra.cl=LOCAL_QUORUM -jar ./target/demo-webapp-0.1.0.jar

 