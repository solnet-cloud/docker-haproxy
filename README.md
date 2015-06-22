# docker-haproxy
HAProxy is a free, very fast and reliable solution offering high availability, load balancing, and proxying for TCP and HTTP-based applications.

More details can be found at http://www.haproxy.org

This Docker build builds on top of a Ubuntu image to provide an instance that runs HAProxy.

It is envisioned that you will bind mount the configuration file read only from the host so will want to expose any listen ports configured to the host.

It is expected that you would you a tool such as Puppet for orchestration of the configuration file.

