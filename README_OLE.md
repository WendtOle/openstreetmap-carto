-g --unsafe-perm "https://git@github.com/kosmtik/kosmtik.git"

# How to start Kosmtik

1. Import Data

- `PG_WORK_MEM=128MB PG_MAINTENANCE_WORK_MEM=2GB OSM2PGSQL_CACHE=2048 OSM2PGSQL_NUMPROC=4 OSM2PGSQL_DATAFILE=<path/to/data/file.osm.pbf docker-compose up import`

- on master it was added that the large shapefiles can be cached

2. Start Kosmtik container

- `docker-compose up kosmtik`
