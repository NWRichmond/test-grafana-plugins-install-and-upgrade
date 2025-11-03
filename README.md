# Grafana 12.x Plugin Testing

This repository contains a Grafana 12.2.0 instance connected to a Prometheus data source, with no plugins preinstalled. This is a test environment to verify that the plugin installation & upgrade process works as expected.

## Running the project

```bash
docker compose up -d
```

## Accessing Grafana

Visit [localhost:3050](http://localhost:3050) to access Grafana 12.2.0.
Use the following credentials to login in order to manage plugin installations:

- Username: admin
- Password: admin

## Installing Plugins from the Plugins Catalog

Under the **Administration** menu, go to **Plugins and data** and click on the **Plugins** card. From there, you can search for Grafana plugins and install them.
