.. role:: cpp(code)
   :language: c++



The Problem
===========


.. _fig:

.. figure:: ./Particle/particle_arrays.png

   Using ``cpp:`` like this, :cpp:`NStructReal = 1`, with
   ``make latexpdf`` causes an error in the pdf construction
   process. In particular, it seems its is trying to free a
   macro defined for the pigment, however the pigment macro
   is undefined and therefore leades to an error.

