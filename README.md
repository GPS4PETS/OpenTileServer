# OpenTileServer Docker

# Info
OpenTileServer for Portainer

# Install
just import the docker-compose.yml to portainer
    
# Add PBF File
open a shell to the tile container and run

    ./osm_load.sh 'https://download.geofabrik.de/europe/andorra-latest.osm.pbf'
    
Change the url for your destination
You can access PostgreSQL on localhost:5432 and Apache on localhost:8080



