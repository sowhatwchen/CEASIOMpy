.. figure:: ../../CEASIOMpy_square_mission.png
    :width: 180 px
    :align: right
    :alt: CEASIOMpy mission


StabilityStatic
===============

:Categories: Mission analysis, Stability

This module is made to check the static stability of an aircraft along longitudinal, lateral and directional axis.


Installation
------------

StabilityStatic is a native |name| module, hence it is available and installed by default.

Analyses
--------

StabilityStatic checks static stabilities in the tree main directions: longitudinal, lateral and directional. For each one, it writes in the CPACS file if the aircraft is stable of not (or not calculated). If stable, it also returns the value of the trim conditions.

Output
------

A lot of graphs are produced and saved in /ToolOutput.

Required CPACS input and settings
---------------------------------

The CPACS must contain an aeroMap. The aeroMap must contain at least a few points to calculate stability (several angles of attack for longitudinal and several angles of sideslip for lateral and directional).

Limitations
-----------

Calculation of the trim conditions with deflected control surface is not automated yet.

More information
----------------

* Loïc thesis link...
