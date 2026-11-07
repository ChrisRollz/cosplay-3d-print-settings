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

---

## Chief Geek Photography (TPU)

**Creator:** [@chiefgeekphotography](https://www.instagram.com/chiefgeekphotography/) on Instagram  
**Contact:** [Creator’s contact page](https://poplme.co/x7bahoMw)  
**Filament:** Generic TPU (brand and hardness unconfirmed)  
**Folder:** [`chiefgeekphotography/`](chiefgeekphotography/)

| File | What it is |
| --- | --- |
| [`generic-tpu-filament.json`](chiefgeekphotography/generic-tpu-filament.json) | Filament information and displayed retraction values, with override status |
| [`tpu-process.json`](chiefgeekphotography/tpu-process.json) | Process profile: quality, speeds, acceleration, supports and multimaterial |

Transcribed from 19 screenshots of the creator’s Instagram Reel. All credit goes to @chiefgeekphotography. These files follow the documentary JSON format used for Slades above; they are not native slicer imports. Only photographed settings are included; missing or uncertain fields are documented in each file.

**Key settings**

| Setting | Value |
| --- | --- |
| Process printer / nozzle | Snapmaker U1 / 0.4 mm |
| Layer height | 0.16 mm (first layer 0.2 mm) |
| First layer speed | 20 mm/s (infill 50 mm/s) |
| Outer / inner wall speed | 75 / 150 mm/s |
| Supports | Tree (auto), build plate only, 30° threshold |
| Support material | Slot 2 PLA for base and interface |
| Support top / bottom Z gap | 0.28 / 0.16 mm |
| Print temperatures / max volumetric speed | Not shown |

The filament screenshots name a Generic TPU profile for BBL H2S, while the process screenshots show Snapmaker U1. Preserve that distinction when consulting these notes. Retraction override boxes are unchecked: the displayed 1.5 mm and 30 mm/s values are not enabled filament overrides. Strength settings (including walls and infill) were not photographed.
