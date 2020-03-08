# `ekg.base` - ModEco

Vanilla EKG module.  
It consists of ElasticSearch, Grafana and Kibana with optional exposure on port 80.
See `conteco.docs.overview` for more information on the ModEco ecosystem.

## Purpose

This module acts as a template.  
It can be used as is for POC purposes or cloned to create, with extensions if required, a functional module with a purpose.

## Structure

The module consists of the following service stacks:

 * `ekg` - ElasticSearch, Grafana and Kibana
 * `ext_elasticsearch` - Nginx to expose ElasticSearch on /elk/elasticsearch
 * `ui_grafana` - Nginx to expose Grafana on /elk/grafana
 * `ui_kibana` - Nginx to expose Kibana on /elk/kibana
