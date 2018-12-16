HZTideHeat
==========

Overview
--------

Surface energy flux on a terrestrial exoplanet in the habitable zone (HZ) due to tidal dissipation according the the eqtide-CPL
model from `vplanet <https://github.com/VirtualPlanetaryLaboratory/vplanet>`_.

===================   ============
**Date**              12/15/18
**Author**            Rory Barnes
**Modules**           eqtide
**Approx. runtime**   3 minutes
**Source code**       `vplanet <https://github.com/VirtualPlanetaryLaboratory/vplanet>`_
===================   ============

This example calculates the surface energy flux on a terrestrial exoplanet that is tidally locked and 
has an eccentricity of 0.05. It requires `vplanet` and it supporting software package `vspace`. 


To run this example
-------------------

.. code-block:: bash

   vspace vspace.in
   python makeplot.py <pdf | png>


Expected output
---------------

.. figure:: HZTideHeat.png
   :width: 600px
   :align: center

Contour plot of surface tidal heat flux of a terrestrial a 1 Earth-mass, 1 Earth-radius 
exoplanet with a tidal Q of 12 and and eccentricity of 0.05. Contour units are W/m^2.
