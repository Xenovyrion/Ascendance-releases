<p align="center">
  <img src="src-tauri/icons/128x128.png" width="96" alt="Ascendance" />
</p>

<h1 align="center">Ascendance</h1>

<p align="center">
  <em>Dofus Mount Breeding Companion</em>
</p>

<p align="center">
<!-- BADGES:START -->
<img alt="Release" src="https://img.shields.io/github/v/release/Xenovyrion/Ascendance-releases?style=for-the-badge" />
<img alt="Platform" src="https://img.shields.io/badge/Platform-Windows-0078D4?style=for-the-badge&logo=windows11&logoColor=white" />
<!-- BADGES:END -->
</p>

---

**Ascendance** is a Windows desktop application designed for Dofus 3.5 breeders. It centralises everything you need to manage your mounts: multi-generation genealogy trees, per-breed grind statistics, enclos gauge timers, achievement tracking, and a breeding advisor that calculates recommended pairs and success rates in real time.

---

## 1. Features

### Breeding Tree (Arbre)
- Visual genealogy tree for Dragodindes, Volkornes and Muldos across all 10 generations
- Per-mount stock tracking: pure males/females, mixed males/females, fertile, sterile, births, clones
- Collapsible generation groups with colour-coded cards per mount type
- **Breeding Advisor** — calculates the optimal next actions (capture or breed) for each achievement target, with estimated success rates based on parent purity and level, Optimakina/Animakina support, and pair recommendations at 95% confidence

### Grind Tracker (Grind)
- Aggregate statistics per mount breed across all generations
- Track births, clones, sterile mounts, and completion state per species
- Filter and sort by mount type or generation

### Enclos Timers (Timers)
- Add timers to track how long it takes for a stat to fill in a given enclos
- Supports all four stat types: **Amour**, **Endurance**, **Maturité**, **Sérénité**
- Tier-aware calculation (T1–T4 based on enclos durabilité) accounts for the gauge depleting as the stat fills
- Quick-set buttons for tier boundaries (0 / 40 000 / 70 000 / 90 000 / 100 000) plus manual input
- Sérénité mode auto-detects direction (Caresseur ↑ / Baffeur ↓) and target zone (−2 000 to +2 000)
- System notifications when a timer expires

### Achievements (Succès)
- Full achievement tree based on the official Dofus 3.5 breeding successes
- Per-objective progress with automatic validation when grind stats are met
- Proposal banner surfacing the next completable objective at a glance

### Game Info (Infos)
- Quick reference for breeding mechanics: birth rates, level bonuses, makina effects, enclos tiers, slot counts

### Settings (Paramètres)
- Choose between multiple colour themes
- Configure makina type (none / Optimakina / Animakina) and target breeding level for advisor calculations
- Adjust the number of advisor actions displayed and their sort order

---

## 6. Data & Privacy

All data is stored locally in a SQLite database on your device — nothing is sent to any server. The auto-updater only checks the GitHub Releases page for a new version number.
