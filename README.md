# Obsidian Glow

A minimal luxury VS Code coding aesthetic inspired by modern automotive digital dashboards and luxury ambient lighting. 

Designed and developed by **[0xRasla](https://github.com/0xRasla)**.

---

## 🏎️ The Concept: Minimal Luxury Cockpit
Imagine settling into the cockpit of a premium high-performance vehicle at night. The digital instrument clusters are dark, high-contrast, and designed to eliminate glare. Sleek status displays feature precise needle indicators and soft color-coded readouts, while a single, rich ambient LED strip glows across the dashboard, outlining active elements with perfect sophistication.

**Obsidian Glow** captures this atmosphere. It relies on a deep, soothing carbon backing, informative instrument hues, and a single signature glowing accent to create an environment that feels alive, premium, and focused.

---

## 🚦 Theme Variations

Obsidian Glow is available in **four** distinct cockpit styles to match your driving mood and lighting environment:

1. **Obsidian Glow (Default)**
   - The signature midnight luxury dashboard. Deep carbon slate backgrounds (`#1a1b26`) paired with high-performance instrument gauges and an electric lavender ambient LED strip (`#bb9af7`).
2. **Obsidian Glow - Carbon OLED**
   - Pure, unlit deep-space cockpit. The carbon backing is dropped to a rich pitch black (`#0d0e15`), causing the dashboard elements and the lavender accent strip to shine with supreme high-contrast brilliance.
3. **Obsidian Glow - Ambient Light**
   - Luxurious silver-metallic daytime cockpit. Clean brushed-silver backings (`#f2f4f8`), charcoal-slate instruments (`#383a47`), and an active Orchid purple ambient highlight (`#8f58e8`).
4. **Obsidian Glow - Sunset Sand**
   - The warm leather cockpit variation. Cream ivory/beige dashboard background (`#fcf8f2`), warm espresso-charcoal text (`#4a3e3d`), and sunset amber gauges (`#d35400`) backlit by a warm gold-orchid LED trim (`#a55eea`).

---

## 🎨 The Dashboard Palette

| Color | Hex | Visual Identity | Usage in Code |
| :--- | :--- | :--- | :--- |
| **Carbon Slate** | `#1a1b26` | Non-glare Dashboard Backing | Core Editor Background |
| **Muted Lavender White** | `#a9b1d6` | Tachometer / Digital Font | Primary Text & Punctuation |
| **Warm Ember / Orange** | `#ff9e64` | Gauge Sweeps & Indicators | Keywords, Numbers, Control Flow |
| **Soft Sage Green** | `#9ece6a` | Eco & Fuel Systems | Strings, Regular Expressions |
| **Dusty Blue** | `#7aa2f7` | Dynamic Navigation Map | Functions, Callbacks, Methods |
| **Pale Blue-White** | `#c0caf5` | Secondary Instrument Readouts | Variables, Parameters |
| **Warmer Gray-Blue** | `#5f6b93` | Quiet Dashboard Statuses | Comments (Sophisticated & highly readable) |
| **Signature Hook Accent** | `#bb9af7` | Premium LED Ambient Lighting | Active Tabs, Selection, Cursor, Active Indent |

---

## 💎 Key Aesthetic Decisions

### 1. Warmer, Less Dead Comments (`#5f6b93`)
Generic dark themes often render comments in cold, dead grays that make codebases look lifeless and fatigue the eyes. **Obsidian Glow** uses a carefully tuned, slightly warmer gray-blue. Comments remain perfectly subtle, but they feel organic, readable, and beautifully integrated into your files.

### 2. The LED Ambient Accent Strip (`#bb9af7`)
To prevent the theme from looking like a generic dark mode, we've introduced a signature **glow lavender** accent. Used sparingly to replicate precision ambient lighting:
- **Active Editor Tab**: Highlighted with a glowing top border.
- **Selection Highlight**: A soft, translucent 20% opacity purple glow.
- **Activity Bar Icons**: Active states glow with this accent.
- **Editor Cursor & Indentation Guides**: Guides your focus without cluttering the screen.
- **Syntax Operators**: Selectively highlights key assignment and separator tokens (`=`, `=>`, `?`, `:`) to define structural boundaries.

---

## 🛠️ Development & Packaging

This project is configured with **Bun** for ultra-fast package management and execution.

### Prerequisites
Make sure [Bun](https://bun.sh) is installed on your system.

### Install Dependencies
To install the development utilities:
```bash
bun install
```

### Developing in Real-time
1. Open this workspace folder in VS Code.
2. Press `F5` on your keyboard to launch a new **Extension Development Host**.
3. In the new window, open any codebase of your choice.
4. Go to Settings (`Ctrl+,` or `Cmd+,`), search for **Color Theme**, and select **Obsidian Glow** to preview changes live as you edit the JSON!

### Package for Distribution
To compile the theme into a standalone `.vsix` file ready for installation or publishing to the VS Code Marketplace:
```bash
bunx vsce package
```

---

## 👤 Author & Credits
Created with ❤️ by **[0xRasla](https://github.com/0xRasla)**. 
- GitHub: [@0xRasla](https://github.com/0xRasla)
