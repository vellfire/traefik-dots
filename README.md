# traefik-dots

My Traefik config, may be useful may not be but works on my machine™

I'll try to keep this updated, but refer to the [Traefik Proxy Docs](https://doc.traefik.io/traefik/)

Works with the Cloudflare resolver

To run, view comments in each file, change to your setup and run:

```
docker network create proxy
docker compose up -d
```

Tested running for multiple domains

\
\
\
Noteworthy documentation links:
- [Let's Encrypt](https://doc.traefik.io/traefik/https/acme/)
- [HTTP Middlewares](https://doc.traefik.io/traefik/middlewares/http/overview/)
- [Routers](https://doc.traefik.io/traefik/routing/routers/)
- [Services](https://doc.traefik.io/traefik/routing/services/)
- [File Providers](https://doc.traefik.io/traefik/providers/file/)
- [Docker Discovery](https://doc.traefik.io/traefik/providers/docker/) (Not used in my setup yet but still useful)
