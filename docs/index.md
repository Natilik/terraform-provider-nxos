
---
layout: ""
page_title: "Provider: NXOS"
description: |-
  The NXOS provider provides resources to interact with a Cisco NX-OS device.
---

# NXOS Provider

The NXOS provider provides resources to interact with a Cisco NX-OS device.

## Example Usage

```terraform
provider "nxos" {
  username = "admin"
  password = "password"
  url      = "https://10.1.1.1"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- **insecure** (Boolean) Allow insecure HTTPS client. This can also be set as the NXOS_INSECURE environment variable. Defaults to `true`.
- **password** (String) Password for the NXOS device account. This can also be set as the NXOS_PASSWORD environment variable.
- **retries** (Number) Number of retries for REST API calls. This can also be set as the NXOS_RETRIES environment variable. Defaults to `3`.
- **url** (String) URL of the Cisco NXOS device. This can also be set as the NXOS_URL environment variable.
- **username** (String) Username for the NXOS device account. This can also be set as the NXOS_USERNAME environment variable.