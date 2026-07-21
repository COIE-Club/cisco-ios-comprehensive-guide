<div align="center">

# 🌐 Cisco IOS Comprehensive Guide

**A practical, community-built cookbook for Cisco IOS — from your first `enable` to a fully redundant enterprise network.**

*cisco • networking • routing • switching • ccna • ccnp • eve-ng • packet-tracer*

<p>
<img src="https://img.shields.io/github/stars/COIE-Club/cisco-ios-comprehensive-guide?style=for-the-badge&color=ffd33d&labelColor=1e2327" alt="Stars">
<img src="https://img.shields.io/github/forks/COIE-Club/cisco-ios-comprehensive-guide?style=for-the-badge&color=58a6ff&labelColor=1e2327" alt="Forks">
<img src="https://img.shields.io/github/license/COIE-Club/cisco-ios-comprehensive-guide?style=for-the-badge&color=8250df&labelColor=1e2327" alt="License">
<img src="https://img.shields.io/badge/PRs-welcome-2ea44f?style=for-the-badge&labelColor=1e2327" alt="PRs Welcome">
</p>

</div>

---

## Why this repo exists

Most Cisco material picks one of two lanes: dense exam theory, or a raw config dump with zero context. This guide tries to sit in the middle. Every topic explains **what the technology does, why an engineer would actually reach for it, and how to configure and verify it yourself** — with a real topology behind every example, not just a wall of commands.

It spans the full range from CCNA 200-301 fundamentals to CCNP ENCOR 350-401 enterprise design, but topics are ordered by **difficulty**, not by exam blueprint. You start with CLI navigation and hostnames; by the end you're standing up DMVPN hubs and full enterprise campus networks.

> Because topics build on each other, working through them in order will teach you more than jumping straight to the advanced stuff.

## 🚧 Where the project stands right now

The rulebook is done: the folder structure, the contribution process, and the topic template are all locked in. What's missing is **you** — the actual topics. If you know your way around IOS and want a piece of a growing reference guide with your name on it, now is the best time to claim one.

## Get oriented

<p align="center">
<a href="structure.md"><img src="https://img.shields.io/badge/Roadmap-See_all_20_stages-2f81f7?style=for-the-badge&labelColor=1e2327" alt="Roadmap"></a>
<a href="_template.md"><img src="https://img.shields.io/badge/Template-Write_a_topic-f2a900?style=for-the-badge&labelColor=1e2327" alt="Template"></a>
<a href="CONTRIBUTING.md"><img src="https://img.shields.io/badge/Contribute-Start_here-2ea44f?style=for-the-badge&labelColor=1e2327" alt="Contribute"></a>
</p>
<p align="center">
<a href="SECURITY.md"><img src="https://img.shields.io/badge/Security-Report_an_issue-d1242f?style=for-the-badge&labelColor=1e2327" alt="Security"></a>
<a href="CODE_OF_CONDUCT.md"><img src="https://img.shields.io/badge/Code_of_Conduct-Community_rules-8250df?style=for-the-badge&labelColor=1e2327" alt="Code of Conduct"></a>
<a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-6e7781?style=for-the-badge&labelColor=1e2327" alt="License"></a>
</p>

## How it's organized

Every topic lives in its own self-contained folder — guide, topology image, and lab file together, nothing loose in the root:

```
01-Device-Basics/
├── 01-CLI-Navigation/
│   ├── README.md
│   └── topology.png
├── 02-Hostname/
│   ├── README.md
│   ├── topology.png
│   └── initial_configs.txt
```

## 🗺️ The 20 stages

| # | Stage | # | Stage |
|---|---|---|---|
| 01 | [Device Basics](https://github.com/COIE-Club/cisco-ios-comprehensive-guide/tree/main/Cisco%20IOS%20Comprehensive%20Guide/01-Device-Basics) | 11 | [First Hop & Multicast](structure.md#11-first-hop-and-multicast) |
| 02 | [Interface Configuration](structure.md#02-interface-configuration) | 12 | [QoS](structure.md#12-qos) |
| 03 | [Layer 2 Switching](structure.md#03-layer-2-switching) | 13 | [Security](structure.md#13-security) |
| 04 | [Spanning Tree](structure.md#04-spanning-tree) | 14 | [Infrastructure Services](structure.md#14-infrastructure-services) |
| 05 | [IP Routing](structure.md#05-ip-routing) | 15 | [Virtualization](structure.md#15-virtualization) |
| 06 | [Dynamic Routing](structure.md#06-dynamic-routing) | 16 | [IPv6](structure.md#16-ipv6) |
| 07 | [Route Control](structure.md#07-route-control) | 17 | [WAN](structure.md#17-wan) |
| 08 | [NAT Services](structure.md#08-nat-services) | 18 | [Automation](structure.md#18-automation) |
| 09 | [DHCP & Address Services](structure.md#09-dhcp-and-address-services) | 19 | [Monitoring & Troubleshooting](structure.md#19-monitoring-and-troubleshooting) |
| 10 | [High Availability](structure.md#10-high-availability) | 20 | [Enterprise Labs](structure.md#20-enterprise-labs) |

## Contributing in three steps

1. **Claim a topic** — check the Issues tab, comment *"I'd like to work on [Topic Name],"* and wait to be assigned.
2. **Build it** — follow [`_template.md`](_template.md), and include a topology image plus a lab file at the correct starting state.
3. **Open a PR** — reference your issue with `Closes #issue-number`.

Full rules, branch naming, and lab-file conventions live in [`CONTRIBUTING.md`](CONTRIBUTING.md).

## Questions?

Open a thread in **Discussions**, or reach the maintainers directly at **coieclub@outlook.com**.

---

<div align="center">

```
██╗    ██╗ ███████╗
██║    ██║ ██╔════╝
██║ █╗ ██║ █████╗  
██║███╗██║ ██╔══╝  
╚███╔███╔╝ ███████╗
 ╚══╝╚══╝  ╚══════╝

██╗      ██████╗  ██╗   ██╗ ███████╗
██║     ██╔═══██╗ ██║   ██║ ██╔════╝
██║     ██║   ██║ ██║   ██║ █████╗  
██║     ██║   ██║ ╚██╗ ██╔╝ ██╔══╝  
███████╗╚██████╔╝  ╚████╔╝  ███████╗
╚══════╝ ╚═════╝    ╚═══╝   ╚══════╝

██╗  ██████╗  ███████╗
██║ ██╔═══██╗ ██╔════╝
██║ ██║   ██║ ███████╗
██║ ██║   ██║ ╚════██║
██║ ╚██████╔╝ ███████║
╚═╝  ╚═════╝  ╚══════╝
```

*(yes, it does say what you think it says)*

</div>
