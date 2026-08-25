# Appendix A: Participant-by-participant OC6 comparisons

This repository contains the participant-by-participant OC6 comparison figures used as Appendix A of the manuscript. The PDF files are organized by load case and numbered consecutively as Figure A1–A12.

## Presentation convention

- The OpenFAST–Abaqus framework response is shown in black.
- The corresponding OC6 participant or OpenFAST–FounDyn comparison is drawn in color above the black reference curve.
- The original OC6 participant database.
- OpenFAST with FounDyn (after Wang and Ishihara, 2022)`.

## Load cases and figure index

### LC3.1 — Wind only

- Figure A1: Tower-top fore–aft displacement
- Figure A2: Tower-top fore–aft acceleration
- Figure A3: Mudline fore–aft displacement
- Figure A4: Mudline rotation about the global y-axis

### LC4.2 — Wave only

- Figure A5: Tower-top fore–aft displacement
- Figure A6: Tower-top fore–aft acceleration
- Figure A7: Mudline fore–aft displacement
- Figure A8: Mudline rotation about the global y-axis

### LC5.1 — Wind and wave

- Figure A9: Tower-top fore–aft displacement
- Figure A10: Tower-top fore–aft acceleration
- Figure A11: Mudline fore–aft displacement
- Figure A12: Mudline rotation about the global y-axis

## Repository structure

```text
Load_cases/
├── LC3.1_Wind-only/
├── LC4.2_Wave-only/
└── LC5.1_Wind-and-wave/
```

Each load-case directory contains four publication-ready PDF figures. The filenames are ASCII-only, sortable, and map one-to-one to the Appendix A figure numbers listed above.
