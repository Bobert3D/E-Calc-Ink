# E-Calc-Ink

E-Calc-Ink is a 30-key calculator hardware project. This repository currently contains component and assembly data for the hardware; the published bill of materials lists an OLED module, not an e-ink panel.

## What's Included

- [`Production/BOM_E-CALC-INK.csv`](Production/BOM_E-CALC-INK.csv): bill of materials, including quantities, references, footprints, and supplier part numbers where available.
- [`Production/PickAndPlace_E-CALC-INK.csv`](Production/PickAndPlace_E-CALC-INK.csv): component placement coordinates and rotation data for assembly. The file identifies components on the top layer.
- [`Production/E Calc Ink Jvjk v2 fixed final.zip`](Production/E%20Calc%20Ink%20Jvjk%20v2%20fixed%20final.zip): PCB manufacturing package containing Gerber layer files, drill files, and a PCB-order note.
- [`E-CALC-INK_PCB_DESIGN.epro2`](E-CALC-INK_PCB_DESIGN.epro2): EasyEDA Pro project archive containing the editable PCB document and project metadata.

The editable PCB design is included, but no separate schematic document, firmware, or device build instructions are currently present in the repository. The production package provides fabrication outputs for manufacturing.

## Why This Project

The production files make the hardware easier to source, fabricate, and assemble: the BOM records component quantities and supplier references, the Gerbers and drill files provide PCB fabrication data, and the pick-and-place file provides component placement coordinates and rotation data. The BOM lists 30 keyboard switches and 30 signal diodes for the key array.

## Getting Started

Open the CSVs in a spreadsheet application or text editor. Use EasyEDA Pro to open `E-CALC-INK_PCB_DESIGN.epro2` and inspect or edit the PCB design. Extract the ZIP archive to access its PCB fabrication package. Before ordering a board or parts, confirm that the design and production exports match the intended revision and assembly process. Some BOM fields, such as manufacturer or supplier part numbers, are blank.

## Maintainers and Contributing

The repository does not identify a current maintainer or provide a separate contribution guide. The MIT license names Cal as the copyright holder. Please open an issue or pull request in this repository to discuss a proposed change. Include enough context to review hardware changes and keep the PCB design, BOM, placement data, and fabrication outputs consistent. Include updated design and production files with hardware changes.

## Support

Use the repository's GitHub Issues for questions or to report a problem. There is no separate project documentation or support channel included at this time.

## License

This repository is licensed under the [MIT License](LICENSE).