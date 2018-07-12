# Grafana Example

Automaticly deploys a fully functional copy of Grafana (currently at version 5.2.1) on Platform.sh.
using a MySQL backend and with a default InfluxDB datasource named "Default".

## Instructions

- Create a new project.
- Add your overrides to `conf/grafana.ini`
- Push this repository.
- Enjoy.

## Datasources

As per http://docs.grafana.org/administration/provisioning/#datasources, you can
add more external datasources in `conf/provisioning/datasources`.

If you wish to add more internal datasources, have a look at `build.sh` and `prestart.sh`

## Dashboards

The same applies to dashboards http://docs.grafana.org/administration/provisioning/#dashboards.
Add them to `conf/provisioning/dashboards`.
