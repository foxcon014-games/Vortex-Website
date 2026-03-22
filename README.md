# Vortex Browser

> Stable Build — v26.40.5 | 13/10/25

A custom browser launcher suite with guest and admin modes, incognito support, and a retro green-glow terminal aesthetic.

---

## Files

| File | Description |
|------|-------------|
| `Vortex_Launcher.html` | Main entry point — launch guest or admin browser, toggle incognito mode |
| `Vortex_Browser.html` | Guest browser (uses `Guest.ico`) |
| `Vortex_Browser_Admin.html` | Admin browser with elevated controls (uses `Admin.ico`) |
| `Launcher.ico` | Icon for the launcher tab |
| `Guest.ico` | Icon for the guest browser tab |
| `Admin.ico` | Icon for the admin browser tab |

---

## How To Use

1. Open `Vortex_Launcher.html` in your browser
2. Choose **Vortex Browser** (guest) or **Vortex Browser Admin**
3. Toggle **Incognito Mode** on/off before launching — incognito wraps pages in `about:blank` to hide history
4. **Open In Private Window** opens the launcher itself in a new private-style window

---

## Features

- Custom green-glow cursor and UI
- Retro VT323 terminal font aesthetic
- Incognito mode using `about:blank` iframe wrapping with link interceptor
- Standalone window detection — auto-adjusts open behaviour
- Loading screen with animated dots
- Flickering title animation
- Admin mode with elevated browser controls

---

## Notes

- All files must be kept in the **same folder** — icons and HTML files reference each other by relative path
- No server required — runs entirely as local HTML files
- Tested on Chromium-based browsers
