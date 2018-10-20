
Running all the below Commands from Storm and Zookeeper Installation paths.

#Command for starting Zookeeper
bin/zkServer.sh start

#Command for starting Nimbus
./storm nimbus

#Command for starting Supervisor
./storm supervisor

#Command for Starting Storm UI
./storm ui

# Command for Submitting to Storm Cluster
./storm jar ~/Downloads/example1-0.0.1-SNAPSHOT.jar TopologyMain

#Command for Killing Topology with topology name.
./storm kill Yahoo-Finanace-Topology
