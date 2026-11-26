<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="logo-dark.png">
    <img src="logo-light.png" alt="Proxies.Vision" width="360">
  </picture>
</p>

<p align="center">Residential proxies at $1 per GB, paid with crypto. No KYC, no subscription.</p>

<p align="center">
  <a href="https://proxies.vision">Website</a> ·
  <a href="https://proxies.vision/docs">Docs</a> ·
  <a href="https://proxies.vision/pricing">Pricing</a> ·
  <a href="https://t.me/proxiesvision_bot">Telegram bot</a>
</p>

### Connect

| | |
|---|---|
| Host | `via.proxies.vision` |
| HTTP | `9000` rotating, `10000-10900` sticky |
| SOCKS5 | `11000` rotating, `12000-12010` sticky |
| Targeting | in the username: `-country-de`, `-city-berlin`, `-asn-3320`, `-session-abc123-lifetime-30` |

```bash
curl -x http://USER-country-us:PASS@via.proxies.vision:9000 https://ipinfo.io/json
```

Your login is in the dashboard after the first purchase. 1 GB for $1 works as a test.

### Help

Setup guides for curl, Python, Node, Playwright, Puppeteer and more are on the [blog](https://proxies.vision/blog), error codes in the [docs](https://proxies.vision/docs/proxy-errors).
