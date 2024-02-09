# MisArch Docker Compose setup

## Prebuild containers
Uses prebuild containers (always current version)
```sh
docker compose up
```

## Building containers
Builds the containers using git submodules (versioned)
```sh
docker compose -f docker-compose-dev.yaml up
```

![It just works](https://i1.sndcdn.com/artworks-IU11mVyx0uGKwZOA-tnGSZw-t500x500.jpg)