.. Popper documentation master file, created by
   sphinx-quickstart on Sun Mar 27 19:41:28 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.


Welcome to Popper's documentation!
==================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

.. automodapi:: popper.asp
   :skip: Grounding, ConstVar, OrderedDict, Function, Number, Tuple_

.. automodapi:: popper.constrain
   :skip: defaultdict, ConstVar, Literal, Clause, Constrain

.. automodapi:: popper.core
   :skip: namedtuple, defaultdict, Grounding, ConstVar

.. automodapi:: popper.generate
   :skip: Literal, defaultdict

.. automodapi:: popper.loop
   :skip: Settings, Stats, timeout, parse_settings, format_program, ClingoGrounder, ClingoSolver, Tester, Constrain, generate_program, Grounding, Clause

.. automodapi:: popper.tester
   :skip: contextmanager, Clause, Literal, datetime, Prolog

.. automodapi:: popper.util
   :skip: perf_counter, contextmanager, Clause, Constrain, StatsEncoder

.. highlight:: python

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
