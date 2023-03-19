# python-web-flask-api-cockroachdb-single-node-without-ssl-to-multi-node-elasticsearch-client-pop

## Description
Reads a multi node cluster for data in `pop-demo` document.

Uses `pop` table then covverts it to json for
elasticsearch to use.

## Tech stack
- python
  - flask
    - elasticsearch
    - elasticsearch_dsl
    - sqlalchemy
- elasticsearch
- kibana
- cockroach

## Docker stack
- python
- elasticsearch
- kibana
- cockroachdb/cockroach:v19.2.4

## To run
`sudo ./install.sh -u`
- Get all beverages: http://localhost/pop
  - Schema id, name, and color
- Query with params: http://localhost/pop/id/<id>

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
