# Agent Check: Macbattery

## Overview

This check monitors [Macbattery][1].

## Setup

### Installation

To install the Macbattery check on your host:


1. Install the [developer toolkit]
(https://docs.datadoghq.com/developers/integrations/python/)
 on any machine.

2. Run `ddev release build macbattery` to build the package.

3. [Download the Datadog Agent][2].

4. Upload the build artifact to any host with an Agent and
 run `datadog-agent integration install -w
 path/to/macbattery/dist/<ARTIFACT_NAME>.whl`.

### Configuration

!!! Add list of steps to set up this integration !!!

### Validation

!!! Add steps to validate integration is functioning as expected !!!

## Data Collected

### Metrics

Macbattery does not include any metrics.

### Service Checks

Macbattery does not include any service checks.

### Events

Macbattery does not include any events.

## Troubleshooting

Need help? Contact [Datadog support][3].

[1]: **LINK_TO_INTEGRATION_SITE**
[2]: https://app.datadoghq.com/account/settings/agent/latest
[3]: https://docs.datadoghq.com/agent/kubernetes/integrations/
[4]: https://github.com/DataDog/integrations-extras/blob/master/macbattery/datadog_checks/macbattery/data/conf.yaml.example
[5]: https://docs.datadoghq.com/agent/guide/agent-commands/#start-stop-and-restart-the-agent
[6]: https://docs.datadoghq.com/agent/guide/agent-commands/#agent-status-and-information
[7]: https://github.com/DataDog/integrations-extras/blob/master/macbattery/metadata.csv
[8]: https://github.com/DataDog/integrations-extras/blob/master/macbattery/assets/service_checks.json
[9]: https://docs.datadoghq.com/help/

