# JLCPCB-Parts-to-KiCad-Library
Shared library for JLCPCB parts to KiCad

First install JLC2KiCadLib with the following command line:

pip install JLC2KiCadLib

Use the following command to add symbols, footprints and 3d models to the library:

```JLC2KiCadLib [PART_NUMBER] -dir "Path/To/JLC_Library" -symbol_lib JLC_PARTS -footprint_lib JLC_PARTS```

Example:

```JLC2KiCadLib C3151659 -dir "C:\Users\name\Documents\KiCad\JLCPCB-Parts-to-KiCad-Library" -symbol_lib JLC_PARTS -footprint_lib JLC_PARTS```

Remember to always pull before adding parts and push after adding
