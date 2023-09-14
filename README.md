effective-coffee-spoon
======================

Brief
-----

KiCad microcontrollers library


Repository content
------------------

This repository is dedicated to my personnal components symbols and footprints
for KiCad. Care has been taken to respect [KiCad design rules](https://klc.kicad.org/#_general_library_guidelines)
so they may be elligible to _KiCad library_ integration or, at least, be
eligible to be distributed as an officially registered [addon / plugin](https://dev-docs.kicad.org/en/addons/).


Specific aspects of this library
--------------------------------

This library uses some additionnal specific conventions that are my own for
now. They may change if any pull request to the KiCad stardard library or
addons would be accepted. These conventions are the following :
  - `snake_case` is prefered for names (file and lib names).
  - _KiCad 6_ is the version used for the library design. Since this version
    has an easy going compatibility with _KiCad 7_ and _KiCad 8_ nightly
    builds.
  - All manufacturer part number (MPN) and supplier part numper (SPN) are
    provided.

Repository tree
---------------

```
effective-coffee-spoon/
  |
  +-> symbols/
  |     +-> mcu_verbose.kicad_sym
  +-> footprints/
  |     +-> mcu_verbose.pretty/
  |           +-> foo-footprint.kicad_mod
  |           +-> bar-footprint.kicad_mod
  |           +-> ...
  +-> 3dmodels/
  |     +-> mcu_verbose.3dshapes/
  |           +-> foo-model.stp
  |           +-> foo-model.wrl
  |           +-> ...
  +-> LICENSE
  +-> README.md
  +-> .gitignore
```

LICENSE
-------

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.