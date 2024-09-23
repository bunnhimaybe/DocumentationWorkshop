.. Sphinx Documentation master file, created by
   sphinx-quickstart on Sun Sep 22 22:28:36 2024.
   You can adapt this file completely to your liking, but it should at least contain the root `toctree` directive.

Sphinx Documentation
===========================

A documentation generator tool that can translate plain text source files into various output formats, produce cross-references, indices, etc. If a directory contains reStructeredText or Markdown documents, Sphinx can generate a series of HTML files, PDF files, pages, and more since the tool focuses on documentation, it can be used to generate blogs, homepages, and books.

Overview
---------------------------
   * Supports Python, C, C++, Javascript, and reStructedText
   * Allows for various type of documentation such as webpages, printable PDF, documents for e-readers (ePub)
   * Allows the use of reStructuredText and Markdowns
   * Extensive system of cross-referencing and code documentation ability to syntax highlights for code samples
   * Allows for first and third party extensions
   * Uses ``docstrings``
   * Allows users to describe various addition and changes for Documentation
   * Allows users to list out various paramaters and methods of the code to provide comment and information of what each function does in the source code

Definition
-----------------------------
:toctree: is a directive that inserts at it's current location. the relative document names are relative to document the directive occurs.
:builders: can be different types of document types such as HTML, and PDF. If there are multiple output files, it will be treated as a collection of hyperlinks
:source: file that can be used to edit files for documentation and reStructuredText, Markdowns, and program languages can be used.
:venv: supports the creation of a virtual environment, allows developers to control software dependendies such as packages and libraries
:docs: location of your build and source directory folders
:doctrees: shows the specific content in each doctrees

.. toctree::
   :maxdepth: 2
   :caption: Contents:

Navigation
---------------------------

.. toctree::
   usage
   customisation
