The |MESSAGEix| framework
=========================

.. figure:: _static/ix_features.png
   :width: 320px
   :align: right

   The |ixmp| (source: :cite:`huppmann_messageix_2018`)

Overview and scope
------------------

|MESSAGEix| is a versatile, open-source, dynamic systems-optimization modelling framework.
It was developed for strategic energy planning and integrated assessment of energy-engineering-economy-environment systems (E4).
The framework can be applied to analyse scenarios of the energy system transformation under technical-engineering constraints and political-societal considerations.
The optimization model can be linked to the general-economy MACRO model to incorporate feedback between prices and demand levels for energy and commodities.
The equations are implemented in the mathematical programming system `GAMS`_ for numerical solution of a model instance.

The |MESSAGEix| framework is fully integrated with |IIASAabbr|'s |ixmp| (ixmp), a data warehouse for high-powered numerical scenario analysis.
The platform supports an efficient workflow between original input data sources, the implementation of the mathematical model formulation, and the analysis of numerical results.
The platform can be accessed via a web-based user interface and application programming interfaces (API) to the scientific programming languages Python and R.
The platform also includes a generic data exchange API to `GAMS`_ for numerical computation.

This documentation provides an introduction and the mathematical formulation of the |MESSAGEix| equations and auxiliary functions.
For the scientific reference of the framework, see Huppmann et al. (2019) :cite:`huppmann_messageix_2018`.
The formulation of |MESSAGEix| is a re-implementation and extension of `'MESSAGE V'` (Messner and Strubegger, 1995 :cite:`messner_users_1995`), the Integrated Assessment model developed at the International Institute for Applied Systems Analysis (IIASA) since the 1980s.
For an overview of the |MESSAGEix| model used at the IIASA Energy Program and a list of recent publications, please refer to the `MESSAGE-GLOBIOM documentation website`_.


Getting Started
---------------

.. toctree::
   :maxdepth: 2

   getting_started
   tutorials

.. _help:

Have a question? First, check the :doc:`faq`, then try the community Google group:

- on the Web at https://groups.google.com/d/forum/message_ix, or
- via e-mail at <message_ix@googlegroups.com>.

Detailed documentation
----------------------

.. toctree::
   :maxdepth: 3

   framework
   api
   core
   guide


Using and contributing to |MESSAGEix|
-------------------------------------

|MESSAGEix| and the |ixmp| are licensed under the `APACHE 2.0 open-source license`_.

Anyone is encouraged to use the framework to develop energy system and integrated assessment models! Please see the :doc:`notice` for using the framework in scientific research. Contributions to the framework itself, which enable new features across all models, are also welcome.

.. toctree::
   :maxdepth: 1

   whatsnew
   notice
   contributing

.. toctree::
   :hidden:

   faq

.. toctree::
   :maxdepth: 2

   bibliography

.. _`GAMS`: http://www.gams.com
.. _`MESSAGE-GLOBIOM documentation website`: http://data.ene.iiasa.ac.at/message-globiom/
.. _`APACHE 2.0 open-source license`: https://github.com/iiasa/message_ix/blob/master/LICENSE
.. |IIASAabbr| raw:: html

   <abbr title="International Institute for Applied Systems Analysis">IIASA</abbr>
