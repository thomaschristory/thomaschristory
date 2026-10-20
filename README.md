# Hi, I'm Thomas 👋

I build tools for network and infrastructure automation: NetBox plugins, command-line tools that generate themselves from OpenAPI specs, and MCP servers that let AI agents work safely with network platforms.

[LinkedIn](https://www.linkedin.com/in/thomaschristory/)

## NetBox plugins

- [netbox-ipam-treeview-plugin](https://github.com/thomaschristory/netbox-ipam-treeview-plugin): DDI-style collapsible tree view for IPAM prefixes.
- [netbox-opentelemetry-plugin](https://github.com/thomaschristory/netbox-opentelemetry-plugin): export logs, audit records, traces and metrics over OTLP ([docs](https://thomaschristory.github.io/netbox-opentelemetry-plugin/)).
- [netbox-permissions-matrix-plugin](https://github.com/thomaschristory/netbox-permissions-matrix-plugin): view and edit object permissions as a matrix of object types and groups ([docs](https://thomaschristory.github.io/netbox-permissions-matrix-plugin/)).
- [netbox-windows-dhcp-plugin](https://github.com/thomaschristory/netbox-windows-dhcp-plugin): read and write Windows DHCP Server data over WinRM ([docs](https://thomaschristory.github.io/netbox-windows-dhcp-plugin/)).
- [netbox-proxy-plugin](https://github.com/thomaschristory/netbox-proxy-plugin): manage HTTP proxy configurations.

## Agent-friendly CLIs

- [netbox-super-cli](https://github.com/thomaschristory/netbox-super-cli): dynamic NetBox CLI generated from the live OpenAPI schema ([docs](https://thomaschristory.github.io/netbox-super-cli/)).
- [panorama-super-cli](https://github.com/thomaschristory/panorama-super-cli): find, dedup and safely merge Palo Alto Panorama objects. Dry-run by default ([docs](https://thomaschristory.github.io/panorama-super-cli/)).
- [vcf-super-cli](https://github.com/thomaschristory/vcf-super-cli): VMware Cloud Foundation 9 (vSphere + NSX) from a dynamically generated command tree ([docs](https://thomaschristory.github.io/vcf-super-cli/)).

## MCP servers

- [catalyst-sdwan-super-mcp](https://github.com/thomaschristory/catalyst-sdwan-super-mcp): Cisco Catalyst SD-WAN Manager ([docs](https://thomaschristory.github.io/catalyst-sdwan-super-mcp/)).
- [catalyst-center-super-mcp](https://github.com/thomaschristory/catalyst-center-super-mcp): Cisco Catalyst Center ([docs](https://thomaschristory.github.io/catalyst-center-super-mcp/)).
- [thousand-eyes-super-mcp](https://github.com/thomaschristory/thousand-eyes-super-mcp): Cisco ThousandEyes ([docs](https://thomaschristory.github.io/thousand-eyes-super-mcp/)).
- [netbox-mcp-server-extended](https://github.com/thomaschristory/netbox-mcp-server-extended): write-enabled fork of the NetBox MCP server. Every write defaults to dry run.

## Infrastructure as code

- [terraform-provider-windowsddi](https://github.com/thomaschristory/terraform-provider-windowsddi): manage Windows Server DHCP (IPv4) and DNS from Terraform, over SSH or WinRM ([docs](https://github.com/thomaschristory/terraform-provider-windowsddi/tree/main/docs)).

## Small utilities

- [snmpv3-utils](https://github.com/thomaschristory/snmpv3-utils): SNMPv3 CLI testing utility.
- [netmiko-rapidfire](https://github.com/thomaschristory/netmiko-rapidfire): run IOS commands quickly with Netmiko.
