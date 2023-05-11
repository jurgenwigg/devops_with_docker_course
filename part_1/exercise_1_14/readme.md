# Commands used to run containers

> Short note: I'm running all docker stuff on VPS where I cannot simply assign various ports to containers so I used different ports assigned to subdomains.

For frontend:

```shell
docker run -d -p 80:8080 example_frontend
```

For backend:

```shell
docker run -d -p 8081:8081 example_backend
```
