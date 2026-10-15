# GVK Ship Core Framework Content Pack

Ship Core Framework (SCF) content pack for the **GV: Deserts of Kharak (GVK)** Space Engineers server.

## Overview
Defines grid classes, speed caps, mobility points (MPs), utility points (UPs), weapon restrictions, and block limits for all grids on Kharak.

- **Mod ID**: `3612475191`
- **Framework Mod Dependency**: [Ship Core Framework (3552595651)](https://steamcommunity.com/sharedfiles/filedetails/?id=3552595651)

## Grid Classes
- **Light Core**: 750 blocks, 80 MPs, 40 UPs, 2 Interior Turrets (Top Speed: 180 m/s)
- **Support Core**: 2,000 blocks, 140 MPs, 40 UPs, 4 Interior Turrets, 4 Salvage Beam Turrets (Top Speed: 150 m/s)
- **Medium Grid**: 2,000 blocks, 140 MPs, 60 UPs, 4 Interior Turrets (Top Speed: 150 m/s)
- **Heavy Grid**: 4,000 blocks, 200 MPs, 80 UPs, 6 Interior Turrets (Top Speed: 120 m/s)
- **Fortress Core**: 6,000 blocks (static), 200 MPs, 120 UPs, 8 Interior Turrets, 4 Salvage Beam Turrets, 1 Fortress Weapon
- **Pipeline Core**: 50 blocks (static), pipeline hub infrastructure
- **Shield Core**: 50 blocks (static), safezone shield generator
- **Scrap Cores**: Salvage and scrap refining grids
- **Small Core**: 2,000 blocks, 80 MPs, 40 UPs
- **No Core**: 100 blocks, restricted functional blocks

## Validation
Lint with `sc_lint.py`:
```powershell
python <path-to-skill>/scripts/sc_lint.py Content --world Content/Data/ShipCoreConfig_World.xml
```
