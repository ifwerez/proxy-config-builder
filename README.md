# proxy configs

auto-generated proxy configurations

## sources

- https://raw.githubusercontent.com/zieng2/wl/main/vless_universal.txt [online, 495 proxies]
- https://raw.githack.com/igareck/vpn-configs-for-russia/main/WHITE-CIDR-RU-all.txt [online, 113 proxies]
- https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_VLESS_RUS.txt [online, 51 proxies]
- 8f5c4a1faeb5 [online, 244 proxies]
- https://internet-tenshi.kangel.tech/1 [online, 2247 proxies]
- https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/1.txt [online, 8621 proxies]
- https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/6.txt [online, 145 proxies]
- https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/22.txt [online, 222 proxies]
- https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/23.txt [online, 50 proxies]
- https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/24.txt [online, 1061 proxies]
- https://github.com/AvenCores/goida-vpn-configs/raw/refs/heads/main/githubmirror/25.txt [online, 104 proxies]

## formats

- **clash (all)**: `clash.yaml`
- **sing-box**: `singbox.json`
- **raw vless urls**: `raw.txt`
- **per protocol clash**: `protocols/clash/*.yaml`
- **per protocol singbox**: `protocols/singbox/*.json`
- **per protocol raw**: `protocols/raw/*.txt`

## subscription urls

### github raw

```
https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/clash.yaml#All-In-One
https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/singbox.json#All-In-One
https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/raw.txt#All-In-One
```

### jsdelivr cdn

```
https://cdn.jsdelivr.net/gh/ifwerez/proxy-config-builder@main/clash.yaml#All-In-One
https://cdn.jsdelivr.net/gh/ifwerez/proxy-config-builder@main/singbox.json#All-In-One
https://cdn.jsdelivr.net/gh/ifwerez/proxy-config-builder@main/raw.txt#All-In-One
```

> [!warning]
> jsdelivr cdn has huge update delays (hours to days). use github raw or bypass mirrors for latest configs.

### ghproxy (bypass)

```
https://ghproxy.net/https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/clash.yaml#All-In-One
https://ghproxy.net/https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/singbox.json#All-In-One
https://ghproxy.net/https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/raw.txt#All-In-One
```

### yandex translate (bypass)

```
https://translate.yandex.ru/translate?url=https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/clash.yaml#All-In-One
https://translate.yandex.ru/translate?url=https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/singbox.json#All-In-One
https://translate.yandex.ru/translate?url=https://raw.githubusercontent.com/ifwerez/proxy-config-builder/main/raw.txt#All-In-One
```

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

last updated: 2026-05-21 20:20:51
proxies: 6418
