VERSIONS
========

Rev1: initial layout, otherwise known as "I HAVE NO IDEA WHAT I'M DOING"

Note: rev1 was not correctly committed/tagged and some rev2 features are
included in the rev1 tag.

Rev2: Incremental improvements to rev1

Mounting hole footprints switched from incorrect custom footprints to KiCAD
standard footprints.

TODO:

  * Increase signal trace width to 15-20 mils
  * Reduce signal trace clearance to 5-10 mils
  * Increase VCC trace width to 50 mils
  * Reduce VCC trace clearance to ~10 mils
  * Compact traces to AUX header
  * properly match capacitor footprints with parts
  * Maybe - Select power header with more clearance between pins - Mini Fit jr?
  * Move part silk screen labels off of traces for clarity
  * Compact signal impedance matching resistors
  * Build/use footprints for locking headers
  * Redo 74HCT245 footprint for directionality
  * Redo Teensy footprint for directionality
  * Bottom silk screen labels for octo pins on Teensy

NOTE: OSH Park 2 layer boards are less precise than 4 layer boards.

  * Trace clearance: 6 mils
  * Trace width: 6 mils
  * Drill size: 13 mils
  * Annular rings: 7 mils

RevX: First SMT revision. Exact date TBD, but after THT boards don't suck.

TODO:

  * SMT resistors/capacitors
  * SMT 74HCT245
  * Shrink the PCB layout as much as is reasonable
