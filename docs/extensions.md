# Extensions
Extensions provide backend functionality for Interlock.  These can be just
about anything (metrics, autostart, autoscale, etc).  Interlock currently
ships with support for two load balancing extensions.  Interlock also uses
external extension containers instead of bundling in a single image.  This
keeps Interlock lightweight as well as providing the ability to specify your
own container image if desired.  By default, it is recommended to use official
Docker images from the Docker Hub for each extension.

# Load Balancing
The following load balancing extensions are supported:

- [HAProxy](./extensions/haproxy.md)
- [Nginx](./extensions/nginx.md)

# Metrics
- [Beacon](./extensions/beacon.md)
