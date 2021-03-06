.. solar-python documentation master file, created by
   sphinx-quickstart on Tue Mar  9 13:17:21 2021.

.. figure:: graphics/cover_photo_shaded.png

Solar Resource Assessment in Python
===================================

AssessingSolar is a practical guide to solar ressource assessment in Python, aiming make it easy to obtain solar radiation data, apply radiation models, and forecasting methods. The development of this guide is a collaborative effort within the International Energy Agency Photovoltaic Power Systems Programme Task 16 `(IEA PVPS Task 16) <https://www.iea-pvps.org/research-tasks/solar-resource-for-high-penetration-and-large-scale-applications/contacts_t16/>`_.

The guide aims to cover a wide range of topics including solar radiation modelling, data quality assessment, and how to obtain and manipulate solar data. Contrary to traditional textbooks or scientific dissemination, this guide presents a general introduction of the topics along with documented how-to examples using Python code. This is achieved by using Jupyter Notebooks, which permits a seamless integration of a explanatory text, code examples, figures, mathematical equations, and references. The Python programming language was chosen as it is open-source, easy to learn and the primary choice for the majority of `open-source solar and PV libraries <https://openpvtools.readthedocs.io>`_, including `pvlib python <https://pvlib-python.readthedocs.io/en/stable/>`_, which will be used extensively in this guide.


How to contribute
~~~~~~~~~~~~~~~~~
We happily welcome contributions! You can either make a pull requests, open an issue, or write to arajen@byg.dtu.dk with any comments or suggestions.


Table of contents
~~~~~~~~~~~~~~~~~

.. toctree::
   :maxdepth: 2
   :caption: Solar radiation modeling

   notebooks/solar_components_and_geometry
   notebooks/solar_position
   notebooks/solar_radiation_modelling
   notebooks/manipulating_time_series

.. toctree::
   :maxdepth: 2
   :caption: Solar resource data

   notebooks/solar_resource_data_overview
   notebooks/satellite_data
   notebooks/reanalysis_data
   notebooks/ground_measurements
   notebooks/quality_asessment
   notebooks/benchmarking

.. toctree::
   :maxdepth: 2
   :caption: Forecasting


   notebooks/forecasting_overview
   notebooks/persistent_forecasting
   notebooks/satellite_forecasting


.. toctree::
   :maxdepth: 2
   :caption: Solar power modeling

   notebooks/solar_power_modelling

