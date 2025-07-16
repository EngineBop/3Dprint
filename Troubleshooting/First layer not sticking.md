## Manual Calibration with BLTouch Sensor (Marlin Firmware) – Dual Nozzle Printer

1. **Home the Printer**
   - Use the control panel or send `G28` to home all axes.

2. **Auto Bed Leveling**
   - Run `G29` to start the auto bed leveling process with the BLTouch sensor.

3. **Set Z-Offset for Each Nozzle**
   - Select the first nozzle (usually `T0`), move it close to the bed, and use a piece of paper to check the gap.
   - Adjust the Z-offset for the first nozzle (`M851 Z<value>`), then store with `M500`.
   - Switch to the second nozzle (`T1`), repeat the process, and set its Z-offset if supported (`M851 Z<value>` or use nozzle offset settings in firmware).
   - Save all settings with `M500`.

4. **Test First Layer for Both Nozzles**
   - Start a dual extrusion test print.
   - Observe the first layer from both nozzles.
   - Fine-tune Z-offsets or nozzle offsets as needed using the printer controls or updated commands.

5. **Save Settings**
   - After adjustments, save settings with `M500` to retain calibration.

**Tips:**
- Ensure both nozzles are clean and at the same height.
- Repeat calibration if you change the bed surface, nozzle, or perform maintenance.
- Check firmware documentation for dual nozzle offset commands if needed.

This process helps ensure both nozzles produce a consistent first layer and improves print adhesion for dual extrusion prints.