- Demonstrates being unable to connect to a mysql service within a single docker-compose cluster.
- `docker-compose up` manages to run, but unable to `prisma deploy` because it still attempts to connect to the `prisma` database
