# ispectrum

This repository contains a vendored copy of `ispectrum` version 1.1.

## Provenance and ownership

The `ispectrum` program itself is attributed in the bundled source and
documentation to Charles Carrano of Boston College, obtained from https://github.com/cu-sense-lab/gnss-scintillation-simulator/blob/master/matlab/Ispectrum/ispectrum-v1.1.zip.

The main bundled references are:

- `README.TXT`, which says the program was written by Charles Carrano
- `INSTALL-NOTES.txt`, which says "This is version 1.1 of ispectrum written by
  Charles Carrano, Boston College."
- `ispectrum.c`, whose file header also attributes the program to Charles
  Carrano

This copy also includes DE-quadrature integration code attributed to Takuya
Ooura. The bundled `README-OOURA.TXT` states:

- Copyright (C) 1996 Takuya OOURA
- The Ooura package may be used, copied, and modified without fee
- Distribution is permitted for the original package

In other words, this repository is not the original upstream home of the code.
It is a redistribution of software authored by Charles Carrano, and it also
contains numerical integration code from Takuya Ooura.

## Paper reference

The bundled documentation points readers to the following paper for the theory
behind `ispectrum`:

Carrano, C. S., and C. L. Rino (2016), "A theory of scintillation for
two-component power law irregularity spectra: Overview and numerical results,"
Radio Science, 51, 789-813.

DOI landing page:

https://doi.org/10.1002/2015RS005903

## Licensing note

This directory includes an explicit copyright and redistribution notice for the
bundled Ooura DE-quadrature package in `README-OOURA.TXT`.
