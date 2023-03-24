===================================
CircPrime: tool for circular RNA primer development
===================================

**CircPrime** is web-based platform, providing a user- friendly solution for DNA primer design and thermocycling conditions for circRNA identification with routine PCR methods.

.. image:: images/Figure_1.png

The user-friendly CircPrime tool for circular RNA primer development is written in Python 3 and implemented on a web-based platform. It is freely available online: http://circprime.elgene.net/. 

CircPrime generates FASTA files using circRNA coordinates and reference genome from the National Center for Biotechnology Information database (NCBI). Then CircPrime extracts junction regions  and develops primer sets with the recommended melting temperature (Tm) for each circRNA in the list (up to 100) using  `Primer3 <https://github.com/primer3-org/primer3>`_

.. image:: images/Figure_2.png

Check out the :doc:`Example usage` and :doc:`Parametrs` section for further information

Contents
--------

.. toctree::

   Example usage
   Parametrs
   api

.. note::

   This project is under active development.

Please cite CircPrime as follows:

Fedor Sharko, Golam Rbbani, Prabhugouda Siriyappagouder, Joost A.M. Raeymaekers, Jorge Galindo-Villegas, Artem Nedoluzhko, Jorge M.O. Fernandes: 
**"CircPrime: a web-based platform for design of specific circular RNA primers. BMC Bioinformatics.** 
Contact: Fedor Sharko (fedosic@gmail.com)
