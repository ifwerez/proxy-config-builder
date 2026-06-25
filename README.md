# proxy configs

auto-generated proxy configurations

> [!warning]
> some clients may experience lag with large proxy lists. it is recommended to use split profiles for better performance.

## sources

- https://raw.githubusercontent.com/zieng2/wl/main/vless_universal.txt [online, 223 proxies]
- https://raw.githack.com/igareck/vpn-configs-for-russia/main/WHITE-CIDR-RU-all.txt [online, 85 proxies]
- https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_VLESS_RUS.txt [online, 87 proxies]
- https://internet-tenshi.kangel.tech/1 [online, 1964 proxies]
- https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/1.txt [offline, 0 proxies]
- https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/6.txt [offline, 0 proxies]
- https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/22.txt [offline, 0 proxies]
- https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/23.txt [offline, 0 proxies]
- https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/24.txt [offline, 0 proxies]
- https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/25.txt [offline, 0 proxies]

## subscription urls

<details>
<summary><b>github raw</b></summary>

| format | url |
|--------|-----|
| clash | `https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/clash.yaml#All-In-One` |
| sing-box | `https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/singbox.json#All-In-One` |
| raw | `https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/raw.txt#All-In-One` |

</details>

<details>
<summary><b>ghproxy bypass</b></summary>

| format | url |
|--------|-----|
| clash | `https://ghproxy.net/https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/clash.yaml#All-In-One` |
| sing-box | `https://ghproxy.net/https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/singbox.json#All-In-One` |
| raw | `https://ghproxy.net/https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/raw.txt#All-In-One` |

</details>

<details>
<summary><b>jsdelivr cdn</b></summary>

| format | url |
|--------|-----|
| clash | `https://cdn.jsdelivr.net/gh/ifwerez/proxy-config-builder@main/clash.yaml#All-In-One` |
| sing-box | `https://cdn.jsdelivr.net/gh/ifwerez/proxy-config-builder@main/singbox.json#All-In-One` |
| raw | `https://cdn.jsdelivr.net/gh/ifwerez/proxy-config-builder@main/raw.txt#All-In-One` |

</details>

<details>
<summary><b>yandex translate bypass</b></summary>

| format | url |
|--------|-----|
| clash | `https://translate.yandex.ru/translate?url=https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/clash.yaml#All-In-One` |
| sing-box | `https://translate.yandex.ru/translate?url=https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/singbox.json#All-In-One` |
| raw | `https://translate.yandex.ru/translate?url=https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/raw.txt#All-In-One` |

</details>

## split configs

<details>
<summary><b>by protocol</b></summary>

| format | vless | vmess | ss | trojan | hysteria2 |
|--------|-------|-------|----|--------|-----------|
| clash | `https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/protocols/clash/vless.yaml` | `https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/protocols/clash/vmess.yaml` | `https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/protocols/clash/ss.yaml` | `https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/protocols/clash/trojan.yaml` | `https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/protocols/clash/hysteria2.yaml` |
| sing-box | `https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/protocols/singbox/vless.json` | `https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/protocols/singbox/vmess.json` | `https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/protocols/singbox/ss.json` | `https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/protocols/singbox/trojan.json` | `https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/protocols/singbox/hysteria2.json` |
| raw | `https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/protocols/raw/vless.txt` | `https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/protocols/raw/vmess.txt` | `https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/protocols/raw/ss.txt` | `https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/protocols/raw/trojan.txt` | `https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/protocols/raw/hysteria2.txt` |

</details>

## qr codes

| clash | sing-box | raw |
|-------|----------|-----|
| ![clash](https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/clash.yaml#All-In-One) | ![singbox](https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/singbox.json#All-In-One) | ![raw](https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/raw.txt#All-In-One) |

[![view all qr codes](https://img.shields.io/badge/view_all_qr_codes-4A90D9?style=for-the-badge)](qr.md)

## contribute sources

you can add new proxy source URLs via a pull request:

1. fork this repository
2. edit `sources.json` and add a new entry to the `sources` array:

```json
{
  "url": "https://example.com/proxies.txt",
  "ua": "mihomo",
  "description": "optional description",
  "enabled": true
}
```

3. for `ua`, use a key from `ua_presets` in `sources.json` (e.g. `mihomo`, `flclash`, `clashmeta`) or a custom user-agent string
4. commit and submit a pull request

new sources are automatically merged on the next update cycle.

last updated: 2026-06-25 12:54:56
proxies: 858
