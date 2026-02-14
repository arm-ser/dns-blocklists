# DNS Blocklist Collection for Pi-hole

Curated DNS blocklists for personal use with [Pi-hole](https://pi-hole.net/). Blocks ads, tracking, telemetry, malware, and metadata collection from smart devices.

## Quick Start

**All-in-one blocklist:** [Download](https://raw.githubusercontent.com/arm-ser/dns-blocklists/main/all.txt)

Copy and paste the URL directly into Pi-hole's blocklist settings.

---

## Collections

| Collection | Source | List |
|:-----------|:-------|:----:|
| Ads, Tracking & Telemetry | arm-ser/dns-blocklists | [Raw](https://raw.githubusercontent.com/arm-ser/dns-blocklists/main/ads-tracking-telemetry.txt) |
| Specific Services & Devices | arm-ser/dns-blocklists | [Raw](https://raw.githubusercontent.com/arm-ser/dns-blocklists/main/specific-services-and-devices.txt) |
| Additional Lists | arm-ser/dns-blocklists | [Raw](https://raw.githubusercontent.com/arm-ser/dns-blocklists/main/additional-all.txt) |
| Firebog Lists | [The Firebog](https://firebog.net/) | [Raw](https://v.firebog.net/hosts/lists.php?type=tick) |
| Blocklists Info | [Blocklists Info](https://blocklists.info/) | [Raw](https://raw.githubusercontent.com/arm-ser/dns-blocklists/main/blocklists.info.txt) |

---

## Individual Lists

### Ads, Tracking & Telemetry

| Description | Source | List |
|:------------|:-------|:----:|
| Tracking & Telemetry | [Notrack](https://gitlab.com/quidsup/notrack-blocklists) | [Raw](https://gitlab.com/quidsup/notrack-blocklists/raw/master/notrack-blocklist.txt) |
| Ads & Tracking | [Developer Dan](https://github.com/lightswitch05/hosts) | [Raw](https://www.github.developerdan.com/hosts/lists/ads-and-tracking-extended.txt) |
| Ads List | [Blocklistproject](https://github.com/blocklistproject/Lists) | [Raw](https://blocklistproject.github.io/Lists/alt-version/ads-nl.txt) |
| Privacy | [Blocklistproject](https://github.com/blocklistproject/Lists) | [Raw](https://blocklistproject.github.io/Lists/alt-version/piracy-nl.txt) |
| Tracking | [Blocklistproject](https://github.com/blocklistproject/Lists) | [Raw](https://blocklistproject.github.io/Lists/alt-version/tracking-nl.txt) |

### Smart TV & Devices

| Description | Source | List |
|:------------|:-------|:----:|
| Smart TV Metadata & Telemetry | [Technoy](https://www.technoy.de/lists/blocklists-fuer-pihole/) | [Raw](https://raw.githubusercontent.com/Perflyst/PiHoleBlocklist/master/SmartTV.txt) |
| Smart TV Metadata & Telemetry | [H. Kamran](https://github.com/hkamran80) | [Raw](https://gist.githubusercontent.com/hkamran80/779019103fcd306979411d44c8d38459/raw/e0f084b396bb8ffcb390c8e7272ae96a6c292d10/SmartTV2.txt) |
| Smart TV Metadata & Telemetry | [Perflyst](https://github.com/Perflyst) | [Raw](https://perflyst.github.io/PiHoleBlocklist/SmartTV.txt) |
| Samsung Smart TV | [Matthias Marquardt](https://github.com/marq24) | [Raw](https://raw.githubusercontent.com/marq24/pihole-blocklist/master/samsung-smart-tv.txt) |
| Amazon Fire TV Metadata * | [Perflyst](https://github.com/Perflyst) | [Raw](https://perflyst.github.io/PiHoleBlocklist/AmazonFireTV.txt) |

### Additional

| Description | List |
|:------------|:----:|
| Fake Science | [Raw](https://raw.githubusercontent.com/RPiList/specials/master/Blocklisten/Fake-Science) |
| No Google | [Raw](https://raw.githubusercontent.com/nickspaargaren/no-google/master/pihole-google.txt) |
| Hate Groups | [Raw](https://raw.githubusercontent.com/chigh/hategroup-dnsbl/master/blocklist.txt) |
| Energized Blu | [Raw](https://raw.githubusercontent.com/EnergizedProtection/EnergizedBlu/master/energized/blu) |
| 1Hosts (Lite) | [Raw](https://raw.githubusercontent.com/arm-ser/dns-blocklists/main/1Hosts.txt) |
| Mullvad Lists | [Raw](https://raw.githubusercontent.com/arm-ser/dns-blocklists/main/mullvad-lists.txt) |

### My Lists

| Description | List |
|:------------|:----:|
| Android | [Raw](https://raw.githubusercontent.com/arm-ser/dns-blocklists/main/other) |

---

## Notes

- Lists marked with `*` have some domains commented out. Uncomment them for more aggressive blocking.
- Use at your own risk.

## Tools Used

- [Tracker Control](https://f-droid.org/packages/net.kollnig.missioncontrol.fdroid/) - Android tracker blocker
- [iodéOS](https://iode.tech/en/iodeos-en/) - Privacy-focused Android OS
- [Inure App Manager](https://github.com/Hamza417/Inure) - Android app manager

## Resources

- [What is Pi-hole?](https://github.com/pi-hole/pi-hole)
- [Adding Lists to Pi-hole](https://www.sammatthews.co.uk/2022/02/pi-hole-ad-lists/)
- [Blocklist Formatting](https://www.reddit.com/r/pihole/comments/bzufqv/hosts_format_for_blocklist/)
