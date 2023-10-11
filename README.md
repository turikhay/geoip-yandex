# geoip-yandex

[Loyalsoldier/geoip](https://github.com/Loyalsoldier/geoip) fork that includes (some) ASNs that are operated or owned by Yandex.


## V2Ray example

```json
{
  "routing": {
    "rules": [
      {
        "type": "field",
        "outboundTag": "direct",
        "ip": [
          "geoip:yandex"
        ]
      }
    ]
  }
}
```

## Download

Use this permanent link:

`https://raw.githubusercontent.com/turikhay/geoip-yandex/release/geoip.dat`

## License

[CC-BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/)

This product includes GeoLite2 data created by MaxMind, available from [MaxMind](http://www.maxmind.com).
