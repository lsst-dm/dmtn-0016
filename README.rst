##########################################################################
DMTN-016 Towards LSE-63 and beyond: A technical roadmap from QA to Level 3
##########################################################################

A high-level description of SQuaRE's delivery plan

View this technote at http://dmtn-016.lsst.io or see a preview of the
current version in `this repo`_

.. _this repo: ./index.rst



..
  Uncomment this section and modify the DOI strings to include a Zenodo DOI badge in the README
  .. image:: https://zenodo.org/badge/doi/10.5281/zenodo.#####.svg
     :target: http://dx.doi.org/10.5281/zenodo.#####

Build this technical note
=========================

You can clone this repository and build the technote locally with `Sphinx`_

.. code-block:: bash

   git clone https://github.com/lsst-dm/dmtn-016
   cd dmtn-016
   pip install -r requirements.txt
   make html

The built technote is located at ``_build/html/index.html``.

Editing this technical note
===========================

You can edit the ``index.rst`` file, which is a reStructuredText document.
A good primer on reStructuredText is available at http://docs.lsst.codes/en/latest/development/docs/rst_styleguide.html

Remember that images and other types of assets should be stored in the ``_static/`` directory of this repository.
See ``_static/README.rst`` for more information.

The published technote at http://dmtn-016.lsst.io will be automatically rebuilt whenever you push your changes to the ``master`` branch on `GitHub <https://github.com/lsst-dm/dmtn-016>`_.

Updating metadata
=================

This technote's metadata is maintained in ``metadata.yaml``.
In this metadata you can edit the technote's title, authors, publication date, etc..
``metadata.yaml`` is self-documenting with inline comments.

****

Copyright 2016 AURA/LSST

This work is licensed under the Creative Commons Attribution 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/.

.. _Sphinx: http://sphinx-doc.org
