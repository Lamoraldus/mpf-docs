Contributing to MPF
===================

Want to add a feature? A missing event somewhere? Wrote a new device which
might be useful for other users? Fixed a bug? Added some small missing piece?

We'd love to take your contribution upstream!

Found a bug which you can reproduce? Fill an issue:

* `MPF Issues on github <https://github.com/missionpinball/mpf/issues>`_. Use
  this for game and platform related bugs
* `MPF-MC Issues on github <https://github.com/missionpinball/mpf-mc/issues>`_. Use
  this for media controller bugs such as problems with slides, widgets or
  audio.

If you want to discuss a feature or bug (or if you are unsure). Visit our
forum: https://groups.google.com/forum/#!forum/mpf-users


Install MPF in development mode
-------------------------------

To work on MPF you need to install it in developer/editable mode:

#. Clone the `mpf repo <https://github.com/missionpinball/mpf/>`_ from GitHub.
#. Run ``pip3 install -e .`` from within the mpf folder to install MPF in editable
   mode.
#. Clone the `mpf-mc repo <https://github.com/missionpinball/mpf-mc/>`_ from
   GitHub (only needed for media controller changes - skip otherwise).
#. Run ``pip3 install -e .`` from within the mpf-mc folder to install MPF MC in
   editable mode (only needed for media controller changes - skip otherwise).
#. Switch bith repositories to the branch corresponding to the version you want
   to work with. This should be ``dev`` in most cases or the current release
   for smaller bug fixed. Do what works best for you. We can help to forward or
   backport your changes.
#. Makes your changes.
#. Add your name to the ``AUTHORS`` file.
#. If possible add an unit test. We can help with that and a first Pull Request
   without a test is definitely fine.
#. Run ``make unit`` and check that all tests still pass. You can run them in
   mpf and mpf-mc.
#. Submit your pull request.


Getting started with an easy hack
---------------------------------

We maintain a list of issues which are self-contained and good to solve on
their own without too much interaction with core code. We label those as 
`easy hacks <https://github.com/missionpinball/mpf/labels/easy%20hack>`_
(although they do not have to be easy, just self-containted). If you want
to work on one of them (or any other issue) comment on the issue or write
in the forum and we will assist you along the way.
