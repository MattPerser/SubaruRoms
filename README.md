# Subaru Stock ROM Repository

A free, organized collection of **stock Subaru ECU ROMs** the
calibration images RomRaider and ECUFlash read.

Files are named:

```
MARKET/Model/CALID-YEAR-MARKET-Subaru-Model-Engine-Transmission.hex
```

They're raw binary ROM images (the `.hex` extension is the RomRaider
convention. They are *not* Intel/Motorola hex text). Open one directly in
RomRaider or ECUFlash with the matching definition.

## What's here

| Folder | Count | Contents |
|--------|------:|----------|
| `USDM/ JDM/ EDM/ ADM/` | 683 | Engine ROMs, by market and model |
| `CDM/` | 8 | Canada-only calibrations, the rare 2.5 manual trims the US never got |
| `_Modules/TCM/` | 64 | Automatic + CVT (Lineartronic) transmission ROMs |
| `_Modules/ETC/` | 3 | Electronic throttle control ROMs |
| `_Modules/BIU/` | 7 | Body Integrated Unit (keyless / body control) |
| `_Modules/CAMERA/` | 12 | EyeSight camera firmware (per-processor images) |
| `_Modules/DMCM/` | 2 | Dual-mode clutch modules |
| `_NewGen_RH850/` | 45 | 2019+ Impreza/Crosstrek (calibration region only) |

These are the latest factory calibrations, checksum-validated and flash-ready.
`manifest.csv` lists full provenance for every file (CALID, checksum status,
sha256); `qc_checksum_report.csv` flags a handful of community-sourced files
with pre-existing issues.


---

Provided for reference and research. Not affiliated with Subaru.
