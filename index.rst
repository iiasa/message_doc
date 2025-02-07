MESSAGEix-GLOBIOM documentation
===============================

.. important::

   This repository from which these pages are built is no longer maintained or updated.
   As of 2024-04-19, the documentation of the MESSAGEix-GLOBIOM global model is included within the documentation of the ``message-ix-models`` package, at https://docs.messageix.org/projects/models/en/latest/global, and edited to align with the code in that package.

   Old links to the current URL or other URLs beginning with https://docs.messageix.org/global or https://docs.messageix.org/projects/global should be updated to point to the new location.

These pages document the IIASA Integrated Assessment Modeling (IAM) framework, also referred to as |MESSAGEix|-GLOBIOM, owing to the fact that the energy model |MESSAGEix| and the land use model GLOBIOM are its most important components.
|MESSAGEix|-GLOBIOM was developed for the quantification of the so-called Shared Socio-economic Pathways (SSPs) which are the first application of the IAM framework.

When referring to |MESSAGEix|-GLOBIOM as described in this document, please use the following citations: [1]_

.. bibliography::
   :list: bullet
   :style: unsrt
   :filter: key in {"message_globiom_2020", "fricko_havlik_2017"}

.. [1] Download these citations in :download:`RIS </bibs/messageix-globiom.ris>` or :download:`BibTeX </bibs/messageix-globiom.bib>` format (web only).

The |MESSAGEix|-GLOBIOM Integrated Assessment Model is based on the |MESSAGEix| framework, an open-source energy systems optimization modelling environment including macro-economic feedback using a stylized computable general equilibrium model.
When referring to the software underpinning |MESSAGEix|-GLOBIOM rather than the data or specific assessments, please see the :ref:`“User guidelines and notice” section <message_ix:notice-cite>` of the documentation, which indicates to use at least the following citation:

.. bibliography::
   :list: bullet
   :style: unsrt
   :filter: key == "huppmann_2019_messageix" and not cited

We thank Edward Byers, Jessica Jewell, Ruslana Palatnik, Narasimha D. Rao, and Fabio Sferra for their valuable comments that helped improving this manuscript.

.. toctree::
   :maxdepth: 1

   overview/index
   socio_econ/index
   energy/index
   macro
   land_use/index
   water/index
   emissions/index
   climate/index
   annex/index
   further-reading
   z_bibliography

.. Under development; excluded.
   See also the exclude_patterns setting in conf.py.

   glossary

.. Leave these lines commented for releases; uncommented during development/on
   `master`.

   .. toctree::
      :hidden:

      _extra/index
