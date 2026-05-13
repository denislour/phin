# ☕ phin — Pi themes inspired by Vietnamese coffee

> *Phin* — from French *filtre* (filter), the soul of Vietnamese coffee

## 📦 Themes

| Theme | File | Vibe |
|:------|:-----|:------|
| ☕ **arabica** | `arabica.json` | Light, warm pastel, elegant |
| ☕ **robusta** | `robusta.json` | Bold, dark roast, strong |

## 🚀 Installation

### Option 1 — pi install (recommended)

```bash
pi install git:github.com/denislour/phin
```

### Option 2 — Manual (copy files)

```bash
cp arabica.json ~/.pi/agent/themes/
cp robusta.json ~/.pi/agent/themes/
```

### Option 3 — GitHub raw URL

In `~/.pi/agent/settings.json`:

```json
{
  "theme": "https://raw.githubusercontent.com/denislour/phin/master/robusta.json"
}
```

## 🗑️ Uninstall

### Option 1 — pi remove

```bash
pi remove git:github.com/denislour/phin
```

### Option 2 — Manual

```bash
rm ~/.pi/agent/themes/arabica.json ~/.pi/agent/themes/robusta.json
```

Then reset theme in `/settings` to `dark` or `light`.

## 🎨 Switching themes

Open `/settings` in pi, then select `arabica` or `robusta`.

Pi hot-reloads themes automatically — no restart needed!

## 🔧 Development

### Schema

Themes use the official pi schema for validation and editor autocompletion:

```
https://raw.githubusercontent.com/earendil-works/pi-mono/main/packages/coding-agent/src/modes/interactive/theme/theme-schema.json
```

## 📄 License

[MIT](LICENSE) — free as in coffee. ☕

---

☕ *Brew a phin, code better.*
