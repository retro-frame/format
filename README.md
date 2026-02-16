# Retro-Frame Data Format Specifications

**Endeavor: Retro-Frame**  
**Repository: \<[http://source.retro-frame.net/format](http://source.retro-frame.net/format)\>**  
**Version: 1.0!1 (alpha, dev)**  
**Compliance: Retro-Frame 1.0**  
**License: MIT (see `LICENSE`)**  

Copyright (c) 2026 Ingo Boehmer \<ingo@retro-leisure.net\>

All product names, logos, and brands are property of their respective owners.


## Contents

1. Overview

2. General data format documentation

3. Data format specifications

4. References


## 1. Overview

Beside execution environments and character encodings, data formats play an
important role in retro programming (e.g. when dealing with files or network
protocols).

On the one hand, standardized or vendor-specific data formats (external
formats) may be used in a program. On the other hand, additional data formats
may be invented by a Retro-Endeavor for its own use (internal formats). The
intention of this repository is to provide specifications of internal formats
as well as of external formats where no, incomplete or poor specifications are
publicly available.

**Retro-Frame** is a Retro-Endeavor that provides common documentation (i.e.
definitions, guidelines, templates and generic specifications) as well as
topic-related specifications (covered by individual repositories like this
one related to data format specifications) which are intended for use in
retrospective programming and may be used as a whole or partially for other
purposes.

* The **Retro-Frame Common Documentation** repository provides common
  definitions, guidelines, templates and generic specifications.

* This repository is part of the ***Retro-Frame Specifications***. Subject to
  the ***Retro-Frame Data format Specifications*** are binary and text data
  formats which may be implemented by a program (e.g. as file formats) and may
  be used by other specifications.

Note that while this repository always has the same release version number as
the **Retro-Frame Common Documentation** repository which is complies to, the
individual data formats use a completely independent versioning scheme.


## 2. General data format documentation

The directory `doc/` is intended to contain general data format documentation:

* `doc/rf-format.txt` provides a list of all Retro-Frame data format
  specifications as well as general data format specifications and guidelines.


## 3. Data format specifications

The directory `spec/` contains data format specifications. Each data format has
a unique name which is the file name of the specification document, prefixed by
`rfdf-` and suffixed by `.txt`.

Currently, the following data format specification documents are provided:

* `spec/rfdf-aedc.txt` provides the specification of the Asymmetrically
  Encrypted Data Collection (AEDC) format.

* `spec/rfdf-asm.txt` provides the specification of the Assembler Code Selector
  ("ASM") format.

* `spec/rfdf-bin.txt` provides the specification of the Unspecified Binary
  (0001) format.

* `spec/rfdf-cp.txt` provides the specification of the Codepage (4350) format.

* `spec/rfdf-cpcode.txt` provides the specification of the Codepage Code
  ("CP-CODE") format.

* `spec/rfdf-cpspec.txt` provides the specification of the Codepage
  Specifications ("CP-SPEC") format.

* `spec/rfdf-pcs.txt` provides the specification of the Packed Character String
  Text (5043) format.

* `spec/rfdf-rfff.txt` provides the specification of the Retro-Frame Magic
  Prefix (5246 / "RFFF") format.

* `spec/rfdf-sym.txt` provides the specification of the Symbol Table ("SYM")
  format.

* `spec/rfdf-text.txt` provides the specification of the Unspecified Text
  ("TEXT") format.

* `spec/rfdf-vee2b.txt` provides the specification of the Virtual Execution
  Environment #2 Binary (EE2B) format.


## 4. References

### Retro-Frame

Retro-Frame homepage, see
\<[http://source.retro-frame.net/](http://source.retro-frame.net/)\>.

### Retro-Frame Common Documentation

Retro-Frame Common Documentation repository, see
\<[http://source.retro-frame.net/common](http://source.retro-frame.net/common)\>.
