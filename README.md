# hornet-queue


1. Download apache-artemis-2.16.0-bin.tar.gz from https://activemq.apache.org/components/artemis/download/
2. Extract to /opt folder
3. From /opt/apache-artemis-2.16.0/bin folder run "./artemis create" to create a brocker
4. /opt/apache-artemis-2.16.0/bin/brocker/bin$ "./artemis run" to start the server
5. Using example from http://www.mastertheboss.com/jboss-server/jboss-jms/introduction-to-activemq-artemis add all jar files from /opt/apache-artemis-2.16.0/lib to Eclipse project Build path as external jars
6. Execute an app
7. Check messages received http://localhost:8161/console/artemis/artemisQueues?nid=root-org.apache.activemq.artemis-0.0.0.0-addresses-DLQ-queues
8. Using examples from folder /opt/apache-artemis-2.16.0/examples/perf/jmeter run 1.jms_p2p_test.jmx
