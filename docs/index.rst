..
  .. image:: graphics/tardis_logo.jpg

.. the "raw" directive below is used to hide the title in favor of just the logo being visible
.. .. raw:: html

..    <style media="screen" type="text/css">
..      h1 { display:none; }
..    </style>

##################################
TARDIS Core Package Documentation
##################################

.. image:: graphics/tardis_banner.svg

|

TARDIS is an open-source Monte Carlo radiative-transfer spectral synthesis code
for 1D models of supernova ejecta. It is designed for rapid spectral modelling
of supernovae. It is developed and maintained by a :ref:`multi-disciplinary team <team>`
including software engineers, computer scientists, statisticians,
and astrophysicists.

If you use this code for any publications or presentations please follow our
citation guidelines in :ref:`tardiscredits`.

User modifications and additions that lead to publications **need to be handed
back to the community** by incorporating them into TARDIS.
Please contact the TARDIS team via the `GitHub page
<https://github.com/tardis-sn/tardis>`_ if you have questions or need
assistance.

-----------------
Mission Statement
-----------------

    *The mission of the TARDIS community is to develop open-source software 
    instruments to analyze and simulate astronomical transients 
    (supernovae, kilonovae, etc.) for research and education purposes. 
    We aim to build up a diverse group of researchers and developers 
    using an open-community model that emphasizes interdisciplinary 
    research and science reproducibility.*



.. toctree::
    :maxdepth: 2
    :hidden:

    installation
    quickstart/quickstart
    tutorials
    API <api/modules>


.. toctree::
    :maxdepth: 3
    :caption: Input/Output
    :hidden:
    
    io/configuration/index
    io/optional/index
    io/visualization/index
    io/output/index
    io/grid/TardisGridTutorial

.. toctree::
    :maxdepth: 2
    :caption: Physics Walkthrough
    :hidden:
    
    physics/setup/index
    physics/montecarlo/index
    physics/est_and_conv/index
    physics/spectrum/index


.. toctree::
    :maxdepth: 2
    :caption: Research with TARDIS
    :hidden:

    Overview <research/index>


.. toctree::
    :maxdepth: 2
    :caption: Team & Credits
    :hidden:

    team_and_governance/index
    credits
    Code of Conduct <CODE_OF_CONDUCT.md>
    sponsors


.. toctree::
    :maxdepth: 2
    :caption: Contributing to TARDIS
    :hidden:

    CONTRIBUTING.md
    development/index
    CHANGELOG.md
    roadmap


.. toctree::
    :caption: References
    :hidden:

    zreferences


.. toctree::
    :maxdepth: 2
    :caption: Outdated
    :hidden:

    outdated/index

----
News
----

.. include:: news.rst
