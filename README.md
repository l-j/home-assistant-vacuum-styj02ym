# Hacky Home Assistant support for Xiaomi vacuum STYJ02YM 

## Works with:
* STYJ02YM (EU version) with 3.5.3_0017 firmware
* STYJ02YM (China version) with 3.5.3_0047 firmware
  * Set `china_version: True` to get additional details about brush, mop and filter life

## Installation:
- install it with HACS
- Add the configuration to configuration.yaml, example:

```yaml
vacuum:
  - platform: miio2
    host: 192.168.68.105
    token: !secret vacuum
    name: Mi hihi
    china_version: False
```
