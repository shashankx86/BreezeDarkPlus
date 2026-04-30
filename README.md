# Breeze Dark Plus

## Installation

### Method 1: System Settings (Recommended)

1. Open **System Settings**
2. Go to **Colors & Themes → Colors**
3. Click **Install from File...**
4. Select your `.colors` file (e.g., `BreezeDarkPlus.colors`)
5. Apply the theme

---

### Method 2: Manual Install

#### User-only

```bash
mkdir -p ~/.local/share/color-schemes/
cp /path/to/BreezeDarkPlus.colors ~/.local/share/color-schemes/
```

Then apply it from **System Settings → Colors**

#### System-wide

```bash
sudo cp /path/to/BreezeDarkPlus.colors /usr/share/color-schemes/
```

Then apply it from **System Settings → Colors**

---

## Uninstall

**User install:**

```bash
rm ~/.local/share/color-schemes/BreezeDarkPlus.colors
```

**System-wide:**

```bash
sudo rm /usr/share/color-schemes/BreezeDarkPlus.colors
```

Or remove it from System Settings via the trash icon.

