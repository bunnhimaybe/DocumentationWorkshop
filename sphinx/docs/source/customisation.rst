Customisation
===========================================

reStructured Text and Markdowns
-------------------------------------------
Sphinx documentation can be customised using various reStructedText and Markdowns. 

Paragraph Markups
---------------------------------------------
These markup allows the creation of short paragraphs inside a blocked unit that brings reader attention. Some of those are notes, important, attention, tips, error, important, and more.

.. warning::
   This is an example of a warning block unit!
   
   A best practice to use Markdown for objects is using the code ``.. function::`` 

   In reStructedText, 
      * Create Headers, using ``===``
      * Create sub-headers using ``---``
         * The assignment and hyphen symbols must be the same length as the Text
   
.. important::
   This is an example of an important block unit!
   
   Please be aware that indentations are important! Indentations can create bullet point list using the asterisks (*) symbol and/or assist in ordered listings.

.. tip::
   This is an example of a tip block unit!

   Remember to save your work and commit any changes!

Objects
-------------------------------------------
Sphinx's objective is to make easy documentation of objects in any domain. A domain is a collection of object types that belong together, complete with mark-up to create and reference description of the objects

To document objects, the ``.. py:function::`` directive to the function and list summaries, descriptions, etc. of the objects, paramaters, and so forth. While users must still write every object, Sphinx will generate the formatted document.

See also and Change
---------------------------------------------
See also and Change directives can be included in your documention with the following tags:
   * ``.. seealso:``
   * ``.. versionadded:``
   * ``.. versionchanged:``