# Demo

The demo is based on https://github.com/open-telemetry/opentelemetry-dotnet-instrumentation/tree/main/examples/demo with further modifications,
* SQL Server receiver
* ASPNET core dashboards
* Logs -> Traces linking
* Collector/telemetry debug logging
* Necessary config changes for docker + M series macbook

A `docker compose up` will start everything and the grafana UI can be found at http://localhost:3000