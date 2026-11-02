# 3D Printing Settings

Some of the best cosplay and armor builders out there print their work, and a lot of them share the slicer settings that get them there. This repo is where I collect those settings from creators I like, so I can find them again and so anyone else can use them too.

Each creator has their own folder with the filament and process profiles they've shared. I save them the way the creator posted them. Most are for Orca-based slicers (Creality Print, Orca Slicer, Bambu Studio).

All credit goes to the creators. If their settings help you, go follow them.

---

## Slades Armory (TPU)

**Creator:** [@slades_armory](https://www.instagram.com/slades_armory/) on Instagram
**Filament:** Overture TPU
**Folder:** [`slades_armory/`](slades_armory/)

| File | What it is |
| --- | --- |
| [`overture-tpu-filament.json`](slades_armory/overture-tpu-filament.json) | Filament profile: temps, cooling, retraction |
| [`overture-tpu-process.json`](slades_armory/overture-tpu-process.json) | Process profile ("my settings v2"): layers, walls, infill, speeds, supports |

**Key settings**

| Setting | Value |
| --- | --- |
| Nozzle temp | 240 °C |
| Bed temp | 35 °C textured PEI, 40 °C smooth PEI |
| Chamber temp | 35 °C |
| Max volumetric speed | 2 mm³/s |
| Retraction | 1 mm at 40 mm/s |
| Layer height | 0.48 mm (first layer 0.24 mm) |
| Walls | 2 |
| Top / bottom layers | 4 / 3 |
| Infill | 3 % rectilinear |
| Supports | Tree (auto), build plate only, 30° threshold |
