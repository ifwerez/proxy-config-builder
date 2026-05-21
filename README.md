# proxy configs

auto-generated proxy configurations

## sources

- https://raw.githubusercontent.com/zieng2/wl/main/vless_universal.txt [online, 838 proxies]
- https://etoneya.best/1 [offline, 0 proxies]
- https://raw.githack.com/igareck/vpn-configs-for-russia/main/WHITE-CIDR-RU-all.txt [online, 335 proxies]
- https://raw.githack.com/igareck/vpn-configs-for-russia/main/BLACK_VLESS_RUS.txt [online, 109 proxies]
- 8f5c4a1faeb5 [online, 244 proxies]
- 8f5c4a1faeb5 [offline, 0 proxies]

## formats

- **clash**: `clash.yaml`
- **sing-box**: `singbox.json`
- **raw vless urls**: `raw.txt`
- **per continent clash**: `continents/clash/*.yaml`
- **per continent singbox**: `continents/singbox/*.json`
- **per continent raw**: `continents/raw/*.txt`

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

last updated: 2026-05-21 08:26:42
proxies: 1072
