# ansible-kibana

An Ansible role for installing [Kibana](http://www.elasticsearch.org/overview/kibana/).

## Role Variables

- `kibana_dir` - Directory to extract the Kibana archive (default: `/opt`)
- `kibana_host` - ElasticSearch host (default: `localhost`)
- `kibana_port` - ElasticSearch port (default: `80`)

## Example Playbook

See the [examples](./examples/) directory.
