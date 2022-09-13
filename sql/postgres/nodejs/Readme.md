```bash
docker run -d \
	--name postgresdb \
    -e POSTGRES_USER=admin \
	-e POSTGRES_PASSWORD=mysecretpassword \
	-v PGDATA=/var/lib/postgresql/data/pgdata \
    -p 5432:5432 \
	postgres
```
