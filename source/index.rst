===========================
Open Canteens Specification
===========================

   Good food and good company are two of life's simplest yet greatest pleasures.

   -- unknown


As stated in this quote, we also think that good food is key for living a good life - no matter if it is for performing well in your career or gathering great experiences in your free time with friends.
Thus, we want to support canteens fulfilling this job.
This API specification shall enable a common interface for the canteens IT environment and (internal as well as external) applications.





History and Alternatives
------------------------

This specification is based on the `Open Food Data <https://github.com/studierendenwerk-ulm/open-food-data>`__ specification, which aimed to provide a general API for campus canteens at universities. 
The `Open Food Data <https://github.com/studierendenwerk-ulm/open-food-data>`__ specification was designed in a general way, so that it can also be applied at company canteens and potentially at common canteens.

Furthermore, there is the `Open Mensa <https://openmensa.org/>`__ project. The project is started by open data enthusiasts and provides a central database and a standardized format for data exchange related to canteen relevant information.

However, both specification come with several drawbacks which shall be covered by this project. For example, both projects focus on Germany. To simplify the comparison between the APIs, we plan to provide a feature comparison in future.

**Please note:** Thanks to the great work of both teams, we are able to extend and improve their specifications and can start ahead of certain fundamentals. Further, we will use the icons provided by the `Open Food Data <https://github.com/studierendenwerk-ulm/open-food-data>`__ specification.

.. toctree::
   :maxdepth: 1
   :hidden:

   model
   features
   api
   
   alternatives


Goals and Purposes
==================


Use Case
========

*To be announced*


The model
=========

In this chapter, you will find a sketch of an UML database model of this specification:

.. uml:: assets/plantuml/database_model.uml
   :width: 600
   :align: center
