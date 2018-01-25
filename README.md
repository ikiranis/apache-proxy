## Create Docker Apache Proxy

* Edit docker/apache/apache-config.conf and add your apps
* Run **docker-compose up -d**



You can create your apache image instead of **apps4net/apache-proxy** with the command:

**docker build -t apache-proxy docker/apache**