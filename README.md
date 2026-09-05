# LoL Build Calculator

A League of Legends build calculator focused on maximum-stat builds.

## Features

- Jhin max-AD calculator
- Sett build calculator
- Vladimir build calculator
- All Champions stat maximizer
- Auto-updating Riot Data Dragon item and champion data
- Lane-specific boot rules
- Summoner's Rift items only

## All Champions stats

The global calculator can maximize:

- Attack Damage
- Ability Power
- Visible Ability Haste
- Ability Haste with Imperial Mandate
- Attack Speed
- Movement Speed
- Health
- Armor
- Magic Resist
- Lethality
- Flat Magic Penetration

## Important rules

- Basic-only and ultimate-only haste do not count as visible Ability Haste.
- Imperial Mandate is mandatory in its dedicated haste mode.
- Percentage armor and magic penetration do not count toward Lethality or Flat Magic Penetration.
- Bot lane can use the separate seventh boot slot.
- Mid lane can use enhanced boots.
- Other lanes use normal boots in a regular item slot.
- Bel'Veth can reach up to 10.00 attack speed.
- Jhin's max-AD optimizer does not exceed 100% crit.
- Arena, ARAM Mayhem, duplicate, deprecated, component, and mode-only items are excluded.
- Forever Forward is excluded.

## Data

The calculator checks Riot Data Dragon for current item and champion data when it loads.

Use **Refresh Riot data** to force an update.

## Usage

Open the HTML file in a browser, choose a champion or stat, set the lane where applicable, then run the optimizer.
