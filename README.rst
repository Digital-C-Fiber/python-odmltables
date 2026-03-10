odMLtables (Extended Version)
=============================

An interface to convert odML structures to and from table-like representations, such as spreadsheets.

This repository is a fork of the original odMLtables project:
https://github.com/INM-6/python-odmltables

It extends the original functionality with additional graphical user interface tools to facilitate metadata exploration and search.

odMLtables provides a set of functions to simplify the setup, maintenance and usage of a metadata management structure using odML. In addition to the Python API, odMLtables provides its main functionality via a graphical user interface.

New Features in this Fork
-------------------------

Search Wizard
^^^^^^^^^^^^^

This fork introduces a graphical **Search Wizard** that allows users to search metadata stored in odML files more efficiently.

The wizard enables users to:

- Search for specific words within metadata entries
- Search for **property–value pairs**

This functionality is intended to simplify metadata findability and exploration when working with experimental datasets.

Microneurography Metadata Workflow
----------------------------------

The modifications in this fork were developed in the context of building a metadata management workflow for **microneurography recordings**.

The **metadata templates**, **workflow description**, and **user manual** for this application are maintained in a separate repository:

Repository for microneurography metadata workflow and templates:  
https://github.com/Digital-C-Fiber/odMLtablesForMNG

Dependencies
------------

odMLtables is based on **odML**. A complete list of dependencies is available in the odMLtables documentation at Read the Docs.

Installation
------------

Since this version is not released on the Python Package Index (PyPI), it must be installed directly from this GitHub repository.

Install the latest version using pip:

.. code-block:: bash

    pip install git+https://github.com/YOUR-USERNAME/python-odmltables.git

To install with graphical user interface support:

.. code-block:: bash

    pip install git+https://github.com/YOUR-USERNAME/python-odmltables.git#egg=odmltables[gui]

Alternatively, clone the repository and install locally:

.. code-block:: bash

    git clone https://github.com/YOUR-USERNAME/python-odmltables.git
    cd python-odmltables
    pip install .

To install with GUI support locally:

.. code-block:: bash

    pip install .[gui]

Documentation
-------------

The odMLtables documentation is available on **Read the Docs**.

It is based on **Sphinx** and can also be built locally. To build the HTML documentation:

.. code-block:: bash

    cd doc
    make html

The generated documentation will be available in:

.. code-block:: bash

    doc/_build/html/index.html

All available output formats can be listed using:

.. code-block:: bash

    make -n

Original Project
----------------

This repository is based on the original odMLtables project developed at:

INM-6, Forschungszentrum Jülich

Original repository:
https://github.com/INM-6/python-odmltables

If you use odMLtables in scientific work, please cite the original project accordingly.

The extensions implemented in this fork were developed in the context of microneurography data analysis and metadata management. A scientific publication describing the related methodology and application is available:

Troglio A, Nickerson A, Schlebusch F, Röhrig R, Dunham J, Namer B, Kutafina E. odML-Tables as a Metadata Standard in Microneurography. Stud Health Technol Inform. 2023 Sep 12;307:3-11. doi: 10.3233/SHTI230687. PMID: 37697832.
https://pubmed.ncbi.nlm.nih.gov/37697832/

Bugs and Issues
---------------

If you observe a bug or encounter issues, please report them via the GitHub issue tracker of this repository.

License
-------

This project follows the same license as the original odMLtables project. Please refer to the LICENSE file for details.

Contact
-------

Email: alina.troglio@rwth-aachen.de
