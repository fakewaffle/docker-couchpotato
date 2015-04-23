# Docker CouchPotato

Docker image for [CouchPotato](https://couchpota.to/).

## Usage

```bash
docker run -d --name couchpotato \
    -p 5050:5050 \
    -v <your-config-folder>:/volumes/config/couchpotato \
    -v <your-data-folder>:/volumes/data \
    fakewaffle/couchpotato
```
