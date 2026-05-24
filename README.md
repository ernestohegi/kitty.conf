# 🐱 Kitty Terminal Configuration

Personal Kitty configuration files.

## 🚀 Installation

Choose one of the options below.

### ✅ Option 1: Clone directly into Kitty config (recommended)

```bash
mv ~/.config/kitty ~/.config/kitty.backup.$(date +%Y%m%d-%H%M%S) 2>/dev/null || true
git clone git@github.com:ernestohegi/kitty.conf.git ~/.config/kitty
```

### 📁 Option 2: Clone elsewhere, then copy into `~/.config/kitty`

```bash
git clone git@github.com:ernestohegi/kitty.conf.git
mkdir -p ~/.config/kitty
cp -r kitty.conf/* ~/.config/kitty/
```

🔄 Restart Kitty, or reload the config with `Ctrl+Shift+F5`.

## 🎨 Themes

Clone [dexpota/kitty-themes](https://github.com/dexpota/kitty-themes) into your Kitty config directory:

```bash
git clone https://github.com/dexpota/kitty-themes.git ~/.config/kitty/kitty-themes
```
