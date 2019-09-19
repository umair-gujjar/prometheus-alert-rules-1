# prometheus-alert-rules

[![Build Status](https://travis-ci.org/bdossantos/prometheus-alert-rules.svg?branch=master)](https://travis-ci.org/bdossantos/prometheus-alert-rules)

![CKC LOL](assets/CKC_LOL.jpg)

> crédit [MedievalOps](https://twitter.com/MedievalOps/status/1174245832692047873?s=09)

## Usage

```yaml
# prometheus.yml

global:
  scrape_interval: 15s
  ...

rule_files:
  - 'alerts/*.yml'

scrape_configs:
  ...
```
