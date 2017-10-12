
# wildfly 10.1 final

derived from jboss/wildfly:10.1.0.Final

exposes /deployments folder

# usage

e.g.

docker pull anothersoftwaredevelopmentblog/docker-wildfly

docker run -p 8080:8080 -v ~/deployments:/deployments --name wf10 anothersoftwaredevelopmentblog/docker-wildfly

or

start in debug mode

docker run -p 8080:8080 -p 8787:8787 -v ~/deployments:/deployments --name wf10 anothersoftwaredevelopmentblog/docker-wildfly /opt/jboss/wildfly/bin/standalone.sh -b "0.0.0.0" --debug


