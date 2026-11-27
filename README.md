# TitanSISdnBhd — Automated IP Blocklists

Automated mirror of curated threat intelligence IP blocklists, updated every 2 hours via GitHub Actions.

## Included Feeds

| Local File | Upstream Source | Description |
| :--- | :--- | :--- |
| `ipsum_level3` | [stamparm/ipsum](https://github.com/stamparm/ipsum) (`levels/3.txt`) | Malicious IPs appearing on at least 3 threat intelligence feeds. |
| `bitwire_inbound` | [bitwire-it/ipblocklist](https://github.com/bitwire-it/ipblocklist) (`inbound.txt`) | Active inbound scanners, brute-force attackers, and spam sources. |
| `bitwire_outbound` | [bitwire-it/ipblocklist](https://github.com/bitwire-it/ipblocklist) (`outbound.txt`) | Known malicious outbound destinations (C2 servers, malware, botnets). |

## Acknowledgments & Credits

Special thanks to the maintainers and contributors of these upstream projects for compiling and maintaining free threat intelligence feeds:

* **[Miroslav Stampar (`stamparm/ipsum`)](https://github.com/stamparm/ipsum)** — Daily aggregated threat intelligence feed (`levels/3.txt`).
* **[Bitwire IT (`bitwire-it/ipblocklist`)](https://github.com/bitwire-it/ipblocklist)** — Inbound and outbound IP blocklists (`inbound.txt`, `outbound.txt`).

---
*Note: All IP data belongs to and is maintained by the respective upstream projects linked above.*
