# Docker setup and notes

1. Don't run docker from the build button, processes get stuck when you click stop (maybe itll get fixed)
2. Instead run `docker-compose up`
3. `docker ps` will show running processes, which will include the open port, for example 0.0.0.0:32775->80/tcp
4. You can then do something like `curl http://localhost:32775/api/values`
