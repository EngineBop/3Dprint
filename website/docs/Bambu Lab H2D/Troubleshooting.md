---
sidebar_position: 5
---

# Troubleshooting

Start with the **exact error message**, affected nozzle or AMS slot, filament type and recent changes. Photograph the fault where useful. Do not repeatedly restart a print without identifying the likely cause.

| Symptom | First checks | Next action |
| --- | --- | --- |
| First layer does not stick | Plate selection, cleanliness, filament profile, first-layer preview | Recheck setup and use the official adhesion guidance |
| No filament extrudes | Correct nozzle selected, filament loaded, reported error | Follow official nozzle/extruder diagnostics; cool before servicing |
| AMS feed or retraction error | Slot, spool movement, filament path, visible PTFE routing | Follow the AMS 2 Pro error-specific procedure |
| Poor surface quality or stringing | Filament moisture, temperature profile, speed, support settings | Test with a known-good material profile |
| Dual-nozzle colour/material issue | Nozzle assignments and sliced preview | Verify material-to-nozzle mapping and reslice |
| Printer reports calibration error | Exact code and stage of calibration | Stop and consult H2D-specific support instructions |

## Fault investigation template

1. **Symptom:** What happened, and at what point in the print?
2. **Evidence:** Error code, photographs, screenshots and logs.
3. **Environment:** Printer firmware, Bambu Studio version, filament, plate, nozzle and AMS slot.
4. **Checks performed:** Record each test and outcome in order.
5. **Root cause:** Confirmed or suspected; clearly distinguish the two.
6. **Resolution:** Steps performed, parts replaced and source of instructions.
7. **Verification:** Repeatable test showing the issue is resolved.

Create a new Markdown page for recurring or significant faults and link it from this page and the [fault log](./Fault%20Log.md).
