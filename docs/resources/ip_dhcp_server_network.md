---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "routeros_ip_dhcp_server_network Resource - terraform-provider-routeros"
subcategory: "IP"
description: |-
  
---

# routeros_ip_dhcp_server_network (Resource)


```terraform
resource "routeros_ip_dhcp_server_network" "dhcp_server_network" {
  address    = "10.0.0.0/24"
  gateway    = "10.0.0.1"
  dns_server = "1.1.1.1"
}
```


<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- `address` (String)
- `boot_file_name` (String)
- `caps_manager` (String)
- `dhcp_option` (String)
- `dhcp_option_set` (String)
- `dns_none` (Boolean)
- `dns_server` (String)
- `domain` (String)
- `gateway` (String)
- `netmask` (Number)
- `next_server` (String)
- `ntp_server` (String)
- `wins_server` (String)

### Read-Only

- `id` (String) The ID of this resource.

