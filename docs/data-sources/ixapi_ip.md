---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "ixapi_ip Data Source - ix-api-terraform-provider"
subcategory: ""
description: |-
  Use the ixapi_ip data source to retrieve a single ip address, identified by ID
---

# ixapi_ip (Data Source)

Use the ixapi_ip data source to retrieve a single ip address, identified by ID



<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- `address` (String) IPv4 or IPv6 Address in the following format: - IPv4: [dot-decimal notation](https://en.wikipedia.org/wiki/Dot-decimal_notation) - IPv6: hexadecimal colon separated notation
- `consuming_account` (String) The `id` of the account consuming a service.  Used to be `owning_customer`.
- `external_ref` (String) Reference field, free to use for the API user. *(Sensitive Property)*
- `fqdn` (String)
- `managing_account` (String) The `id` of the account responsible for managing the service via the API. A manager can read and update the state of entities.
- `prefix_length` (Number) The CIDR ip prefix length
- `valid_not_after` (String)
- `valid_not_before` (String)
- `version` (Number) The version of the internet protocol.

### Read-Only

- `id` (String) The ID of this resource.

