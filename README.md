
# wildfly 10.1 final

derived from jboss/wildfly:10.1.0.Final

exposes /deployments folder

# usage

e.g.

docker pull anothersoftwaredevelopmentblog/docker-wildfly

docker run -p 8080:8080 -v ~/deployments:/deployments --name wf10 anothersoftwaredevelopmentblog/docker-wildfly


