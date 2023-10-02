Example based on https://informatievlaanderen.github.io/VSDS-Linked-Data-Interactions/ldio/examples/ex2-scrape-api 


## Getting started

Start the LDES Server and have the MongoDB storage initialized:

```shell
docker compose up
```


Start the LDI worker:

```shell
docker compose --profile delay-started up
```
