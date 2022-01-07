# simplejack
Large scale platform template. Creates a scalable container platform with lots of configured services included. 
- Domain Names
  - Manage DNS
- Portainer
- MongoDB 
- ? GlusterFs
- Run Front-Door LB

A CLI tool for the cluster's basic operations: 
- Create.
- Monitor - show Portainer url, elastic. 
- Destroy.

Validate Cluster
- Run acceptance tests -
  - Check that Cluster is up
  - Check Domain is mapped
  - Valid front page
  - Portainer Running
  - MongoDB scaling tests
  - ? GlusterFS tests
