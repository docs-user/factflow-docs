Welcome to the FactFlow documentation
===================================

**FactFlow** is a process simulation program that is an **Add-on** to the **FactSage** thermochemical software and database package. It is directed to users who are very familiar with **Equilib** and who wish to perform a large series of equilibrium calculations that are connected via streams. **FactFlow** is primarily developed to **simplify the use of streams and equilibrium reactors** via an easy-to-use graphical interface or **flowsheet**. 

**FactFlow** accesses the **FactSage** databases (.cst files) and the user defines the initial conditions including compositions and amounts of the individual streams. When calculating, **FactFlow** employs the same chemical equilibrium calculation algorithms as in **Equilib**.

.. image:: FactFlow.png
   :alt: FactFlow
   :align: center


Check out the :doc:`getting-started` section for a quick start guide, :doc:`nodes` for more detailed explanations on what each Node does, and :ref:`analysis` for a guide on how to calculate equilibrium over a range of values.


.. note::

   The documentation for this project is under active development.

Contents
--------

.. toctree::

   getting-started
   .. toctree::
   nodes
   analysis
