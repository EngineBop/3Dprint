---
sidebar_position: 2
title: H2D User Manual
---

# Bambu Lab H2D AMS Combo — User Manual

> Local operating guide (draft). Use the current official Bambu Lab H2D documentation for setup, safety, maintenance and error-specific procedures. This guide is not a substitute for the manufacturer's manual.

## 1. Printer overview

Our H2D is an enclosed FDM 3D printer with dual-nozzle capability and an AMS 2 Pro filament handling system. Record the exact installed configuration in [Getting started](./Getting%20Started.md).

## 2. Safety and preparation

- Keep the print area clear and place the printer on a stable surface.
- Hot nozzles and build plates can cause burns; allow components to cool before handling.
- Follow manufacturer guidance for material-specific ventilation and enclosure settings.
- Never reach into the moving mechanism during printing.
- Stop printing if unusual sounds, collisions, smoke or persistent errors occur.

## 3. First-time setup

Follow the official H2D unboxing/setup guide, remove shipping restraints, complete initial on-screen calibration, then configure Bambu Studio with the correct H2D/nozzle/plate combination. See [Getting started](./Getting%20Started.md).

## 4. Preparing a model

1. Open Bambu Studio and select the correct H2D profile.
2. Import STL or 3MF and verify dimensions and orientation.
3. Select the installed build plate and filament profiles.
4. For multicolour or multimaterial work, check AMS assignments and nozzle/material mapping.
5. Set supports and infill for the part's purpose.
6. Slice and review the preview, especially the first layer.

## 5. Starting and monitoring a print

1. Confirm the printer is idle and the print area is clear.
2. Send the sliced job to the intended H2D.
3. Verify plate, nozzle and filament mappings in the print confirmation.
4. Monitor the first layer; stop if extrusion or adhesion is incorrect.
5. After completion, wait for safe cooldown before removing the part.

## 6. Filament and AMS 2 Pro

Check that each spool is compatible with the AMS and material profile. Confirm the correct slot, material and colour in Bambu Studio. Use the current AMS 2 Pro guide for loading, drying and feed-path maintenance. Do not assume every filament is AMS-compatible.

## 7. Dual-nozzle printing

Assign materials to the intended nozzles, check the sliced tool-change preview and confirm the printer's actual nozzle sizes match the profile. For the first test, use a simple single-material job before trying a two-material target.

## 8. Routine maintenance

See [Maintenance](./Maintenance.md). Follow official H2D-specific lubrication, cleaning and replacement intervals; do not reuse the CreatBot procedures.

## 9. Troubleshooting

Record the exact error code and relevant configuration. Start with [Troubleshooting](./Troubleshooting.md), then consult the manufacturer's model-specific article.

## 10. Official documentation and example references

- [Bambu Lab Wiki — manufacturer knowledge base](https://wiki.bambulab.com/)
- [Bambu Lab support — documentation and assistance](https://bambulab.com/en/support)
- [Bambu Studio — official slicer project](https://github.com/bambulab/BambuStudio)

**Image policy:** Use links to official manufacturer images, diagrams and example articles. Do not copy manufacturer-owned images into this repository without confirming reuse permission and attribution requirements. Add our own photos later as available.

## 11. Local operating records

Record firmware version, Bambu Studio version, nozzle types/sizes, plate type, AMS configuration, material and print outcomes in the relevant sections.
