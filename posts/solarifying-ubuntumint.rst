.. title: Solarifying Ubuntu/Mint
.. slug: solarifying-temp
.. date: 2015-02-07 21:36:02 UTC+01:00
.. tags: draft, debian, ubuntu, linuxmint, solar, pv sandia, usa, research, python, packaging, pythonxy, 
.. category: 
.. link: 
.. description: 
.. type: text

Similar as the rest of the 


https://github.com/Sandia-Labs/PVLIB_Python/pull/39#event-235878712
on 

Sat, 14 Feb 2015 

python-pvlib 

[pvlib - 0.3.0~ppa3~revno-81~ubuntu15.04.1](https://code.launchpad.net/~pythonxy/+archive/ubuntu/pythonxy-devel/+sourcepub/4779140/+listing-archive-extra)

What's left now to have a set of useful packages?

Here's a small list:

* PyEphem

  * `astronomy library for Python <http://rhodesmill.org/pyephem/>`_
  * used by PVlib in `pvlib.solarposition.pyephem <http://wholmgren-pvlib-python.readthedocs.org/en/develop/pvlib.html?highlight=pyephem#pvlib.solarposition.pyephem>`_
  * upstream code `is being imported <https://code.launchpad.net/~dacoex/pythonxy-upstream/pyephem>`_

* `pingswept / pysolar <https://github.com/pingswept/pysolar>`_
* `pvwatts <https://github.com/breuckelen/pvwatts>`_
* `kshmirko / pysolar-py3 <https://github.com/kshmirko/pysolar-py3>`_
* `mpaolino / pypvwatts <https://github.com/mpaolino/pypvwatts>`_
* `nrcharles / solpy <https://github.com/nrcharles/solpy>`_


And what could be done next?

* Comapring the results of the different implementations of algorithms
* add :climate: data packages

 * `tchubb / SkewT <https://github.com/tchubb/SkewT>`_: A python/matplotlib package to do basic atmospheric profile plots 
 * `nrcharles / caelum <https://github.com/nrcharles/caelum>`_: python library wrapper for various typical historical weather sources
 * `xray/ xray <https://github.com/xray/xray>`_ : N-D labeled arrays and datasets in Python 
 
