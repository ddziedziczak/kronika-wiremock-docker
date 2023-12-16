# kronika-wiremock-docker
A docker container containing WireMock stub server for Kronik@ Ingest API orchestrated by docker-compose.

run `docker-compose up --build -d` to start

Default ports:
* HTTP: 8081
* HTTPS: 9443

## Setup an ssl certificates
You can find matching certificates at `sensitive-data-archive/sda-pipeline/dev_utils/certs/(server.jks and client.jks)` . Can be generated by `sh make_certs.sh`.
