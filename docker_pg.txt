docker run -d --name anthroweb-pg -e POSTGRES_PASSWORD=anthroweb -e PGDATA=/var/lib/postgresql/data/pgdata -v /Users/mith/data/anthroweb_pg:/var/lib/postgresql/data -p 5432:5432 postgres
