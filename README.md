
# wildfly 

derived from jboss/wildfly:14.0.0.Final

exposes /deployments folder

# usage

e.g.

docker pull anothersoftwaredevelopmentblog/docker-wildfly

docker run -p 8080:8080 -p 9990:9990 -v ~/deployments:/deployments --name wf14 anothersoftwaredevelopmentblog/docker-wildfly

# admin console

use user admin password test

