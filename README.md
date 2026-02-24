# Roblox ↔ Polytoria Tools

A collection of free, open-source conversion tools for the Polytoria community. Everything runs client-side in your browser — no accounts, no uploads, no cost.

**Live site → [kaiser9820.github.io/roblox-to-polytoria](https://kaiser9820.github.io/roblox-to-polytoria)**

---

## Tools

| # | Tool | Status |
|---|------|--------|
| 01 | [RBX → PT Shirt Converter](roblox-to-polytoria-shirt-converter.html) | ✅ Live |
| 02 | [PT → RBX Shirt Converter](pt2rbx.html) | ✅ Live |
| 03 | Studio Plugin (`.rbxm`) | 🔜 Coming Soon |

---

## How it works

The shirt converters remap every UV region from the Roblox shirt template layout to Polytoria's layout (and vice versa) using the HTML5 Canvas API. No data ever leaves your device.

**Input:** Any PNG, JPG, or WEBP shirt template (585×559 recommended)  
**Output:** 1024×1024 PNG ready to upload to Polytoria

---

## Repo structure

```
roblox-to-polytoria/
├── index.html                              ← Homepage / hub
├── roblox-to-polytoria-shirt-converter.html
├── pt2rbx.html
└── plugin.rbxm                             ← Coming soon
```

---

## Contributing

PRs and issues are welcome. If you have a tool idea or find a bug, open an issue.

---

Made by [Kaiser9820](https://github.com/Kaiser9820) for the Polytoria community.
