================================================================
HONEST: Measuring Hurtful Sentence Completion in Language Models
================================================================


.. image:: https://img.shields.io/pypi/v/honest.svg
        :target: https://pypi.python.org/pypi/honest

.. image:: https://img.shields.io/travis/MilaNLProc/honest.svg
        :target: https://travis-ci.com/MilaNLProc/honest

.. image:: https://readthedocs.org/projects/honest/badge/?version=latest
        :target: https://honest.readthedocs.io/en/latest/?version=latest
        :alt: Documentation Status

.. image:: https://raw.githubusercontent.com/aleen42/badges/master/src/medium.svg
    :target: https://medium.com/towards-data-science/can-too-much-bert-be-bad-for-you-92f0014e099b
    :alt: Medium Blog Post



...


Large language models (LLMs) have revolutionized the field of NLP. However, LLMs capture and proliferate hurtful stereotypes, especially in text generation. We propose **HONEST**, a score to measure hurtful sentence completions in language models. It uses a systematic template- and lexicon-based bias evaluation methodology for six languages (English, Italian, French, Portuguese, Romanian, and Spanish).

See the papers for additional details:

Nozza D., Bianchi F., and Hovy D. "HONEST: Measuring hurtful sentence completion in language models." The 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies. Association for Computational Linguistics, 2021. https://aclanthology.org/2021.naacl-main.191


Installing
----------

.. code-block:: bash

    pip install -U honest

Citation
--------

Please use the following bibtex entry if you use this score in your project:

::

  @inproceedings{nozza-etal-2021-honest,
    title = {"{HONEST}: Measuring Hurtful Sentence Completion in Language Models"},
    author = "Nozza, Debora and Bianchi, Federico  and Hovy, Dirk",
    booktitle = "Proceedings of the 2021 Conference of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies",
    month = jun,
    year = "2021",
    address = "Online",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2021.naacl-main.191",
    doi = "10.18653/v1/2021.naacl-main.191",
    pages = "2398--2406",
  }

Development Team
----------------

* Federico Bianchi <f.bianchi@unibocconi.it> Bocconi University
* Debora Nozza <debora.nozza@unibocconi.it> Bocconi University
* Dirk Hovy <dirk.hovy@unibocconi.it> Bocconi University

Software Details
----------------

* Free software: MIT license
* Documentation: https://honest.readthedocs.io.

Credits
-------

This package was created with Cookiecutter_ and the `audreyr/cookiecutter-pypackage`_ project template.

.. _Cookiecutter: https://github.com/audreyr/cookiecutter
.. _`audreyr/cookiecutter-pypackage`: https://github.com/audreyr/cookiecutter-pypackage

Note
----

Remember that this is a research tool :)
