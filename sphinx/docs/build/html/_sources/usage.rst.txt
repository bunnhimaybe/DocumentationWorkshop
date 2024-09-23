Installation and Environment
====================================

How to Install Sphinx
-------------------------

Python must be installed and the recommended download is Python 3+ but Python 2.7 is fine. Make sure the 'pip' and 'PATH' boxes during download installation is checked.

To install Sphinx, run the following command based on the operating system (OS) used in your command or terminal line.

.. py:function:: pip install -U sphinx

   initialises the package installation for Python and other indexes

   :sphinx: an auto-document extension for python

For Windows users:
    ``$ pip install -U sphinx``
For Linux users:
    ``$ apt-get install python3-sphinx``
For MacOS users:
    ``$ brew install sphinx-doc``


How to Set-Up Environment
---------------------------
* Create a folder in a directory
    * Pathway: C Drive > Users > [YourFolder] > [CreateFolder]
* Open [CreateFolder] in Visual Code Studio
* Create a new file and name it README.rst 
* Open command line and change directory to the [CreateFolder] pathway and type the following:
    * ``python -m venv .venv``
* Change directory to the [CreateFolder] > [.venv] pathway and type the following:
    * ``sphinx-quickstart docs``
* Separate source and build directory, choose 'yes'
* Insert project name, author, release, and language information
* Make HTML document using the following command:
    * ``make html``
* Add additional ``doctree`` by creating new file.rst and place the file name ``index.rst`` file under ``toctree``

.. note::
    * config.py: includes imports, extensions, project information, 
    * index.rst: main root page of the documentation
    * usage.rst: second page of the documentation 
    * customisation.rst: third page of the documentation