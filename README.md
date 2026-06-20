# Westwood Astro — PixInsight Scripts

A PixInsight update repository of scripts by [Loran Hughes](https://WestwoodAstro.net),
built for the **V8 JavaScript runtime** introduced in PixInsight 1.9.4 (Lockhart).

Install it as an update repository (recommended) and PixInsight will keep the scripts
up to date automatically, or drop a single script in by hand for a quick try.

---

## Scripts

### OSC Narrowband Extraction
`Script ▸ Westwood Astro ▸ OSCNarrowbandExtraction`

Interactive extraction of narrowband channels from one‑shot‑color (OSC) data, with an
**in‑dialog, real‑time preview** of the synthetic SII channel that updates live as you
move the SII‑amount slider.

- Live preview of the synthetic SII channel while you tune the SII amount
- Optional **HOO**, **SHO**, and **Foraxx** (2‑ and 3‑channel) palette image creation
- Synthetic luminance channel
- Per‑channel statistical stretch tuned for Foraxx palettes

> Derived in part from Paul Hancock's Foraxx Palette Utility (see [Credits](#credits)).

---

## Requirements

- **PixInsight 1.9.4 (Lockhart) or later** — these scripts target the V8 runtime and will
  not run on the legacy SpiderMonkey 24 engine.

---

## Installation

### Update repository (recommended)

1. In PixInsight, open **Resources ▸ Updates ▸ Manage Repositories**.
2. Click **Add** and paste the repository URL (note the trailing slash):

   ```
   https://raw.githubusercontent.com/WestwoodAstro/pix-scripts/main/updates/
   ```

3. Run **Resources ▸ Updates ▸ Check for Updates**, apply the changes, and **restart**
   PixInsight when prompted.
4. The scripts appear under **Script ▸ Westwood Astro**.

---

## Credits

- **OSC Narrowband Extraction** © 2026 Loran Hughes, [WestwoodAstro.net](https://WestwoodAstro.net) (Incorporates ideas and code from the **Foraxx Palette Utility** © 2024 Paul Hancock).

## License

Distributed under the **GNU General Public License v3.0**. See the license header in each
script and <https://www.gnu.org/licenses/>.
