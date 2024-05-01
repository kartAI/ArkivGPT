# ArkivGPT
This repo contains the files for the ArkivGPT project. The project is to create summaries of construction cases from archives. The project uses docker containers to run the different parts of the system. The system consists of a frontend, gateway, processor and OCR system. The frontend is the web UI presented to the user. The gateway is the API gateway system. The processor is the system talking to OCR, GeoDoc and the GPT. The OCR is the OCR system.

## Prerequisites
- Docker
- Docker Compose
- GeoDoc clientid and key
- OpenAI GPT key and endpoint

## Configuration
Create a GeoDoc.clientid, GeoDoc.key, GPT.key and GPT.endpoint file in the root of the project. The GeoDoc files should contain the clientid and key for the GeoDoc API. The GPT files should contain the key and endpoint for the GPT API.


## Installation
Clone this repository
``` bash
git clone git@github.com:kartAI/ArkivGPT.git
```

Change dir into the folder
``` bash
cd ArkivGPT
```

Update the project to get the required submodules
```bash
git submodule update --init --recursive
```

Run the docker compose files
``` bash
docker compose up --build
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
The processor talking to OCR, GeoDoc and the GPT

### OCR
The OCR system