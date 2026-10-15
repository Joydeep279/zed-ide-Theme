# OneNord for Zed

**A beautifully crafted, distraction-free theme for [Zed](https://zed.dev/), available in Dark and Light variants.**

OneNord combines the cool, icy atmosphere of Nord with carefully balanced pastel syntax colors to create a clean, cohesive coding environment. Its soothing dark and crisp light palettes, soft accents, and refined UI colors offer a comfortable visual experience for long coding sessions without sacrificing readability.

Designed for developers who appreciate minimalism, consistency, and thoughtful details.

## Previews

### Dark Theme

![OneNord Dark Preview](dark%20preview.png)

### Light Theme

![OneNord Light Preview](light%20preview.png)

## Features

- **Deep, Soothing Dark Palette** — A rich blue-gray background (`#2B2F40`) creates a calm workspace with balanced contrast.
- **Pastel Syntax Highlighting** — Soft blues, mauves, greens, and peach tones distinguish code elements without overwhelming the interface.
- **Consistent UI Colors** — A cohesive palette across the sidebar, editor tabs, terminal, status bar, and other interface components.
- **Git & Diff Support** — Distinct colors for added, modified, and deleted lines make version-control changes easier to scan.
- **Distraction-Free Design** — A restrained color palette keeps the focus on your code while maintaining a clear visual hierarchy.
- **Designed for Long Sessions** — Muted backgrounds and thoughtfully selected accents aim to provide a comfortable coding experience.

## Installation

### Option 1: Install from Zed Extensions (Recommended)

Once published to the Zed Extensions registry:

1. Open the Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`)
2. Search for `zed: extensions`
3. Search for **OneNord**
4. Click **Install**

### Option 2: Install as a Dev Extension

To install directly from a local clone of this repository:

1. Clone this repository:

   ```bash
   git clone https://github.com/Joydeep279/zed-ide-Theme.git
   ```

2. Open the Command Palette in Zed (`Ctrl+Shift+P` / `Cmd+Shift+P`)
3. Run `zed: install dev extension`
4. Select the cloned repository folder

Zed will load the extension and make the theme available immediately.

### Option 3: Manual Local Theme

If you prefer to install the theme file directly without using the extension system:

1. Copy `themes/onenord.json` to Zed's local themes directory:

   **Windows**

   ```text
   %USERPROFILE%\AppData\Roaming\Zed\themes\
   ```

   **macOS / Linux**

   ```text
   ~/.config/zed/themes/
   ```

   If the `themes` directory does not exist, create it manually.

2. Restart Zed so it loads the local theme file.

## Usage

### Activate OneNord

Open the theme selector:

- **Windows/Linux:** `Ctrl + K`, then `Ctrl + T`
- **macOS:** `Cmd + K`, then `Cmd + T`

Search for **OneNord** and select **OneNord Dark** or **OneNord Light** to apply the theme.

### Set OneNord as Your Default Theme

You can also configure OneNord as your default theme in Zed's `settings.json`.

Open the Settings file through the Command Palette using `zed: open settings file`, then set the theme:

```json
{
  "theme": {
    "mode": "system",
    "light": "OneNord Light",
    "dark": "OneNord Dark"
  }
}
```

Or set a specific variant directly:

```json
{
  "theme": "OneNord Dark"
}
```

Make sure the theme name matches the name defined in the theme JSON file.

## Extension Structure

```text
zed-ide-Theme/
├── extension.toml         # Extension manifest
├── themes/
│   └── onenord.json       # Theme family (Dark + Light)
├── Readme.md
├── dark preview.png
└── light preview.png
```

## Color Philosophy

OneNord is built around a simple idea: **a dark interface should feel calm, not dull.**

| Element | Design Direction |
| --- | --- |
| Background | Deep blue-gray |
| Syntax | Soft, expressive pastels |
| Interface | Consistent and understated |
| Diff highlights | Clear, meaningful distinctions |
| Overall feel | Minimal, cool, and comfortable |

## Contributing

Feedback, suggestions, and contributions are welcome!

If you find a visual inconsistency, spot an issue, or have an idea for improving the theme, feel free to open an issue or submit a pull request.

## Feedback

Using OneNord? I'd love to hear what you think.

- Share your feedback and suggestions.
- Report bugs or color inconsistencies.
- Suggest improvements to syntax highlighting or UI colors.

## License

See the repository's `LICENSE` file for licensing information.

---

**OneNord for Zed** — *Cool tones. Clear code. Calm focus.*
