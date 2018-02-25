Inline markup
=============

Surrounding only
----------------

An *emphasis text*.

A **strong text**.

A `interpreted text`.

A ``literal text``.

The\ *Emphasis*\ **Strong**\ `Literal`\ Text.

A :sub:`subscript text`.

A :sup:`superscript text`.

A :title:`title reference text`.

Surrounding and Directive
-------------------------

A |Substitution Reference Text|.

A reference_.

A `reference too`_.

A _`reference three`.

A :ref:`reference <label-sec>`. Auto-titled: :ref:`label-sec`.

A :ref:`reference to paragraph <label-para>` cannot auto-titling.

A :doc:`document reference <inlinemarkup>` text. Auto-titled: :doc:`inlinemarkup`

A :download:`download reference <example.txt>`.

A footnote [footnote1]_ [footnote2]_.

A footnote [*]_ [*]_ [#]_ [#]_.

.. |Substitution Reference Text| replace:: substitution reference text

.. _reference: https://www.google.com/

.. _`reference too`: https://www.google.com/

.. _label-sec:

labeled section
^^^^^^^^^^^^^^^

.. _label-para:

labeled paragraph.

.. [footnote1] footnote target
.. [footnote2] footnote target
.. [*] footnote target
.. [*] footnote target
.. [#] footnote target
.. [#] footnote target

