# DEPRECATED - USE OFFICIAL REPOS

Nexus 3: https://hub.docker.com/r/sonatype/nexus3/


Nexus 2: https://hub.docker.com/r/sonatype/nexus/

---

[Docker](http://www.docker.com/) container for [Sonatype Nexus](http://www.sonatype.org/nexus)

Docker: `docker pull conceptnotfound/sonatype-nexus`

Port: 8081

Volume: /nexus

Environment variables:

* CONTEXT_PATH (default /nexus)

Usage
------

To run nexus:
```bash
docker run -d -p 8081:8081 --name nexus conceptnotfound/sonatype-nexus
```
