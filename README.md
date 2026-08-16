<div align="center">

<!-- title -->

<!--lint ignore no-dead-urls-->

# Awesome NetBox with stars

<!-- subtitle -->

A curated list of awesome resources related to NetBox!

<!-- image -->

<a href="" target="_blank" rel="noopener noreferrer">
  <img src="images/netbox_logo.svg" width="300" alt="NetBox logo" />
</a>

<!-- description -->

[NetBox](https://github.com/netbox-community/netbox) ⭐ 21,317 | 🐛 212 | 🌐 Python | 📅 2026-08-15 is an infrastructure resource modeling (IRM) tool providing the ideal <strong>"source of truth"</strong> to power network automation.

</div>

<!-- TOC -->

## Contents

* [Featured (new releases)](#featured-new-releases)
* [Official Docs & Quickstarts](#official-docs--quickstarts)
* [Plugins](#plugins)
* [Ansible](#ansible)
* [Deployment](#deployment)
* [Utilities](#utilities)
* [Synchronization](#synchronization)
* [SDKs](#sdks)
* [Terraform](#terraform)
* [Resources](#resources)
  * [Educational](#educational)
  * [Blogs](#blogs)
  * [Community](#community)
  * [Videos](#videos)

<!-- CONTENT -->

## Featured (new releases)

<!--lint ignore double-link-->

* [Zero to Hero Course](https://zerotohero.netbox.dev/) - A short course designed to take new NetBox users from ‘Zero to Hero’.

## Official Docs & Quickstarts

<!--lint disable double-link-->

* 📖 [NetBox Documentation](https://netboxlabs.com/docs/) - Official NetBox Documentation.
* 🔧 [NetBox Demo Instance](https://demo.netbox.dev/) - Demo instance of NetBox (restarted daily).
* 📖 [NetBox Plugin Tutorial](https://github.com/netbox-community/netbox-plugin-tutorial) ⭐ 137 | 🐛 4 | 📅 2026-03-18 - NetBox Plugin Development Tutorial.

<!--lint enable double-link-->

## Plugins

* [netboxlabs.com/netbox-plugins/](https://netboxlabs.com/netbox-plugins/) - NetBox Community Plugins

## Ansible

* [netbox-community/ansible\_modules](https://github.com/netbox-community/ansible_modules) ⭐ 395 | 🐛 245 | 🌐 Python | 📅 2026-08-04 - NetBox modules for Ansible using Ansible Collections.
* [lae/ansible-role-netbox](https://github.com/lae/ansible-role-netbox) ⭐ 224 | 🐛 18 | 🌐 Python | 📅 2026-06-17 - Cross-platform Ansible role for deploying NetBox.
* [osism/ansible-collection-services](https://github.com/osism/ansible-collection-services) ⭐ 35 | 🐛 12 | 🌐 Python | 📅 2026-08-15 - Ansible collection with service roles.

## Deployment

* [netbox-community/netbox-docker](https://github.com/netbox-community/netbox-docker) ⭐ 2,728 | 🐛 14 | 🌐 Python | 📅 2026-08-13 - Docker Image of NetBox.
* [netbox-community/netbox-chart](https://github.com/netbox-community/netbox-chart) ⭐ 353 | 🐛 5 | 🌐 Mustache | 📅 2026-08-15 - Helm Chart for NetBox.

## Utilities

* [netbox-community/devicetype-library](https://github.com/netbox-community/devicetype-library) ⭐ 1,584 | 🐛 28 | 🌐 Python | 📅 2026-08-14 - A collection of community-sourced DeviceType definitions.
* [Solvik/netbox-agent](https://github.com/Solvik/netbox-agent) ⭐ 394 | 🐛 59 | 🌐 Python | 📅 2026-08-13 - Project aims to create hardware automatically into Netbox based on standard tools (dmidecode, lldpd, parsing /sys/, etc).
* [minitriga/Netbox-Device-Type-Library-Import](https://github.com/minitriga/Netbox-Device-Type-Library-Import) ⭐ 386 | 🐛 55 | 🌐 Python | 📅 2025-03-11 - The library is intended to be your friend and help you import all the device-types defined within the the NetBox Device Type Library Repository.
* [lopes/netbox-scanner](https://github.com/lopes/netbox-scanner) ⭐ 205 | 🐛 17 | 🌐 Python | 📅 2026-06-05 - A scanner util for NetBox.
* [den-it/ntmap](https://github.com/den-it/ntmap) ⭐ 165 | 🐛 14 | 🌐 JavaScript | 📅 2023-01-10 - Network topology map using Netbox as a data source.
* [netreplica/graphite](https://github.com/netreplica/graphite?source=awesome-netbox) ⭐ 89 | 🐛 25 | 🌐 JavaScript | 📅 2026-08-01 - Standalone topology visualizer Netreplica `graphite`.
* [NCCloud/netbox-resources-operator](https://github.com/NCCloud/netbox-resources-operator) ⭐ 11 | 🐛 1 | 🌐 Python | 📅 2026-06-25 - A Kubernetes operator to manage NetBox resources.
* [kosimovsky/nbcli](https://github.com/kosimovsky/nbcli) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2022-06-29 - CLI tool for Netbox API.
* [netbox2monit](https://codeberg.org/thomas-mc-work/netbox2monit) - Creates a [configuration file](https://mmonit.com/monit/documentation/monit.html) for [monit](https://mmonit.com/monit/) based on the machines defined in a Netbox instance.

## Synchronization

* [bb-Ricardo/netbox-sync](https://github.com/bb-Ricardo/netbox-sync) ⭐ 408 | 🐛 54 | 🌐 Python | 📅 2026-05-16 - Sync objects from VMware or redfish sources to NetBox.
* [TheNetworkGuy/netbox-zabbix-sync](https://github.com/TheNetworkGuy/netbox-zabbix-sync) ⭐ 230 | 🐛 36 | 🌐 Python | 📅 2026-07-20 - Python script to syncronise Netbox devices to Zabbix.
* [scaleway/netbox2netshot](https://github.com/scaleway/netbox2netshot) ⭐ 47 | 🐛 2 | 🌐 Rust | 📅 2025-01-30 - Inventory synchronization tool between Netbox and Netshot.
* [sol1/icingaweb2-module-netbox](https://github.com/sol1/icingaweb2-module-netbox) ⭐ 36 | 🐛 1 | 🌐 PHP | 📅 2026-07-23 - Icingaweb2 module to syncronise Netbox objects Icinga Director.

## SDKs

* [netbox-community/pynetbox](https://github.com/netbox-community/pynetbox) ⭐ 682 | 🐛 4 | 🌐 Python | 📅 2026-07-21 - Python API client library.
* [netbox-community/go-netbox](https://github.com/netbox-community/go-netbox) ⭐ 225 | 🐛 10 | 🌐 Go | 📅 2025-05-09 - Go API client library.
* [benclaussen/NetboxPS](https://github.com/benclaussen/NetboxPS) ⚠️ Archived - Powershell module for Netbox.
* [ninech/netbox-client-ruby](https://github.com/ninech/netbox-client-ruby) ⭐ 27 | 🐛 10 | 🌐 Ruby | 📅 2026-07-08 - Ruby API client library (NetBox v2).
* [timeforplanb123/anac](https://github.com/timeforplanb123/anac) ⭐ 15 | 🐛 1 | 🌐 Python | 📅 2022-06-19 - Python Async NetBox API Client, based on httpx and pydantic.
* [hexa2k9/netbox-php](https://github.com/hexa2k9/netbox-php) ⭐ 3 | 🐛 0 | 🌐 PHP | 📅 2023-02-15 - PHP API client library.
* [KashinYaS/NetBoxPowerShell](https://github.com/KashinYaS/NetBoxPowerShell) ⭐ 1 | 🐛 0 | 🌐 PowerShell | 📅 2022-07-14 - PowerShell wrapper to NetBox API.

## Terraform

* [e-breuninger/terraform-provider-netbox](https://github.com/e-breuninger/terraform-provider-netbox) ⭐ 291 | 🐛 145 | 🌐 Go | 📅 2026-08-04 - Terraform provider to interact with Netbox.
* [smutel/terraform-provider-netbox](https://github.com/smutel/terraform-provider-netbox) ⭐ 67 | 🐛 2 | 🌐 Go | 📅 2026-07-29 - Terraform provider for Netbox.

## Resources

### Educational

<!--lint disable double-link-->

* [NetBox Plugin Tutorial](https://github.com/netbox-community/netbox-plugin-tutorial) ⭐ 137 | 🐛 4 | 📅 2026-03-18 - NetBox Plugin Development Tutorial.
* [Zero to Hero Course](https://zerotohero.netbox.dev/) - A short course designed to take new NetBox users from ‘Zero to Hero’.

<!--lint enable double-link-->

### Blogs

* [Integrating Okta SSO with NetBox](https://www.oasys.net/posts/okta-sso-with-netbox/) - Instructions for configuring NetBox and Okta for native SSO authentication.
* [Netbox Active Directory/LDAP Integration](https://www.thierolf.org/blog/2021/netbox-active-directoryldap-integration/) - How to setup Netbox with Active Directory as backend for users and groups.
* [NetBox NAPALM automation with bastion host](https://www.oasys.net/posts/netbox-napalm-automation-with-bastion-host/) - Configuring the NAPALM integration to use a SSH proxy.
* [NetBox: How to run it on your Synology](https://kevenaar.name/netbox-how-to-run-it-on-your-synology/) - Installing Netbox on your Synology NAS.

### Community

* [GitHub Discussions](https://github.com/netbox-community/netbox/discussions) ⭐ 21,317 | 🐛 212 | 🌐 Python | 📅 2026-08-15 - Discussion forum hosted by GitHub; ideal for Q\&A and other structured discussions.
* [Slack](https://netdev.chat/) - Real-time chat hosted by the NetDev Community; best for unstructured discussion or just hanging out.

### Videos

* [Itential](https://www.youtube.com/watch?v=1DTlDF05LH4) - Integrating NetBox as a Source of Truth for Network Automation.
* [Viatto NetBox](https://www.youtube.com/c/KeepingITSimple/search?query=netbox) - Full NetBox course videos.
* [NS1 Labs](https://www.youtube.com/c/NS1Labs/search?query=netbox) - Community calls, Zero-to-Hero, NetBox feature video from the creator of NetBox.

<!-- END CONTENT -->

## Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-16._
