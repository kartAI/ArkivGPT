# ArkivGPT

This repo contains the files for the ArkivGPT project

## Installation
Clone this repository
``` bash
git clone git@github.com:kartAI/ArkivGPT.git
```

Update the project to get the required submodules
```bash
git submodule update --init --recursive
```

Change dir into the folder
``` bash
cd ArkivGPT
```

Run the docker compose files
``` bash
docker compose up
```

## Usage

The frontend should now be accessible at
[http://localhost](http://localhost)

Swagger API reference is accessible at
[http://localhost/swagger/index.html](http://localhost/swagger/index.html)

The API itself is accessible at
[http://localhost/api/](http://localhost/api/)


## System Structure

### Frontend
The web UI presented to the user

### Gateway
The API gateway system

### Processor
The processor talking to GeoDoc and the GPT
