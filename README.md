# Multiple Environment Docker Swarm Boilerplate

## Features

### Multiple environments and scalability

Goes with two subdomain-environments preconfigured, yet architecture poses no limitation on number of environments.

### Quick install

Quick and straightforward install: initial configuration takes a few minutes, no bash scripts involved. 

### NoOps

Everything is contained in Docker containers managed by Swarm. Doesn't need additional maintenance to run.

### Limited exposure

Minimum security concerns due to limited exposure of the application. Application components interact using private Docker network and all calls from the outside go through one Nginx reverse proxy.

### Registry

Provides private Docker registry with authentication.