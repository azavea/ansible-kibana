# ansible-kibana

An Ansible role for installing [Kibana](https://www.elastic.co/products/kibana).

## Role Variables

- `kibana_version` - Kibana version to install
- `kibana_short_version` - Kibana short version
- `kibana_bind_host` - Kibana address to bind to (default: `127.0.0.1`)
- `kibana_port` - Kibana port (default: `5601`)
- `kibana_elasticsearch_endpoint` - ElasticSearch endpoint (default: `http://localhost:9200`)
- `kibana_index` - Name of Kibana index in ElasticSearch (default: `.kibana`)

## Example Playbook

See the [examples](./examples/) directory.
