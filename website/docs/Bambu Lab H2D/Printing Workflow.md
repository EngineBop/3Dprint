---
sidebar_position: 3
---

# Printing workflow

## Standard workflow

1. **Prepare the model.** Obtain or export a valid STL or 3MF file. Confirm units, geometry and desired orientation.
2. **Open Bambu Studio.** Select the correct H2D printer and nozzle configuration.
3. **Select materials.** Match filament type and spool assignments to the printer/AMS. Dry moisture-sensitive filament when required by the manufacturer's guidance.
4. **Set print parameters.** Confirm build plate, layer height, wall count, infill, supports and any project-specific tolerances.
5. **For dual-nozzle prints:** assign materials or support interfaces to the intended nozzle, and check the sliced preview for tool changes and material usage.
6. **Slice and inspect.** Review the preview for unsupported regions, collisions, first-layer coverage, print time and filament consumption.
7. **Send the job.** Choose the intended printer and verify the actual plate and loaded filament before starting.
8. **Monitor the first layer.** Stop the print if there is poor adhesion, unexpected extrusion or interference.
9. **Finish safely.** Allow the plate and part to cool appropriately before removal. Record unusual behaviour.

## Before clicking Print

- [ ] Correct printer and nozzle profile
- [ ] Correct filament type and slot assignment
- [ ] Correct plate selected in software and installed in printer
- [ ] Supports, orientation and clearances reviewed
- [ ] Sliced preview checked
- [ ] Print area clear

## GIS and terrain models

For DEM-to-STL workflows, check horizontal/vertical units, exaggeration, mesh watertightness and final scale before slicing. Existing CreatBot DEM-to-STL notes may provide background, but use H2D-specific slicing profiles.
