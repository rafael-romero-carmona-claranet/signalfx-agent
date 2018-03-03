<!--- GENERATED BY gomplate from scripts/docs/monitor-page.md.tmpl --->

# collectd/etcd

 Monitors an etcd key/value store.

See https://github.com/signalfx/integrations/tree/master/collectd-etcd and
https://github.com/signalfx/collectd-etcd


Monitor Type: `collectd/etcd`

[Monitor Source Code](https://github.com/signalfx/signalfx-agent/tree/master/internal/monitors/collectd/etcd)

**Accepts Endpoints**: **Yes**

**Multiple Instances Allowed**: Yes

## Configuration

| Config option | Required | Type | Description |
| --- | --- | --- | --- |
| `host` | **yes** | `string` |  |
| `port` | **yes** | `integer` |  |
| `name` | no | `string` |  |
| `clusterName` | no | `string` |  |
| `sslKeyFile` | no | `string` |  |
| `sslCertificate` | no | `string` |  |
| `sslCACerts` | no | `string` |  |
| `sslCertValidation` | no | `bool` |  (**default:** `true`) |
| `enhancedMetrics` | no | `bool` |  (**default:** `false`) |
| `metricsToInclude` | no | `list of string` |  |
| `metricsToExclude` | no | `list of string` |  |





