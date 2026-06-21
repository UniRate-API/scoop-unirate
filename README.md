# scoop-unirate

Scoop bucket for the [UniRate CLI](https://github.com/UniRate-API/unirate-cli) — currency exchange rates, conversion, and VAT from the command line.

## Install

```powershell
scoop bucket add unirate https://github.com/UniRate-API/scoop-unirate
scoop install unirate/unirate
```

## Usage

```powershell
$env:UNIRATE_API_KEY = "your_key_here"

unirate convert 100 USD EUR
unirate rate EUR GBP
unirate rates --base USD --json
unirate currencies
unirate vat DE
```

Get a free API key at [unirateapi.com](https://unirateapi.com).

---

<!-- unirate-ecosystem-start -->
**Other UniRate integrations:** [Python](https://github.com/UniRate-API/unirate-api-python) · [Node.js](https://github.com/UniRate-API/unirate-api-nodejs) · [Go](https://github.com/UniRate-API/unirate-api-go) · [Rust](https://github.com/UniRate-API/unirate-api-rust) · [Ruby](https://github.com/UniRate-API/unirate-api-ruby) · [MCP](https://github.com/UniRate-API/unirate-mcp) · [React](https://github.com/UniRate-API/react-unirate) · [Next.js](https://github.com/UniRate-API/next-unirate) · [Vue](https://github.com/UniRate-API/vue-unirate) · [Nuxt](https://github.com/UniRate-API/nuxt-unirate) · [CLI](https://github.com/UniRate-API/unirate-cli)
<!-- unirate-ecosystem-end -->