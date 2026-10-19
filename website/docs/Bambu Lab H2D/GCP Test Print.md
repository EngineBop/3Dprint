---
sidebar_position: 4
title: GCP Target Test Print
---

# Drone training — Ground Control Point target test print

## Goal

Produce a sample ground control point (GCP) target plate for a drone-training demonstration. A printed demonstration plate is not automatically suitable for survey use: target size, contrast, visibility, durability and centre definition must be validated for the intended flight height and imagery.

## Before printing

- [ ] Locate or create the GCP plate STL/3MF model
- [ ] Verify overall dimensions and centre marker geometry
- [ ] Confirm the H2D has completed setup and calibration
- [ ] Confirm installed plate, nozzle sizes and loaded filament
- [ ] Select the matching printer and material profiles in Bambu Studio

## First test print

1. Import the GCP model into Bambu Studio.
2. Verify millimetre dimensions and orient the plate flat.
3. Choose a known-good filament profile (PLA is a reasonable first trial if loaded and compatible).
4. For a single-colour trial, use one nozzle; for a two-colour design, confirm material-to-nozzle assignments and preview the colour boundaries.
5. Slice, review the first layer and estimated duration, then send the print to the H2D.
6. Observe the first layer. Stop if adhesion or extrusion is wrong.
7. Let the plate cool, remove the part and inspect geometry, legibility and flatness.

## Test record

| Field | Record |
| --- | --- |
| Model file and version | |
| Target dimensions | |
| Filament(s) and AMS slots | |
| Nozzle(s) and plate | |
| Layer height / infill | |
| Slicer estimate / actual duration | |
| First-layer result | |
| Print quality / corrective actions | |

## Next steps

If the test succeeds, duplicate or arrange multiple models in Bambu Studio and reslice, checking clearance and estimated completion time. If printing a field-use GCP, confirm target visibility and survey requirements separately.
