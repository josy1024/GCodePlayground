# FailFast Examples

This directory contains examples of common 3D printing failures and issues to avoid.

some related to Filaments, some to Printer Settings

## PETG: Filament

Switch to EXPERT mode

* Volumentric speed ~19 - Max 21 - <https://help.prusa3d.com/de/article/maximale-volumengeschwindigkeit_127176>,

* Temp depend on Manufacturer (Layer, Bed)
* Cooling: 20-50%, No cooling for the first 4 layers

## Images

### [petg-stringing-too-fast.png](petg-stringing-too-fast.png)

Example of PETG printing with stringing issues caused by printing speed being too fast. This demonstrates the problem of insufficient retraction or excessive nozzle temperature relative to the printing speed. FIX: slow down

### [petg-too-low-temp-first-layers.png](petg-too-low-temp-first-layers.png)

Example of PETG printing with temperature issues in the first layers. The nozzle temperature was too low, resulting in poor layer adhesion and extrusion quality.
