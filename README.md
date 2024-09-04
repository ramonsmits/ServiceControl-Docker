# ServiceControl docker deployment

Create a ServiceControl docker example deployment and adds a basis authentication Traefik reverse proxy.

> [!NOTE]
> This reverse proxy configuration is not secure, [setup Traefik to use HTTPS](https://doc.traefik.io/traefik/https/overview/).

Access ServicePulse via <http://servicepulse.localhost>

This docker compose uses the following ServiceControl container images:

- https://hub.docker.com/r/particular/servicepulse
- https://hub.docker.com/r/particular/servicecontrol
- https://hub.docker.com/r/particular/servicecontrol-monitoring
- https://hub.docker.com/r/particular/servicecontrol-audit
- https://hub.docker.com/r/particular/servicecontrol-ravendb
