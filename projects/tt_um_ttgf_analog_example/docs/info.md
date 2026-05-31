<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This is a minimal demonstration of the Tiny Tapeout **gf180mcu analog** template
using a single power rail (VDPWR / VGND). The GDS and LEF in `gds/` and `lef/`
were produced from the gf180mcu analog DEF template with Magic, using the
`magic_init_project.tcl` flow. Analog pins `ua[0]` and `ua[1]` are wired to a
small piece of Metal4 so they register as used analog pins; the rest of the
design is just the standard Tiny Tapeout interface.

## How to test

There is nothing to drive digitally — this project only exists to exercise the
gf180mcu analog hardening + precheck flow. On silicon you would probe `ua[0]`
and `ua[1]`.

## External hardware

None.
