# 🍫 Protein Tier List

Rank and argue about protein powder flavors like they deserve. A drag-and-drop tier list built for people who take their supplements seriously.

**🔗 Live demo → [tyronsamaroo.github.io/protein-tier-list](https://tyronsamaroo.github.io/protein-tier-list/)**

---

## Features

- **Drag-and-drop ranking** across 6 tiers: S (God Tier) → F (Trash)
- **Multi-user profiles** — switch between users, each with their own rankings stored in `localStorage`
- **Share your tier list** via a single URL — rankings are base64-encoded in the hash
- **Brand filter** — narrow the view to Ryse, MuscleSport, Ghost, PEScience, Raw/CBUM, or Dymatize
- **Grid view** — see all flavors grouped by brand with tier badges
- **Right-click context menu** for quick tier assignment and deletion
- **Progress tracker** — see how much of your list is ranked

## Usage

No install needed — open `index.html` in any browser or visit the [live page](https://tyronsamaroo.github.io/protein-tier-list/).

```bash
# Run locally with Python
python3 -m http.server 3456
# open http://localhost:3456
```

## Controls

| Action | How |
|--------|-----|
| Move a card | Drag it to a tier |
| Quick move | Right-click → pick a tier |
| Select + place | Click a card, then click a tier label |
| Share | Controls → Share → copy the URL |
| Add flavor | Controls → Add Flavor |
| Switch profile | Click a name in the profile bar |

## Tech Stack

- React 18 (CDN/UMD — zero build step)
- Vanilla CSS with CSS custom properties
- `localStorage` for persistence
- Base64 URL encoding for share links

## Tier Legend

| Tier | Vibe |
|------|------|
| 👑 S | God Tier — you buy these in bulk |
| 🔥 A | Elite — genuinely good |
| 💪 B | Solid — gets the job done |
| 🤷 C | Mid — drinkable but forgettable |
| 😐 D | Nah — you finish the tub but don't reorder |
| 🗑️ F | Trash — you gave it to someone you don't like |
