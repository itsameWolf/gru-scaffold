# Printing instructions

This directory contains all the .stl file required to assemble GRU. They are separated into multiple folders to help with organisation. Each file specifies the quantity to be printed in its name to avoid confusion.

Most components have been printed using PC, with at least 4 perimeter walls and 30% infill at a 0.2mm layer height. All files are oriented optimally.
PC could be replaced with PLA for all parts excepts the motor mounts which could be printed in ABS/ASA as the motor are run hot. PLA should work better because of its rigidity but fiber filled ABS/ASA could be rigid enough. **These substitutions have not been tested**

## Special settings

All files marked with [*] require some additional setting or considerations covered below.

| File | Instructions |
| ---- | ------------ |
| belt_reducer_frame[*].stl | This part has been printed using SLA as there is no optimal orientation for FDM |
| bushing_cap[*].stl | Needs to be printed at a 100% infill |
| combo_bushing_pulley[*].stl | This part been printed using SLA for the better dimensional accuracy and smoother surface, but FDM will work too with a lot of sanding and grease |
| fan_duct[*].stl | This part has been printed using SLA due to the thin and tall geometry, but FDM should work too on a well tuned machine with use of supports |
| toolhead[*].stl | This part requires support from build platform only |
